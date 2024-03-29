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

*	**Syntactical corrections (S)**, i.e. corrections regarding the structure of multi-word phrases and clauses, including corrections of missing or redundant words, word order, the choice between a compound and a multi-word expression, and more complex syntactic corrections such as corrections between a finite clause structure and an infinitive phrase.

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

* En före nänmt problem nynorska i norge har tas upp i artiklen " Obligatoriska språkprov sliter på norsk tvåspråkighet " av Bengt Östling ( 11.11.2013 ) där han har jämförts **" tvångsvenska " debatten** i Finland med **nynorska debatten** i Norge -> Ett tidigare nämnt problem som nynorskan i Norge har tas upp i artikeln " Obligatoriska språkprov sliter på norsk tvåspråkighet " av Bengt Östling ( 11.11.2013 ) , där han har jämfört **"tvångssvenska"-debatten** i Finland med **nynorska-debatten** i Norge

*	**kultur-hus** -> **kulturhus**

*	**New York bor** -> **New York-bor**

*	**New Yorkbor** -> **New York-bor**

* **tv program** -> **tv-program**

*	**engång** -> **en gång**

*	för två **årsen** -> för två **år sen**

In the following example, the change from a comma to a long dash between _Finland_ and _Sverige_ is tagged with P-W, and the change from a space to a hyphen between _Sverige_ and _historien_ is tagged with O-Comp:

* Författaren börjar med att beskriva det långa **Finland , Sverige historien** och hur Finland var en gång i tiden en del av Sverige -> Författaren börjar med att beskriva den långa **Finland–Sverige-historien** och hur Finland en gång i tiden var en del av Sverige

Corrections which involve both a removal of a space and a change of the form of the first part of the compound are tagged both with O-Comp and L-Der:

*	**Kommunikation förändring** -> **Kommunikationsförändring**

### L – Lexical corrections

The L tags represent the lexical correction category. It includes four sub-categories.

#### L-Der (word formation)

The L-Der tag represents the correction category _deviant word formation_. It is used for corrections of the internal morphological structure of word stems, both with regard to compounding and to derivation.

The L-Der tag is exclusively used for links between one-word units, where the normalized word has kept at least one root morpheme from the original word, but where another morpheme has been removed, added, exchanged or had its form altered.

_Examples_

*	A derivational affix has been corrected, e.g.: De är **stressiga** på grund av studier -> De är **stressade** på grund av studier
  
* A derivational affix has been added, e.g. **ändring** -> **förändring**

*	A derivational affix has been removed, e.g. **förstöra** -> **störa**

*	The form of the first part of a compound has been corrected (for instance by adding or removing a “foge-s”), e.g. **tvångsvenska** -> **tvångssvenska**; **sagabok** -> **sagobok**

*	A verbal particle of a compound form of a particle verb has been added, removed or corrected, e.g.:

     - Internet **uppmanar** vår förståelse -> Internet **utmanar** vår förståelse
     
     - För att sammanfatta och svara på frågan om likheter och skillnader finns mellan nynorskans ställning i Norge och svenkans ställning i Finland man måste förstå att debatten i båda länder är jätte lik varandra , bara hantering **avskiljer** -> För att sammanfatta och svara på frågan om det finns likheter och skillnader mellan nynorskans ställning i Norge och svenkans ställning i Finland måste man förstå att debatterna i de båda länderna är jättelika varandra , bara hanteringen **skiljer**
     
     - I annan text " Tre röster om svenskans ställning i Finland " Parnass 2013:3 som är skriven av författaren Catharina Söderbergh beskriver dem tre olika **ställningar** som finns om svenska inom Finland -> I en annan text , " Tre röster om svenskans ställning i Finland " ( Parnass 2013:3 ) , som är skriven av författaren Catharina Söderbergh , beskriver författaren de tre olika **inställningar** som finns till svenska i Finland
     
(See the special section on verbal particles and reflexives.)

* A lexical root morpheme has been exchanged, e.g.: **dagsskolan** -> **förskolan**

* A verbal particle has been exchanged for a derivational affix, e.g.: **efterlyser** -> **belyser**

* A root morpheme and a derivational morpheme has been added, e.g.: **maktfull** --> **maktfullkomlig**

**Note (1)**: Corrections of verbal particles of phrasal forms of particle verbs are not tagged with the L-Der tag, but with the L-W tag. (See the special section on verbal particles and reflexives.)

**Note (2)**: The L-Der tag is not used for corrections which involve the addition of a -t suffix to an adjective which is used as an adverb, since this correction category is treated as a morphological correction with its own tag, M-Adj/adv.

**Note (3)**: When the correction of a word tagged with L-Der involves a change of phrase type or part of speech, the correction is tagged with S-Type, in addition to L-Der.

_Examples_

* **norska** bokmål -> **norskt** bokmål

* en **nybyggnad** lägenhet -> en **nybyggd** lägenhet

* Jag ska **solen** och bada -> Jag ska **sola** och bada

* Jag behöver pengar för liv och **betalning** av min hus -> Jag behöver pengar för att leva och **betala** mitt hus

Changes from _båda_ to _både_, or the other way around, are tagged as L-Der (and S-Type) rather than as L-W:

* något ha en " svart " avställning **båda** i jobbet och från bostad -> Någon har en " svart " inkomst **både** från jobbet och från bostaden 


#### L-FL (foreign word corrected to Swedish)

The L-FL tag is used for words from a foreign (non-Swedish) language which have been corrected to a Swedish word. It may also be applied to words which have certain non-Swedish traits due to influence from a foreign language.

_Examples_

*	Det fanns flera rum, två kök, **balkony** och trädgård -> **balkong**

*	Jag och min **family** -> **familj**

* varför man ens lär sig svenska idag i Finland som beror på historiska **event** -> varför man ens lär sig svenska idag i Finland , vilket beror på historiska **händelser**

* Bostad i D-hemland är litet het **topik** för att **diskussera** -> Bostäder i D-hemland är ett lite hett **ämne** att **diskutera**

The L-FL tag is used for corrections with the following characteristics:

*	The word in the original text is recognizable as a word from a foreign language _to the annotator_ (who is obviously not equally proficient in all languages). Alternatively, _the annotator_ recognizes certain non-Swedish traits in the word which are due to influence from a foreign language.

*	The word in the original text may or may not be correctly formed and used according to the norms of the assumed influencing language.

*	The word in the original text may have both Swedish and foreign traits, but if it is identifiable as an existing well-established Swedish word which has been replaced by an altogether different word, it should not be marked as L-FL, but as L-W. This holds even if the deviant choice of words is clearly due to lexical influence from the foreign language. For instance, the following example should be marked as L-W, although it is likely that the faulty use of _busiga_ is influenced by the English word busy. (See the section on non-Swedish words and sequences below.)

     - Alla blir **busiga** med sina sociala medier. -> Alla blir **upptagna** med sina sociala medier
     
*	It is not reasonable to interpret the correction as a correction of a spelling mistake or a word formation mistake. In that case the correction should be tagged with the O tag or the L-Der tag respectively. In other words: The O and L-Der tags have higher priority than the L-FL tag. (See the section on non-Swedish words and sequences below.)

#### L-Ref (anaphoric expressions)

The L-Ref tag is used for anaphoric expressions (particularly pronouns and pronominal adverbs) which have been corrected in order to have the grammatical form (gender, number, reflexive/non-reflexive), semantic content (masculine/feminine, directional/locational etc.), and specificity which suits its correlate and its textual position.

The L-Ref tag has higher priority than the M-Num, M-Gend and L-W tags.

The L-Ref tag has lower priority than the M-Def tag, and should only be applied in cases when the M-Def tag cannot be applied.

_Examples_

*	Jag har en bror, **hon** heter xx -> **han** heter xx

*	Stämmer det att våra sociala media skapar individualism och ensamhet? Eller skapar **det** kontakter och trivs? -> Eller skapar **de** kontakter … (_In cases like this, the L-Ref tag has higher priority than the M-Num tag._)

*	Innan trädet blev borta dem fick fars äpplen och **sin** fru lagade saft och mos av äpplena -> Innan trädet var borta fick de fars äpplen och **hans** fru lagade saft och mos av äpplena

