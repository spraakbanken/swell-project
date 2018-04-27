# Anonymization guidelines

The purpose of anonymization is to de-identify all information that can reveal the identity of the person who wrote the text. This information can include person names, age, areas, cities and need to be replaced or overseen to ensure anonymity. Your task is to 1) identify information that can relate to a person, and categorize what type of information it is so that we? can change that information. This document contains instructions for how to proceed. 

## Basic principles


Remove/change the information that can reveal a person behind the essay(s), yet keep to the “minimal change” rule. The data should be usable in research scenarios.  Example? 

![](https://ws.spraakbanken.gu.se/ws/swell/png?He%20get%20to%20cleaned%20his%20son~son%20.%2F%2FHe%20got%20his%20son~son%20to%20cleaned%20his%20room%20.)

Annotators have to make the assessment of the risks and needs for pseudonymization (an element of subjectivity)

Keep track of whether the token is “original” or “masked”

Categories that need to be marked in the texts, but not necessarily replaced. We would  make an assessment later when we have enough statistics over the learners behind the essays: 
country of origin (Jag kommer från Syrien versus Jag kommer från Luxembourg) - depending upon how many subjects in our database are from the named countries
country of “intermediate” residence (Vi har stannat en månad i Turkiet )
number of family members (Jag har fem bröder och fyra systrar) - we will need to see whether it is a normal pattern in many essays. If yes - no masking/suppression is necessary
professions (Jag är webbutvikler) 

Categories that can be used for discrimination, such as political views, religious convictions, sexual orientation, should also be marked - but not necessarily masked right away? A decision would need to be made by an annotator. E.g. I en dag såg vi en stor demstration det var för mycket människor vill inte Turkiets statsminister Ardogan och vi kände mycket glad för att det var första dag ser vi en fri demstration.

Pseudonymize: 
Names: 
Types: <surname><firstname><middlename>
Descriptor: 
Gender: male, female, unknown <m>, <f>, <unk>
Case: genitive <gen>
Initial:  <ini>
Running number: <1, 2…> [enumerate each unique name type entity with a number starting with 1]
Misspelled: <ort>
	
![](https://ws.spraakbanken.gu.se/ws/swell/png?Their%3A'firstname%3Amale'_was_a_problem_yesteray_.//There_was_a_problem_yesterday_.)

Pseudonymization: 
Provide a list with first names, male, female and gender neutral (incl. international). 
For surnames, gender-specific types, when unclear use gender-neutral names (e.g. Andrea, Charlie, Kim, Tayler) 
Provide a list with surnames (incl. international)
Replace with an initial “A” Provide a list with middle names (incl. international)  
Initial replaced by “A”
Change token by token

To consider: 
allow cross-reference/anaphora resolution, i.e. allow to keep track of the entities that the L2 learner refers to, e.g. if more than one unique name occurs in the text, each unique name shall be replaced by a unique pseudonym 
random substitution for each unique name in the text given a list of names or
select a few names (while keeping the gender and cross-reference info) and use these names - throughout all texts
Use typical names for various ethnicities

Institution: <institution>
Schools, working place, team, etc. revealing the person’s school, working place, sport team, ...
Descriptor: 
<school>, <work>, <other_institution>
Misspelled: <ort>
Pseudonymization: 
Replace with from a list of school names and companies (e.g. from Yellow pages) 

Geographic data (country, city, zip codes, area names, …)
Type: <country_of_origin>, <country>, <geo>,<zip_code>, <region>, <city-SWE>, <city>, <area>, <street>, <number>
	<country>: except Sweden
<city>: city including villages (på svenska “ort”)
	<geo>: forest, lake, mountain, etc
	<zip_code>: replace each number with zero
	<street>: square
	<street_nr>: street number

Descriptor: 
Misspelled: <ort>

Pseudonymization: 
Random substitution given a list of named entities of various attributes for each attribute, except for Sweden, and country of origin
Country of origin -> markup but do not pseudomize and replace those countries that few people come from
<zip_code>: Replace letters with ABC and each number with 0 (ABC 0000), keep the delimiter

Transportation: <transport>, <transport_line>
<transport>: bus, metro, tram, train, express
<transport_line>: number, color
Descriptor: 
Misspelled: <ort>

Pseudonymization: 
Replace randomly with bus, metro, tram, or train 
In case of line number, replace actual number with 1, in case of several number in sequence, enumerate (1, 2, 3…)
Age: <age>
Person’s age (e.g. 18 years old)
Pseudonymization: 
Change the year within the range of numbers in 5-year interval. If an author writes 18 y.o., provide a number from a range of numbers <age> (+ - 3) -> e.g. 15-21

Dates (all elements directly related to an individual, day, month, year) <day>, <month-digit>, <month-word>, <year>. Keep the delimiters as in original (, . - /)
Descriptor: 
Misspelled: <ort>

Pseudonymization: 
<day> -> random number between 1-28
<month-digit> -> random replace 1-12
<month-word> -> random replace: januari, februari, ...
<Year> -> 5-year interval: e.g. 2013 is replaced by a random number from a range of numbers (+ - 3), i.e. 2010-2016

Phone numbers <phone_nr>
Pseudonymization: 
Replace each number with a “0” in the sequence (0000-000000) and keep the delimiter

Email addresses <email>
Pseudonymization: 
One single for all: email@dot.com

[personal] web pages (URL) <url>
Pseudonymization: 
Replace all with url.com 

Social security numbers <personid_nr>
Pseudonymization:  
Replace each number with 123456-0000, and keep the delimiter (-)

Account numbers <account_nr>
Pseudonymization: 
Replace each number with 0 and keep the delimiter(s)

Certificate/licence numbers (e.g. vehicle) <license_nr>
Pseudonymization: 
Replace letters with ABC and each number with 0 (ABC 0000)

Extra (something else, not covered but the previous categories)
Description: <oblig>, <nonoblig>


Mark up but do not pseudomize: 
Profession <prof>
Descriptor: <prof>, <edu>
Misspelled: <ort>

Sensitive information <sensitive>
Descriptor: 
Misspelled: <ort>

Evaluate if subgroups are needed: religion, ethnicity, sexual orientation, political views, events that might reveal a person, physical and mental disabilities
Number of siblings, family members

To be included: Examples
