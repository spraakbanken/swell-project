# Correction annotation guidelines

## Introduction

### The purpose of the correction annotation
The purpose of the correction annotation is to make the learner corpus searchable for different types of deviations from a standard language norm. The annotation of the learner texts according to the correction-taxonomy of the SweLL project is hence an important step in making the learner language assembled in the corpus analyzable for research and educational purposes.

### The purposes of this document
This document has three interconnected purposes:

* It documents choices made by the SweLL project group regarding the principles of the correction annotation.

* It provides guidance for annotators on how to apply the SweLL annotation taxonomy in order to ensure the greatest possible inter-annotator agreement.

* It provides the essential material for a thorough description of the correction annotation for future users of the Swell corpus. This projected description will accompany the published corpus.

### The organization of the document
The rest of this document is divided into two main sections: one section with general directions for the correction annotation, and one section on the SweLL correction annotation taxonomy.

## General directions for the correction annotation

### What is a correction? What is annotated?
By _correction_ we mean a difference between the original learner text and the normalized version of the text. The correction annotation is thus a categorization of such differences.

This means that the correction annotation only indirectly indicates properties of the source text. What is directly indicated is _the relationship between the original version and the normalized version of the text_. The correction annotation is thus highly dependent on the preceding normalization.

While the purpose of the correction annotation is to make the texts searchable for deviations from a standard language norm, such deviations are only possible to categorize on the basis of assumptions of the learner’s intended content, along with judgements of the acceptability and suitability of standard language expressions communicating that content. This means that _any_ annotation of “deviations”, “errors” etc. in learner texts is actually an annotation of a _relationship_ between (a segment of) the analyzed text and an assumed standard language version of the text (segment). By the choice of the term _correction annotation_ (rather than, for instance, _error annotation_) the SweLL project emphasizes these conditions of learner language analysis. The normalized text versions make explicit this necessary assumption about the standard version of the text to which the original text is related. (The principles underlying the normalization are described in the normalization guidelines.)

A consequence of the fundamental principle of annotating _corrections_, understood as differences between the original text and _one specific_ interpretation of this text, rather than “errors in general”, is that certain clear deviations from the norms of written standard Swedish in the original texts are left without annotations – because they are not deviations _in relation to the normalized text_. This occurs for instance when a misspelled word in the original text has been corrected to another word altogether. Such a correction will be annotated as an instance of a faulty choice of word (L-W), and since the word in the original text cannot be analyzed as a misspelling of the word in the normalized text, the spelling error will be left without annotation.

### Tags
The correction annotation is created by marking links between the original text and the normalized text with tags representing the categories in the SweLL correction annotation taxonomy, which is presented below. The tags are available in the Svala annotation tool in a list to the left on the screen.

A link may be tagged with one or several tags.

### Links between the original version and the normalized version of the text
The links on which the tags are placed are visualized as lines in the Svala annotation tool. They run between elements of the original text and corresponding elements of the normalized text. The linked text elements typically consist of one token in each text version, but they may also consist of more than one token in one of the texts or in both texts. Moreover, links may run between a text element in one text version and “nothing”. This is normally the case when tokens have been added or removed in the normalized version of the text.

During the normalization process, preliminary links between the original and the normalized texts are created automatically. These links may be adjusted during the correction annotation process. The correct link must be in place before a tag is inserted. Links may be adjusted in the following way:

In order to break a link, place the marker on one of the linked text elements or on the link itself, and press the _orphan_ button on the menu to the left.

In order to create a new link, mark all of the tokens which you wish to link (at least one token in the original text and at least one token in the normalized text) by clicking the tokens while holding ctrl (PC) or shift (Mac). Then press the _group_ button on the menu to the left.

### Document comments
The _Document comment_ field provides an opportunity to comment on deviations from the standard norm regarding text properties which cannot be adequately reflected by tags on individual links. This field may for instance be used when the verb tense choices in the text are inconsistent at a global text level, but when corrections of individual verb forms have generally not been made, since there is consistency more locally in the text.

The field may also be used for any kind of general comment on the text which the annotator regards as essential for the future corpus user.

## The Swell correction annotation taxonomy
In this section the Swell correction annotation taxonomy is presented, and directions on how to apply and interpret the tags associated with the correction categories are provided.

First, the general structure of the taxonomy is described. After that, the annotation categories are presented in the order in which they occur in the Svala annotation tool. After the presentation of all the correction categories follows a section on a few specific categorization issues, cutting through several correction categories. This includes the following sections:

*	Compounds vs multi-word expressions

*	Non-Swedish words and sequences

*	Verbal particles and reflexives

### The general structure of the taxonomy
The SweLL correction annotation taxonomy contains five main categories of correction types:

*	**Orthographic corrections (O)**, including “regular spelling corrections” (corrections of the string of letters), corrections between upper and lower case, and corrections of the use of spaces and hyphens between words.

*	**Lexical corrections (L)**, including 1) corrections of the choice of word and 2) corrections of the internal morphological structure of word stems – i.e. corrections regarding the formation of words through compounding and derivation.

*	**Morphological corrections (M)**, by which we specifically mean corrections concerning _inflectional morphology_. This category also covers some extra-morphological corrections which are closely related to inflectional forms and grammatical categories involving inflections.

*	**Punctuation corrections (P)**, including corrections of the choice of punctuation marks as well as the adding or removal of punctuation marks, and also instances of merging or splitting sentences.

*	**Syntactical corrections (S)**, i.e. corrections regarding the internal structure of multi-word phrases and clauses, including corrections of missing or redundant words, word order, the choice between a compound and a multi-word expression, and more complex syntactic corrections such as corrections between a finite clause structure and an infinitive phrase.