* Östling skriver om politiker som tycker att obligatorisk språkundervisningen och prov på nynorska krävs för att försäkra ett minoritets språk som har ett gamal kulturarv knutet till **den** . -> Östling skriver om politiker som tycker att obligatorisk språkundervisning och prov på nynorska krävs för att skydda ett minoritetsspråk som har ett gammalt kulturarv knutet till **sig** .

* “ Finns det något som är mer värt än pengar ? ” Jag vet faktiskt inte , **den** är en svår fråga . -> “ Finns det något som är mer värt än pengar ? ” Jag vet faktiskt inte , **det** är en svår fråga . (_In cases like this, and the following examples, the L-Ref tag has higher priority than the M-Gend tag._)

* Om man jobbar åtta timmar varje vardag för att få pengar , sedan är det lite hycklande att säga något som , ” Ja , det finns jo viktigare saker i livet ! ” **Den** är en tredjedel av din dag ! -> Om man jobbar åtta timmar varje vardag för att få pengar , är det sedan lite hycklande att säga något som : ” Ja , det finns ju viktigare saker i livet ! ” **Det** är en tredjedel av din dag !

* Jag tycker om Gotland och **den** ligger i Sverige . -> Jag tycker om Gotland , och **det** ligger i Sverige .

* I artikeln " Svenskan tynar i Finland " ( Forsknings & Framsteg 2009:2 ) Cecilia Christner Raid om varför man ens lär sig svenska idag i Finland **som** beror på historiska event . -> I artikeln " Svenskan tynar i Finland " ( Forskning & Framsteg 2009:2 ) skriver Cecilia Christner Riad om varför man ens lär sig svenska idag i Finland , **vilket** beror på historiska händelser . (_In cases like this, and the following examples, the L-Ref tag has higher priority than the L-W tag._)

* Man kan flyga till Gotland eller åka till Nynäshamn och åka båt till **där** -> Man kan flyga till Gotland eller åka till Nynäshamn och åka båt **dit** .

The L-Ref tag may also be used when a noun which is used anaphorically has been exchanged for a pronoun, or the other way around, in order for the specificity of the anaphoric expression to suit its textual position:

* Heter Jag Karin och Jag har änmält mig till danskursen och bitalad för det men tyvär fick Jag inte tid för att koma . Jag kunde inte att komma för jobbar och pl$ggar Jag tillsamman och **det** passar inte med min tiden -> Jag heter Karin och jag har anmält mig till danskursen och betalat för den , men tyvärr hade jag inte tid att komma . Jag kunde inte komma för att jag både jobbar och pluggar , och **kursen** passar inte med mina tider

#### L-W (wrong word or phrase)

The L-W tag represents the correction category _wrong word or phrase_. It is used when a word or phrase in the original text has been replaced by another word or phrase in the normalized version. The  L-W tag is thus placed on strings which are _exchanged_ rather than _corrected_ (see note below for further explanation).

The L-W tag is only applied when at least one of the strings (the original string and the normalized string) is (an attempt at) a word or a fixed phrase.

The L-W tag has lower priority than the L-Ref tag.

_One word replaced by one word_:

*	Uppfinningen som **transformerade** hela kommunikationsområdet -> Uppfinningen som **förändrade** hela kommunikationsområdet

*	Jag bor i D-område **på** en lägenhet -> Jag bor i D-område **i** en lägenhet

*	På det sättet kan kommunen **motionera** alla medborgare att träna → På det sättet kan kommunen **motivera** alla medborgare att träna.

* vi solade och badade mycket och träffäde några **personer** från flera länder -> Vi solade och badade mycket och träffade **människor** från flera länder .

*	Alla blir **busiga** med sina sociala medier. -> Alla blir **upptagna** med sina sociala medier (See the section on non-Swedish words and sequences for further comments on this example.)

_One word replaced by a multi-word expression_:

*	Med detta som bakgrund så kan man konstatera att majoriteten av **Finland** på olika missnöjesnivåer avskyr inlärning av svenska på grund- och gymnasieskolor . -> Med detta som bakgrund så kan man konstatera att majoriteten av **Finlands befolkning** , på olika missnöjesnivåer , avskyr inlärning av svenska på grund- och gymnasieskolor .

_Multi-word expression replaced by one word_:

*	Jag maner att om vi **har önskemål** kan vi göra nånting utan pengar -> Jag menar att om vi **vill** kan vi göra nånting utan pengar .

_Multi-word expression replaced by another multi-word expression_:



_Phrasal verb replaced by another phrasal verb, both verb and particle exchanged_:

*	Traditioner ger människorna tid att **stå still** och fundera över livet → … att **stanna upp** och fundera över livet.

_Compound particle verb replaced by a phrasal verb, both verb and particle replaced_:

* Konsekvenserna man skulle få ifall undervisning i svenska blev frivillig så skulle mer än hälften av finska befolkningen **avskaffa** svenskan som modersmålsundervisning och istället fokusera på finska då dem sällan använder svenskan . -> Konsekvenserna man skulle få ifall undervisning i svenska blev frivilligt är att då skulle mer än hälften av den finska befolkningen **välja bort** svenskan som modersmålsundervisning och istället fokusera på finska då de sällan använder svenskan .

_Verbal particle replaced by another verbal particle, but verb kept; the verbal particle rather than the whole phrasal verb is tagged with L-W_:

*	Han torkade **bort** bordet -> Han torkade **av** bordet

_Fixed expression consisting of a lexical word (e.g. a noun) and a grammatical word (e.g. a preposition) replaced by another fixed expression consisting of the same lexical word but another grammatical word; the grammatical word rather than the full fixed expression is tagged with L-W_:

* såsom våra ”moderna” språk är ibland en blandning av flera utrotade minoritetsspråk som **under** tiden skapade något nytt och unik -> såsom våra ”moderna” språk ibland är en blandning av flera utrotade minoritetsspråk som **med** tiden skapade något nytt och unikt .

**Note (1)**: Corrections consisting in the mere removal or addition of the reflexive sig or a verbal particle are not tagged with L-W, but with S-R or S-M respectively – even if both the bare verb and the phrasal verb may be characterized as lexical units. 

**Note (2)**: When a correction tagged with L-W involves a change of phrase type/part of speech, the correction is also marked with the additional tag S-Type.

_Examples_

*	plötsligt bröt muren **sinsemellan** -> plötsligt rasade muren **mellan dem**

* jag behover pengar f$r **liv** och betalning av min hus -> jag behöver pengar för **att leva** och betala för mitt hus

* Tycker om min plats har en **köpa mat** ett , litet centrum en förskolan en vårdcentralen -> Jag tycker om platsen där jag bor , den har en **mataffär** , ett litet centrum , en förskola , en vårdcentral

* Man kan promonera **lång tid** finns det blåser -> Man kan promenera **länge** när det blåser

* **Några tider** vi kan titta och lyssna på hur funkar det -> **Ibland** kan vi titta och lyssna på hur det funkar .

* Finns många nya lagenheterna i dyrare delar i huvudstaden , men detta är **lång distans från  räker nummer** . -> Det finns många nya lägenheter i dyrare delar i huvudstaden , men detta är **långt ifrån tillräckligt** .

*  jag bor **in** lägenhet plan ett -> Jag bor **i** en lägenhet på plan ett

* den obligatoriska svenskundervisningen i **dem** finska skolorna -> den obligatoriska svenskundervisningen i **de** finska skolorna (_The pronoun form_ dem _is changed to the form_ de _used as a definite article. Cf. M-Case._)

**Note (3)**: An expression tagged with L-W should be _replaced_ rather than _corrected_. This means:

* If both the original string and the normalized string are multi-word expressions containing one and the same lexical word, as well as one or more grammatical words which are changed, the L-W tag should be placed on the grammatical word(s) and not on the lexical word, as in the example above where _under tiden_ is exchanged for _med tiden_.

* If both the original string and the normalized string contain the same lexical morphemes but with another internal structure, the S-Comp tag should be applied rather than the L-W tag. Example: _avsnittet av texten_ -> _textavsnittet_

