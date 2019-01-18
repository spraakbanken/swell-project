# Normalization guidelines

<!--- Improvements needed:
1. The current principles are language-independent with Swedish examples. We probably also need more specific principles or rules that work directly off Swedish grammar (as in the Falko manual for German)
2. More examples of each principle
3. An appendix with illustrations of the principles and examples in SVALA, displaying source text, alignments and target text --->

## Motivation and purpose

Normalization of a learner text aims at correcting it in accordance with a postulated standard variant of the language, thereby making it possible to study the deviations from this. More specifically, by normalization in SVALA we mean editing of the original learner text such that the sentences a) are correct with respect to orthography, morphology and syntax and b) are semantically coherent. The first point is compatible with the Minimal Target Hypothesis in the German learner corpus Falko ([Reznicek et al. 2012, page 42 ff.](https://www.linguistik.hu-berlin.de/de/institut/professuren/korpuslinguistik/forschung/falko)). In contrast, the latter point goes beyond the Minimal Target Hypothesis in Falko, which does not have to make sense as long as it is syntactically correct. A German example of this (from [Boyd 2018, slide 7](https://sweclarin.se/sites/sweclarin.se/files/event_atachements/L2wsh_Boyd_slides.pdf)) is "Rufst du deine Antwort an?" ("Do you call your answer?"), which is semantically anomalous, but where a semantically coherent target hypothesis would be "Rufst du mich wegen deiner Antwort an?" ("Will you call me to answer?"). A reason that our target hypothesis goes beyond the Minimal Target Hypothesis in Falko is that SVALA only has a single level of target hypotheses, whereas in Falko there is also the Extended Target Hypothesis, which involves correction of semantics, pragmatics and stylistics.

The purpose of normalization is twofold: 

1. To render the text in a version which is amenable to automatic annotation using a standard linguistic analysis pipeline such as [efselab](https://github.com/robertostling/efselab).

2. To obtain a separate, explicit representation of the corrections (that is, the target hypotheses).

Although we strive to write guidelines to maximize inter-annotator agreement with respect to normalization, there will typically (if not always) be multiple possible normalizations of a deviating expression in a learner text. There are two reasons for this:

1. Different target hypotheses can be assumed.

   Jag trivs mycket bor med dem   &nbsp; &larr; Original

   Jag trivs mycket med att bo med dem   &nbsp; &larr; Target hypothesis 1 (_preferred_)
   
   Jag trivs mycket bra med dem   &nbsp; &larr; Target hypothesis 2
   
   Here, it is not clear if by "mycket bor" the learner meant "mycket med att bo" or "mycket bra". Since our notion of minimal target hypothesis requires not changing the meaning (or at least changing it as little as possible), we prefer "mycket med att bo" despite the fact that this involved more tokens that are changed (see further below).

2. Assuming a particular target hypothesis, several normalizations are still possible. (This is analogous to the fact that there are several possible correct translations of a sentence.)

   Mit Bostaden är stor och ser gul farg fint hus   &nbsp; &larr; Original

   Min bostad   är stor och har gul färg , ett fint hus   &nbsp; &larr; Smaller change (_preferred_)

   Min bostad   är stor och har gul färg , och ligger i ett fint hus   &nbsp; &larr; Bigger change

   Min bostad   är stor och gul , och ligger i ett fint hus   &nbsp; &larr; Even bigger change

   As exemplified above, our notion of minimal target hypothesis involves changing as few tokens as possible to render the sentence in a grammatical form, while (as far as possible) not changing the meaning, pragmatics or style.

<!--- (Our tool currently only allows for a single target hypothesis, so there is no way of encoding multiple hypotheses.) --->

## General principles of normalisation

### Definition

The minimal target hypothesis is a rendering of the learner expression in a form that is correct with respect to orthography, spelling, morphology and syntax, while involving as few changes of tokens as possible, and as little change of meaning, pragmatics or style as possible. _Lexical choice?_

### Principle of minimal change

1. Change as few tokens as possible.

   In item (2) above, inserting "och ligger i ett fint hus" is more idiomatic but not preferred since it changes more words than "ett fint hus"
   
   ett fint hus   &nbsp; &larr; Preferred change to obtain a proper noun phrase
   
   och ligger i ett fint hus   &nbsp; &larr; Bigger change
<!---
   Here is another example:
   
   Här kommer arbetslösheten som en stor faktor till stress, som inte mindre än stressen på grund av arbetsbelastning.

   Här kommer arbetslösheten som en stor faktor till stress, som inte är mindre än stressen på grund av arbetsbelastning. &nbsp; &larr; Preferred change

   Här kommer arbetslösheten som en stor faktor till stress, lika viktigt som stressen på grund av arbetsbelastning. &nbsp; &larr; More idiomatic but requires too much change of the original text
 --->   
 
 2. As far as possible, do not change the meaning, pragmatics or style. A consequence of not changing the style is that grammaticality becomes a rather broad notion.

&nbsp;&nbsp; &nbsp; &nbsp; Examples of style that we do not correct:

&nbsp;&nbsp; &nbsp; &nbsp; Main-clause word order in dependent clause with "att": "Allt är bra för att jag kan inte bo ensam"
   
&nbsp;&nbsp; &nbsp; &nbsp; "Orsaken beror på..."

3. If minimizing the number of tokens changed conflicts with retaining the meaning, then keep the meaning (permitting more tokens to be changed).

   In item (1) above (different target hypotheses), changing "bor" to "bra" is a bigger change than changing "bor" to "med att bo" because it replaces one word with another word with a different meaning

### Principle of verb as core

(Suggestion adapted from Falko ([Reznicek et al. 2012, page 45](https://www.linguistik.hu-berlin.de/de/institut/professuren/korpuslinguistik/forschung/falko)).) If a verb does not match its arguments, retain the verb and adjust the arguments. Dummies are added for missing mandatory objects. The same applies to verb-dependent prepositional objects.

### Principle of nominal congruence hierarchy 

(Suggestion adapted from Falko ([Reznicek et al. 2012, page 46](https://www.linguistik.hu-berlin.de/de/institut/professuren/korpuslinguistik/forschung/falko)).) In the absence of agreement between determiner, attribute(s) and nominal head, the head is retained.

### Principle of content words

(Is this a consequence of the previous principle?) Keep the form of the content word and change its surrounding context, rather than keeping the function word

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;det är mycket skillnader

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;det är många skillnader   &nbsp; &larr; Preferred change

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;det är stora skillnader   &nbsp; &larr; "stora" is more idiomatic but is further away from the original ("mycket")

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;det är stor skillnad   &nbsp; &larr; The form of the content word is changed, which we regard as a bigger change

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;min kompis och jag träffar till klubb

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;min kompis och jag träffas på klubb &nbsp; &larr; Preferred change (function word changed)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;min kompis och jag går till klubb &nbsp; &larr; Content word changed

### Principle of frequency

If it is otherwise not clear which target hypothesis to prefer, use the one that is most frequent in Korp (or some other reference material), and which can thus be assumed to be the more conventionalised expression.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Det var mycket svårt för oss att hitta den lägenhet i Stockholm
   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Det var mycket svårt för oss att hitta en lägenhet i Stockholm &nbsp; &larr; Preferred change
   
Frequency in Korp (all corpora selected): "hitta lägenhet" 1904, "hitta en lägenhet" 4180

### Principle of positive assumption

In cases where it is difficult to decide whether an expression is correct or incorrect, assume the the learner was correct. 

_Do we have grammatical examples of this?_

Note: This principle is also useful in transcription, in case of squiggles that could be interpreted in different ways. For example, in some handwriting it is difficult to distinguish "a" from "o". We may then assume, for example, that a partly illegible word should be read as the present verb form "dansar" (English: danse) rather than the illegal form "dansor". Similarly, we may assume strokes above "a" or "o" to be correct diacritics for the Swedish characters "å", "ä" or "ö", rather than errors.

## General principles of normalisation


-----------------------------

Note: Old text commented out (still available in markdown)

<!--- 

## Content

### Normalization principles

 1. Principle of minimal change
 
 2. Principle of positive assumption	
 
 3. Principle of frequency	
 
 4. Principle of content vs form word
 
 ### Guidelines by error type	
 
 6. Lexical errors	
 
 7. Orthographic errors	
 
 8. Morphological errors
 
 9. Syntactical errors
 
 10. Intelligibility errors	
 
 11. Follow-up (consequence) errors


## Normalization principles

### Principle of minimal change

For normalization, we start with this simple instruction: 
- Try to make a minimal change to the original text to achieve a grammatically (and lexically?) correct/readable/understandable version. We would need to collect examples for that.

Example:
Här kommer arbetslösheten som en stor faktor till stress, som inte mindre än stressen på grund av arbetsbelastning.

a) Här kommer arbetslösheten som en stor faktor till stress, som är inte mindre än stressen på grund av arbetsbelastning.

b) Här kommer arbetslösheten som en stor faktor till stress, lika viktigt som stressen på grund av arbetsbelastning.

Here example a) is the way to go, since it keeps to the minimal change principle. B) is more idiomatic but requires too many changes/interpretation of the original text.

### Principle of positive assumption

- In cases where it is difficult to decide whether the learner is right or wrong, apply the principle of positive assumption, i.e. assume the the learner meant right ... We would need examples for that.
- See manual for the annotation tool on how to perform editing operations
- We need to extend normalization guidelines further, and our role is to add more of that as we work - i.e. when we see that we miss some instruction, we suggest it!


### Principle of frequency

In cases where it is not obvious which TH is closest to the minimal change principle - changing the article or deleting it - apply the TH that is the most frequent in Korp [eller annat referensmaterial?]  [Can we expect that, too much work, too much that can go wrong...?/JP] and hence supposed to be the more conventionalized expression (according to the corpus data).

Det var mycket svårt för oss att hitta den lägenhet i Stockholm → det var mycket svårt att hitta en lägenhet i Stockholm
Träffar i Korp (alla korpusar valda): hitta lägenhet 1904, hitta en lägenhet 4180



### Principle of content vs form word

Content word + formal word // minimal change:

If a content word and a formal word (e.g. V+Prep) in a deviant way, the formal word should be adapted to the content word in the
TH - unless it is obvious from the context that the contenword is the one to be changed. This  overrides the minimal change principle.

min kompis och jag träffar till klubb NN” [F W] → min kompis och jag träffas på klubb NN
(NOT: [W] – går till klubb NN)

## Guidelines by error type

### SweLL pilot - analysis & insights (Elena and Julia, OBS! prel. anteckningar, EJ ANPASSAD TILL SENASTE VERSIONEN AV KODBOKEN):

### Lexical errors

Idiomaticity: When you mark something as non-idiomatic mark the whole expression/sequence
You CAN provide a normalized version of the sequence, but you do not NEED to.

Exemple:
Frågan är: kan man ta bort stress från människor?
Mark as ID, change to → Frågan är: kan man minska stress för människor?
Mark as ID, Leave it as it is 



### Orthographic errors


### Morphological errors
F-AGR // F-NUM: 
In case several interpretations are possible, the rule of the thumb is 
The subject is correct, the attribute/predicative should agree with the subject, UNLESS it is obvious from the context that the subject should be changed:


Jag och min familj bor, min mamma och min syster, bor i en lägenhet i Tumba. Det finns 2 rum och ett kök. Det är bra för sma family → Det är bra för en liten familj
[or should we keep to the minimal change principle here? I think that gets confusing and creates too many gray areas.../JP]

F-DEF // optional article and minimal change:


### Syntactical errors

### Follow-up (consequence) correction

#Anteckningar SweLL-möte 180931

Inte ändra bisatser som : "allt är bra för att jag kan inte bo ensam" - inte särskilt avvikande (se SAG)

Innehållsord tas bort in minsta möjliga mån - exempel bostaden och fint hus (Elena tar skärmdump)

Can-do i originaltexten får inte gå förlorad i normaliseringen! 

## Mål:

- Ändra så meningen är grammatisk
- Ändra inte på stilnivå

## Priorotering:

1. Behåll betydelsen !!
2. Ändra så få ord som möjligt

--->


