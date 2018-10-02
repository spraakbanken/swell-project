# Anonymization guidelines

The purpose of anonymization is to de-identify all information that can reveal the identity of the person who wrote the text. This information can include person names, age, areas, cities, or political, religious and other views and need to be replaced or overseen to ensure anonymity. Your task is to 1) identify all information that can relate to the specific person who wrote the text, and categorize what type of information it is so that the person can be de-identified by changing/hiding the specific information. This document contains instructions for how to proceed. 

## Basic principles

1. Remove/change the information that can reveal a person behind the essay(s), yet keep to the “minimal change” rule. The data should be usable in research scenarios.  _Example?_ 

2. Annotators have to make the assessment of the risks and needs for pseudonymization (an element of subjectivity)

3. Keep track of whether the token is “original” or “masked”

4. Categories that need to be marked in the texts, but not necessarily replaced. We would  make an assessment later when we have enough statistics over the learners behind the essays: 
  * country of origin (_Jag kommer från Syrien_ versus _Jag kommer från Luxembourg_) - depending upon how many subjects in our database are from the named countries [Consider to merge this with <country>]
  * country of “intermediate” residence (_Vi har stannat en månad i Turkiet_)
  * number of family members (_Jag har fem bröder och fyra systrar_) - we will need to see whether it is a normal pattern in many essays. If yes - no masking/suppression is necessary
  * professions (_Jag är webbutvikler_) 

5. Categories that can be used for discrimination, such as political views, religious convictions, sexual orientation, should also be marked - but not necessarily masked right away? A decision would need to be made by an annotator. E.g. _I en dag såg vi en stor demstration det var för mycket människor vill inte Turkiets statsminister Ardogan och vi kände mycket glad för att det var första dag ser vi en fri demstration._

## Supra-categories : <span style="color:red">[NEW]</span>

May be applied on top of other categories, as (extra)linguistic information. Only marked forms are tagged, i.e. genitive case is marked, whereas common case - not (by default everything is assumed to have common case).

### Running numbers: <span style="color:red">[NEW]</span>
Applies to all @placeholders. Each unique name entity (NE) type (e.g.name) should get its own running number, starting with 1. If the same NE is repeated in the text, the same running number is assigned to it. At the moment this should be done manually. 

### Morphology: 
 * Case: < genitive > , e.g. Volvos
 * Form: < definite > , e.g. Statsbiliotekets <span style="color:red">[NEW]</span>
 * Number: < plural > , e.g. Mölndalsbor <span style="color:red">[NEW]</span>


## Pseudonymize: 

### 1. Personal Names: 
  * Types: < firstname > < middlename > < surname > 
  * Descriptor: 
      - Gender: male, female, unknown < m > , < f > , < unk >
<!--       - Case: genitive < gen > -->
      
   - Initial:  < ini > 
   
<!--     - Running number:  1, 2…   [enumerate each unique name type entity with a number starting with 1] -->

  * Pseudonymization: 
      - Provide a list with first names, male, female and gender neutral (incl. international). 
      - For surnames, gender-specific types, when unclear use gender-neutral names (e.g. Andrea, Charlie, Kim, Tayler) 
      - Provide a list with surnames (incl. international)
      - Middlenames: Replace with an initial “A”
      - Initial replaced by “A”
<!--     - Change token by token [BEA, WHAT IS MEANT BY THIS?] -->

  * To consider: 
      - allow cross-reference/anaphora resolution, i.e. allow to keep track of the entities that the L2 learner refers to, e.g. if more than one unique name occurs in the text, each unique name shall be replaced by a unique pseudonym 
      - random substitution for each unique name in the text given a list of names or
      - select a few names (while keeping the gender and cross-reference info) and use these names - throughout all texts
      - Use typical names for various ethnicities
      