* If both the original string and the normalized string are multi-word expressions with the same main word (for instance the central noun of a noun phrase), one or several S-tags should be used rather than the L-W tag. The following correction is thus not marked as L-W but as S-Clause: _min plats_ -> _platsen där jag bor_

* If both the original and the normalized string are single words, all root morphemes of the word should be changed. Otherwise the L-Der tag should be applied. Example: _dagsskola_ -> _förskola_

### M – Morphological corrections

The M tags represent the category _morphological corrections_. It covers corrections related to inflections. This includes primarily corrections of individual inflectional forms, but in some cases also corrections of more complex grammatical constructions closely related to inflectional forms. The latter concerns basic definiteness constructions (see M-Def), the periphrastic comparative and superlative adjective constructions (see M-F), and tense-related verbal constructions involving auxiliaries (see M-Verb).

The category of morphological corrections includes eight sub-categories.

#### M-Adj/adv (adjective corrected to adverb)

The M-Adj/adv tag is used for corrections involving the change of an adjective to its t-form, when the t-form is called for due to the adjective being used as an adverb.

_Examples_

*	Användaren mår **dålig** -> **dåligt**

*	Hur påverkar detta våra måenden **långsiktig?** -> **långsiktigt**

* Jag tror att man måste hitta balansen mellan rikdom och andra saker som är **riktiga** viktiga -> Jag tror att man måste hitta balansen mellan rikedom och andra saker som är **riktigt** viktiga

The M-Adj/adv is also used for similar changes, when an adjective or adjective-like word is changed to a morphologically closely related but distinct adverb form:

* När jag kommer **första** i 2012 , jag bodde i en social lagenhet med 3 andra person -> När jag **först** kom 2012 bodde jag i en kommunal lägenhet med 3 andra personer

Moreover, the M-Adj/adv tag is used when an adjectival form of the word _liten_ is changed to the adverb form of the same word, i.e. _lite_. This holds also when the form _litet_ is changed to the form _lite_. Although the form _litet_ is occasionally used as an adverb in standard Swedish, it is too archaic to be used in most of the Swell text genres, and adverbial uses of the form _litet_ are thus normally corrected to the form _lite_ during normalization. Such changes are also tagged with M-Adj/adv:

* Bostad i D-hemland är **litet** het topik för att diskussera -> Bostäder i D-hemland är ett **lite** hett ämne att diskutera .


#### M-Case

The M-Case tag is used for corrections regarding the choice of case form for nouns (nominative vs genitive) and pronouns (nominative vs accusative).

_Examples_

*	50 **kilometer** avstånd -> **kilometers**

*	Som kan bidra till **samhället** utveckling -> **samhällets**

*	Det ger **man** en positiv energi -> Det ger **en** en positiv energi

*	Folk hinner inte prata med **de** -> Folk hinner inte prata med **dem**

*	Ingen förstår **hon** -> Ingen förstår **henne**

**Note**: When the form _dem_ is changed to the form _de_ used as a definite article, the correction is tagged as L-W, not as M-Case:

* den obligatoriska svenskundervisningen i **dem** finska skolorna -> den obligatoriska svenskundervisningen i **de** finska skolorna


#### M-Def (definiteness)

The M-Def tag is used for corrections regarding definiteness constructions. The kinds of corrections which are involved in this correction category are:

*	Change between indefinite and definite forms of nouns (_bok_ vs _boken_; _rum_ vs _rummet_) **In these cases the M-Def tag has higher priority than the L-Ref tag.**

*	Change between, removal of and addition of indefinite and definite articles (_en_, _ett_; _den_, _det_, _de_). **In these cases the M-Def tag has higher priority than the S-M and S-R tags.**

*	Change between indefinite and definite forms of adjectives and adjective-like pronouns (_stor_/_stort_ vs _stora_; _egen_/_eget_ vs _egna_)

_Examples_

*	Vi gick till McDonalds och åt **maten** -> **mat**

*	Jag trivs bättre på **jobb** här -> **jobbet**

*	Jag har läst ditt **mejlet** -> ditt **mejl**

*	min **stor** dag -> min **stora** dag

*	De **gränserna** som fanns mellan kvinnor och män har nästan försvunnit -> De **gränser** som fanns

*	När kommer **den buss** -> När kommer **bussen**

*	Då kommer svenska språket försvinna ur Finska samhället -> Då kommer svenska språket försvinna från **det** finska samhället

*	Han har egen **rummet** och jag egen -> Han har **ett** eget rum och jag **ett** eget

#### M-F (wrong form, correct grammatical category)

The M-F tag is used when a declension/conjugation form (typically a suffix) which is used to express a specific grammatical category (e.g. number or plural) has been corrected to a form belonging to another declension/conjugation within the same grammatical category. The tag is used for the following correction types:

_Nouns_:

*	Correction of a plural suffix: **båter** -> **båtar**, **huvudproblemer** -> **huvudproblem**

**Note**: Unsuffixed noun forms will be interpreted as singular when corrected to a suffixed plural form, although unsuffixed plurals exist. Corrections like _båt_ -> _båtar_ will thus be tagged with the M-Num tag and not with the M-F tag.

_Verbs_:

*	Correction of a present tense suffix: jag **lager** mat -> jag **lagar** mat

*	Correction of a past tense suffix: **böjade** -> **böjde**

*	Correction of a supine suffix: **kunnit** -> **kunnat**

*	Correction from a verb form with a basic stem form and a suffix (past tense or supine) to a stem-changed verb form (with or without suffix): **sjungde** -> **sjöng**; **drickit** -> **druckit**

_Adjectives_:

*	Correction of a comparative suffix: **högare** -> **högre**

*	Correction of a superlative suffix: **högast** -> **högst**

*	Correction from an adjective form (comparative or superlative) with a basic stem form and a suffix to a stem-changed form: **långare** -> **längre**; **ungast** -> **yngst**

*	Correction of the choice between a periphrastic and an inflectional comparative or superlative construction: I Sverige är **mer kallt** än i xx -> I Sverige är det **kallare** än i xx

The tag may also be used for some analogous changes of pronouns:

* Enligt Hermanssons artikel debatten om huruvida nynorska skulle behållas eller om **dens** öde skulle vara upp till folket och marknaden att bestämma över resulterar i blandade åsikter . -> Enligt Hermanssons artikel resulterar debatten om huruvida nynorskan ska bevaras eller om **dess** öde ska vara upp till folket och marknaden att bestämma över i blandade åsikter .

#### M-Gend (gender)

The M-Gend tag is used to mark corrections of gender forms (neuter vs non-neuter) of nouns, articles, adjectives, and pronouns with adjective-like functions.

_Examples_

*	Det är **en** mycket **trevlig** område -> Det är **ett** mycket **trevligt** område

*	**Den** viktigaste är att … -> **Det** viktigaste är att …

*	**Den** första telefonnät -> **Det** första telefonnätet

*	Kommunikationen är **möjligt** -> Kommunikationen är **möjlig**

* ifall undervisning i svenska blev **frivillig** -> **frivilligt**

*	Han har **egen** rummet och jag **egen** -> Han har ett **eget** rum och jag ett **eget** (cf. the same example under M-Def)

* många i båda länder tycker att minoritet språken borde förbjudas eller att minoritetspåken har för mycket makt inom **landen** -> många i båda länderna tycker att minoritetsspråken borde förbjudas eller att minoritetsspråken har för mycket makt i **landet**

The M-Gend tag is also used for corrections of the overuse of the distinctly masculine form of adjectives:

*	min **käre** mamma -> min **kära** mamma

(Since the masculine form is never obligatory, corrections from the feminine/common form to the masculine form are not made during the normalization, and thus do never occur in the correction annotation process.)

**Note**: Gender corrections of pronouns which are due to their anaphoric reference will be covered by the L-Ref tag.

#### M-Num (number)

The M-Num tag is used to mark number corrections of nouns, articles, adjectives, participles, and pronouns with adjective-like functions.

_Examples_

*	Stress kan komma i många **form** -> Stress kan komma i många **former**

*	Så fort bilder är **tagen** -> Så fort bilderna är **tagna**

