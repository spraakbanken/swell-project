# Anonymization guidelines

The purpose of anonymization is to de-identify all information that can reveal the identity of the person who wrote the text. This information can include person names, age, areas, cities and need to be replaced or overseen to ensure anonymity. Your task is to 1) identify information that can relate to a person, and categorize what type of information it is so that we? can change that information. This document contains instructions for how to proceed. 

## Basic principles

1. Remove/change the information that can reveal a person behind the essay(s), yet keep to the “minimal change” rule. The data should be usable in research scenarios.  _Example?_ 

2. Annotators have to make the assessment of the risks and needs for pseudonymization (an element of subjectivity)

3. Keep track of whether the token is “original” or “masked”

4. Categories that need to be marked in the texts, but not necessarily replaced. We would  make an assessment later when we have enough statistics over the learners behind the essays: 
  * country of origin (_Jag kommer från Syrien_ versus _Jag kommer från Luxembourg_) - depending upon how many subjects in our database are from the named countries
  * country of “intermediate” residence (_Vi har stannat en månad i Turkiet_)
  * number of family members (_Jag har fem bröder och fyra systrar_) - we will need to see whether it is a normal pattern in many essays. If yes - no masking/suppression is necessary
  * professions (_Jag är webbutvikler_) 

5. Categories that can be used for discrimination, such as political views, religious convictions, sexual orientation, should also be marked - but not necessarily masked right away? A decision would need to be made by an annotator. E.g. _I en dag såg vi en stor demstration det var för mycket människor vill inte Turkiets statsminister Ardogan och vi kände mycket glad för att det var första dag ser vi en fri demstration._

## Pseudonymize: 

### 1. Names: 
  * Types: < surname > < firstname > < middlename > 
  * Descriptor: 
      - Gender: male, female, unknown < m > , < f > , < unk >
      - Case: genitive < gen > 
      - Initial:  < ini > 
      - Running number: < 1, 2… >  [enumerate each unique name type entity with a number starting with 1]
      - Misspelled: < ort > 
  * Pseudonymization: 
      - Provide a list with first names, male, female and gender neutral (incl. international). 
      - For surnames, gender-specific types, when unclear use gender-neutral names (e.g. Andrea, Charlie, Kim, Tayler) 
      - Provide a list with surnames (incl. international)
      - Middlenames: Replace with an initial “A”
      - Initial replaced by “A”
      - Change token by token
  * To consider: 
      - allow cross-reference/anaphora resolution, i.e. allow to keep track of the entities that the L2 learner refers to, e.g. if more than one unique name occurs in the text, each unique name shall be replaced by a unique pseudonym 
      - random substitution for each unique name in the text given a list of names or
      - select a few names (while keeping the gender and cross-reference info) and use these names - throughout all texts
      - Use typical names for various ethnicities
      