In addition to the correction tags included in these five main correction categories, the Svala tool provides six other tags, including tags for corrections made as a consequence of other corrections (C), corrections not covered by any of the defined correction categories (Unid), unintelligible strings (X), strings cited from a foreign language (Cit-FL), and finally two tags for notes and comments – OBS! for internal work notes, and Com! for comments intended for the corpus users.

In the following the annotation categories and their tags will be presented in the order in which they appear in the Svala annotation tool – i.e. the O tags first, followed by the four other main correction categories in alphabetic order (L, M, P, S), and, finally, the remaining six tags under the heading _Other tags_.

### O – Orthographic corrections

The O tags represent the orthographic correction category. It includes three sub-categories.

#### O (regular spelling correction)

The plain O tag is used for regular spelling corrections, i.e. when the string of letters is different in the original text and the normalized text, due to a spelling mistake.

_Examples_

*	Det **tåg** 6 timmar från Teheran till Göteborg -> **tog**

* Det finns **monga** affärer -> **många**

#### O-Cap (upper/lower case)

The O-Cap tag is used for corrections regarding the choice between upper and lower case letters.

_Examples_

*	Det fanns en affär och vi gick dit. **vi** köpte flera saker -> Det fanns en affär och vi gick dit. **Vi** köpte flera saker.

*	På **Måndag** är det den 3 **Mars**. -> På **måndag** är det den 3 **mars**.

#### O-Comp (spaces and hyphens between words)

The O-Comp tag is used for corrections which involve the removal of a space between two words which have been interpreted as making up a compound in the normalized text version, or, more rarely, the  adding of a space between two words. It may also be used for corrections regarding the use of hyphens in compounds.

This tag should only be used for corrections concerning the mere orthographic rendering – with or without a space or a hyphen – of a compound or a multi-word expression, and not for corrections which are rather to be interpreted as involving an actual alternation between a compound and a multi-word expression. The latter case is covered by the S-Comp tag. (See the S-Comp section, and the section on compounds vs multi-word expressions.)

_Examples_

*	Jag kände mig **jätte konstig** -> **jättekonstig**

* Det ligger ett **kultur hus** nära min bostad -> **kulturhus**

*	**kultur-hus** -> **kulturhus**

*	**New York bor** -> **New York-bor**

*	**New Yorkbor** -> **New York-bor**

*	**itisdags** -> **i tisdags**

*	**ochsåvidare** -> **och så vidare**

Corrections which involve both a removal of a space and a change of the form of the first part of the compound are tagged both with O-Comp and L-Der:

*	**Kommunikation förändring** -> **Kommunikationsförändring**

### L – Lexical corrections

The L tags represent the lexical correction category. It includes four sub-categories.

#### L-Der (word formation)

The L-Der tag represents the correction category _deviant word formation_. It is used for corrections of the internal morphological structure of word stems, both with regard to compounding and to derivation.

The L-Der tag is exclusively used for links between one-token units. It covers the following correction types:

*	A derivational affix has been corrected, e.g.: De är **stressiga** på grund av studier -> De är **stressade** på grund av studier
  
* A derivational affix has been added, e.g. **ändring** -> **förändring**

*	A derivational affix has been removed, e.g. **förstöra** -> **störa**

*	The form of the first part of a compound has been corrected (for instance by adding or removing a “foge-s”), e.g. **tvångsvenska** -> **tvångssvenska**; **sagabok** -> **sagobok**

*	A verbal particle of a compound form of a particle verb has been added, removed or corrected, e.g.:

     - Internet uppmanar vår förståelse  Internet utmanar vår förståelse
     
     - Han inhämtade väskorna från hotellrummet  Han hämtade väskorna från hotellrummet
     
     - Hon minde honom om mötet på eftermiddagen  Hon påminde honom om mötet på eftermiddagen
     
(See the special section on verbal particles and reflexives.)

**Note (1)**: Corrections of verbal particles of phrasal forms of particle verbs are not tagged with the L-Der tag, but with the L-W tag. (See the special section on verbal particles and reflexives.)