*	Alla sitter bakom sina **skärmens** sken -> Alla sitter bakom sina **skärmars** sken

**Note**: Number corrections of pronouns which are due to their anaphoric reference will be covered by the L-Ref tag.

#### M-Other

The M-Other tag is used for corrections involving inflectional morphology for which none of the other M tags are suited, or for ambiguous cases when different sound interpretations of the correction lead to different M tags.

The usage of the M-Other tag covers corrections between the comparational forms of adjectives, including corrections between non-morphologically related words functioning as different comparational forms of the same adjective (e.g. _dålig_ and _sämre_ or _många_ and _fler_):

* I slutligen kan jag säga utifrån texterna jag läste att det finns **många** nackdelar än fördelar med att avskaffa den obligatorisk svenskan i Finland -> Slutligen kan jag säga , utifrån texterna jag har läst , att det finns **fler** nackdelar än fördelar med att avskaffa den obligatoriska svenskan i Finland

* Morfar ville visa de att det finns nånting som är **viktigaste** , deras förändringen t.ex. -> Morfar ville visa dem att det finns nånting som är **viktigare** , deras förändring t.ex.

**Note**: Take care not to overuse the M-Other tag. The other M tags should be carefully considered before choosing this one.

#### M-Verb

The M-Verb tag covers corrections regarding inflectional verb forms and basic tense constructions involving auxiliaries.

The verb-related grammatical categories involved are primarily tense, mode and voice.

The verb forms involved are the non-finite verb forms (infinitive and supine), the basic tense forms (present and past), the imperative, and the s-forms (both when used in passive constructions and in other uses).

The extra-inflectional constructions involved are the tense-related constructions including the auxiliary verbs _ha_, _skola_ and _komma_ and the non-finite verb forms.

_Examples_

*	Jag **trivs** där för att jag hade fler vänner -> Jag **trivdes** där för att jag hade fler vänner

*	Slutligen tror jag att sociala medier **blev** en essentiell del -> Slutligen tror jag att sociala medier **har blivit** en essentiell del

*	Det betyder inte att vi glomma bort vår tradition  Det betyder inte att vi **ska** glömma bort vår tradition

*	Världen **utvecklar** i teknologin i varje minut -> Världen **utvecklas** i teknologin i varje minut

### P – Punctuation corrections

The P tags represent the category of _punctuation corrections_, including instances of of merging or splitting sentences. It has four sub-categories.

#### P-M (missing punctuation)

The P-M tag is used for corrections involving the addition of a punctuation mark.

_Examples_

*	Jag har fyra **barn två** pojkar och två flickor -> Jag har fyra **barn, två** pojkar och två flickor

*	År 1972 togs den sista manuella växeln ur **bruk anger** Björkkvist -> År 1972 togs den sista manuella växeln ur **bruk, anger** Björkkvist

*	Det ger en positiv **energi därmed** kan man bli av med stress -> Det ger en positiv **energi. Därmed** kan man bli av med stress

*	Min mamma lagar så god **mat jag** trivs med hennes mat -> Min mamma lagar så god **mat. Jag** trivs med hennes mat

**Note**: Additions of hyphens between words are not included in this category, but in the O-Comp category.

#### P-R (redundant punctuation)

The P-R tag is used for corrections involving the removal of a punctuation mark.

_Examples_

*	Jag minns inte **exakt. vad** det var med det var gott -> Jag minns inte **exakt vad** det var men det var gott

**Note**: Removals of hyphens between the constituent words in a compound are not included in this category, but in the O-Comp category.


#### P-Sent (sentence segmentation)

The P-Sent tag is used for corrections involving splitting a sentence or merging two sentences into one, when this correction involves more than the pure insertion or removal of a punctuation mark – in the typical case the adding or removal of a conjunction.

_Examples_

*	Jag heter xxx och jag pratar arabiska och engelska och lite **svenska och vi** har tre rum i huset -> Jag heter xxx och jag pratar arabiska och engelska och lite **svenska. Vi** har tre rum i huset.

In this example, the P-Sent tag is placed on a link between _och_ in the original text and the period in the normalized text. The link between _vi_ and _Vi_ is tagged with C, as a consistency correction necessitated by another correction.

* Catharina börjar med att beskriva Marie Tolppanens ( som är en politiker inom Finlands riksdag ) åsikt om svenska **som** hon tycker att svenska har ingen plats finska skolor och enligt hon är det betydligt mer logiskt att barnen ska lära sig ryska istället för svenska -> Catharina börjar med att beskriva Marie Tolppanens ( som är en politiker i Finlands riksdag ) åsikt om svenska **.** Hon tycker att svenska har ingen plats i finska skolor och enligt henne är det betydligt mer logiskt att barnen ska lära sig ryska istället för svenska

In this example, the P-Sent tag is placed on a link between _som_ in the original text and the period in the normalized text. The link between _hon_ and _Hon_ is tagged with C, in the same way as in the example above.

#### P-W (wrong punctuation)

The P-W tag is used when a punctuation mark in the original text has been replaced with another punctuation mark in the normalized text.

_Examples_

*	Mina barn heter **Peter; Maria; Elisabeth** och John -> Mina barn heter **Peter, Maria, Elisabeth** och John

**Note (1)**: Instances where a space has been corrected to a hyphen between the constituent words in a compound are not marked with this tag, but with O-Comp or S-Comp. The same holds for instances where a hyphen between words has been corrected to a space.

**Note (2)**: Instances where a hyphen has been used in the original text where a dash would be more appropriate are left uncorrected and should thus not appear as corrections to be annotated.

**Note (3)**: Possible errors involving the incorrect placement of _a space before a punctuation mark_ will not be corrected in the normalization process, since spaces are always inserted before punctuation marks for the sake of tokenization. Consequently, such errors will not be tagged.

**Note (4)**: Possible errors involving the lack of _a space between a punctuation mark and the following word_ are corrected in the normalization process (a space is inserted), but are nevertheless left untagged.

_Example_:

*	Jog kan ante skriv meka ord .tack  Jag kan inte skriva många ord. Tack.

In this example, a space is inserted between the period and _tack_, and the _t_ in _tack_ is changed from lower to upper case. _Tack_ will be tagged with O-Cap, but the insertion of the space will not be tagged.

### S – Syntactical corrections

The S tags represent the syntactical correction category. It contains eleven sub-categories.

#### S-Adv (adverbial placement)

The S-adv tag is used for corrections involving the placement of an adverbial.

This word order tag has the highest priority of the three word order tags (S-Adv, S-FinV and S-WO), and should be applied whenever a word order correction may be interpreted as concerning the placement of an adverbial. Particularly, word order corrections regarding the relative ordering between an adverbial and a finite verb, should be marked as S-Adv rather than as S-FinV.

_Examples_

*	Jag **ofta** är vaken länge på kvällarna. → Jag är **ofta** vaken länge på kvällarna.

*	Å ena sidan **idag** har… → Å ena sidan har **idag**… 

*	Jag är jättetrött eftersom jag sover **inte** på nätterna. → Jag är jättetrött eftersom jag **inte** sover på nätterna.

*	som i sin tur har **tydligt** påverkat ... →  som i sin tur **tydligt** har påverkat ... 

*	och **med hela världen** dela sina idéer och tankar. → och dela sina idéer och tankar **med hela världen**.

*	om hur **under 600 år** Finland var en del av Sverige → om hur Finland var en del av Sverige under **600 år**

#### S-Clause 
The S-Clause tag is used for corrections involving changes of the most basic clause structure. The corrections in this category may be divided into the two following main types:

1. The structure of a clause is changed in a way which involves changing the primary syntactic function (subject, finite verb, object, _egentligt subjekt_ (‘object-positioned subject’) and predicative) of one or more of the words involved, for instance:

* Subject changed to a prepositional complement in an adverbial:

     - **du blir bättre** -> **det blir bättre för dig**
   
* Changes between a passive construction and an active construction:

     - I texten **sägs det av henne** att hon efterlyser de som enbart talar finska och är positiva till svenskan och tvåspråkigheten . -> I texten **säger hon** att hon efterlyser de som enbart talar finska och är positiva till svenskan och tvåspråkigheten .
     
