# Normalization guidelines

Note: "Normalization" should maybe be called "correction"?

## Purpose

Normalisation is not an unambiguous concept, but the aim of this guideline is to make our criteria for this task as precise as possible. Still, there will typically be multiple possible normalisations of a text, just as there are several correct translations of a sentence. Why do we then do normalisation? A key purpose is to make our target hypothesis explicit, given that target hypotheses always exist regardless of whether we make them explicit or not. (Note, by the way, that our tool only allows for a single target hypothesis.) Another purpose is that we expect the resulting parallel (original and normalised) text to be a highly valuable resource for development of automatic methods for identifying learner errors (and this resource will be valuable even if there are multiple ways in which the text could have been normalised). A third purpose is more speculative, but our intuition is that the quality of error coding will improve if the conceptually different tasks of error detection, correction and annotation are performed independently.

## Why are different normalisations possible?

There are two reasons why different normalisations are possible for a learner text:

1. Different target hypotheses

   Jag trivs mycket bor med dem . <-- Original

   Jag trivs mycket bra med dem . <-- Target hypothesis 1

   Jag trivs mycket med att bo med dem .  <-- Target hypothesis 2

2. Even if we agree on a target hypothesis, several normalisations are still possible. Här behövs det kriterier för "minimal ändring".

   Mit Bostaden är stor och ser gul farg   fint hus . <-- Original

   Min bostad   är stor och har gul färg , ett fint hus . <-- Suggested minimal change

   Min bostad   är stor och har gul färg , och ligger i ett fint hus . <-- Larger change

   Min bostad   är stor och gul , och ligger i ett fint hus . <-- Even larger change

## Criteria

-- Ändra så att meningen är grammatisk (vilket är ett vitt begrepp)

-- Ändra inte på stilnivå (det får låta som från en femåring så länge det inte är ogrammatiskt)

Exempel på saker vi inte rättar:

"Orsaken beror på..."

Huvudsatsordföljd i att-bisats

Prioritet vid ändringar för att göra normalisering

1. Behåll betydelsen (viktigast!)

Att ändra "bor" till "bra" är en större ändring än att ändra "bor" till "med att bo"

2. Ändra så få ord som möjligt

ett fint hus .
och ligger i ett fint hus . <-- Större ändring

3. Utgå från innehållsordets form och ändra omgivande kontext i stället för tvärtom

det är mycket skillnader

det är många skillnader <-- vår ändring

det är stora skillnader <-- "stora" är längre från ursprungstexten ("mycket")

det är stor skillnad <-- innehållsordets form ändrad, ger större ändring

4. Positive assumption.

Hellre fria än fälla. Utgå från att de kan 

ser gul färg???

-----------------------------

Old text:

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




