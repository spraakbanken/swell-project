# Normalization guidelines

<!--- Improvements needed:
1. The current principles are language-independent with Swedish examples. We probably also need more specific principles or rules that work directly off Swedish grammar (as in the Falko manual for German)
2. More examples of each principle
3. An appendix with illustrations of the principles and examples in SVALA, displaying source text, alignments and target text 

Normalization of a learner text aims at correcting it in accordance with a postulated standard variant of the language, thereby making it possible to study the deviations from this. 
--->

## Motivation and purpose

Normalization in SVALA means editing of the original learner text in such a way that the sentences a) are correct with respect to orthography, morphology and syntax and b) are semantically coherent. The first point corresponds to the Minimal Target Hypothesis in the German learner corpus Falko ([Reznicek et al. 2012, page 42 ff.](https://www.linguistik.hu-berlin.de/de/institut/professuren/korpuslinguistik/forschung/falko)), whereas the latter point goes beyond this by allowing changes that affect meaning. A German example that highlights the difference (from [Boyd 2018, slide 7](https://sweclarin.se/sites/sweclarin.se/files/event_atachements/L2wsh_Boyd_slides.pdf)) is the Minimal Target Hypothesis "Rufst du deine Antwort an?", which is semantically anomalous ("Do you call your answer?") but syntactically correct. To represent correction of semantics, pragmatics and stylistics, there is an additional level in Falko called the Extended Target Hypothesis, which in this example is "Rufst du mich wegen deiner Antwort an?" ("Will you call me regarding your answer?"). The reason that the target hypothesis in SVALA has a wider definition than the Minimal Target Hypothesis in Falko is that SVALA only has a single level of target hypotheses. 

The purpose of normalization is twofold: 

1. To render the text in a version which is amenable to automatic annotation using a standard linguistic analysis pipeline. (For Swedish, such a pipeline is [efselab](https://github.com/robertostling/efselab) or [Sparv](https://spraakbanken.gu.se/verktyg/sparv). The SweLL data is currently processed with the Sparv-pipeline. It is possible to re-annotate later with other pipelines.)

2. To obtain a separate, explicit representation of the corrections (that is, the target hypotheses). Such a representation is highly useful by allowing for many new types of search of the corpus.

    * Finding missing occurrences of a construction in the learner text in the sense that it could or should have been used, for example, when something that ought to have been expressed using a passive was not.

    * Finding mismatches between the learner and corrected text, for example, an adjective in the learner text that corresponds to an adverb in the corrected text.

Although we strive to write guidelines to maximize inter-annotator agreement with respect to normalization, there will typically (if not always) be multiple possible normalizations of a deviating expression in a learner text. There are two reasons for this:

1. Different target hypotheses can be assumed.

   Jag trivs mycket bor med dem   &nbsp; &larr; Original

   Jag trivs mycket med att bo med dem   &nbsp; &larr; Target hypothesis 1 (_preferred_)
   
   Jag trivs mycket bra med dem   &nbsp; &larr; Target hypothesis 2
   
   Here, it is not clear if by "mycket bor" the learner meant "mycket med att bo" or "mycket bra". Since our notion of minimal target hypothesis requires not changing the meaning (or at least changing it as little as possible), we prefer "mycket med att bo" despite the fact that this involved more tokens that are changed (see further below).

2. Assuming a particular target hypothesis, several normalizations may be possible.

   Mit Bostaden är stor och ser gul farg fint hus   &nbsp; &larr; Original

   Min bostad   är stor och har gul färg , ett fint hus   &nbsp; &larr; Smaller change (_preferred_)

   Min bostad   är stor och har gul färg , och ligger i ett fint hus   &nbsp; &larr; Bigger change

   Min bostad   är stor och gul , och ligger i ett fint hus   &nbsp; &larr; Even bigger change

## Principle of minimal change

The basic principle of normalization in SVALA is that of miminal change. This means changing as few tokens as possible and the meaning as little as possible while correcting orthography, morphology and syntax and ensuring that the sentence is semantically coherent. In case of conflict between these, token changes are preferred to meaning changes. The pragmatics and style should not be changed.

### Example

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
 
 2. Change the meaning as little as possible, and do not change pragmatics or style.

&nbsp;&nbsp; &nbsp; &nbsp; Examples of style that we do not correct:

&nbsp;&nbsp; &nbsp; &nbsp; Main-clause word order in dependent clause with "att": "Allt är bra för att jag kan inte bo ensam"
   
&nbsp;&nbsp; &nbsp; &nbsp; "Orsaken beror på..."

3. If there is a conflict between minimizing the number of tokens and retaining the meaning, then give priority to retaining the meaning (permitting more tokens to be changed).

   In item (1) above (different target hypotheses), changing "bor" to "bra" is a bigger change than changing "bor" to "med att bo" because it replaces one word with another word with a different meaning

## Specific principles

### Principle of verb as core

If a verb does not match its arguments, retain the verb and adjust the arguments. Dummies are added for missing mandatory objects. The same applies to verb-dependent prepositional objects. (Adapted from Falko ([Reznicek et al. 2012, page 45](https://www.linguistik.hu-berlin.de/de/institut/professuren/korpuslinguistik/forschung/falko)). Is it relevant? Swedish examples?) 

### Principle of nominal congruence hierarchy 

In the absence of agreement between determiner, attribute(s) and nominal head, the head is retained. (Adapted from Falko ([Reznicek et al. 2012, page 46](https://www.linguistik.hu-berlin.de/de/institut/professuren/korpuslinguistik/forschung/falko)).) 

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

In cases where it is difficult to decide whether an expression is correct or incorrect, assume that the learner was correct. 

_Do we have grammatical examples of this?_

Note: This principle is also useful in transcription, in case of squiggles that could be interpreted in different ways. For example, in some handwriting it is difficult to distinguish "a" from "o". We may then assume, for example, that a partly illegible word should be read as the present verb form "dansar" (English: danse) rather than the illegal form "dansor". Similarly, we may assume strokes above "a" or "o" to be correct diacritics for the Swedish characters "å", "ä" or "ö", rather than errors.

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