* Subject changed to _egentligt subjekt_ (’object-positioned subject’):

     - på andra sidan finns **människor som har så mycket pengar att de kan köpa halva världen** -> Å andra sidan finns det **människor som har så mycket pengar att de kan köpa halva världen** (cf. S-Msubj and note below)
     
     - Fler faktorer för detta finns , exempelvis **mellan 1950 och 1980 skedde en inflyttning** då många svenskar från Finland flyttade tillbaka till Sverige -> Fler faktorer bakom detta finns , exempelvis **att det mellan 1950 och 1980 skedde en inflyttning** då många svenskar från Finland flyttade tillbaka till Sverige (Att _is marked with S-type_, det _is marked with S-Msubj, and_ en inflyttning _is marked with S-Clause. Cf. S-Msubj and S-Type.)
     
2. The structure of a phrase or a clause is changed in a way which involves adding a clause to its internal structure, for instance:

* The structure of a noun phrase is changed by changing a _framförställt attribut_ (‘preceding attribute’) to an _efterställt attribut_ (‘succeeding attribute’) in the form of a relative clause

     - **min plats** -> **platsen där jag bor**
     
* The structure of a clause is changed in a way which involves adding an extra level of subordination. In the following example an ambiguous clause structure is normalized in a way which involves adding a finite verb (_är_), and thus an extra clause, to the structure. The following clause is changed from a main clause to a subordinate clause (by changing _så_ to _att då_). _Är_ is tagged with S-Clause, and a link between _så_ in the original text and _att då_ in the normalized text is tagged with S-Type:

     - Konsekvenserna man skulle få ifall undervisning i svenska blev frivillig så skulle mer än hälften av finska befolkningen avskaffa svenskan som modersmålsundervisning och istället fokusera på finska då dem sällan använder svenskan -> Konsekvenserna man skulle få ifall undervisning i svenska blev frivilligt **är** att då skulle mer än hälften av den finska befolkningen välja bort svenskan som modersmålsundervisning och istället fokusera på finska då de sällan använder svenskan

**Note**: When a clause is changed by 1) adding an expletive _det_ as a subject and 2) changing a subject to an _egentligt subjekt_ (‘object-positioned subject’), two tags are needed to mark the corrections:

* The S-Msubj tag is placed on the added _det_.

* The S-Clause tag is placed on the element which has been changed from subject to _egentligt subjekt_ (‘object-positioned subject’).


#### S-Comp (compound vs multi-word expression)

The S-Comp tag is used for:

* corrections regarding the choice between a compound and a multi-word expression. This includes the choice between a compound and a phrasal structure for the combination of a verb and a verbal particle. (See the special section on verbal particles and reflexives.)

     - **det vardagliga livet** -> **vardagslivet**

     -	**livsskillnaden** -> **skillnaden i liv**

     -	**svenska undervisningar** -> **svenskundervisning**

     - **avsnittet av texten** -> **textavsnittet**

     -	Enligt Hyltenstam så kan minoritetsspråk räddas om man **inblandar** dem äldre som kan språket -> Enligt Hyltenstam så kan minoritetsspråk räddas om man **blandar in** de äldre som kan språket
     
     -	Om det händer att det finns planhalvor så kan det bero på blyghet, osäkerhet, rädsla eller **socialfobi** -> **social fobi** (See the section on compounds vs multi-word phrases for further discussion of this example.)

     -	Hejdlös **sociala medier användning** orsakar ensamhet -> Hejdlös **användning av sociala medier** orsakar ensamhet (See the section on compounds vs multi-word phrases for further discussion of this example.)

* other corrections involving the restructuring of the same lexical morphemes within a phrase

     - Skillnader är stor av **Sveriges bostad** -> Skillnaderna är stora mot **bostäder i Sverige**

     - Cecila Christner skriver om hur det svenska språket i skolor blir kallad tvångsvenska **i samma tid** svenska har blivit icke populärt i Finland -> Cecilia Christner skriver om hur det svenska språket i skolorna blir kallat tvångssvenska **samtidigt** som svenska har blivit impopulärt i Finland

* corrections involving the change between an expression with a lexical negation and an expression with a derivational negation:

     - Cecila Christner skriver om hur det svenska språket i skolor blir kallad tvångsvenska i samma tid svenska har blivit **icke populärt** i Finland -> Cecilia Christner skriver om hur det svenska språket i skolorna blir kallat tvångssvenska samtidigt som svenska har blivit **impopulärt** i Finland

**Note**: Corrections regarding the mere orthographic rendering of a string with or without a space should not be marked with the S-Comp tag but with the O-Comp tag. (See O-Comp and the section on compounds vs multi-word expressions below.)

#### S-Ext  (extensive, complex correction)

The S-Ext tag is used for extensive, complex corrections. The syntactic structure of the normalized text segment may rather be described as _created_ than as _corrected_, and the correction often also involves the addition of lexical words. The original text gives a fair indication of the intended meaning (otherwise the correction would be X-marked), but it gives a very poor basis for assuming a specific syntactic goal structure.

_Examples_

* **Det därför tycker jag om det är** simma lungt och blåser -> **Jag tycker om det för att jag tycker om** att simma lugnt och när det blåser

* Jag hoppas att du **intressant för din ny livs** -> Jag hoppas att du **tycker att ditt nya liv är intressant**

* Så hur mycket pojkarna bettalad **värt inte deras äppelträd** eftersom trädet var viktig för dem -> Så hur mycket pojkarna betalade **var mindre än vad deras äppelträd var värt** eftersom trädet var viktigt för dem .

* Det är lite bättre i huvudstad , när många manniskor bo tilsammans eftersom **de kan e betala för** -> Det är lite bättre i huvudstaden , när många människor bor tillsammans eftersom **det gör att de kan betala** (det gör att _in the normalization is tagged with S-Ext_; e _in the original text is tagged with X and S-R_; för _is tagged with S-R_.)

**Note**: The S-Ext tag should only be applied in cases when a correction has actually been made, and when the original text gives fairly sound support for the interpretation presented in the normalized version. Text segments which are so difficult to interpret that they are either left unchanged or normalized on the basis of guesses rather than interpretations should be tagged with X.

#### S-FinV (placement of finite verb)

The S-FinV tag is used for corrections concerning the placement of a finite verb, unless the correction regards the ordering between the finite verb and an adverb, in which case the correction is tagged with the S-Adv tag. The S-FinV tag thus has lower priority than the S-Adv tag, but higher priority than the S-WO tag.

_Examples_

*	Vor du **bor**? -> Var **bor** du?

*	I morgon jag **åker** -> I morgon **åker** jag

*	Efteråt man **surfar** på internet -> Efteråt **surfar** man på internet

*	När jag ätiti, jag **sover** -> När jag ätit, **sover** jag

*	Eller det **skapar** kontakter och trivs? -> Eller **skapar** de kontakter och trivsel?

#### S-M (word missing, other)

The S-M tag is used when a word is missing in the original text and has been added in the normalized version. This includes the addition of reflexives and verbal particles. (See the special section on verbal paricles and reflexive.)

The S-M tag has lower priority than the S-Msubj tag and the M-Def tag, and should only be applied in cases when neither of these other tags may be applied.

_Examples_

*	Hon fördelen med att behålla den obligatoriska svenskan -> Hon **beskriver** fördelen med att behålla den obligatoriska svenskan.

*	Sådana känslor gör användaren mår dåligt -> Sådana känslor gör **att** användaren mår dåligt

*	Jag gillar inte tapeterna i min kusins lägenhet men han inte byta dem eftersom det är hyresrätt → ... han **kan** inte byta dem ...

*	Jag trivs mycket bo med dem -> jag trivs mycket **med att** bo med dem

*	Man måste akta att man inte ramlar -> man måste **akta sig så** att man inte ramlar

*	men känner bara fysiskt närvarande -> men känner **sig** bara fysiskt närvarande

*	Jag slår ord i ordboken när jag inte vet -> Jag slår **upp** ord i ordboken när jag inte vet...

#### S-Msubj (subject missing)

The S-Msubj tag is used to mark corrections involving the addition of a subject which is missing in a clause in the original text. This includes cases when the pronoun/subordinating conjunction _som_ has been inserted as a subject.

