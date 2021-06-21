# **Metadata description: SpIn** 

(a subcorpus in SweLL-pilot)

*Elena Volodina, 2021-06-11*

_____________________________________________________________________________________
## Contents
[1. General information](#1-general-information)

  - [1.1 Description of the project](#11-description-of-the-project)
  
  - [1.2 Description of the SpIn subcorpus](#12-description-of-the-SpIn-subcorpus)
  
  - [1.3 To cite SpIn subcorpus](#13-to-cite-SpIn-subcorpus)

[2. Metadata description for the SpIn corpus](#2-metadata-description-for-the-SpIn-corpus)    

  - [2.1 Personal metadata](#21-personal-metadata)

  - [2.2 Task metadata](#22-task-metadata)    

  - [2.3 Essay metadata](#23-essay-metadata)

  - [2.4 School metadata](#24-school-metadata)

  - [2.5 Anonymization](#25-anonymization)    
  
_____________________________________________________________________________________
## 1. General information

**Total nr essays**: 256  (June, 19, 2021)

**Nr sentences**: 4 327

**Nr tokens**: 44 996, incl. punctuation

**Levels represented**: A1, A2, B1, B2

**No manual coding/labeling** was performed, except very basic anonymization

_____________________________________________________________________________________

### 1.1 Description of the project

SpIn is a subcorpus of SweLL-pilot collection of learner essays written by adult immigrants learning Swedish in Sweden. The essays were collected from the courses provided at the Center for Language Introduction (Centrum för SpråkIntroduktion), which has given the name to this subcorpus. Learner filled in consent forms and allowed use of their essays and personal metadata for research. 

The work on this corpus was funded by *Språkbanken* and *Center for Language Technology* (CLT), both at the University of Gothenburg, Sweden, during 2012-2016. Part of the work on transcription and anonymization was carried out later as part of the *L2 profiles* < https://spraakbanken.gu.se/en/projects/l2profiles > and *SweLL infrastructure project* < https://spraakbanken.gu.se/en/projects/swell >. 

For approved users, SpIn is available through Korp search interface and/or as a full dataset via a link that is sent to approved users. To get access, see < https://tinyurl.com/y4vrmu9v >, section "Access to corpora". 

The SpIn corpus is maintained at the University of Gothenburg, Språkbanken-Text < https://spraakbanken.gu.se >, as part of the SweLL infrastructure.  

_____________________________________________________________________________________

### 1.2 Description of the SpIn subcorpus 

(*Version from 2016*) Elena Volodina, Ildikó Pilán, Ingegerd Enström, Lorena Llozhi, Peter Lundkvist, Gunlög Sundberg, Monica Sandell. 2016. SweLL on the rise: Swedish Learner Language corpus for European Reference Level studies. Proceedings of LREC 2016, Slovenia. < https://arxiv.org/pdf/1604.06583.pdf >

(*Version from 2021*) The above article + updated statistics in this documentation. The major difference between the versions from 2016 and 2021 is that additional 112 essays have been transcribed and anonymized. Additionally, all attributes and the corresponding values (e.g. level, language names, etc) have been harmonized between several other learner subcorpora in the SweLL collection to make possible searches in several of them at the same time.

*Personal data management*: Essays were collected following a consent from the learners. The consent allows the use of essays for research by registered (approved) users. Handwritten essays were transcribed and manually anonymized according to the principles described in Volodina et al (2016) above.

*Mode/format*: All essays were written as mid-term exams, in a classroom setting. Most of the essays were written by hand and were transcribed later according to the Transcription guidelines (see Volodina et al., 2016).

*Time constraints* varies between tasks; No *access to extra materials* was allowed (see details in Task Metadata).

To get information on access to SpIn and other SweLL corpora, see the webpage: 
https://spraakbanken.gu.se/en/projects/swell/swell4users and
https://spraakbanken.gu.se/projekt/swell/l2korp 

_____________________________________________________________________________________

### 1.3 To cite the SpIn subcorpus

Elena Volodina, Ildikó Pilán, Ingegerd Enström, Lorena Llozhi, Peter Lundkvist, Gunlög Sundberg, Monica Sandell. 2016. SweLL on the rise: Swedish Learner Language corpus for European Reference Level studies. Proceedings of LREC 2016, Slovenia. < https://arxiv.org/pdf/1604.06583.pdf >

_____________________________________________________________________________________



## 2. Metadata description for the SpIn corpus
_____________________________________________________________________________________

### 2.1 Personal metadata

Explanatory term [*attribute name in Korp / attribute name in the xml file*]

| ***General*** |   |
|:-------------|:--------------|
|• Student ID [*student ID / student_id*]|166 unique students, e.g. S16. Letter prefix (for a school) + a running number|
|• Age in 5-year intervals [*age / age*] | Age groups in SpIn: 16-20; 21-25; 26-30 |
|• Birth year in 5-year intervals [*birth year / birthyear_interval*]|1990-1994 => 7 students|
||1995-1999 => 151 students|
||2000-2004 => 3 students|
||unknown => 5 students|
|• Gender [*gender / gender*]|Kvinna => 54 |
||Man => 110|
||Unknown => 2|
|• Time in Sweden (sum in months) [*residence / time_in_sweden*]|0 - 42 |
|• Native language(s) [*native language / iso_l1*]|29  unique languages in 38 unique combinations of 1-3 languages|
|• Education level [*education level / edu_level*]|0-6 years => 65|
||7-9  years => 44|
||10-13 years => 52|
||14+ years => 0|
||N/A => 5|
|• Exam [*exam / exam*]|Educational certificate, if available. Free text.|

_____________________________________________________________________________________

### 2.2 Task metadata

Explanatory term [*attribute name in Korp / attribute name in the xml file*]

|***Administrative Metadata***||
|:-------------|:--------------|
|• Task ID [*task id / task_id*]|Task ID in the corpus. A letter prefix (for a school) + T(ask) + a running number, e.g. AT14. Total of 37 unique tasks|
|• Datum [*date / datum*]|Automatic Korp value, e.g. “2014-01-01”|
|• Task date [*task date / task_date*]| The year and week (year-week) when the essay was written, e.g. 2012-W44 (SpIn data collected during 2012-2016)|
|• Course type / school form [*school type / school_type*]|Ungdomsgymnasiet|
|• Course level [*course subject / course_subject*]|Språkintroduktion för nyanlända|
|• Grading scale [*grading scale / grading_scale*]|CEFR (A1-B2)|
|***Writing task details***||
|• Task type [*task type / task_type*]|E.g. formativ skrivuppgift, mitterminsprov, exam|
|• Task - format [*task format / task_format*]|Handwritten, Digital|
|• Task duration (in minutes)|25--180|
|• Text type / genre [*genre / text_types*]|E.g. berättande, argumenterande|
|• Task instructions |N/A for SpIn|
|• Allowed aids|None|
|• Tasks - subject / topic [*task subject / subject*]|E.g. Min skola, Bästa dag i mitt liv, etc.|
|• Lessontext_topic [*lessontext_topic / lessontext_topic*]|Topics in accordance with COCTAILL taxonomy < https://www.aclweb.org/anthology/W14-3510.pdf >|
|• Task-url|N/A for SpIn. Handouts for the tasks were not used or made available|

_____________________________________________________________________________________

### 2.3 Essay metadata

Explanatory term [*attribute name in Korp / attribute name in the xml file*]

|***Description***||
|:-------------|:--------------|
|• CEFR level [*proficiency level / cefr_level*]|A1 => 59 essays|
||A2 => 143 essays|
||B1 => 46|
||B2 => 2|
||Unknown => 6   |                 
|• Grade [*grade / grade*]|N/A|
|• Full text [*full text / svala_link*] |A link to the full essay that opens in SVALA annotation tool |

_____________________________________________________________________________________

### 2.4 School metadata

Explanatory term [*attribute name in Korp / attribute name in the xml file*]

|***Description***||
|:-------------|:--------------|
|School ID [*source / source*]|Letter *S* for Centrum för **S**pråkintroduktion|
||a one-year intensive program that aims to prepare newly arrived refugees/learners for the next transitional training stage before they can proceed with the upper-secondary studies at national Swedish schools|

_____________________________________________________________________________________

### 2.5 Anonymization

|***Description***||
|:-------------|:--------------|
|Names, streets|Format: NN, NN-gata|