![](https://ws.spraakbanken.gu.se/ws/swell/png?mode%3Aanon%20Alice~Alice%3A'firstname%3Afemale'%3A1%20and~and%20Bob~Bob%3A'firstname%3Amale'%3A2%20went~went%20to~to%20Paris~Paris%3Acity%20.%40s6~%40s6%20'Alice%5C's'~'Alice%5C's'%3A'firstname%3Afemale'%3A1%3Agen%20wallet~wallet%20was~was%20stolen~stolen%20.%40s11~%40s11%2F%2F'firstname%3Afemale'~Alice%201~Alice%20and~and%20'firstname%3Amale'~Bob%202~Bob%20went~went%20to~to%20city~Paris%20.~%40s6%20'firstname%3Afemale'~'Alice%5C's'%201~'Alice%5C's'%20gen~'Alice%5C's'%20wallet~wallet%20was~was%20stolen~stolen%20.~%40s11)

### 2. Institution: < institution > 
   * To use for: Schools, working place, team, etc. indications revealing the person’s school, working place, sport team, ...
  * Descriptor: < school > , < work > , < other_institution >
  * Misspelled: < ort >
  * Pseudonymization: 
      - Replace with from a list of school names and companies (e.g. from Yellow pages) 

### 3. Geographic data (country, city, zip codes, area names, …)
  * Types: < country_of_origin > , < country > , < geo > , < zip_code > , < region > , < city-SWE > , < city > , < area > , < street > , < number >
      - < country > : except Sweden
      - < city > : city including villages (på svenska “ort”)
         
         ![alt text](https://spraakbanken.gu.se/sites/spraakbanken.gu.se/files/Anon_gen.png "xxx")
         
         
         ![](https://ws.spraakbanken.gu.se/ws/swell/png?mode%3Aanon%20Jag%40s0~%40s0%20bor%40s1~%40s1%20i%40s2~%40s2%20en%40s3~%40s3%2040kvm~40kvm%20l%C3%A4genhet~l%C3%A4genhet%20i%40s6~%40s6%20Vasastan~Vasastan%3Aarea%3A1%20tisammans%40s8~%40s8%20med%40s9~%40s9%20min~min%20sambo~sambo%20.%40s12~%40s12%20Vi~Vi%20har~har%20bott%40s15~%40s15%20tisammans%40s16~%40s16%20f%C3%B6r~f%C3%B6r%20tv%C3%A5~tv%C3%A5%20eller~eller%20tre~tre%20%C3%A5r~%C3%A5r%20nu.~nu.%20V%C3%A5r~V%C3%A5r%20legenhet~legenhet%20ligger~ligger%20p%C3%A5%40s26~%40s26%20f%C3%B6rsta~f%C3%B6rsta%20v%C3%A5ning%2C~v%C3%A5ning%2C%20so~so%20m%C3%A5nga%40s30~%40s30%20folk~folk%20passera~passera%20och%40s33~%40s33%20g%C3%A5~g%C3%A5%20upp%40s35~%40s35%20trapperna~trapperna%20.%40s37~%40s37%20Det%40s38~%40s38%20finns%40s39~%40s39%20m%C3%A5nga%40s40~%40s40%20aff%C3%A4rer~aff%C3%A4rer%20och%40s42~%40s42%20resturanger~resturanger%20n%C3%A4ra~n%C3%A4ra%20%2C%40s45~%40s45%20och%40s46~%40s46%20R%C3%A5dmansgatan~R%C3%A5dmansgatan%3Astreet%3A2%20tunnelbana~tunnelbana%3Atransport%3A3%20station~station%20finns%40s50~%40s50%20bara~bara%20200m~200m%20promonera~promonera%20.%40s54~%40s54%20Fr%C3%A5n~Fr%C3%A5n%20mitt~mitt%20f%C3%B6nster~f%C3%B6nster%20jag%40s58~%40s58%20kan%40s59~%40s59%20ser~ser%20Stadsbibliotekets~Stadsbibliotekets%3A'other_institution'%3A4%3Agen%20bussh%C3%A5llplats~bussh%C3%A5llplats%20.%40s63~%40s63%20Det%40s64~%40s64%20%C3%A4r%40s65~%40s65%20bra%40s66~%40s66%20s%C3%A5%40s67~%40s67%20man~man%20kan%40s69~%40s69%20springer~springer%20till%40s71~%40s71%20n%C3%A4sta~n%C3%A4sta%20bussen~bussen%20.%40s74~%40s74%20M%C3%A5nga~M%C3%A5nga%20bilar~bilar%20k%C3%B6rar~k%C3%B6rar%20upp%40s78~%40s78%20och%40s79~%40s79%20ner~ner%20gatan~gatan%20v%C3%A4rje~v%C3%A4rje%20kv%C3%A4ll%2C~kv%C3%A4ll%2C%20det%40s84~%40s84%20%C3%A4r%40s85~%40s85%20inte~inte%20s%C3%A5%40s87~%40s87%20bra%40s88~%40s88%20'.%0A%0A'%40s89~%40s89%20F%C3%B6rre~F%C3%B6rre%20jag%40s91~%40s91%20flyttade~flyttade%20till%40s93~%40s93%20sverige%40s94~%40s94%20jag%40s95~%40s95%20bott%40s96~%40s96%20i%40s97~%40s97%20en%40s98~%40s98%20stor~stor%20r%C3%A5dhus~r%C3%A5dhus%20i%40s101~%40s101%20London%2C~London%2C%3Acity%3A5%20Storbritanien~Storbritanien%3Acountry%3A6%3Aort%20.%40s104~%40s104%20Jag%40s105~%40s105%20delade~delade%20husen~husen%20me~me%20fyra~fyra%20kompisar~kompisar%20%2C%40s111~%40s111%20det%40s112~%40s112%20var~var%20j%C3%A4ttekul~j%C3%A4ttekul%20.%40s115~%40s115%20London~London%3Acity%3A5%20%C3%A4r%40s117~%40s117%20mycket%40s118~%40s118%20dyrt%40s119~%40s119%20%2C%40s120~%40s120%20s%C3%A5%40s121~%40s121%20jag%40s122~%40s122%20plannerade~plannerade%20att~att%20flytat~flytat%20till%40s126~%40s126%20sverige%40s127~%40s127%20till%40s128~%40s128%20studerar~studerar%20dataventskap~dataventskap%3Aedu%3A7%20p%C3%A5%40s131~%40s131%20Stockholms~Stockholms%3Acity-SWE%3A8%3Agen%20Universitet~Universitet%20.%40s134~%40s134%20Utbildning~Utbildning%20%C3%A4r%40s136~%40s136%20mycket%40s137~%40s137%20billigare~billigare%20i%40s139~%40s139%20Sverie~Sverie%20%C3%A4n~%C3%A4n%20England~England%3Acountry%3A6%20'.%0A%0A'%40s143~%40s143%20I~I%20framtid~framtid%20jag%40s146~%40s146%20vill~vill%20bor%40s148~%40s148%20i%40s149~%40s149%20ett~ett%20hus~hus%20med%40s152~%40s152%20g%C3%A5rd%2C~g%C3%A5rd%2C%20s%C3%A5%40s154~%40s154%20jag%40s155~%40s155%20kan%40s156~%40s156%20f%C3%A5~f%C3%A5%20en%40s158~%40s158%20hund~hund%20.%40s160~%40s160%20Jag%40s161~%40s161%20m%C3%A5ste~m%C3%A5ste%20spara~spara%20mycket%40s164~%40s164%20pengar~pengar%20%2C%40s166~%40s166%20bost%C3%A4der~bost%C3%A4der%20i%40s168~%40s168%20Stockholm~Stockholm%3Acity-SWE%3A8%20%C3%A4r%40s170~%40s170%20dyrt%40s171~%40s171%20ocks%C3%A5~ocks%C3%A5%20'!%0A'~'!%0A'%2F%2FJag~%40s0%20bor~%40s1%20i~%40s2%20en~%40s3%2040kvm~40kvm%20l%C3%A4genhet~l%C3%A4genhet%20i~%40s6%20area~Vasastan%201~Vasastan%20tisammans~%40s8%20med~%40s9%20min~min%20sambo~sambo%20.~%40s12%20Vi~Vi%20har~har%20bott~%40s15%20tisammans~%40s16%20f%C3%B6r~f%C3%B6r%20tv%C3%A5~tv%C3%A5%20eller~eller%20tre~tre%20%C3%A5r~%C3%A5r%20nu.~nu.%20V%C3%A5r~V%C3%A5r%20legenhet~legenhet%20ligger~ligger%20p%C3%A5~%40s26%20f%C3%B6rsta~f%C3%B6rsta%20v%C3%A5ning%2C~v%C3%A5ning%2C%20so~so%20m%C3%A5nga~%40s30%20folk~folk%20passera~passera%20och~%40s33%20g%C3%A5~g%C3%A5%20upp~%40s35%20trapperna~trapperna%20.~%40s37%20Det~%40s38%20finns~%40s39%20m%C3%A5nga~%40s40%20aff%C3%A4rer~aff%C3%A4rer%20och~%40s42%20resturanger~resturanger%20n%C3%A4ra~n%C3%A4ra%20%2C~%40s45%20och~%40s46%20street~R%C3%A5dmansgatan%202~R%C3%A5dmansgatan%20transport~tunnelbana%203~tunnelbana%20station~station%20finns~%40s50%20bara~bara%20200m~200m%20promonera~promonera%20.~%40s54%20Fr%C3%A5n~Fr%C3%A5n%20mitt~mitt%20f%C3%B6nster~f%C3%B6nster%20jag~%40s58%20kan~%40s59%20ser~ser%20'other_institution'~Stadsbibliotekets%204~Stadsbibliotekets%20gen~Stadsbibliotekets%20bussh%C3%A5llplats~bussh%C3%A5llplats%20.~%40s63%20Det~%40s64%20%C3%A4r~%40s65%20bra~%40s66%20s%C3%A5~%40s67%20man~man%20kan~%40s69%20springer~springer%20till~%40s71%20n%C3%A4sta~n%C3%A4sta%20bussen~bussen%20.~%40s74%20M%C3%A5nga~M%C3%A5nga%20bilar~bilar%20k%C3%B6rar~k%C3%B6rar%20upp~%40s78%20och~%40s79%20ner~ner%20gatan~gatan%20v%C3%A4rje~v%C3%A4rje%20kv%C3%A4ll%2C~kv%C3%A4ll%2C%20det~%40s84%20%C3%A4r~%40s85%20inte~inte%20s%C3%A5~%40s87%20bra~%40s88%20'.%0A%0A'~%40s89%20F%C3%B6rre~F%C3%B6rre%20jag~%40s91%20flyttade~flyttade%20till~%40s93%20sverige~%40s94%20jag~%40s95%20bott~%40s96%20i~%40s97%20en~%40s98%20stor~stor%20r%C3%A5dhus~r%C3%A5dhus%20i~%40s101%20city~London%2C%205~London%2C%20country~Storbritanien%206~Storbritanien%20ort~Storbritanien%20.~%40s104%20Jag~%40s105%20delade~delade%20husen~husen%20me~me%20fyra~fyra%20kompisar~kompisar%20%2C~%40s111%20det~%40s112%20var~var%20j%C3%A4ttekul~j%C3%A4ttekul%20.~%40s115%20city~London%205~London%20%C3%A4r~%40s117%20mycket~%40s118%20dyrt~%40s119%20%2C~%40s120%20s%C3%A5~%40s121%20jag~%40s122%20plannerade~plannerade%20att~att%20flytat~flytat%20till~%40s126%20sverige~%40s127%20till~%40s128%20studerar~studerar%20edu~dataventskap%207~dataventskap%20p%C3%A5~%40s131%20city-SWE~Stockholms%208~Stockholms%20gen~Stockholms%20Universitet~Universitet%20.~%40s134%20Utbildning~Utbildning%20%C3%A4r~%40s136%20mycket~%40s137%20billigare~billigare%20i~%40s139%20Sverie~Sverie%20%C3%A4n~%C3%A4n%20country~England%206~England%20'.%0A%0A'~%40s143%20I~I%20framtid~framtid%20jag~%40s146%20vill~vill%20bor~%40s148%20i~%40s149%20ett~ett%20hus~hus%20med~%40s152%20g%C3%A5rd%2C~g%C3%A5rd%2C%20s%C3%A5~%40s154%20jag~%40s155%20kan~%40s156%20f%C3%A5~f%C3%A5%20en~%40s158%20hund~hund%20.~%40s160%20Jag~%40s161%20m%C3%A5ste~m%C3%A5ste%20spara~spara%20mycket~%40s164%20pengar~pengar%20%2C~%40s166%20bost%C3%A4der~bost%C3%A4der%20i~%40s168%20city-SWE~Stockholm%208~Stockholm%20%C3%A4r~%40s170%20dyrt~%40s171%20ocks%C3%A5~ocks%C3%A5%20'!%0A'~'!%0A')
         
         
         
      
      - < geo >: forest, lake, mountain, etc
      - < zip_code >: replace each number with zero
      - < street >: square
      - < street_nr > : street number
  * Descriptor: 
      - Misspelled: < ort >
  * Pseudonymization: 
      - Random substitution given a list of named entities of various attributes for each attribute, except for Sweden, and country of origin
      - Country of origin -> markup but do not pseudomize and replace those countries that few people come from
      - < zip_code >: Replace letters with ABC and each number with 0 (ABC 0000), keep the delimiter

### 4. Transportation: < transport >, < transport_line >
  * < transport >: bus, metro, tram, train, express
  * < transport_line > : number, color
  * Descriptor: 
      - Misspelled: < ort >
  * Pseudonymization: 
      - Replace randomly with bus, metro, tram, or train 
      - In case of line number, replace actual number with 1, in case of several number in sequence, enumerate (1, 2, 3…)

### 5. Age: < age >
  * Person’s age (e.g. 18 years old)
  * Pseudonymization: 
      - Change the year within the range of numbers in 5-year interval. If an author writes 18 y.o., provide a number from a range of numbers < age > (+ - 3) - > e.g. 15-21
         

### 6. Dates (all elements directly related to an individual, day, month, year) 
  * Types: < day > , < month-digit >, < month-word >, < year >. Keep the delimiters as in original (, . - /)
  * Descriptor: 
      - Misspelled: < ort >
  * Pseudonymization: 
      - < day > - > random number between 1-28
      - < month-digit > - > random replace 1-12
      - < month-word > - > random replace: januari, februari, ...
      - < year > - > 5-year interval: e.g. 2013 is replaced by a random number from a range of numbers (+ - 3), i.e. 2010-2016

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

### 14. Mark up but do not pseudomize: 
  * Profession < prof >
      - Descriptor: < prof >, < edu> 
      - Misspelled: < ort >
  * Sensitive information < sensitive >
      - Descriptor: 
      - Misspelled: < ort >

### 15. Comments < OBS! >
   * Use for marking place to return to. The label(s) get red-pink background for easier identification when there is a need to return to it/them.
   

![](https://ws.spraakbanken.gu.se/ws/swell/png?'Alice%5C's'%3A1%3AOBS!%3A'firstname%3Afemale'%3Agen%20wallet%20was%20stolen%20.%2F%2F'Alice%5C's'%20wallet%20was%20stolen%20.)

## Evaluate if subgroups are needed: 
religion, ethnicity, sexual orientation, political views, events that might reveal a person, physical and mental disabilities
Number of siblings, family members

## To be included: 
Examples