The S-Msubj tag has higher priority than the S-M tag.

_Examples_

*	Regnar ute -> **Det** regnar ute

*	Det är inte bara arbetet och arbetslivet kan ge stress -> Det är inte bara arbetet och arbetslivet **som** kan ge stress

*	Det är viktigt att veta vad händer -> Det är viktigt att veta vad **som** händer

* I annan text " Tre röster om svenskans ställning i Finland " Parnass 2013:3 som är skriven av författaren Catharina Söderbergh beskriver dem tre olika ställningar som finns om svenska inom Finland -> I en annan text , " Tre röster om svenskans ställning i Finland " ( Parnass 2013:3 ) , som är skriven av författaren Catharina Söderbergh , beskriver **författaren** de tre olika inställningar som finns till svenska i Finland

* Finns många nya lagenheterna i dyrare delar i huvudstaden -> **Det** finns många nya lägenheter i dyrare delar i huvudstaden

The S-Msubj tag should be placed on a _det_ which has been inserted as a subject, also in the following cases:

* _Det_ replaces a subject which has been changed to an _egentligt subjekt_ (‘object-positioned subject’) (cf. S-Clause)

     - på andra sidan finns **människor som har så mycket pengar att de kan köpa halva världen** -> Å andra sidan finns **det människor som har så mycket pengar att de kan köpa halva världen** (_The inserted_ det _is tagged as S-Msubj and the moved subject is marked as S-Clause_)
     
* A heavy subject is moved to a position further back in the clause, and _det_ is inserted in the subject position:
     
     - Hon försätter skriva om **att inte avskaffa den obligatoriska svenskan på skolan** är fördel för ungdomar -> Hon fortsätter skriva om att **det** är en fördel för ungdomar **att inte avskaffa den obligatoriska svenskan i skolan** (_The inserted_ det _is tagged as S-Msubj and the moved subject is marked as S-WO._)
     
* _Det_ (and possibly _att_) is inserted as a subject before an infinitive phrase already functioning as a subject (and the infinitive phrase becomes an attribute to _det_):

     - Hon skriver också om att ha svenska som obligatorisk i Finland visar att alla är ju finnar och att " finlandssvenska " är bara påhittat . -> Hon skriver också om att **det att** ha obligatorisk svenska i Finland visar att alla är ju finnar och att " finlandssvenska " är bara påhittat .

**Note**: The S-Msubj tag should only be applied in those cases when the clause is already present in the original text. Thus, in the following example, the generic pronoun _man_ is added as a subject as a part of a correction involving changing an infinitive phrase to a finite clause, and the correction, including the addition of _man_, is marked as S-type. The S-Msubj tag should not be applied.

* Att växa upp som en flicka så var det väldigt många orättvisor man fick vänja sig vid. -> När man växte upp som en flicka så var det väldigt många orättvisor man fick vänja sig vid.

#### S-Other

The S-Other tag is used for syntactic corrections not covered by any of the other S-tags.

#### S-R (word redundant)

The S-R tag is used when a word is redundant in the original text and has been removed in the normalized version. This includes the removal of reflexives and verbal particles. (See the section on verbal particles and reflexives.)

The S-R tag has lower priority than the M-Def tag, and should only be applied in cases when the M-Def tag is not applicable.

_Examples_

*	På 2000- talet kom många kommunikationsappar , bland annat **var** Facebook , Twitter , Instegram och Snapchat , påpekar Rose ( 2012 ) -> På 2000- talet kom många kommunikationsappar , bland annat Facebook , Twitter , Instagram och Snapchat , påpekar Rose ( 2012 )

*	Man behöver inte **att** klä på sig -> Man behöver inte klä på sig

*	Det är ett personligt ansvar **för** att välja -> Det är ett personligt ansvar att välja ...

* X-stad är närmare **till** X-land än X-stad. -> X-stad är närmare X-land än X-stad.

*	De första mobiltelefonerna kom **i** 1957. -> De första mobiltelefonerna kom 1957.

*	De nya kommunikationssätten har medfört **med** stora möjligheter -> De nya kommunikationssätten har medfört stora möjligheter

*	sociala medier blev en essentiell del av våra liv som vi inte kan slänga **det** i den moderna världen -> sociala medier blev en essentiell del av våra liv som vi inte kan slänga i den moderna världen

*	De promenerade **sig** i parken -> De promenerade i parken

*	Hon gav **bort** honom en blomma -> Hon gav honom en blomma

#### S-Type (change of phrase or clause type)

The S-Type tag is used when a phrase or clause has in its entirety been changed to another phrase- or clause-type, such as:

* changes between a noun phrase and an infinitive phrase:

     - jag behover pengar f$r **liv** och **betalning av** min hus -> jag behöver pengar för **att leva** och **betala** för mitt hus (_Cf. the same examples under L-W and L-Der; two tags are used for each of these changes_)
     
* changes between a finite clause and a noun phrase:

     - I artikeln " Tre röster om svenskan ställning i Finland " ( Parnass , 2013:3 ) skriver Catharina Söderbergh om tre personer som har sagt sin åsikt om tvångssvenskan och **hur svenskan befinner sig** . -> I artikeln " Tre röster om svenskans ställning i Finland " ( Parnass 2013:3 ) skriver Catharina Söderbergh om tre personer som har sagt sin åsikt om tvångssvenskan och **läget för svenskan** .
     
* changes between an infinitive phrase and finite clause:

     - **Att växa** upp som en flicka så var det väldigt många orättvisor man fick vänja sig vid. -> **När man växte** upp som en flicka så var det väldigt många orättvisor man fick vänja sig vid. (Cf. S-Msubj.)
     
* changes between a subordinate clause and a main clause:

     - Fler faktorer för detta finns , exempelvis **mellan 1950 och 1980 skedde en inflyttning** då många svenskar från Finland flyttade tillbaka till Sverige -> Fler faktorer bakom detta finns , exempelvis **att det mellan 1950 och 1980 skedde en inflyttning** då många svenskar från Finland flyttade tillbaka till Sverige (Att _is marked with S-type_, det _is marked with S-Msubj, and_ en inflyttning _is marked with S-Clause. Cf. S-Msubj and S-Clause._)
     
     - Konsekvenserna man skulle få ifall undervisning i svenska blev frivillig **så skulle mer än hälften av finska befolkningen avskaffa svenskan som modersmålsundervisning** och istället fokusera på finska då dem sällan använder svenskan -> Konsekvenserna man skulle få ifall undervisning i svenska blev frivilligt **är att då skulle mer än hälften av den finska befolkningen välja bort svenskan som modersmålsundervisning** och istället fokusera på finska då de sällan använder svenskan (Är _is tagged with S-Clause_; _a link between_ så _and_ att då _is marked with S-Type_.)
     
**Note (1)**: The S-Type tag may be combined with the L-W tag and the L-Der tag. See these sections for examples.

**Note (2)**: Word-order corrections covered by the word-order tags (S-Adv, S-FinV, S-WO) are not in themselves a basis for considering the correction a change of clause type (but rather as corrections to suit a clause type which has been indicated by other means). The S-Type tag should thus not be applied to a correction solely on the basis of an adverbial having been moved from a typical main clause position to a typical subordinate clause position (or vice versa). That correction is covered by the S-Adv tag. For an S-Type tag to be applied to a clause which has been changed from a subordinate clause to a main clause etc., the change of clause structure has to be indicated for instance by the addition of or removal of a subjunction.

#### S-WO (word order, other)

The S-WO tag is used for word order corrections which are not covered by the S-Adv or the S-FinV categories.

In corrections regarding the relative placement of a phrasal head and a modifying element (for instance a noun and its attribute), the modifying element should be marked rather than the phrasal head (e.g. _min_ rather than _bostad_ in the example below):

*	Bostaden **min** -> **Min** bostad

In cases when the word order change may be interpreted as moving an element “out of” a normally fairly fixed structure, that element should be marked rather than an element included in the more fixed structure (_dem_ rather than _upp_ in the example below).

*	Man kan inte vänta att lägga **de** upp på social medier -> Man kan inte vänta med att lägga upp **dem** på sociala medier