Note (2): The L-Der tag is not used for corrections which involve the addition of a -t suffix to an adjective which is used as an adverb, since this correction category is treated as a morphological correction with its own tag, M-Adj/adv.
L-FL (foreign word corrected to Swedish)
The L-FL tag is used for words from a foreign (non-Swedish) language which have been corrected to a Swedish word. It may also be applied to words which have certain non-Swedish traits due to influence from a foreign language.
Examples
•	Det fanns flera rum, två kök, balkony och trädgård  balkong
•	Jag och min family  familj
The L-FL tag is used for corrections with the following characteristics:
•	The word in the original text is recognizable as a word from a foreign language to the annotator (who is obviously not equally proficient in all languages). Alternatively, the annotator recognizes certain non-Swedish traits in the word which are due to influence from a foreign language.
•	The word in the original text may or may not be correctly formed and used according to the norms of the assumed influencing language.
•	The word in the original text may have both Swedish and foreign traits, but if it is identifiable as an existing well-established Swedish word which has been replaced by an altogether different word, it should not be marked as L-FL, but as L-W. This holds even if the deviant choice of words is clearly due to lexical influence from the foreign language. For instance, the following example should be marked as L-W, although it is likely that the faulty use of busiga is influenced by the English word busy. (See the section on non-Swedish words and sequences below.)
o	Alla blir busiga med sina sociala medier.  Alla blir upptagna med sina sociala medier
•	It is not reasonable to interpret the correction as a correction of a spelling mistake or a word formation mistake. In that case the correction should be tagged with the O tag or the L-Der tag respectively. In other words: The O and L-Der tags have higher priority than the L-FL tag. (See the section on non-Swedish words and sequences below.)
L-Ref (pronoun reference)
The L-Ref tag represents the correction category reference correction. It includes anaphoric pronouns which have been corrected in order to have the grammatical form (gender, number, reflexive/non-reflexive) which suits its reference as revealed by the context.
Examples
•	Jag har en bror, hon heter xx  han heter xx
•	Stämmer det att våra sociala media skapar individualism och ensamhet? Eller skapar det kontakter och trivs?  Eller skapar de kontakter …
•	Innan trädet blev borta dem fick fars äpplen och sin fru lagade saft och mos av äpplena  Innan trädet var borta fick de fars äpplen och hans fru lagade saft och mos av äpplena
L-W (wrong word or phrase)
The L-W tag represents the correction category wrong word or phrase. It is used when a word/fixed phrase in the original text is identifiable as a Swedish word/fixed phrase, but has been replaced with another word or construction in the normalized text. Among the kind of multi-word expressions which may be marked with this tag are phrasal verbs and multi-word prepositions.
FLER EXEMPEL SKA IN HÄR!
One word replaced by one word:
•	Uppfinningen som transformerade hela kommunikationsområdet  Uppfinningen som förändrade hela kommunikationsområdet
•	Jag bor i D-område på en lägenhet  Jag bor i D-område i en lägenhet .
•	På det sättet kan kommunen motionera alla medborgare att träna → På det sättet kan kommunen motivera alla medborgare att träna.
•	Jag bor samma med min bror  Jag bor tillsammans med min bror
•	Alla blir busiga med sina sociala medier.  Alla blir upptagna med sina sociala medier (See the section on non-Swedish words and sequences for further comments on this example.)
One word replaced by a multi-word expression:
•	EXEMPEL SKA IN HÄR
Multi-word expression replaced by one word:
•	EXEMPEL SKA IN HÄR
Multi-word expression (fixed phrase) replaced by another multi-word expression:
•	såsom våra ”moderna” språk är ibland en blandning av flera utrotade minoritetsspråk som under tiden skapade något nytt och unik  såsom våra ”moderna” språk ibland är en blandning av flera utrotade minoritetsspråk som med tiden skapade något nytt och unikt
Phrasal verb replaced by an expression with another main verb:
•	Traditioner ger människorna tid att stå still och fundera över livet → … att stanna upp och fundera över livet.
Verbal particle replaced by another verbal particle, but verb kept:
•	Han torkade bort bordet  Han torkade av bordet
In cases like this the verbal particle – not the whole phrasal verb – is marked with the tag L-W.
Note (1): Corrections consisting in the mere removal or addition of the reflexive sig or a verbal particle are not tagged with L-W, but with S-R or S-M respectively – even if both the bare verb and the phrasal verb may be characterized as lexical units. 
Note (2): While the marked element in the original text has to be either a word or a clear case of a fixed phrase, the substitute expression in the normalized text does not necessarily have to be a word or an indisputable case of a fixed phrase, but it suffices that it is a common endocentric phrase, such as mellan dem in the following exampel, which replaces sinsemellan in the original text:
•	plötsligt bröt muren sinsemellan  plötsligt rasade muren mellan dem
M – Morphological corrections
The M tags represent the category morphological corrections. It covers corrections related to inflections. This includes primarily corrections of individual inflectional forms, but in some cases also corrections of more complex grammatical constructions closely related to inflectional forms. The latter concerns basic definiteness constructions (see M-Def), the periphrastic comparative and superlative adjective constructions (see M-F), and tense-related verbal constructions involving auxiliaries (see M-Verb).
The category of morphological corrections includes eight sub-categories.
M-Adj/adv (adjective corrected to adverb)
The M-Adj/adv tag is used for corrections involving the change of an adjective to its t-form, when the t-form is called for due to the adjective being used as an adverb.
Examples
•	Användaren mår dålig  dåligt
•	Hur påverkar detta våra måenden långsiktig?  långsiktigt
M-Case
The M-Case tag is used for corrections regarding the choice of case form for nouns (nominative vs genitive) and pronouns (nominative vs accusative).
Examples
•	50 kilometer avstånd  kilometers
•	Som kan bidra till samhället utveckling  samhällets
•	Det ger man en positiv energi  Det ger en en positiv energi
•	Folk hinner inte prata med de  Folk hinner inte prata med dem
•	Ingen förstår hon  Ingen förstår henne
M-Def (definiteness)
The M-Def tag is used for corrections regarding definiteness constructions. The kinds of corrections which are involved in this correction category are:
•	Change between indefinite and definite forms of nouns (bok vs boken; rum vs rummet)
•	Change between, removal of and addition of indefinite and definite articles (en, ett; den, det, de). In these cases the M-Def tag has higher priority than the S-M and S-R tags.
•	Change between indefinite and definite forms of adjectives and adjective-like pronouns (stor/stort vs stora; egen/eget vs egna)
Examples
•	Vi gick till McDonalds och åt maten  mat
•	Jag trivs bättre på jobb här  jobbet
•	Jag har läst ditt mejlet  ditt mejl
•	min stor dag  min stora dag
•	De gränserna som fanns mellan kvinnor och män har nästan försvunnit  De gränser som fanns
•	När kommer den buss  När kommer bussen
•	Då kommer svenska språket försvinna ur Finska samhället  Då kommer svenska språket försvinna från det finska samhället
•	Han har egen rummet och jag egen  Han har ett eget rum och jag ett eget
M-F (wrong form, correct grammatical category)
The M-F tag is used when a declension/conjugation form (typically a suffix) which is used to express a specific grammatical category (e.g. number or plural) has been corrected to a form belonging to another declension/conjugation within the same grammatical category. The tag is used for the following correction types:
Nouns:
•	Correction of a plural suffix: båter  båtar
Note: Unsuffixed noun forms will be interpreted as singular when corrected to a suffixed plural form, although unsuffixed plurals exist. Corrections like båt  båtar will thus be tagged with the M-Num tag and not with the M-F tag.
Verbs:
•	Correction of a present tense suffix: jag lager mat  jag lagar mat
•	Correction of a past tense suffix: böjade  böjde
•	Correction of a supine suffix: kunnit  kunnat
•	Correction from a verb form with a basic stem form and a suffix (past tense or supine) to a stem-changed verb form (with or without suffix): sjungde  sjöng; drickit  druckit
Adjectives:
•	Correction of a comparative suffix: högare  högre
•	Correction of a superlative suffix: högast  högst
•	Correction from an adjective form (comparative or superlative) with a basic stem form and a suffix to a stem-changed form: långare  längre; ungast  yngst
•	Correction of the choice between a periphrastic and an inflectional comparative or superlative construction: I Sverige är mer kallt än i xx  I Sverige är det kallare än i xx
M-Gend (gender)
The M-Gend tag is used to mark corrections of gender forms (neuter vs non-neuter) of nouns, articles, adjectives, and pronouns with adjective-like functions.
Examples
•	Det är en mycket trevlig område  Det är ett mycket trevligt område
•	Den viktigaste är att …  Det viktigaste är att …
•	Den första telefonnät  Det första telefonnätet
•	Kommunikationen är möjligt  Kommunikationen är möjlig
•	Han har egen rummet och jag egen  Han har ett eget rum och jag ett eget (cf. the same example under M-Def)
The M-Gend tag is also used for corrections of the overuse of the distinctly masculine form of adjectives:
•	min käre mamma  min kära mamma
(Since the masculine form is never obligatory, corrections from the feminine/common form to the masculine form are not made during the normalization, and thus do never occur in the correction annotation process.)
Note: Gender corrections of pronouns which are due to their anaphoric reference will be covered by the L-Ref tag.
M-Num (number)
The M-Num tag is used to mark number corrections of nouns, articles, adjectives, and pronouns with adjective-like functions.
Examples
•	Stress kan komma i många form  Stress kan komma i många former
•	Så fort bilder är tagen  Så fort bilderna är tagna
•	Alla sitter bakom sina skärmens sken  Alla sitter bakom sina skärmars sken
Note: Number corrections of pronouns which are due to their anaphoric reference will be covered by the L-Ref tag.
M-Other
The M-Other tag is used for corrections involving inflectional morphology for which none of the other M tags are suited, or for ambiguous cases when different sound interpretations of the correction lead to different M tags.
Examples
•	det är ett lite hus  litet
Note: Take care not to overuse the M-Other tag. The other M tags should be carefully considered before choosing this one.
M-Verb
The M-Verb tag covers corrections regarding inflectional verb forms and basic tense constructions involving auxiliaries.
The verb-related grammatical categories involved are primarily tense, mode and voice.
The verb forms involved are the non-finite verb forms (infinitive and supine), the basic tense forms (present and past), the imperative, and the s-forms (both when used in passive constructions and in other uses).
The extra-inflectional constructions involved are the tense-related constructions including the auxiliary verbs ha, skola and komma and the non-finite verb forms.
Examples
•	Jag trivs där för att jag hade fler vänner  Jag trivdes där för att jag hade fler vänner
•	Slutligen tror jag att sociala medier blev en essentiell del  Slutligen tror jag att sociala medier har blivit en essentiell del
•	Det betyder inte att vi glomma bort vår tradition  Det betyder inte att vi ska glömma bort vår tradition
•	Världen utvecklar i teknologin i varje minut  Världen utvecklas i teknologin i varje minut
P – Punctuation corrections
The P tags represent the category of punctuation corrections, including instances of of merging or splitting sentences. It has four sub-categories.
P-M (missing punctuation)
The P-M tag is used for corrections involving the addition of a punctuation mark.
Examples
•	Jag har fyra barn två pojkar och två flickor  Jag har fyra barn, två pojkar och två flickor
•	År 1972 togs den sista manuella växeln ur bruk anger Björkkvist  År 1972 togs den sista manuella växeln ur bruk, anger Björkkvist
•	Det ger en positiv energi därmed kan man bli av med stress  Det ger en positiv energi. Därmed kan man bli av med stress
•	Min mamma lagar så god mat jag trivs med hennes mat  Min mamma lagar så god mat. Jag trivs med hennes mat
Note: Additions of hyphens between words are not included in this category, but in the O-Comp category.
P-R (redundant punctuation)
The P-R tag is used for corrections involving the removal of a punctuation mark.
Examples
•	Jag minns inte exakt. vad det var med det var gott  Jag minns inte exakt vad det var men det var gott
Note: Removals of hyphens between the constituent words in a compound are not included in this category, but in the O-Comp category.
P-W (wrong punctuation)
The P-W tag is used when a punctuation mark in the original text has been replaced with another punctuation mark in the normalized text.
Examples
•	Mina barn heter Peter; Maria; Elisabeth och John  Mina barn heter Peter, Maria, Elisabeth och John
Note (1): Instances where a space has been corrected to a hyphen between the constituent words in a compound are not marked with this tag, but with O-Comp or S-Comp. The same holds for instances where a hyphen between words has been corrected to a space.
Note (2): Instances where a hyphen has been used in the original text where a dash would be more appropriate are left uncorrected and should thus not appear as corrections to be annotated.
Note (3): Possible errors involving the incorrect placement of a space before a punctuation mark will not be corrected in the normalization process, since spaces are always inserted before punctuation marks for the sake of tokenization. Consequently, such errors will not be tagged.
Note (4): Possible errors involving the lack of a space between a punctuation mark and the following word are corrected in the normalization process (a space is inserted), but are nevertheless left untagged.
Example:
•	Jog kan ante skriv meka ord .tack  Jag kan inte skriva många ord. Tack.
In this example, a space is inserted between the period and tack, and the t in tack is changed from lower to upper case. Tack will be tagged with O-Cap, but the insertion of the space will not 
P-Sent (sentence segmentation)
The P-Sent tag is used for corrections involving splitting a sentence or merging two sentences into one, when this correction involves more than the pure insertion or removal of a punctuation mark – in the typical case the adding or removal of a conjunction.
Examples
•	Jag heter xxx och jag pratar arabiska och engelska och lite svenska och vi har tre rum i huset  Jag heter xxx och jag pratar arabiska och engelska och lite svenska. Vi har tre rum i huset.
In this example, the P-Sent tag is placed on a link between och in the original text and the period in the normalized text. The link between vi and Vi is tagged with C, as a consistency correction necessitated by another correction.
S – Syntactical corrections
The S tags represent the syntactical correction category. It contains eight sub-categories.
S-Adv (adverbial placement)
The S-adv tag is used for corrections involving the placement of an adverbial.
This word order tag has the highest priority of the three word order tags (S-Adv, S-FinV and S-WO), and should be applied whenever a word order correction may be interpreted as concerning the placement of an adverbial. Particularly, word order corrections regarding the relative ordering between an adverbial and a finite verb, should be marked as S-Adv rather than as S-FinV.
Examples
•	Jag ofta är vaken länge på kvällarna. → Jag är ofta vaken länge på kvällarna.
•	Å ena sidan idag har… → Å ena sidan har idag… 
•	Jag är jättetrött eftersom jag sover inte på nätterna. → Jag är jättetrött eftersom jag inte sover på nätterna.
•	som i sin tur har tydligt påverkat ... →  som i sin tur tydligt har påverkat ... 
•	och med hela världen dela sina idéer och tankar. → och dela sina idéer och tankar med hela världen.
•	om hur under 600 år Finland var en del av Sverige → om hur Finland var en del av Sverige under 600 år
S-Comp (compound vs multi-word expression)
The S-Comp tag is used for corrections regarding the choice between a compound and a multi-word expression. This includes the choice between a compound and a phrasal structure for the combination of a verb and a verbal particle. (See the special section on verbal particles and reflexives.)
Examples
•	det vardagliga livet  vardagslivet
•	livsskillnaden  skillnaden i liv
•	svenska undervisningar  svenskundervisning
•	Enligt Hyltenstam så kan minoritetsspråk räddas om man inblandar dem äldre som kan språket  Enligt Hyltenstam så kan minoritetsspråk räddas om man blandar in de äldre som kan språket
•	Om det händer att det finns planhalvor så kan det bero på blyghet, osäkerhet, rädsla eller socialfobi  social fobi (See the section on compounds vs multi-word phrases for further discussion of this example.)
•	Hejdlös sociala medier användning orsakar ensamhet  Hejdlös användning av sociala medier orsakar ensamhet (See the section on compounds vs multi-word phrases for further discussion of this example.)
Note: Corrections regarding the mere orthographic rendering of a string with or without a space should not be marked with the S-Comp tag but with the O-Comp tag. (See O-Comp and the section on compounds vs multi-word expressions below.)
S-FinV (placement of finite verb)
The S-FinV tag is used for corrections concerning the placement of a finite verb, unless the correction regards the ordering between the finite verb and an adverb, in which case the correction is tagged with the S-Adv tag. The S-FinV tag thus has lower priority than the S-Adv tag, but higher priority than the S-WO tag.
Examples
•	Vor du bor?  Var bor du?
•	I morgon jag åker  I morgon åker jag
•	Efteråt man surfar på internet  Efteråt surfar man på internet
•	När jag ätiti, jag sover  När jag ätit, sover jag
•	Eller det skapar kontakter och trivs?  Eller skapar de kontakter och trivsel?
S-M (word missing, other)
The S-M tag is used when a word is missing in the original text and has been added in the normalized version. This includes the addition of reflexives and verbal particles. (See the special section on verbal paricles and reflexive.)
The S-M tag has lower priority than the S-Msubj tag and the M-Def tag, and should only be applied in cases when neither of these other tags may be applied.
Examples
•	Hon fördelen med att behålla den obligatoriska svenskan  Hon beskriver fördelen med att behålla den obligatoriska svenskan.
•	Sådana känslor gör användaren mår dåligt  Sådana känslor gör att användaren mår dåligt
•	Jag gillar inte tapeterna i min kusins lägenhet men han inte byta dem eftersom det är hyresrätt → ... han kan inte byta dem ...
•	Jag trivs mycket bo med dem  jag trivs mycket med att bo med dem
•	Man måste akta att man inte ramlar  man måste akta sig att man inte ramlar
•	men känner bara fysiskt närvarande  men känner sig bara fysiskt närvarande
•	Jag slår ord i ordboken när jag inte vet  Jag slår upp ord i ordboken när jag inte vet...
S-Msubj (subject missing)
The S-Msubj tag is used to mark corrections involving the addition of a subject which is missing in the original text. This includes cases when the pronoun/subordinating conjunction som has been inserted as a subject.
The S-Msubj tag has higher priority than the S-M tag.
Examples
•	Regnar ute  Det regnar ut
•	Det är inte bara arbetet och arbetslivet kan ge stress  Det är inte bara arbetet och arbetslivet som kan ge stress
•	Det är viktigt att veta vad händer  Det är viktigt att veta vad som händer
S-Other
The S-Other tag is used for syntactic corrections which are not covered by the other S-tags. This includes for instance changes between an infinitive construction and a finite clause construction.
•	Att växa upp som en flicka så var det väldigt många orättvisor man fick vänja sig vid.  När man växte upp som en flicka så var det väldigt många orättvisor man fick vänja sig vid.
Note: Take care not to overuse the S-Other tag. The other S tags should be carefully considered before choosing this one.
S-R (word redundant)
The S-R tag is used when a word is redundant in the original text and has been removed in the normalized version. This includes the removal of reflexives and verbal particles. (See the section on verbal particles and reflexives.)
The S-R tag has lower priority than the M-Def tag, and should only be applied in cases when the M-Def tag is not applicable.
Examples
•	På 2000- talet kom många kommunikationsappar , bland annat var Facebook , Twitter , Instegram och Snapchat , påpekar Rose ( 2012 ) .  På 2000- talet kom många kommunikationsappar , bland annat Facebook , Twitter , Instagram och Snapchat , påpekar Rose ( 2012 ) .
•	Man behöver inte att klä på sig  Man behöver inte klä på sig
•	Det är ett personligt ansvar för att välja  Det är ett personligt ansvar att välja ...
•	X-stad är närmare till X-land än X-stad.  X-stad är närmare X-land än X-stad.
•	De första mobiltelefonerna kom i 1957.  De första mobiltelefonerna kom 1957.
•	De nya kommunikationssätten har medfört med stora möjligheter  De nya kommunikationssätten har medfört stora möjligheter
•	sociala medier blev en essentiell del av våra liv som vi inte kan slänga det i den moderna världen  sociala medier blev en essentiell del av våra liv som vi inte kan slänga i den moderna världen
•	De promenerade sig i parken  De promenerade i parken
•	Hon gav bort honom en blomma  Hon gav honom en blomma
S-WO (word order, other)
The S-WO tag is used for word order corrections which are not covered by the S-Adv or the S-FinV categories.
In corrections regarding the relative placement of a phrasal head and a modifying element (for instance a noun and its attribute), the modifying element should be marked rather than the phrasal head (e.g. min rather than bostad in the example below):
•	Bostaden min  Min bostad
In cases when the word order change may be interpreted as moving an element “out of” a normally fairly fixed structure, that element should be marked rather than an element included in the more fixed structure (dem rather than upp in the example below).
•	Man kan inte vänta att lägga de upp på social medier  Man kan inte vänta med att lägga upp dem på sociala medier
In other cases the placement of the tag may be chosen freely between the elements which have been moved relative to each other, but the readability of the resulting visualization should be taken into consideration.
Other tags
The final group of tags, collected under the heading Other, contains six tags used for various purposes:
•	The C tag is used for corrections which are necessitated by other corrections, but which do not reflect mistakes in the original text.
•	The Com! and OBS! tags are used for notes and comments – the Com! tag for comments intended for the future corpus user, and the OBS! tag for work notes on pending analyses meant for internal project use.
•	The Cit-FL tag is used for segments of foreign language which have not been corrected during normalization.
•	The X tag is used for unintelligible strings.
•	The Unid tag is used for “unidentified” corrections, i.e. corrections which are not covered by any of the correction categories defined in the taxonomy.
Four of these tags, namely Cit-FL, Com!, OBS! and X are available already during the normalization process, and are normally inserted already by the normalizer.
C – Consistency corrections
The C tag represents consistency corrections, a category which covers necessary (follow-up) corrections in the text that come as a result of a previous correction, i.e. originally there was no mistake in the segment, but due to an introduced correction in the neighboring context, a correction is necessary in the segment. By using this tag we indicate that the error was not made originally by the learner.
In some instances it may not be self-evident which one of two related corrections that should be considered as necessitating the other, but by marking one of them with C we avoid marking a single mistake in the original text as two.
Examples
•	Bostaden min  Min bostad
The shift of word order is marked as a word order correction (S-WO). The change from definite form (bostaden) to indefinite form (bostad) of the noun is made necessary because of the shift of word order, and is thus marked as a consistency correction (C).
•	Det ger en en positiv energi därmed kan man bli av med stress …  Det ger en en positiv energi . Därmed kan man bli av med stress …
The insertion of the full stop is tagged as a punctuation correction (P-M). The capitalization of the following D is made necessary because of the insertion of the full stop, and is thus marked as a consistency correction (C).
•	Min bostanden ser ut som lilla centrum med vlere affere  Mitt bostadsområde ser ut som ...
The change from bostanden to bostadsområde is marked as a lexical correction (L-W) and a morphological correction (M-DEF). The gender change of the pronoun, from min (non-neuter) to mitt (neuter) is made necessary because of the change or word (from the non-neuter bostad to the neuter bostadsområde), and is thus marked as a consistency correction (C).
•	Hon fortsätter att skriva att inte avskaffa den obligatoriska svenskan på skolan är fördel för ungdomar.  Hon fortsätter att skriva att det är en fördel för ungdomar att inte avskaffa den obligatoriska svenskan i skolan.
In this case the insertion of the pronominal subject copy (det) may be seen as the necessary effect of postponing the infinitive phrase (inte avskaffa den obligatoriska svenskan i skolan). The movement of the infinitive phrase is tagged with S-WO, and the added det is marked with C. 
Cit-FL (cited foreign word judged acceptable in the normalization)
The Cit-FL tag is used for foreign (non-Swedish) words, phrases or text segments, which have been kept by the normalizer since their usage has been judged acceptable given the norms of the text type in question. This may be the case for instance for explicitly marked citations or intentional code switching appropriate for the genre.
Note that the only requirement for applying this code is that the word or text segment is recognizable as another language than Swedish, and that the choice to use this other language is judged appropriate for the genre. No judgement or correction of the word or text segment is made relative to the norms of the foreign language in questions. For instance, spelling mistakes are left uncorrected.
The Cit-FL tag is usually added already during normalization.
Com! (comments for the corpus users)
The Com! tag is connected to an edge comment field, which is open for freely composed comments. It is available already during the normalization process.
The Com! tag is used for comments on specific tokens or text sequences which are relevant for future users of the corpus, and which are thus meant to be kept in the published corpus. (Comments regarding the text as a whole or recurring properties in the text may be added in the Document comment field.)
The Com! tag may for instance be used to mark text segments which are copied from the task formulation. If a significant portion of the text consists of copied text, this should preferably be indicated also in the Document comment field, in addition to the edge comment field connected to the Com! tag which is inserted on the specific text segment or the specific text segments.
OBS! (notes and pending analyses)
The OBS! tag is, like the Com! tag, connected to an edge comment field, and is available already during the normalization process.
The OBS! tag is used to mark pending analyses to which the annotator wants to return, remarks which the normalizer wishes to pass on to the correction annotator, etc.
X (unintelligible string)
The X tag is used to mark unintelligible strings in the original text. The tag is available and usually added already during the normalization process. The marked original string may be left unchanged in the normalized version, or the normalizer may replace it with some more or less wild guess of the intended message.
The X tag may be used both in cases when there is no reasonable interpretation of the string, and when there are several somewhat reasonable interpretations, but none of these interpretations may be settled as better than the other.
The X tag is also used for strings which are identified as or suspected to be samples of a foreign language, when neither the L-FL nor the Cit-FL tag is applicable; The X tag is used to mark foreign words when 1) The L-FL tag may not be applied because the word bears no resemblance to a Swedish word, and 2) the Cit-FL tag may not be applied because the usage of the foreign language is not judged to be appropriate for the text genre. (See the section on foreign words and sequences below.)
Examples
•	En argumentera på är viktigt hur man bor är bor på en bra hem
•	och vi har 3 rum it huset dar rum är meka bra liv med maen familija dar huset familjbostder och jag vill sta och jog kan ante skriv meka ord  och vi har 3 rum i huset . dar rum är mycket bra liv med min familj där i huset från Familjebostäder och jag vill stanna och jag kan inte skriva många ord
Texten som detta exempel är hämtat ifrån bär i övrigt en del drag av tyska eller möjligen nederländska, och en halvrimlig gissning är att dar rum står för darum. En annan (mindre trolig) möjlighet är att dar rum är avsett att betyda där rum, men den tolkningen gör det nödvändigt med stora ingrepp i texten i övrigt för att få ihop en syntaktiskt fungerande sträng. Genom att markera dar rum med X och behålla strängen oförändrad i den normaliserade versionen möjliggörs en normalisering av texten i övrigt som bättre följer principen om minimal change.
Stanna är en någorlunda rimlig gissning av avsikten med sta, men inte tillräckligt välgrundad för att korrigeringen ska kunna markeras som ett ortografiskt fel. Många andra tolkningar är förstås möjliga.
Unid (unidentified correction)
Finally, the Unid tag is used for corrections which are not covered by any of the correction categories defined in the taxonomy.
The Unid code is a last option which should only be considered after all other solutions have been carefully considered.
Note: The Unid tag should only be applied in cases when a correction has actually been made, and when the original text gives fairly sound support for the interpretation presented in the normalized version. Text segments which are so difficult to interpret that they are either left unchanged or normalized on the basis of guesses rather than solid interpretations should be tagged with X.
Some specific categorization issues
Compounds vs multi-word expressions
Corrections concerning the forming of an expression as a compound or a multi-word expression are divided into two categories in the SweLL correction taxonomy: Corrections which are judged to concern the mere orthographic rendering with or without a space between two words are marked with the O-Comp tag, while corrections which are judged to concern the actual choice between a compound and a multi-word expression are marked with the S-Comp tag. Borderline or unclear cases between these two categories obviously exist, but for the most part one of the options is clearly the better one.
The O-Comp tag is primarily used for corrections of standard cases of särskrivning (the faulty writing of a compound with a space in between the two compounded words):
•	Det ligger ett kultur hus nära min bostad  kulturhus
It may also be used for corrections which involve changing the first word of the compound into a specific compound form, in addition to the removal of the space between the two words. In such cases, the correction is marked with both the O-Comp tag and the L-Der tag:
•	Kommunikation förändring  Kommunikationsförändring
More rarely, the O-Comp tag may be applied when a multi-word expression in the original text has been corrected through the adding of a space between two of the words:
•	itisdags  i tisdags
The S-Comp tag is used whenever the correction made is more complex than the mere addition or removal of a space between two words (and possibly changing the form of the first word of a compound).
•	det vardagliga livet  vardagslivet
•	livsskillnaden  skillnaden i liv
•	svenska undervisningar  svenskundervisning
•	Enligt Hyltenstam så kan minoritetsspråk räddas om man inblandar dem äldre som kan språket  Enligt Hyltenstam så kan minoritetsspråk räddas om man blandar in de äldre som kan språket
However, in some cases the S-Comp tag is more suitable than the O-Comp tag, although the correction superficially merely involves the presence of a space. This is the case when two words may be correctly formed as a compound (without a space) and as a two-word expression (with a space), and the meaning of the compound version and the two-word version are either the same or else both plausible in the context. The correction made is thus not due to the chosen expression being unthinkable, but due to the other expressions happening to be the established lexical unit:
•	Om det händer att det finns planhalvor så kan det bero på blyghet, osäkerhet, rädsla eller socialfobi  social fobi 
In this case, socialfobi is a perfectly well formed compound, but it is corrected to the two-word expression social fobi because this is the established way to express the intended meaning. The mistake made by the writer is therefore not judged to be a case of having missed a space in between two words in a two-word expression, but it is judged to be a case of the writer actually having chosen the compound expression instead of the established two-word expression. The correction is thus marked with the S-Comp tag.
Moreover, in some cases the S-Comp tag may be applied although neither the original nor the normalized string is a single orthographic word. This is the case when the string in the original text may be interpreted as an instance of a compound, although it includes spaces:
•	Hejdlös sociala medier användning orsakar ensamhet  Hejdlös användning av sociala medier orsakar ensamhet
In this particular case, the string in the original text may be interpreted as a compound between a two-word phrase (sociala medier) and the word användning. According to the norms of written standard Swedish, such compounds should be written as sociala medier-användning etc. While such a minimal correction is not an unthinkable solution for the normalization, the normalizer has here judged a restructuring of the NP as a better solution, and the correction should be tagged S-Comp.
Non-Swedish words and sequences
There are a number of ways to handle non-Swedish words during normalization and correction annotation. Many of the fundamental choices are made during the normalization process rather than during the correction annotation process.
The first judgement to be made when coming across a word stemming from another language in the material is naturally whether the word may be recognized as having been incorporated into written standard Swedish; in such cases the word is left uncorrected and untagged. This judgement is made during normalization.
When a word (or sequence) in an original text is recognized as belonging to a foreign language – or as having traits from a foreign language – and when this word may not be recognized as part of written standard Swedish, a number of options are at hand:
1)	The word/sequence is judged as a genre appropriate usage of cited foreign language (explicitly signaled citations, code switching etc.).  Not corrected, tagged Cit-FL during normalization.
2)	The word is not judged as a genre appropriate usage of cited foreign language and is thus corrected to a Swedish word during normalization:
a)	The form used may be interpreted as a misspelled Swedish word.  Corrected during normalization, tagged O during correction annotation: kaffee  kaffe; can  kan
b)	The form used may be interpreted as a Swedish word with an incorrect usage of derivational affixes etc.  Corrected during normalization, tagged L-Der during correction annotation: national helgdag  nationell helgdag
c)	Neither a or b applies.  Corrected during normalization, tagged L-FL during correction annotation: balkony  balkong; family  familj; gas bojler  gaskokare
Note: A word in the original text which is identifiable as a Swedish word, but which is used with another meaning in a way which is likely to be due to influence from a similar non-Swedish word, should be corrected and marked as L-W (not as L-FL):
•	Alla blir busiga med sina sociala medier.  Alla blir upptagna med sina sociala medier
In this example, it is likely that the incorrect usage of the correct Swedish word busiga is influenced by the word’s similarity to the English word busy – and it is partly based on this assumption that the writer’s intended meaning has been interpreted as upptagna. But since busiga is a correct Swedish word, with a distinctly Swedish morphological structure, the correction is tagged as L-W rather than as L-FL.
Verbal particles and reflexives
Several tags are used for corrections involving phrasal or compound verbs made up by a verb and verbal particle or a reflexive marker, primarily O-Comp, S-Comp, L-Der, L-W, S-M and S-R. This section provides an overview of the usage of these six tags for this category of corrections.
•	O-Comp: A space is removed between a verbal particle and a following verb, making up a compound verb:
o	upp mana  uppmana
•	S-Comp: A compound form of a particle verb is changed to a phrasal form, or the other way around.
o	Enligt Hyltenstam så kan minoritetsspråk räddas om man inblandar dem äldre som kan språket  Enligt Hyltenstam så kan minoritetsspråk räddas om man blandar in de äldre som kan språket
o	Tåget går av från spår 3  Tåget avgår från spår 3
•	L-Der: A particle of a compound particle verb is changed, removed or added. Both the original and the normalized string consist of one single token. The original string may or may not be an existing Swedish word.
o	Internet uppmanar vår förståelse  Internet utmanar vår förståelse
o	Han inhämtade väskorna från hotellrummet  Han hämtade väskorna från hotellrummet
o	Hon minde honom om mötet på eftermiddagen  Hon påminde honom om mötet på eftermiddagen
•	L-W, placed on the whole phrasal verb: Either the original string or the normalized string (or both) is a phrasal verb, and the verb itself is changed, not just the particle/reflexive marker.
o	Traditioner ger människorna tid att stå still och fundera över livet → … att stanna upp och fundera över livet.
•	L-W, placed on the particle: A verbal particle is replaced by another verbal particle, but the verb is kept.
o	Han torkade bort bordet  Han torkade av bordet
•	S-M: An independent (non-compound) verbal particle or a reflexive marker is added.
o	men känner bara fysiskt närvarande  men känner sig bara fysiskt närvarande
o	Jag slår ord i ordboken när jag inte vet  Jag slår upp ord i ordboken när jag inte vet...
•	S-R: An independent (non-compound) verbal particle or a reflexive is removed.
o	De promenerade sig i parken  De promenerade i parken
o	Hon gav bort honom en blomma  Hon gav honom en blomma
Appendix with illustrated examples