![](https://ws.spraakbanken.gu.se/ws/swell/png?mode%3Aanon%20Alice~Alice%3A'firstname%3Afemale'%3A1%20and~and%20Bob~Bob%3A'firstname%3Amale'%3A2%20went~went%20to~to%20Paris~Paris%3Acity%20.%40s6~%40s6%20'Alice%5C's'~'Alice%5C's'%3A'firstname%3Afemale'%3A1%3Agen%20wallet~wallet%20was~was%20stolen~stolen%20.%40s11~%40s11%2F%2F'firstname%3Afemale'~Alice%201~Alice%20and~and%20'firstname%3Amale'~Bob%202~Bob%20went~went%20to~to%20city~Paris%20.~%40s6%20'firstname%3Afemale'~'Alice%5C's'%201~'Alice%5C's'%20gen~'Alice%5C's'%20wallet~wallet%20was~was%20stolen~stolen%20.~%40s11)


### 2. Geographic data (country, city, zip codes, area names, …)
  * Types: <!-- < country_of_origin > , -->
  < country > , < geo > , < zip_code > , < region > , < city-SWE > , < city > , < area > , < place > , < street_nr >
  
   - < region > versus < area > : < region > is a larger unit, like *län* in Sweden ; < area > is a smaller part of something, e.g. of a city, like *Balltorp* in Mölndal
   - < country > : except Sweden
      
 ![alt text](https://spraakbanken.gu.se/sites/spraakbanken.gu.se/files/Svala_anon_region.png "region")
      
<!-- c **_WHAT DO WE MEAN BY REGION? Should person's place of living, like "Baltorp" in Mölndal or "Sköndal" in Stockholm be marked as "region"? Or "area" ? (Elena, A10AT1) In the case of "jag bor in irak maysan soudirak" how to mark "maysan" versus "soudirak" (Elena, A11AT1)) ???_** -->
      
   - < city > : city including villages (på svenska “ort”)    
   - < geo >: forest, lake, mountain, etc
   - < zip_code >: zip/area code
   - < place >: specific place, street, square, bridge, 
   - < street_nr > : street or place number
   
 <!-- * Descriptor: 
      - Running number: < 1, 2… > [enumerate each unique name type entity with a number starting with 1] -->
  * Pseudonymization: 
      - Random substitution given a list of named entities of various attributes for each attribute, except for Sweden, and possibly country of origin
 <!--     - Country of origin -> markup but do not pseudomize and replace those countries that few people come from -->
      
   - < zip_code >: Replace letters with ABC and each number with 0 (ABC 0000), keep the delimiter

### 3. Institution: < institution > 
   * To use for: Schools, working place, team, etc. indications revealing the person’s school, working place, sport team, ...
  * Descriptor: < school > , < work > , < other_institution >
  * Pseudonymization: 
      - Replace with from a list of school names and companies (e.g. from Yellow pages) 
      
![alt text](https://spraakbanken.gu.se/sites/spraakbanken.gu.se/files/Anon_gen.png "xxx")


### 4. Transportation: < transport >, < transport_line >
  * < transport >: bus, metro, tram, train, express. Do not necessarily need to be replaced when used in generic terms, e.g. *I have several busses and metro near my house.* 
  * < transport_line > : number, color
  * Descriptor: 
  * Pseudonymization: 
      - Replace randomly with bus, metro, tram, or train 
      - In case of line number, replace actual number with 1, in case of several numbers in sequence, enumerate (1, 2, 3…)
      - Only replace entity when specific stops/stations are mentioned, not when transportation types are mentioned in general terms, e.g. in *Det finns en tunnelbana , heter Stadsbiblioteket och många buss-stationer nära* the only placeholder would be used for *Stadsbiblioteket*
      
<!--      - **_Do we need to replace "tunnelbana" och "buss-stationer" in the following context: "Det finns en tunnelbana , heter XXX och många buss-stationer nära" (Elena, A18AT1)? They seem to be generally descriptive, though probably can help identify the city that the person lives in. If yes, how do we represent "plural" in "buss-stationer"?_** -->

### 5. Age: < age-digits >, < age-string >
  * Person’s age (e.g. 18 years old)
  * Pseudonymization: 
      - Change the year within the range of numbers in 5-year interval. If an author writes 18 y.o., provide a number from a range of numbers < age > (+ - 2) - > e.g. 16-20
      - The same as above applies to < age-string > , rendered in strings
      - **_??? There is a complication, though: if for example age is written in letters (and also misspelled, like "niotton" or "sIxtton"), then automatic replacement becomes nontrivial. We need to have an option to add "pseudonimyzation" manually directly in the tool by rewriting the target token. At the moment this is not possible.  Another issue with this is that misspelling can be pretty bad and there is a need for "interpretation" by an assistant, e.g. "åttonde" år (elder sister) versus "tionde" år (little sister). Added as an issue for anonymization tool. (Elena, A10AT1) ???_**
         

### 6. Dates (all elements directly related to an individual, day, month, year) 
  * Types: < day > , < month-digit >, < month-word >, < year >, <date-digits>. Keep the delimiters as in original (, . - /)
  * Descriptor: 
  * Pseudonymization: 
      - < day > - > random number between 1-28
      - < month-digit > - > random replace 1-12
      - < month-word > - > random replace: januari, februari, ...
      - < year > - > 5-year interval: e.g. 2013 is replaced by a random number from a range of numbers (+ - 2), i.e. 2011-2015
      - < date-digits > - used for all dates that are written as a sequence of numbers with delimiters. Replace all numbers with "1" and keep delimiters, e.g.   
* 2018-12-01 --> @date_digits --> 1111-11-11
* 18/01/12 -->  @date_digits --> 11/11/11 
* 180112 --> @date_digits --> 111111
* 18.01.12 --> @date_digits --> 11.11.11
* 01/12 --> @date_digits --> 11/11


### 7. Phone numbers < phone_nr >
  * Pseudonymization: 
      - Replace each number with a “0” in the sequence (0000-000000) and keep the delimiter
      
### 8. Email addresses < email >
  * Pseudonymization: 
      - One single for all: email@dot.com

### 9. [personal] web pages (URL) < url >
  * Pseudonymization: 
      - Replace all with url.com 

### 10. Social security numbers < personid_nr  >
  * Pseudonymization:  
      - Replace each number with 123456-0000, and keep the delimiter (-)

### 11. Account numbers < account_nr >
  * Pseudonymization: 
      - Replace each number with 0 and keep the delimiter(s)

### 12. Certificate/licence numbers (e.g. vehicle) < license_nr >
  * Pseudonymization: 
      - Replace letters with ABC and each number with 0 (ABC 0000)

### 13. Extra (something else, not covered but the previous categories)
  * Description: < oblig >, < nonoblig >
   - < oblig > need to be replaced because of sensitivity
   - < nonoblig > might be sensitive and replaced later

### 14. Mark up but do not pseudomize: 
  * Profession < prof >
      * Descriptor: < prof >, < edu> 
      - < prof > profession
      - < edu > education 
  * Sensitive information < sensitive >
      - Descriptor: 
      * e.g. political or religious views, number of siblings, family members

      Example: 
I en dag såg vi en stor demstration det var för mycket människor vill inte Turkiets statsminister Ardogan och vi kände mycket glad för att det var första dag ser vi en fri demstration. 
->
I en dag såg vi en stor demstration det var för mycket människor vill inte Turkiets statsminister Ardogan och < sensitive >. 


### 15. Comments < OBS! >
   * Use for marking place to return to. The label(s) get red-pink background for easier identification when there is a need to return to it/them.
   

![](https://ws.spraakbanken.gu.se/ws/swell/png?'Alice%5C's'%3A1%3AOBS!%3A'firstname%3Afemale'%3Agen%20wallet%20was%20stolen%20.%2F%2F'Alice%5C's'%20wallet%20was%20stolen%20.)

## For < sensitive > we need to evaluate if subgroups are needed: 
religion, ethnicity, sexual orientation, political views, events that might reveal a person, physical and mental disabilities
Number of siblings, family members

## To be included: 
Examples
Original:
Jag heter Ali och bor i Borlänge. Jag flyttade till Sverige för 1 år sedan. Jag har flytt från Afghanistan med min familj 2015. Jag har fem bröder och tre systrar. Vi bor på Tegelvägen 32. Jag vill jobba. Jag vill bli arkitekt. Sverige är skön. Jag är muslim.

Marked-up:
Jag heter <firstname1-m> och bor i <city1>. Jag flyttade till Sverige för 1 år sedan. Jag har flytt från <country_of_origin>,  med min familj <year-2012-2018>. Jag har <sensitive> bröder och <sensitive> systrar. Vi bor på <street1> <street_nr>. Jag vill jobba. Jag vill bli <prof>. Sverige är skön. Jag är <sensitive>.

Pseudonymized*: 
Jag heter Mohammed och bor i Göteborg. Jag flyttade till Sverige för 1 år sedan. Jag har flytt från Afghanistan med min familj 2013. Jag har två bröder och två systrar. Vi bor på Gustavsgatan 1. Jag vill jobba. Jag vill bli <prof>. Sverige är skön. Jag är <sensitive>.