In other cases the placement of the tag may be chosen freely between the elements which have been moved relative to each other, but the readability of the resulting visualization should be taken into consideration.

### Other tags

The final group of tags, collected under the heading _Other_, contains six tags used for various purposes:

*	The C tag is used for corrections which are necessitated by other corrections, but which do not reflect mistakes in the original text.

*	The Com! and OBS! tags are used for notes and comments – the Com! tag for comments intended for the future corpus user, and the OBS! tag for work notes on pending analyses meant for internal project use.

*	The Cit-FL tag is used for segments of foreign language which have not been corrected during normalization.

*	The X tag is used for unintelligible strings.

*	The Unid tag is used for “unidentified” corrections, i.e. corrections which are not covered by any of the correction categories defined in the taxonomy.

Four of these tags, namely Cit-FL, Com!, OBS! and X are available already during the normalization process, and are normally inserted already by the normalizer.

#### C – Consistency corrections

The C tag represents consistency corrections, a category which covers necessary (follow-up) corrections in the text that come as a result of a previous correction, i.e. originally there was no mistake in the segment, but due to an introduced correction in the neighboring context, a correction is necessary in the segment. By using this tag we indicate that the error was not made originally by the learner.

In some instances it may not be self-evident which one of two related corrections that should be considered as necessitating the other, but by marking one of them with C we avoid marking a single mistake in the original text as two.

_Examples_

*	**Bostaden** min -> Min **bostad**

The shift of word order is marked as a word order correction (S-WO). The change from definite form (_bostaden_) to indefinite form (_bostad_) of the noun is made necessary because of the shift of word order, and is thus marked as a consistency correction (C).

*	Det ger en en positiv **energi därmed** kan man bli av med stress … -> Det ger en en positiv **energi . Därmed** kan man bli av med stress …

The insertion of the full stop is tagged as a punctuation correction (P-M). The capitalization of the following D is made necessary because of the insertion of the full stop, and is thus marked as a consistency correction (C).

*	**Min** bostanden ser ut som lilla centrum med vlere affere -> **Mitt** bostadsområde ser ut som ...

The change from _bostanden_ to _bostadsområde_ is marked as a lexical correction (L-W) and a morphological correction (M-DEF). The gender change of the pronoun, from _min_ (non-neuter) to _mitt_ (neuter) is made necessary because of the change of word (from the non-neuter _bostad_ to the neuter _bostadsområde_), and is thus marked as a consistency correction (C).

*	För det första **är** vi **går** skolan från dagsskolan till allika nivå för att vi hittar jobb sen tjänar vi lön .
För det första **går** vi i skolan från förskolan till olika nivåer för att vi ska hitta ett jobb , sen får vi lön .

The removal of _är_ is marked as S-R, while the movement of _går_ to the finite verb position (where it replaces the likewise finite verb _är_) is tagged with C.

* När jag kommer **första** i 2012 , jag bodde i en social lagenhet med 3 andra person -> När jag **först** kom 2012 bodde jag i en kommunal lägenhet med 3 andra personer 

The link between _första_ and _först_ is tagged with S-Adj/adv (see this section) **and** with C, which indicates that the word order change is a consequence of the change from adjective to adverb. (An alternative normalization would be to keep the adjective form _första_ and add the noun _gången_.)

* Jag stoppade i lång tid att saga till mina vänner i D-hemland hur jag bo här , **vad** extra vi ha här , e.g. tvättstuga -> ->  Jag slutade för länge sen att säga till mina vänner i D-hemland hur jag bor här , **vilka** extra **saker** vi har här , t.ex. tvättstuga  och att man kan betala hela avgiften för en lägenhet på under en minut 

The addition of _saker_ is tagged as S-M, and the correction of _vad_ to _vilka_ is tagged with C, since it is the congruence with _saker_ which determines the choice of pronoun.

#### Cit-FL (cited foreign word judged acceptable in the normalization)

The Cit-FL tag is used for foreign (non-Swedish) words, phrases or text segments, which have been kept by the normalizer since their usage has been judged acceptable given the norms of the text type in question. This may be the case for instance for explicitly marked citations or intentional code switching appropriate for the genre. The Cit-FL tag is thus used to mark words and text segments which have _not_ been corrected in the normalized version, but which nevertheless are not passable as standard Swedish.

Note that the only requirement for applying this code is that the word or text segment is recognizable as another language than Swedish, and that the choice to use this other language is judged appropriate for the genre and the text. No judgement or correction of the word or text segment is made relative to the norms of the foreign language in questions. For instance, spelling mistakes are left uncorrected.

The Cit-FL tag is usually added already during normalization.

_Examples_

_Judged as appropriate code switching_:

* Badrum var **basic** men rent -> Badrummet var **basic** men rent

_Clearly marked citation of norwegian passage_:

* I samma artikel skriver Bengt Östling om man läser några webbsidor där norska ungdomar debatterar , förstår man att diskussionen om den obligatoriska nynorskan är inflammerad . **" Ett språk som holdes kunstig i live gjennom tvan og finansiering gjennom skatt , og sakte men sikkert dör ut ja . Det finns ikke vilje hos folk til å beholde nynorsk "** , lyder det i ett debattinlägg . -> I samma artikel skriver Bengt Östling att om man läser några webbsidor där norska ungdomar debatterar , förstår man att diskussionen om den obligatoriska nynorskan är inflammerad . **" Ett språk som holdes kunstig i live gjennom tvan og finansiering gjennom skatt , og sakte men sikkert dör ut ja . Det finns ikke vilje hos folk til å beholde nynorsk "** , låter det i ett debattinlägg .

#### Com! (comments for the corpus users)

The Com! tag is connected to an _edge comment_ field, which is open for freely composed comments. It is available already during the normalization process.

The Com! tag is used for comments on specific tokens or text sequences which are relevant for future users of the corpus, and which are thus meant to be kept in the published corpus. (Comments regarding the text as a whole or recurring properties in the text may be added in the Document comment field.)

The Com! tag may for instance be used to mark text segments which are copied from the task formulation. If a significant portion of the text consists of copied text, this should preferably be indicated also in the Document comment field, in addition to the edge comment field connected to the Com! tag which is inserted on the specific text segment or the specific text segments.

#### OBS! (notes and pending analyses)

The OBS! tag is, like the Com! tag, connected to an edge comment field, and is available already during the normalization process.

The OBS! tag is used to mark pending analyses to which the annotator wants to return, remarks which the normalizer wishes to pass on to the correction annotator, etc.

#### X (unintelligible string)

The X tag is used to mark unintelligible strings in the original text. The tag is available and usually added already during the normalization process. The marked original string may be left unchanged in the normalized version, or the normalizer may replace it with some more or less wild guess of the intended message.

The X tag may be used both in cases when there is no reasonable interpretation of the string, and when there are several somewhat reasonable interpretations, but none of these interpretations may be settled as better than the other.

_Examples_

*	**En argumentera på är viktigt hur man bor är bor på en bra hem**

*	och vi har 3 rum it huset **dar rum** är meka bra liv med maen familija dar huset familjbostder och jag vill **sta** och jog kan ante skriv meka ord -> och vi har 3 rum i huset . **dar rum** är mycket bra liv med min familj där i huset från Familjebostäder och jag vill **stanna** och jag kan inte skriva många ord

The text from which this example is collected has some german or possibly dutch traits, and a fairly resonable guess is that _dar rum_ is meant to be darum. Another, less likely, possibility is that _dar rum_ is intended to mean _där rum_, but that interpretation necessitates extensive changes in the rest of the text passage in order to create a syntactically functional string. By marking _dar rum_ with X and keeping the rest of the sentence unchanged in the normalized text version, the normalization as a whole is better adjusted to the principle of _minimal change_.

_Stanna_ is a reasonable guess about the intention with _sta_, but not well founded enough for the correction to be marked as an orthographic correction. Many other interpretations are obviously also possible.

The X tag may be combined with the S-R tag when the unitelligible string is also redundant, and thus eliminated in the normalization:

