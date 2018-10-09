# Normalization guidelines

## Background

A key assumption of our approach is that it is beneficial to separate error coding into two steps, both in terms of workflow and representation: _normalisation_ (that is, correction of the learner text according to the target hypotheses) and the actual _annotation_ of the corrections. Based on this separation, our system (Svala) automatically constructs a parallel corpus of the learner and normalised texts, with word alignments that may be corrected by the annotator. Strictly speaking, normalisation therefore involves not only correction of the learner text but also correction of misaligned links.

1. By letting the annotator correct the text prior to error annotation (whether in smaller or larger chunks), they will be in a better position to build a coherent understanding of the learner's linguistic competence and to form target hypotheses that are consistent with this understanding.

2. Since error correction and error annotation are conceptually distinct tasks, it is logical to perform them independently. For example, it might be beneficial to outsource normalisation to researchers in second-language acquisition, that is, to people who are experts in comparing target hypotheses for learner texts. In contrast, annotation of corrections might be handled just as well by students.

3. There is currently no consensus on how to measure inter-annotator agreement for normalisation. Because of this, inter-annotator agreement for error annotation should be calculated based on a given normalisation. By separating normalisation and error annotation (and their representations), this becomes straightforward.

4. An additional, independent advantage of the separation of normalisation and annotation is that the resulting parallel corpus will be a highly valuable resource for development of automatic methods for identifying learner errors.

There are several motivations for this.

## Why are different normalisations possible?

Normalisation is not an unambiguous concept, and there will typically be multiple possible normalisations of a learner text, just as there are several correct translations of a sentence. (Our tool currently only allows for a single target hypothesis, so there is no way of encoding multiple hypotheses.) In general, there are two reasons for why different normalisations are possible:

1. Different target hypotheses can be assumed

   Jag trivs mycket bor med dem   &nbsp; &larr; Original

   Jag trivs mycket med att bo med dem   &nbsp; &larr; Target hypothesis 1: preferred change
   
   Jag trivs mycket bra med dem   &nbsp; &larr; Target hypothesis 2

2. Assuming a particular target hypothesis, several normalisations are still possible

   Mit Bostaden är stor och ser gul farg fint hus   &nbsp; &larr; Original

   Min bostad   är stor och har gul färg , ett fint hus   &nbsp; &larr; Preferred change

   Min bostad   är stor och har gul färg , och ligger i ett fint hus   &nbsp; &larr; Bigger change

   Min bostad   är stor och gul , och ligger i ett fint hus   &nbsp; &larr; Even bigger change

## Principles for normalisation

Assuming a sentence that needs correction, use the following principles:

### Obligatory principles

First, _always_ keep to the following two principles:

1. Change the sentence to make it grammatically correct (which is admittedly a broad concept)

2. Don't change the style (it may sound like coming from a five-year old as long as it's grammatical)

   Examples of things we don't correct:

   Main-clause word order in dependent clause with "att": "Allt är bra för att jag kan inte bo ensam"
   
   "Orsaken beror på..."

### Principle of minimal change

Secondly, if several normalisations are possible, use the following criteria to discriminate between them in order of decreasing priority:

1. Keep the meaning. This is the most important criterion!

   In item (1) above (different target hypotheses), changing "bor" to "bra" is a bigger change than changing "bor" to "med att bo" because it replaces one word with another word with a different meaning

2. Change as few words as possible

   In item (2) above, inserting "och ligger i ett fint hus" is more idiomatic but not preferred since it changes more words than "ett fint hus"
   
   ett fint hus   &nbsp; &larr; Preferred change to obtain a proper noun phrase
   
   och ligger i ett fint hus   &nbsp; &larr; Bigger change
<!---
   Here is another example:
   
   Här kommer arbetslösheten som en stor faktor till stress, som inte mindre än stressen på grund av arbetsbelastning.

   Här kommer arbetslösheten som en stor faktor till stress, som inte är mindre än stressen på grund av arbetsbelastning. &nbsp; &larr; Preferred change

   Här kommer arbetslösheten som en stor faktor till stress, lika viktigt som stressen på grund av arbetsbelastning. &nbsp; &larr; More idiomatic but requires too much change of the original text
 --->   

Minimal change is equivalent to the _minimal target hypothesis_ in the [Falko corpus](https://www.linguistik.hu-berlin.de/en/institut-en/professuren-en/korpuslinguistik/mitarbeiter-innen-en/marc/ReznicekEA_toAppear.pdf) in the sense that it a) differs minimally from the learner text and b) is grammatical at the expense of ignoring errors concerning semantics, pragmatics and style.

### Principle of content and function words

Keep the form of the content word and change its surrounding context, rather than keeping the function word

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

In cases where it is difficult to decide whether an expression is correct or incorrect, assume the the learner was correct. [Do we have grammatical examples?] This principle is also useful in transcription, and then concerns squiggles that could be interpreted in different ways. For example, in some handwriting it is difficult to distinguish "a" from "o". We may then assume, for example, that a partly illegible word should be read as the present verb form "dansar" (English: danse) rather than the illegal form "dansor". Similarly, we may assume strokes above "a" or "o" to be correct diacritics for the Swedish characters "å", "ä" or "ö", rather than errors.

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