* Det är lite bättre i huvudstad , när många manniskor bo tilsammans eftersom **de kan e betala för** -> Det är lite bättre i huvudstaden , när många människor bor tillsammans eftersom **det gör att de kan betala** (det gör att _in the normalization is tagged with S-Ext_; e _in the original text is tagged with X and S-R_; för _is tagged with S-R_.)

#### Unid (unidentified correction)

The Unid tag is used for any type of correction which cannot be covered by any of the correction categories defined in the taxonomy.

### Some specific categorization issues

#### Compounds vs multi-word expressions

Corrections concerning the forming of an expression as a compound or a multi-word expression are divided into two categories in the SweLL correction taxonomy: Corrections which are judged to concern the mere orthographic rendering with or without a space between two words are marked with the O-Comp tag, while corrections which are judged to concern the actual choice between a compound and a multi-word expression are marked with the S-Comp tag. Borderline or unclear cases between these two categories obviously exist, but for the most part one of the options is clearly the better one.

The **O-Comp** tag is primarily used for corrections of standard cases of _särskrivning_ (the faulty writing of a compound with a space in between the two compounded words):

*	Det ligger ett **kultur hus** nära min bostad -> **kulturhus**

It may also be used for corrections which involve changing the first word of the compound into a specific compound form, in addition to the removal of the space between the two words. In such cases, the correction is marked with both the O-Comp tag and the L-Der tag:

*	**Kommunikation förändring** -> **Kommunikationsförändring**

More rarely, the O-Comp tag may be applied when a multi-word expression in the original text has been corrected through the adding of a space between two of the words:

*	**itisdags** -> **i tisdags**

The **S-Comp** tag is used whenever the correction made is more complex than the mere addition or removal of a space between two words (and possibly changing the form of the first word of a compound).

*	**det vardagliga livet** -> **vardagslivet**

*	**livsskillnaden** -> **skillnaden i liv**

*	**svenska undervisningar** -> **svenskundervisning**

*	Enligt Hyltenstam så kan minoritetsspråk räddas om man **inblandar** dem äldre som kan språket -> Enligt Hyltenstam så kan minoritetsspråk räddas om man **blandar in** de äldre som kan språket

However, in some cases the S-Comp tag is more suitable than the O-Comp tag, although the correction superficially merely involves the presence of a space. This is the case when two words may be correctly formed as a compound (without a space) _and_ as a two-word expression (with a space), and the meaning of the compound version and the two-word version are either the same or else both plausible in the context. The correction made is thus not due to the chosen expression being unthinkable, but due to the other expressions happening to be the established lexical unit:

*	Om det händer att det finns planhalvor så kan det bero på blyghet, osäkerhet, rädsla eller **socialfobi** -> **social fobi **

In this case, _socialfobi_ is a perfectly well formed compound, but it is corrected to the two-word expression _social fobi_ because this is the established way to express the intended meaning. The mistake made by the writer is therefore not judged to be a case of having missed a space in between two words in a two-word expression, but it is judged to be a case of the writer actually having chosen the compound expression instead of the established two-word expression. The correction is thus marked with the S-Comp tag.

Moreover, in some cases the S-Comp tag may be applied although neither the original nor the normalized string is a single orthographic word. This is the case when the string in the original text may be interpreted as an instance of a compound, although it includes spaces:

*	Hejdlös **sociala medier användning** orsakar ensamhet -> Hejdlös **användning av sociala medier** orsakar ensamhet

In this particular case, the string in the original text may be interpreted as a compound between a two-word phrase (_sociala medier_) and the word _användning_. According to the norms of written standard Swedish, such compounds should be written as _sociala medier-användning_ etc. While such a minimal correction is not an unthinkable solution for the normalization, the normalizer has here judged a restructuring of the NP as a better solution, and the correction should be tagged S-Comp.

#### Non-Swedish words and sequences

There are a number of ways to handle non-Swedish words during normalization and correction annotation. Many of the fundamental choices are made during the normalization process rather than during the correction annotation process.

The first judgement to be made when coming across a word stemming from another language in the material is naturally whether the word may be recognized as having been incorporated into written standard Swedish; in such cases the word is left uncorrected and untagged. This judgement is made during normalization.

When a word (or sequence) in an original text is recognized as belonging to a foreign language – or as having traits from a foreign language – and when this word may _not_ be recognized as part of written standard Swedish, a number of options are at hand:

1)	The word/sequence is judged as a genre appropriate usage of cited foreign language (explicitly signaled citations, code switching etc.). -> Not corrected, tagged Cit-FL during normalization.

2)	The word is not judged as a genre appropriate usage of cited foreign language and is thus corrected to a Swedish word during normalization:

     a)	The form used may be interpreted as a misspelled Swedish word. -> Corrected during normalization, tagged O during correction annotation: **kaffee** -> **kaffe**; **can** -> **kan**
     
     b)	The form used may be interpreted as a Swedish word with an incorrect usage of derivational affixes etc. -> Corrected during normalization, tagged L-Der during correction annotation: **national helgdag** -> **nationell helgdag**
     
     c)	Neither a nor b applies. -> Corrected during normalization, tagged L-FL during correction annotation: **balkony** -> **balkong**; **family** -> **familj**; **gas bojler** -> **gaskokare**
  
**Note**: A word in the original text which is identifiable as a Swedish word, but which is used with another meaning in a way which is likely to be due to influence from a similar non-Swedish word, should be corrected and marked as L-W (not as L-FL):

*	Alla blir **busiga** med sina sociala medier. -> Alla blir **upptagna** med sina sociala medier

In this example, it is likely that the incorrect usage of the correct Swedish word _busiga_ is influenced by the word’s similarity to the English word _busy_ – and it is partly based on this assumption that the writer’s intended meaning has been interpreted as 'upptagna'. But since _busiga_ is a correct Swedish word, with a distinctly Swedish morphological structure, the correction is tagged as L-W rather than as L-FL.

#### Verbal particles and reflexives

Several tags are used for corrections involving phrasal or compound verbs made up by a verb and verbal particle or a reflexive marker, primarily O-Comp, S-Comp, L-Der, L-W, S-M and S-R. This section provides an overview of the usage of these six tags for this category of corrections.

*	O-Comp: A space is removed between a verbal particle and a following verb, making up a compound verb:

     - **upp mana** -> **uppmana**
     
*	S-Comp: A compound form of a particle verb is changed to a phrasal form, or the other way around:

     -	Enligt Hyltenstam så kan minoritetsspråk räddas om man **inblandar** dem äldre som kan språket -> Enligt Hyltenstam så kan minoritetsspråk räddas om man **blandar in** de äldre som kan språket
     
     -	Tåget **går av** från spår 3 -> Tåget **avgår** från spår 3
     
*	L-Der: A particle of a compound particle verb is changed, removed or added. Both the original and the normalized string consist of one single token. The original string may or may not be an existing Swedish word.

     -	Internet **uppmanar** vår förståelse -> Internet **utmanar** vår förståelse
     
     -	Han **inhämtade** väskorna från hotellrummet -> Han **hämtade** väskorna från hotellrummet
     
     -	Hon **minde** honom om mötet på eftermiddagen -> Hon **påminde** honom om mötet på eftermiddagen
     
*	L-W, placed on the whole phrasal verb: Either the original string or the normalized string (or both) is a phrasal verb, and the verb itself is changed, not just the particle/reflexive marker:

     -	Traditioner ger människorna tid att **stå still** och fundera över livet → … att **stanna upp** och fundera över livet.
     
*	L-W, placed on the particle: A verbal particle is replaced by another verbal particle, but the verb is kept:

     -	Han torkade **bort** bordet -> Han torkade **av** bordet
     
*	S-M: An independent (non-compound) verbal particle or a reflexive marker is added:

     -	men känner bara fysiskt närvarande -> men känner **sig** bara fysiskt närvarande
     
     -	Jag slår ord i ordboken när jag inte vet -> Jag slår **upp** ord i ordboken när jag inte vet...
     
*	S-R: An independent (non-compound) verbal particle or a reflexive is removed.

     -	De promenerade **sig** i parken -> De promenerade i parken
     
     -	Hon gav **bort** honom en blomma -> Hon gav honom en blomma
     
## Appendix with illustrated examples



