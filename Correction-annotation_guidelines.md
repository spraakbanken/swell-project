# Correction annotation guidelines

# Table of Contents

- [1. Introduction](#1-introduction)
 
  - [1.1  The purpose of the correction annotation](#11-the-purpose-of-the-correction-annotation)

  - [1.2  The purposes of this document](#12-the-purposes-of-this-document)

  - [1.3  The organization of the document](#13-the-organization-of-the-document)

- [2. The most fundamental principles and terms](#2-the-most-fundamental-principles-and-terms)

  - [2.1  What is a correction? What is annotated?](#21-what-is-a-correction-what-is-annotated)

  - [2.2  Correction, unit, link and tag](#22-correction-unit-link-and-tag)

- [3. The general structure of the taxonomy](#.-the-general-structure-of-the-taxonomy)

  - [3.1  The main correction categories](#31-the-main-correction-categories)

  - [3.2  Overview of the taxonomy](#32-overview-of-the-taxonomy)

  - [3.3  Tag choice algorithm](#33-tag-choice-algorithm)

    - [3.3.1 Additions](#331-additions)

    - [3.3.2 Deletions](#332-deletions)

    - [3.3.3 Movements (word order changes)](#333-movements-word-order-changes)

    - [3.3.4 Changes involving a multi-word unit in either the original version, the normalized version or both](#334-changes-involving-a-multi-word-unit-in-either-the-original-version-the-normalized-version-or-both)

    - [3.3.5 Changes: one-word unit changed to one-word unit, change of inflectional morphology or functionally parallel stem change](#335-changes-one-word-unit-changed-to-one-word-unit-change-of-inflectional-morphology-or-functionally-parallel-stem-change)

     - [3.3.6 Changes: one-word unit changed to one-word unit, word stem exchanged or morphologically restructured](#336-changes-one-word-unit-changed-to-one-word-unit-word-stem-exchanged-or-morphologically-restructured)

     - [3.3.7 Changes: one-word unit changed to a one word unit, spelling (including uses of spaces and hyphens and token-internal punctuation)](#337-changes-one-word-unit-changed-to-a-one-word-unit-spelling-including-uses-of-spaces-and-hyphens-and-token-internal-punctuation)

     - [3.3.8 Changes: at least one of the units is a punctuation mark](#338-changes-at-least-one-of-the-units-is-a-punctuation-mark)

- [4. General directions for the correction annotation](#4-general-directions-for-the-correction-annotation)

  - [4.1 Adjustment of links and attachment of tags](#41-adjustment-of-links-and-attachment-of-tags)

  - [4.2 Some errors are not tagged](#42-some-errors-are-not-tagged)

  - [4.3 Only visible corrections are tagged](#43-only-visible-corrections-are-tagged)

  - [4.4 Positive assumption principle](#44-positive-assumption-principle)

  - [4.5 Several tags on the same link](#45-several-tags-on-the-same-link)

  - [4.6 Grouping of tokens](#46-grouping-of-tokens)

  - [4.7 Corrections of tokens included in group units](#47-corrections-of-tokens-included-in-group-units)

  - [4.8 Annotation of strings including unreadable signs in transcribed texts](#48-annotation-of-strings-including-unreadable-signs-in-transcribed-texts) 

  - [4.9 Document comments](#49-document-comments)

- [5. Descriptions of each tag](#5-descriptions-of-each-tag)

  - [5.1 O - Orthographic corrections](#51-o-orthographic-corrections)

     - [5.1.1 O (regular spelling correction)](#511-o-regular-spelling-correction)

     - [5.1.2 O-Cap (upper/lower case)](#512-o-cap-upperlower-case)

     - [5.1.3 O-Comp (spaces and hyphens between words)](#513-o-comp-spaces-and-hyphens-between-words)

  - [5.2 L - Lexical corrections](#52-l-lexical-corrections)

     - [5.2.1 L-Der (word formation)](#521-l-der-word-formation)

     - [5.2.2 L-FL (foreign word corrected to Swedish)](#522-l-fl-foreign-word-corrected-to-swedish)

     - [5.2.3 L-Ref (anaphoric expressions)](#523-l-ref-anaphoric-expressions)

     - [5.2.4 L-W (wrong word or phrase)](#524-l-w-wrong-word-or-phrase)

  - [5.3 M - Morphological corrections](#53-m-morphological-corrections)

     - [5.3.1 M-Adj/adv (adjective corrected to adverb)](#531-m-adjadv-adjective-corrected-to-adverb)

     - [5.3.2 M-Case](#532-m-case)

     - [5.3.3 M-Def (definiteness)](#533-m-def-definiteness)

     - [5.3.4 M-F (wrong form, correct grammatical category)](#534-m-f-wrong-form-correct-grammatical-category)

     - [5.3.5 M-Gend (gender)](#535-m-gend-gender)

     - [5.3.6 M-Num (number)](#536-m-num-number)

     - [5.3.7 M-Other](#537-m-other)

     - [5.3.8 M-Verb](#538-m-verb)

  - [5.4 P - Punctuation corrections](#54-p-punctuation-corrections)

     - [5.4.1 P-M (missing punctuation)](#541-p-m-missing-punctuation)

     - [5.4.2 P-R (redundant punctuation)](#542-p-r-redundant-punctuation)

     - [5.4.3 P-Sent (sentence segmentation)](#543-p-sent-sentence-segmentation)

     - [5.4.4 P-W (wrong punctuation)](#544-p-w-wrong-punctuation)

  - [5.5 S - Syntactical corrections](#55-s-syntactical-corrections)

     - [5.5.1 S-Adv (adverbial placement)](#551-s-adv-adverbial-placement)

     - [5.5.2 S-Clause (basic clause structure)](#552-s-clause-basic-clause-structure)

     - [5.5.3 S-Comp (compound vs multi-word expression)](#553-s-comp-compound-vs-multi-word-expression)

     - [5.5.4 S-Ext (extensive correction)](#554-s-ext-extensive-correction)

     - [5.5.5 S-FinV (placement of finite verb)](#555-s-finv-placement-of-finite-verb)

     - [5.5.6 S-M (word missing, other)](#556-s-m-word-missing-other)

     - [5.5.7 S-Msubj (subject missing)](#557-s-msubj-subject-missing)

     - [5.5.8 S-Other](#558-s-other)

     - [5.5.9 S-R (word redundant)](#559-s-r-word-redundant)

     - [5.5.10 S-Type (change of phrase type/part of speech)](#5510-s-type-change-of-phrase-typepart-of-speech)

     - [5.5.11 S-WO (word order, other)](#5511-s-wo-word-order-other)

  - [5.6 Other tags](#56-other-tags)

     - [5.6.1 C - Consistency corrections](#561-c-consistency-corrections)

     - [5.6.2 Cit-FL (cited foreign word judged acceptable in the normalization)](#562-cit-fl-cited-foreign-word-judged-acceptable-in-the-normalization) 

     - [5.6.3 Com! (comments for the corpus users)](#563-com-comments-for-the-corpus-users)

     - [5.6.4 OBS! (notes and pending analyses)](#564-obs-notes-and-pending-analyses)

     - [5.6.5 Unid (unidentified correction)](#565-unid-unidentified-correction)

     - [5.6.6 X (unintelligible string)](#566-x-unintelligible-string)

- [6. Discriminating between specific correction categories](#6-discriminating-between-specific-correction-categories)

  - [6.1 O vs punctuation tags](#61-o-vs-punctuation-tags)

  - [6.2 O-Comp vs S-Comp](#62-o-comp-vs-s-comp)

  - [6.3 L-Der vs L-W](#63-l-der-vs-l-w)

  - [6.4 L-Der vs S-Comp](#64-l-der-vs-s-comp)

  - [6.5 L-W vs M-Case](#65-l-w-vs-m-case)

  - [6.6 L-W vs M-Verb](#66-l-w-vs-m-verb)

  - [6.7 L-W vs S-Clause](#67-l-w-vs-s-clause)

  - [6.8 L-W vs S-Comp](#68-l-w-vs-s-comp)

  - [6.9 S-Clause vs word order tags](#69-s-clause-vs-word-order-tags)

  - [6.10 S-Clause vs S-Comp](#610-s-clause-vs-s-comp)

  - [6.11 S-Clause vs S-Ext](#611-s-clause-vs-s-ext)

  - [6.12 S-Clause vs S-M](#612-s-clause-vs-s-m)

  - [6.13 S-Clause vs S-Msubj](#613-s-clause-vs-s-msubj)

  - [6.14 S-Clause vs S-R](#614-s-clause-vs-s-r)

  - [6.15 S-Ext vs S-M](#615-s-ext-vs-s-m)

  - [6.16 S-Ext vs X](#616-s-ext-vs-x)

  - [6.17 S-Type vs S-M and S-R](#617-s-type-vs-s-m-and-s-r)

- [7. Other categorization issues](#7-other-categorization-issues)

  - [7.1 Non-Swedish words and sequences](#71-non-swedish-words-and-sequences)

  - [7.2 Verbal particles and reflexives](#72-verbal-particles-and-reflexives)

  - [7.3 Clause corrected or created?](#73-clause-corrected-or-created)

  - [7.4 Spaces, hyphens and dashes](#74-spaces-hyphens-and-dashes)

  - [7.5 Singular indefinite article removed from plural indefinite NP](#75-singular-indefinite-article-removed-from-plural-indefinite-np)

  - [7.6 Exceptions to the default ranking of the word order tags](#76-exceptions-to-the-default-ranking-of-the-word-order-tags)

# 1. Introduction

## 1.1 The purpose of the correction annotation
----------------------------------------

The purpose of the correction annotation is to make the learner corpus
searchable for different types of deviations from a standard language
norm. The annotation of the learner texts according to the correction
taxonomy of the SweLL project, made with the annotation tool Svala, is
hence an important step in making the texts in the corpus analyzable for
research and educational purposes.


## 1.2 The purposes of this document
-----------------------------

This document has three interconnected purposes:

-   It documents choices made by the SweLL project group regarding the
    principles of the correction annotation.

-   It provides guidance for annotators on how to apply the SweLL
    annotation taxonomy in order to ensure the greatest possible
    inter-annotator agreement.

-   It provides the essential material for a thorough description of the
    correction annotation for future users of the Swell corpus.

## 1.3 The organization of the document
--------------------------------

The rest of this document contains the following six main sections:

2.  *The most fundamental principles and terms*, explaining what a
    correction is, and the basic terms *correction*, *unit*, *link* and
    *tag*.

3.  *The general structure of the taxonomy*, providing a description of
    the general structure of the taxonomy, short descriptions of each
    tag, indications of tag relationships requiring special attention,
    and a sketched algorithm for the choice of tag.

4.  *General directions for the correction annotation*, explaining the
    basic practices for using the Svala annotation tool, and providing
    directions for the annotation which are more general than the usage
    of specific tags.

5.  *Descriptions of each tag*, given in the order they appear in the
    Svala annotation tool.

6.  *Discriminating between specific correction categorie*s, providing
    guidance for discriminating between specific pairs or groups of
    tags.

7.  *Other categorization issues*, including the following six
    subsections:

    1.  *Non-Swedish words and sequences*

    2.  *Verbal particles and reflexives*

    3.  *Clause corrected or created?*

    4.  *Spaces, hyphens and dashes*

    5.  *Singular indefinite article removed from plural indefinite NP*

    6.  *Exceptions to the default ranking of the word order tags*

# 2. The most fundamental principles and terms

## 2.1 What is a correction? What is annotated?
----------------------------------------

By *correction* we mean a difference between the original learner text
and the normalized version of the text. The correction annotation is
thus a categorization of such differences.

This means that the correction annotation only indirectly indicates
properties of the original learner text. What is directly indicated
is *the relationship between the original version and the normalized
version of the text*. The correction annotation is thus highly dependent
on the preceding normalization.

While the purpose of the correction annotation is to make the texts
searchable for deviations from a standard language norm, such deviations
are only possible to categorize on the basis of assumptions of the
learner's intended content, along with judgements of the suitability of
standard language expressions communicating that content. This means
that *any* annotation of "deviations", "errors" etc. in learner texts is
actually an annotation of a *relationship* between (a segment of) the
analyzed text and an assumed standard language version . By the choice
of the term *correction annotation* (rather than, for instance, *error
annotation*) the SweLL project emphasizes these conditions of learner
language analysis. The normalized text versions make explicit this
necessary assumption about the specific standard version of the text to
which the original text is related. (The principles underlying the
normalization are described in the normalization guidelines.)

## 2.2 Correction, unit, link and tag
------------------------------

A **correction** may consist of:

-   an *addition* of a unit; the unit is only present in the normalized
    text

-   a *deletion* of a unit; the unit is only present in the original
    text

-   a *movement* of a unit; the unit is present both in the original
    text and the normalized text, but it is placed differently relative
    to the surrounding text

-   a *change* of a unit; a unit in the normalized text is *a corrected
    version* of a corresponding unit in the original text

A **unit** normally consists of one token - *a token unit* - but it
may also consist of a group of tokens - a *group unit* (see section
[4.6](#46-grouping-of-tokens)).

The correction annotation is created by marking **links** between the
original text and the normalized text. **Tags** are placed on to the
links, representing the categories in the SweLL correction annotation
taxonomy, which is presented and described in major parts of this
document. A link may be tagged with one or several tags.

The links on which the tags are placed are visualized as lines in the
Svala annotation tool. In the case of a *movement* or *change*
correction, the link runs between a unit in the original text and the
corresponding unit in the normalized text. In the case of a *deletion*
correction, the link runs between the unit in the original text and
"nothing" - i.e. an empty space between the tokens in the normalized
text. In the case of an *addition* correction, the link runs between the
unit in the normalized text and "nothing", in a corresponding fashion. 


# 3. The general structure of the taxonomy

## 3.1 The main correction categories

The SweLL correction annotation taxonomy contains five main categories:

-   **Orthographic corrections (O)**, including "regular spelling
    corrections" (corrections of the string of letters), corrections
    between upper and lower case, and corrections of the use of spaces
    and hyphens between words.

-   **Lexical corrections (L)**, including 1) corrections of the choice
    of word and 2) corrections of the internal morphological structure
    of word stems - i.e. corrections regarding the formation of words
    through compounding and derivation.

-   **Morphological corrections (M)**, by which we specifically mean
    corrections concerning *inflectional morphology*. This category also
    covers some extra-morphological corrections which are closely
    related to inflectional forms and grammatical categories involving
    inflections.

-   **Punctuation corrections (P)**, including corrections of the choice
    of punctuation marks as well as the adding or removal of punctuation
    marks, and also instances of merging or splitting sentences.

-   **Syntactical corrections (S)**, i.e. corrections regarding the
    structure of multi-word phrases and clauses, including corrections
    of missing or redundant words, word order, the choice between a
    compound and a multi-word expression, and more complex syntactic
    corrections such as corrections between a finite clause structure
    and an infinitive phrase.

In addition to the correction tags included in these five main
correction categories, the Svala tool provides six other tags, including
tags for corrections made as a consequence of other corrections (**C**),
corrections not covered by any of the defined correction categories
(**Unid**), unintelligible strings (**X**), strings cited from a foreign
language (**Cit-FL**), and finally two tags for notes and comments --
**OBS!** for internal work notes, and **Com!** for comments intended for
the corpus users.


## 3.2 Overview of the taxonomy

The following table provides an overview of all tags.

The left-most column lists the tag names in the order in which they
appear in the Svala annotation tool, which is also the order in which
they are presented in the section *Descriptions of each tag*. This means
that the tags are primarily sorted according to the five major
categories: The tags in the group of orthographic corrections (O-tags)
come first, and the other four major categories in alphabetical order:
lexical corrections (L-tags), morphological corrections (M-tags),
punctuation corrections (P-tags), and syntactical corrections (S-tags).
After these five major categories follow the group of miscellaneous
other tags. Within each correction category, the tags are listed in
alphabetical order.

The second column in the table provides a short description of the
correction type.

In some cases, the tags are hierarchically ordered, so that a tag with
lower priority is only applied in those instances when the tag with
higher priority cannot be applied. This hierarchical ordering is
indicated in the two columns *Higher priority than* and *Lower priority
than*.

The discrimination between certain pairs or groups of tags requires
special attention. Such tag relationships are indicated in the
right-most column (*Discrimination issues*). Most of these
discrimination issues are handled in the section *Discriminating between
specific correction categories*, but some are also dealt with in the
section *Some more general categorization issues*. References to the
relevant sections are provided in the column *Discrimination issues*.


<style>
table th:first-of-type {
    width: 15%;
}
table th:nth-of-type(2) {
    width: 25%;
}
table th:nth-of-type(3) {
    width: 15%;
}
</style>

| **Tag name** | **Short description of the correction type** | **Higher priority than** | **Lower priority than** | **Sections dealing with relevant discrimination issues** |
|--------------|-------------|-------------|-------------|-------------|
| O | spelling | L-FL | L-Der | O vs punctuation tags [(6.1)](#6.1-o-vs-punctuation-tags) Spaces, hyphens and dashes [(7.4)](#74-spaces-hyphens-and-dashes) |
| O-Cap | upper/lower case |  |  |  |
| O-Comp | spaces and hyphens between words | P-M,P-R |  | O-Comp vs S-Comp [(6.2)](#62-o-comp-vs-s-comp) Verbal particles and reflexives [(7.2)](#72-verbal-particles-and-reflexives) Spaces, hyphens and dashes [(7.4)](#74-spaces-hyphens-and-dashes) |
| L-Der | word formation (derivation and compounding) | O | M-Adj/adv | L-Der vs  L-W [(6.3)](#63-l-der-vs-l-w) L-Der vs S-Comp [(6.4)](#64-l-der-vs-s-comp) Verbal particles and reflexives [(7.2)](#72-verbal-particles-and-reflexives) |
| L-FL        | non-Swedish word corrected to Swedish word | | O, L-Der | Non-Swedish words and sequences [(7.1)](#71-non-swedish-words-and-sequences) |
| L-Ref       | choice of anaphoric expression | M-Num, M-Gend, L-W | M-Def  |             |
| L-W         | wrong word or phrase | | L-Ref       | L-Der vs L-W [(6.3)](#63-l-der-vs-l-w) L-W vs M-Case [(6.5)](#65-l-w-vs-m-case) L-W vs M-Verb [(6.6)](#66-l-w-vs-m-verb) L-W vs S-Comp [(6.8)](#68-l-w-vs-s-comp) Non-Swedish words and sequences [(7.1)](#71-non-swedish-words-and-sequences) Verbal particles and reflexives [(7.2)](#72-verbal-particles-and-reflexives) |
| M-Adj/adv   | adjective form of word corrected to adverb form  | L-Der, M-Gend     |             |             |
| M-Case      | nominative vs genitive; nominative vs accusative  |             |             | L-W vs M-Case [(6.5)](#65-l-w-vs-m-case)   |
| M-Def       | definiteness: articles; forms of nouns and adjectives        | L-Ref. S-M, S-R       |             | Singular indefinite article removed from plural indefinite NP [(7.5)](#75-singular-indefinite-article-removed-from-plural-indefinite-np)   |
| M-F         | grammatical category kept, form changed gender |             | M-Num       |             |
| M-Gend      | gender      |             | L-Ref, M-Adj/adv   |             |
| M-Num       | number      | M-F         | L-Ref       |             |
| M-Other     | other morphological corrections, including change between different comparisons forms of adjectives     |             | All other M-categories  |             |
| M-Verb      | verb forms; use of *ha, komma* and *skola* auxiliaries | S-M, S-R         |             | L-W vs M-Verb [(6.6)](#66-l-w-vs-m-verb) Clause  corrected or created? [(7.3)](#73-clause-corrected-or-created) |
| P-M         | punctuation missing (added) |             | O-Comp (spaces and hyphens)     | O vs punctuation tags [(6.1)](#6.1-o-vs-punctuation-tags) Spaces, hyphens and dashes [(7.4)](#74-spaces-hyphens-and-dashes) |
| P-R         | punctuation redundant (removed) |             | O-Comp (spaces and hyphens)    | O vs punctuation tags [(6.1)](#6.1-o-vs-punctuation-tags) Spaces, hyphens and dashes [(7.4)](#74-spaces-hyphens-and-dashes)       |
| P-Sent      | sentence segmentation    |             |             |             |
| P-W         | wrong punctuation       |             | O-Comp (spaces and hyphens)    | O vs punctuation tags [(6.1)](#6.1-o-vs-punctuation-tags) Spaces, hyphens and dashes [(7.4)](#74-spaces-hyphens-and-dashes)       |
| S-Adv       | adverbial placement  | S-FinV, S-WO      |             | S-Clause vs word order tags [(6.9)](#69-s-clause-vs-word-order-tags) Exceptions to the default ranking of the word order tags [(7.6)](#76-exceptions-to-the-default-ranking-of-the-word-order-tags) S-Clause vs word order tags [(6.9)](#69-s-clause-vs-word-order-tags)  |
| S-Clause    | change of basic clause structure: syntactic function of components, hierarchical clause structure |             |             | S-Clause vs word order tags [(6.9)](#69-s-clause-vs-word-order-tags) S-Clause vs S-Comp [(6.10)](#610-s-clause-vs-s-comp) S-Clause vs S-Ext [(6.11)](#611-s-clause-vs-s-ext) S-Clause vs S-M [(6.12)](#612-s-clause-vs-s-m) S-Clause vs S-Msubj [(6.13)](#613-s-clause-vs-s-msubj) S-Clause vs S-R [(6.14)](#614-s-clause-vs-s-r) Clause corrected or created? [(7.3)](#73-clause-corrected-or-created) |
| S-Comp      | compound vs multi-word expression, and other restructuring of the same lexical morphemes within a phrase |             |             | O-Comp vs  S-Comp [(6.2)](#62-o-comp-vs-s-comp) L-Der vs S-Comp  [(6.4)](#64-l-der-vs-s-comp) L-W vs S-Comp [(6.8)](#68-l-w-vs-s-comp) S-Clause vs S-Comp [(6.10)](#610-s-clause-vs-s-comp) Verbal particles and reflexives [(7.2)](#72-verbal-particles-and-reflexives)       |
| S-Ext       | extensive and complex correction   |             |             | S-Clause vs S-Ext [(6.11)](#611-s-clause-vs-s-ext) S-Ext vs S-M [(6.12)](#612-s-clause-vs-s-m) S-Ext vs X  [(6.16)](#616-s-ext-vs-x)      |
| S-FinV      | finite verb placement | S-WO        | S-Adv       | S-Clause vs word order tags [(6.9)](#69-s-clause-vs-word-order-tags) Exceptions to the default ranking of  the word order tags [(7.6)](#76-exceptions-to-the-default-ranking-of-the-word-order-tags)       |
| S-M         | word  missing (added)      |             | M-Def, M-Verb, S-Msubj      | S-Clause vs S-M [(6.12)](#612-s-clause-vs-s-m) S-Ext vs S-M [(6.15)](#615-s-ext-vs-s-m) Clause corrected or created? [(7.3)](#73-clause-corrected-or-created) Verbal particles and reflexives [(7.2)](#72-verbal-particles-and-reflexives)       |
| S-Msubj     | subject missing (added)    | S-M         |             | S-Clause vs S-Msubj [(6.13)](#613-s-clause-vs-s-msubj) Clause corrected or created? [(7.3)](#73-clause-corrected-or-created)       |
| S-Other     | other syntactical correction      |             | All other S-categories   |             |
| S-R         | word redundant (removed)       |             | M-Def, M-Verb      | S-Clause vs S-R [(6.14)](#614-s-clause-vs-s-r) S-Type vs S-M and S-R [(6.17)](#617-s-type-vs-s-m-and-s-r)  Verbal particles and reflexives  |
| S-Type      | change of phrase type/part of speech   |             |             | S-Type vs S-M and S-R [(6.17)](#617-s-type-vs-s-m-and-s-r) |
| S-WO        | word order, other |             | S-Adv, S-FinV      | S-Clause vs word order tags [(6.9)](#69-s-clause-vs-word-order-tags) Exceptions to the default ranking of  the word order tags [(7.6)](#76-exceptions-to-the-default-ranking-of-the-word-order-tags)       |
| C           | consistency correction, necessitated by other correction |             |             |             |
| Cit-FL      | non-Swedish word **kept**, i.e. **not corrected** |             |             | Non-Swedish words and sequences [(7.1)](#71-non-swedish-words-and-sequences)|
| Com!        | comments for the corps user   |             |             |             |
| OBS!        | internal and temporary comments for the annotators   |             |             |             |
| Unid        | unidentified correction           |             | All other categories  |             |
| X           | unintelligible string         |             |             | S-Ext vs X [(6.16)](#616-s-ext-vs-x) |


## 3.3 Tag choice algorithm

While the correction types are primarily presented as belonging to the
five major linguistically defined categories (orthographic, lexical,
morphological, punctuation-related, and syntactical corrections), they
may also be categorized based on the more straight-forward relationship
between the original text and the normalized text: as *additions*,
*deletions*, *movements* or *changes* of units (see section [2.2](#22-correction-unit-link-and-tag)).

To some extent, the corrections within these categories may be
hierarchically ordered, on different levels of priority, so that certain
tags should only be considered in those cases when a tag with a higher
priority is not applicable. In this section, such an algorithm for the
choice of tag is sketched.

It must however be stressed that the algorithm presented below is a
simplification of the actual decision flow, since in reality tags of
different kinds also "compete" with each other to a certain extent; the
same correction may for instance be considered both for an addition
category and for a change category. Moreover, the limits between the
categories are not as clear cut as a straight-forward application of the
decision flow algorithm requires. A somewhat more complex picture of the
relationships between the correction categories is presented in sections
[3.2](#32-overview-of-the-taxonomy) (*Overview of the taxonomy*) and 5 (*Descriptions of each tag*), and
more nuanced descriptions of how to discriminate between the categories
are given in sections 6 (*Discriminating between specific correction
categories*) and 7 (*Other categorization issues*).

With that said, here is the algorithm sketch:

**When choosing a tag, the following four alternatives should first be
considered (in the order listed):**

1.  Is the correction a follow-up correction of another correction? → C

2.  Is the original unit unintelligible? → X

3.  Is the original unit a non-Swedish word or phrase (which is not
    interpretable as a misspelled Swedish word or phrase or as a
    non-standard composition of Swedish morphemes)? → L-FL

4.  Is the correction extensive, involving a greater than usual element
    of subjectivity or randomness, so that the syntactic structure of
    the normalized unit may rather be described as *created* than as
    *corrected*? → S-Ext

**If none of the four cases above holds, proceed as follows:**

5.  Is the correction an *addition*? → See *Additions* [(3.3.1)](#additions)

6.  Is the correction a *deletion*? → See *Deletions* [(3.3.2)](#deletions)

7.  Is the correction a *movement* (word order change)? → See *Movements
    (word order changes)* [(3.3.3)](#movement-word-order-changes)

8.  Is the correction a *change*?

    a.  Is at least one of the units involved (the original or the
        normalized one) a multi-word unit? → See *Changes involving a
        multi-word unit in either the original version, the normalized
        version or both* [(3.3.4)](#334-changes-involving-a-multi-word-unit-in-either-the-original-version-the-normalized-version-or-both)

    b.  Is the correction a change between two *one-word units* (the
        original unit is not necessarily a *one-token* unit since it may
        also be a word which is incorrectly written as two tokens)?

    -  Does the change involve *inflectional morphology* or a stem           changed which is due to a change of a grammatical quality which       is usually expressed with inflectional morphology (such as *går →     gick* or *mus → möss*)? → See *Changes: one-word unit changed to      one-word unit, change of inflectional morphology or functionally      parallel stem change* [(3.3.5)](#335-changes-one-word-unit-changed-to-one-word-unit-change-of-inflectional-morphology-or-functionally-parallel-stem-change)

    -  Is the *word stem* exchanged (except according to i) or morphologically restructured? → See *Changes: one-word unit changed to one-word unit, word stem exchanged or morphologically restructured* [(3.3.6)](#336-changes-one-word-unit-changed-to-one-word-unit-word-stem-exchanged-or-morphologically-restructured)

    - Is the *spelling*, including *the use of spaces and hyphens* and *the use of upper/lower case letters*, changed? → See *Changes: one-word unit changed to a one word unit, spelling (including uses of spaces and hyphens and token-internal punctuation)* [(3.3.7)](#337-changes-one-word-unit-changed-to-a-one-word-unit-spelling-including-uses-of-spaces-and-hyphens-and-token-internal-punctuation)

    c.  Is at least one of the units a punctuation mark? → See *Changes:
        at least one of the units is a punctuation mark* [(3.3.8)](#338-changes-at-least-one-of-the-units-is-a-punctuation-mark)


### 3.3.1 Additions

1.  **Priority one**

    -   The addition increases the number of clauses → **S-Clause**

2.  **Priority two**; alternatives with equal priority

    -   Definite or indefinite article added → **M-Def**

    -   *Ha, skola* or *komma* auxiliary added → **M-Verb**

    -   The infinitive marker *att*, used in a construction with a
        *komma* auxiliary, added → **M-Verb**

    -   Punctuation mark added → **P-M**

    -   *Subjunktion* 'subordinating conjunction' or other
        *bisatsinledare* 'subordinating connector' added → **S-Clause**

    -   Subject added (into a clause which exists in the original
        version) → **S-Msubj**

3.  **Otherwise** → **S-M**

### 3.3.2 Deletions

1.  **Priority one**

    -   The deletion involves a reduction of the number of clauses → **S-Clause**

2.  **Priority two**; alternatives with equal priority:

    -   Definite or indefinite article deleted → **M-Def**

    -   *ha, skola* or *komma* auxiliary deleted → **M-Verb**

    -   the infinitive marker *att* used in a construction involving a
        *ha, skola* or *komma* auxiliary deleted → **M-Verb**

    -   Punctuation mark deleted → **P-R**

    -   *Subjunktion* 'subordinating conjunction' or other
        *bisatsinledare* 'subordinating connector' deleted → **S-Clause**

3.  **Otherwise** → **S-R**



### 3.3.3 Movements (word order changes)

1.  **Priority one**

    -   The unit has been moved as part of a change between a main
        clause structure and a subordinate clause structure *which is
        also indicated by other means* (as the removal or the addition
        of a *subjunktion* 'subordinating conjunction') *or* the unit
        has been moved because its syntactic function has changed
        → **S-Clause**

2.  **Priority two**

    -   Choose the tag which gives one rather than two word order
        changes.

3.  **Priority three**

    -   The *fundament* 'pre-finite element' is exchanged for textual
        rather than clause-internal reasons → **S-WO**

4.  **Priority four**

    -   Adverbial moved → **S-Adv**

5.  **Priority five**

    -   Finite verb moved → **S-FinV**

6.  **Otherwise** → **S-WO**

### 3.3.4 Changes involving a multi-word unit in either the original version, the normalized version or both

1.  **Priority one**

    -   The change is limited to the mere addition of a space (or
        several spaces) *between the words in a multi-word-phrase* → **O-Comp**

2.  **Priority two**

    -   The change involves a change of the primary syntactic function
        of a word/phrase *or* the number of clauses is changed
        → **S-Clause**

3.  **Priority three**; alternatives with equal priority:

    -   At least one of the units (the original one or the normalized
        one) is (an attempt at) a word or a fixed phrase, and at least
        one lexical morpheme is changed → **L-W**

        -   The syntactic category/part of speech is changed The
            *additional* tag → **S-Type** is applied

    -   The normalized unit is a morphosyntactic restructuring of the
        lexical morphemes which are present in the original unit
        → **S-Comp**

4.  **Otherwise → S-Other**


### 3.3.5 Changes: one-word unit changed to one-word unit, change of inflectional morphology or functionally parallel stem change

1.  **Priority one**; alternatives with equal priority:

    -   Change of an adjective, noun, article or pronoun

        -   **Priority one**: Definiteness change → **M-Def**

        -   **Priority two**: An anaphoric expression has been changed
            to suit its correlate and textual position → **L-Ref**

        -   **Priority three**: An adjective is changed from a form
            which is not used as an adverb to a form which is used as an
            adverb → **M-Adj/adv**

        -   **Priority four**; alternatives with equal priority:

            -   Case change → **M-Case**

            -   Gender change → **M-Gend**

            -   Number change → **M-Num**

    -   Change of a verb form (which involves a change of function)
        → **M-Verb**

2.  **Priority two**: A declension/conjugation form (typically a suffix)
    which is used to express a specific grammatical category (e.g.
    plural or present tense) has been corrected to a form belonging to
    another declension/conjugation expressing the same grammatical
    category → **M-F**

3.  **Otherwise → M-Other**


### 3.3.6 Changes: one-word unit changed to one-word unit, word stem exchanged or morphologically restructured

1.  **Priority one**; alternatives with equal priority:

    -   One *ha, skola* or *komma* auxiliary has been exchanged for
        another *ha, skola* or *komma* auxiliary → **M-Verb**

    -   An anaphoric expression has been changed to suit its correlate
        and textual position → **L-Ref**

    -   Change between an indefinite and a definite article → **M-Def**

2.  **Priority two**; alternatives with equal priority:

    -   The root morpheme(s) of the category-defining part of the stem
        is kept → **L-Der**

        -   The syntactic category/part of speech is changed The
            *additional* tag → **S-Type** is applied (*in addition to
            L-Der*)

    -   The root morpheme(s) of the category-defining part of the stem
        is changed → **L-W**

        -   The syntactic category/part of speech is changed The
            *additional* tag → **S-Type** is applied (*in addition to
            L-W*)


### 3.3.7 Changes: one-word unit changed to a one word unit, spelling (including uses of spaces and hyphens and token-internal punctuation)

1.  **Priority one**; alternatives with equal priority:

    -   The change is limited to the mere usage of spaces and hyphens
        *between the words in a compound* → **O-Comp**

    -   Regular spelling correction (letters changed) → **O**

    -   Addition or removal of token-internal punctuation → **O**

    -   Change between upper and lower case letters → **O-Cap**

### 3.3.8 Changes: at least one of the units is a punctuation mark

1.  Alternatives with equal priority:

    -   Punctuation mark changed to another punctuation mark → **P-W**

    -   Change between a conjunction and a sentence-separating
        punctuation mark → **P-Sent**


# 4. General directions for the correction annotation

This section explains the basic practices for using the Svala annotation
tool, and provides directions for the annotation which are more general
than the usage of specific tags.

## 4.1 Adjustment of links and attachment of tags

During the normalization process, links between the original text and
the normalized texts are created automatically. These links may be
adjusted both already during the normalization and during the correction
annotation process. The correct link must be in place before a tag is
inserted. Links may be adjusted in the following way:

In order to break a link, place the marker on one of the linked text
elements or on the link itself, and press the *orphan* button on the
menu to the left.

In order to create a new link, mark all of the tokens which you wish to
link by clicking the tokens while holding ctrl (PC) or shift (Mac). Then
press the *group* button on the menu to the left.

The tags are available in the Svala annotation tool in a list to the
left on the screen. In order to place a tag on a link, mark the link and
click on the tag in the tag list. Tags are removed from links in the
very same fashion: Mark the link with the tag, and the click on the
corresponding tag in tag list.

BILD

## 4.2 Some errors are not tagged

A consequence of the fundamental principle of annotating *corrections*,
understood as differences between the original text and *one
specific* interpretation of this text, rather than "errors in general",
is that certain clear deviations from the norms of written standard
Swedish in the original texts are left without annotations - because
they are not deviations *in relation to the normalized text*. This
occurs for instance when a misspelled word in the original text has been
corrected to another word altogether. Such a correction will be
annotated as an instance of a faulty choice of word (L-W), and since the
word in the original text cannot be analyzed as a misspelling of the
word in the normalized text, the spelling error will be left without
annotation.

-   Du kan göra manga **nognting** → Du kan göra många **saker**

    The misspelling of *någonting* is not tagged, since *nognting* is related to *saker* and not to *någonting*.


## 4.3 Only visible corrections are tagged

Another fundamental principle of the correction annotation is that only
"superficially visible" corrections are tagged - i.e. corrections which
are reflected by differences between the original string and the
normalized string. Here are some examples of the consequences of this
principle:

In the following example, *det* is inserted as an expletive subject into
a clause (and tagged S-Msubj). This correction also means that the
subject of the original clause (marked with italics) is changed to an
*egentligt subjekt ('object-positioned subject'). The latter change is
however not reflected in any additional difference (i.e. on top of the
addition of det) between the original string and the normalized string.
The change of the subject of the original string to an egentligt subjekt
in the normalized string is thus left without any tag.*

-   på andra sidan finns ***människor som har så mycket pengar att de
    kan köpa halva världen*** → Å andra sidan finns **det *människor som
    har så mycket pengar att de kan köpa halva världen*** 

In the following example a passive construction is changed to an active
construction (and tagged as S-Clause). Consequently, the subordinate
clause (marked with italics) is changed from an *egentligt subjekt* to
an object. This changed is left untagged.

-   I texten **sägs det av henne** *att hon efterlyser de som enbart
    talar finska och är positiva till svenskan och tvåspråkigheten* . → I
    texten **säger hon** *att hon efterlyser de som enbart talar finska
    och är positiva till svenskan och tvåspråkigheten* .

## 4.4 Positive assumption principle

The *positive assumption principle* remains to be a working principle
also for the correction annotation, just as for the transcription and
the normalization. This means that, when in doubt about which of two
tagging alternatives to choose, the alternative implying the "smallest
correction" should be chosen. For instance, when it seems equally likely
that a correction is due to a spelling mistake as to a word choice
mistake, the O tag should be chosen rather than the L-W tag, since
correcting the spelling of a word may be considered less invasive than
exchanging the word altogether.

The positive assumption principle is particularly important when tagging
strings including signs which have been marked as unreadable in the
transcription process. See *Annotation of strings including unreadable
signs in transcribed texts* [(4.8)](#48-annotation-of-strings-including-unreadable-signs-in-transcribed-texts).


## 4.5 Several tags on the same link

In many instances, the same unit is corrected in multiple ways
reflecting separate correction categories, without one correction being
included in or implied by another (cf. 4.7 *Corrections of tokens
included in group units*). In these cases, the link should be marked
with one tag for each correction type.

-   Both spelling and the use of a hyphen between two words in a
    compound is changed, the link is tagged with both O and O-Comp:

    -   **energi-niveå** → **energinivå**

-   Both spelling and definiteness of a noun is changed, the link is
    tagged with both O and M-Def:

    -   Finns många nya **lagenheterna** i dyrare delar i huvudstaden →
        Det finns många nya **lägenheter** i dyrare delar i huvudstaden

-   Both definiteness and number of a noun is changed, the link is
    tagged with M-Def and M-Num:

    -   Alla sitter bakom sina **skärmens** sken → Alla sitter bakom
        sina **skärmars** sken

-   Both case and placement of a pronoun is changed, the link is tagged
    with M-Case and M-WO:

    -   Man kan inte vänta att lägga **de** upp på social medier → Man kan
        inte vänta med att lägga upp **dem** på sociala medier

In the examples above, each correction category is reflected by its own
separate difference between the original text and the normalized text.
For instance, the changed spelling concerns another fragment of the
string than the changed definiteness. There are however also some
instances when one single corrected element reflects two correction
categories simultaneously. Also in such cases the link should be tagged
with tags for the both correction types.

In the following example, the correction from the infinitive phrase
*köpa mat* to the compound noun *mataffär* is simultaneously a
correction of the choice of word (L-W) and a correction of the phrase
type (S-Type), and the link is tagged with both of these tags:

-   Tycker om min plats har en **köpa mat** ett , litet centrum en
    förskolan en vårdcentralen Jag tycker om platsen där jag bor , den
    har en **mataffär** , ett litet centrum , en förskola , en
    vårdcentral

Similarly, the following example is tagged with both L-Der (word
formation correction) and S-Type (phrase type correction):

-   Jag ska **solen** och bada Jag ska **sola** och bada

In the following example the adjective *nationell* in the original text
has a gender form (non-neuter) which is incongruent with the noun it
modifies (*språk*, neuter), and its singular form does not match the
co-ordinated subject (*svenska och finska*) with which the whole
predicative NP (*nationell språk*) is associated.

-   Sedan 1919 bliv både svenska och finska **nationell** språk i
    Finland → Sedan 1919 är både svenska och finska **nationella** språk i
    Finland

In cases like this, arguments could be made both for the solution to tag
this correction both as M-Num and M-Gend (since the correction
eliminates both the gender error and the number error) and for the
solution to mark such changes only with the M-Num tag (since the plural
adjective is undifferentiated for gender). We have however decided for
the former solution: Corrections of this kind are tagged both with M-Num
and M-Gend.


## 4.6 Grouping of tokens

Corrections are by default tagged token by token. Group units are only
created in the following cases:

1.  A *movement* correction concerns a phrase made up of several tokens.

2.  A *change* correction concerns strings without a token-to-token
    correspondence between the original and the normalized version, i.e.
    at least one of the corresponding units (the original unit or the
    normalized unit) is made up by more than one token.

Grouping of moved units may be made for all the word order correction
categories, i.e. S-Adv, S-FinV and S-WO. Whenever a moved token is part
of a multi-token phrase which is moved altogether, the whole phrase
should be grouped. The only exception is when a single token included in
such a moved phrase is also corrected, see *Corrections of tokens
included in group units* [(4.7)](#47-corrections-of-tokens-included-in-group-units) below.

Grouping of moved units is made also in the case of coordinated phrases
being moved altogether:

-   Jag kunde inte att komma för **jobbar och pluggar** jag tillsamman →
    Jag kunde inte komma för att jag både **jobbar och pluggar**

Grouping of changed units is primarily made for the following correction
types:

-   O-Comp:

    -   Jag kände mig **jätte konstig** → **jättekonstig**

-   L-FL:

    -   **gas "bojler"** → **gaskokare**

-   L-W:

    -   Jag maner att om vi **har önskemål** kan vi göra nånting utan
        pengar → Jag menar att om vi **vill** kan vi göra nånting utan
        pengar

    -   Traditioner ger människorna tid att **stå still** och fundera
        över livet → ... att **stanna upp** och fundera över livet

    -   Konsekvenserna man skulle få ifall undervisning i svenska blev
        frivillig så skulle mer än hälften av finska
        befolkningen **avskaffa** svenskan som modersmålsundervisning
        och istället fokusera på finska då dem sällan använder svenskan
        . → Konsekvenserna man skulle få ifall undervisning i svenska blev
        frivilligt är att då skulle mer än hälften av den finska
        befolkningen **välja bort** svenskan som modersmålsundervisning
        och istället fokusera på finska då de sällan använder svenskan .

-   S-Clause

    -   I texten **sägs det av henne** att hon efterlyser de som enbart
        talar finska → I texten **säger hon** att hon efterlyser de som
        enbart talar finska

    -   I artikeln \" Tre röster om svenskan ställning i Finland \" (
        Parnass , 2013:3 ) skriver Catharina Söderbergh om tre personer
        som har sagt sin åsikt om tvångssvenskan och **hur svenskan
        befinner sig**. → I artikeln \" Tre röster om svenskans ställning
        i Finland \" ( Parnass 2013:3 ) skriver Catharina Söderbergh om
        tre personer som har sagt sin åsikt om tvångssvenskan
        och **läget för svenskan** .

    -   **Att växa** upp som en flicka så var det väldigt många
        orättvisor man fick vänja sig vid. → **När man växte** upp som
        en flicka så var det väldigt många orättvisor man fick vänja sig
        vid.

-   S-Comp

    -   **det vardagliga livet** → **vardagslivet**

    -   Enligt Hyltenstam så kan minoritetsspråk räddas om
        man **inblandar** dem äldre som kan språket → Enligt Hyltenstam så
        kan minoritetsspråk räddas om man **blandar in** de äldre som
        kan språket

    -   Skillnader är stor av **Sveriges bostad** → Skillnaderna är stora
        mot **bostäder i Sverige**

-   S-Ext

    -   **Det därför tycker jag om det är** simma lungt och blåser
         → **Jag tycker om det för att jag tycker om** att simma lugnt och
        när det blåser

    -   Så hur mycket pojkarna bettalad **värt inte deras
        äppelträd** eftersom trädet var viktig för dem → Så hur mycket
        pojkarna betalade **var mindre än vad deras äppelträd var
        värt** eftersom trädet var viktigt för dem .

-   S-Type (and L-W)

    -   jag behover pengar f\$r **liv** och **betalning av** min hus → jag
        behöver pengar för **att leva** och **betala** för mitt hus

**Note**: M-Def corrections and M-Verb corrections involving more than
one token in one or both text versions are **not grouped**, but tagged
token by token.

-   Slutligen tror jag att sociala medier **blev** en essentiell del → 
    Slutligen tror jag att sociala medier **har blivit** en essentiell
    del

    A link between *blev* and *blivit* is tagged with M-Verb, as well as a separate link between *har* and "nothing".

-   Tyvärr **ska** jag inte komma på kursen → Tyvärr **kommer** jag inte
    **att** komma på kursen

    A link between *ska* and *kommer* is tagged with M-Verb, as well as a separate link between *att* and "nothing".

-   När kommer **den buss** → När kommer **bussen**

    **A link between *buss* and *bussen* is tagged M-Def, as well as a separate link between *den* and "nothing".**

-   Han har egen **rummet** och jag egen → Han har **ett** eget **rum**
    och jag **ett** eget

    A link between *rummet* and *rum* is tagged M-Def, as well as separate links between each instance of the added indefinite article *ett* and "nothing".


## 4.7 Corrections of tokens included in group units

Corrections of tokens which are included in a corrected group unit may
be of three kinds, which are handled in different ways:

1.  The correction of the included token is part of the correction which
    motivated the forming of the group unit.

      - The token correction is not tagged separately, but is considered
        included in the tag placed on the link from the group unit.

          - **min plats** → **platsen där** **jag bor**

        All words involved in this correction (*min plats* and *platsen där jag bor*) are grouped together, and the correction as a whole is tagged S-Clause. Accordingly, *min* is not tagged as S-R, *jag* is not tagged as S-Msubj, *där* and *bor* are not tagged as S-M, and the change from *plats* to *platsen* is not tagged as M-Def.

          - **Att växa** upp som en flicka så var det väldigt många orättvisor
           man fick vänja sig vid  → **När man växte** upp som en flicka så 
           var det väldigt många orättvisor man fick vänja sig vid**

        Here, the change of structure from an infinitive phrase to a finite clause is analysed as an instance of S-Clause, and this tag is placed on the link between the group unit *Att växa* in the original text and the group unit *När man växte* in the normalized text. *Man* is thus not tagged as S-Msubj, the change from *växa* to *växte* is not tagged as M-Verb, etc.

          - Finns många nya lagenheterna i dyrare delar i huvudstaden , men
            detta är **lång distans från räker nummer**. → Det finns många nya
            lägenheter i dyrare delar i huvudstaden , men detta är **långt ifrån
            tillräckligt**

        This correction is analysed as an instance of L-W (wrong word or phrase). While the adverb *långt* in the normalized text could be seen as corresponding to the adjective *lång* in the original text, this correction is included in the exchange of the whole phrase. These two tokens (*lång* and *långt*) are thus not aligned separately, and the correction is not tagged as a separate correction.

2.  The correction of the included token is not part of the correction
    which motivated the forming of the group unit.

      1. The correction of the token may still be considered a correction of the whole group unit, since the token is the head of the grouped phrase.

           - The additional correction is marked by placing an additional tag on the group unit, which is not broken up.

               - Skillnader är stor av **Sveriges bostad**  Skillnaderna
                är stora mot **bostäder i Sverige**

             The forming of the group unit is motivated by the analysis of the change from *Sveriges bostad* to *bostäder i Sverige* as an instance of S-Comp, and that tag is placed on the link connecting the group in the original text with the group in the normalized text. The change from singular to plural of *bostad* affects the number of the whole phrase, and although this correction would not in itself motivate the forming of a group unit, the M-Num tag is also placed on the group link.

      2. The correction of the token specifically concerns the individual token - not the whole group unit

           - The group unit cannot be visualized as a group, but needs to be broken up.

           - The individually corrected token is tagged with the tag which concerns that token specifically.

           - The part of the broken group unit which contains the longest string or the phrase head is tagged with the tag which concerns the correction of the whole group unit.

           - The other part(s) of the broken group unit (including the individually corrected token) are marked with C.

               - Hon försätter skriva om **att inte avskaffa den obligatoriska svenskan på skolan** är fördel för ungdomar Hon fortsätter skriva om att **det** är en fördel för ungdomar **att inte avskaffa den obligatoriska svenskan i skolan**

             The infinitive phrase att inte avskaffa den obligatoriska svenskan på ( i) skolan is moved as a group unit. However, the change from på to I calls for breaking up the group in the Svala visualization. Thus, att inte avskaffa den obligatoriska svenskan is visually grouped together and the link is tagged with S-WO. The link between på and i is marked with L-W, but also with C, to indicate that the movement of this word is part of the movement of the already tagged part of the phrase. The link from skolan to skolan is exclusively tagged with C.

               - Jag hoppas att du **intressant för din ny livs**  Jag hoppas att du **tycker att ditt nya liv är intressant**

             tycker att in the normalization forms a unit which is tagged with S-Ext (the link runs between this normalized unit and "nothing"); din is linked with ditt and tagged M-Gend and C; ny is linked with nya and tagged M-Def and C; livs is linked with liv and tagged M-Case and C; intressant för is linked with är intressant and tagged C.*

## 4.8 Annotation of strings including unreadable signs in transcribed texts

Signs which are judged unreadable in handwritten originals are
transcribed as "\$". When possible (i.e. when the string as a whole is
nevertheless interpretable) such signs are eliminated in the normalized
version of the text. When annotating such corrections, the *positive
assumption* principle should be applied. In other words:

If it is possible that the original string was correct, assume that it
was correct and leave the correction (i.e. the difference between the
original string including the "\$" and the normalized string without the
"\$") without *any* tag representing a correction category. A *Com!* tag
is however applied, with the edge comment "Original assumed to be
correct." Cf. *Com! (comments for the corpus users)*.

This holds in the following cases:

-   The \$ has simply been removed in the normalized version; it is
    possible that \$ marks a character which was intended to be marked
    as removed in the original.

    -   *ja\$g* → *jag*

-   The \$ corresponds to exactly one letter in the normalized version;
    it is possible that \$ marks the letter to which it has been changed
    in the normalized version.

    -   *hi\$\$a* → *hitta*

Only if it is not possible that the original string was correct should
the correction be annotated with a suitable tag.


## 4.9 Document comments

The *Document comment* field provides an opportunity to comment on
deviations from the standard norm regarding text properties which cannot
be adequately reflected by tags on individual links. The field may also
be used for any kind of general comment on the text which the annotator
regards as essential for the future corpus user.

This field may for instance be used when the verb tense choices in the
text are inconsistent at a global text level, but when corrections of
individual verb forms have generally not been made, since there is
consistency more locally in the text.

# 5. Descriptions of each tag

In the following the annotation categories and their tags will be
presented in the order in which they appear in the Svala annotation tool
- i.e. the O tags first, followed by the four other main correction
categories in alphabetic order (L, M, P, S), and, finally, the remaining
six tags under the heading *Other tags*.


## 5.1 O-Orthographic corrections

The O tags represent the orthographic correction category. It includes
three sub-categories.

### 5.1.1 O (regular spelling correction)

The plain O tag is used for regular spelling corrections, i.e. when the
string of letters is different in the original text and the normalized
text, due to a spelling mistake.

-   Det **tåg** 6 timmar från Teheran till Göteborg  → **tog**

-   Det finns **monga** affärer  → **många**

The O tag is also used for instances when token-internal punctuation
marks have been removed or added. (See *[6.1](#61-o-vs-punctuation-tags)* *O vs punctuation
tags*.)

-   **t.v.** → **tv**

    (The intended use of *t.v.* here is the noun *teve*, not the phrase *tills vidare*.)

-   **vdar → vd:ar**

**Higher priority than**:

-   **L-FL**; see *Non-Swedish words and sequences*.

**Lower priority than**:

-   **L-Der**; when a correction may be interpreted both as derivational
    correction and an orthographic correction, the L-Der tag should be
    applied rather than the O tag.

**Discrimination issues**

-   Concerning corrections of the use of spaces and hyphens between
    words, see *[7.4](#74-spaces-hyphens-and-dashes)* (*Spaces, hyphens and dashes*).

-   Concerning the use of other token-internal punctuation marks, see
    *[6.1](#61-o-vs-punctuation-tags)* (*O vs punctuation tags*).

### 5.1.2 O-Cap (upper/lower case)

The O-Cap tag is used for corrections regarding the choice between upper
and lower case letters.

-   Det fanns en affär och vi gick dit. **vi** köpte flera saker → Det
    fanns en affär och vi gick dit. **Vi** köpte flera saker.

-   På **Måndag** är det den 3 **Mars**. → På **måndag** är det den
    3 **mars**.

### 5.1.3 O-Comp (spaces and hyphens between words)

The O-Comp tag is used for corrections which involve the removal of a
space between two words which have been interpreted as making up a
compound in the normalized text version, or, more rarely, the adding of
a space between two words. It may also be used for corrections regarding
the use of hyphens in compounds.

-   Jag kände mig **jätte konstig**  → **jättekonstig**

-   Det ligger ett **kultur hus** nära min bostad  → **kulturhus**

-   **kultur-hus** → **kulturhus**

-   han har jämförts **\" tvångsvenska \" debatten** i Finland
    med **nynorska debatten** i Norge han har
    jämfört **\"tvångssvenska\"-debatten** i Finland
    med **nynorska-debatten** i Norge

-   **tv program**  → **tv-program**

-   **New York bor**  → **New York-bor**

-   **New Yorkbor**  → **New York-bor**

-   **buss-stationer → busstationer**

-   för två **årsen**  → för två **år sen**

In the following example, the change from a comma to a long dash
between *Finland* and *Sverige* is tagged with P-W, and the change from
a space to a hyphen between *Sverige* and *historien* is tagged with
O-Comp:

-   Författaren börjar med att beskriva det långa **Finland , Sverige
    historien** → Författaren börjar med att beskriva den
    långa **Finland--Sverige-historien** 

Corrections which involve both a removal of a space and a change of the
form of the first part of the compound are tagged both with O-Comp and
L-Der:

-   **Kommunikation förändring** → **Kommunikationsförändring**

**Higher priority than**

-   **P-M**; additions of hyphens and spaces are tagged O-Comp rather
    than P-M.

-   **P-R**; deletions of hyphens and spaces are tagged O-Comp rather
    than P-R.

-   **P-W**; changes between spaces and hyphens between words are tagged
    O-Comp rather than P-W.

**Discrimination issues**

-   The O-Comp tag should only be used for corrections concerning the
    mere orthographic rendering, with or without a space or a hyphen, of
    a compound or a multi-word expression, and not for corrections which
    are rather to be interpreted as involving an actual alternation
    between a compound and a multi-word expression. The latter case is
    covered by the S-Comp tag. See *[6.2](#62-o-comp-vs-s-comp)* *O-Comp vs S-Comp*.

-   Concerning other corrections involving spaces and hyphens, see *[7.4](#74-spaces-hyphens-and-dashes)*
    *Spaces, hyphens and dashes*.


## 5.2 L-Lexical corrections
------------------------

The L tags represent the lexical correction category. It includes four
sub-categories.

### 5.2.1 L-Der (word formation)

The L-Der tag represents the correction category *deviant word
formation*. It is used for corrections of the internal morphological
structure of word stems, both with regard to compounding and to
derivation.

The L-Der tag is exclusively used for links between one-word units (not
necessarily one-token units, since a word may mistakenly be written as
two tokens), where the normalized word has kept at least one root
morpheme from the original word, but where another morpheme has been
removed, added, exchanged or had its form altered.

-   A derivational affix has been corrected:

    -   De är **stressiga** på grund av studier → De är **stressade** på
        grund av studier

-   A derivational affix has been added:

    -   **ändring** → **förändring**

-   A derivational affix has been removed:

    -   **förstöra** → **störa**

-   The form of the first part of a compound has been corrected (for
    instance by adding or removing a "foge-s"):

    -   **tvångsvenska** → **tvångssvenska**

    -   **sagabok** → **sagobok**

    -   **solenkräm → solkräm**

-   The first word of the compound has been exchanged, while the second,
    category-defining word, has been kept (cf. *[6.3](#63-l-der-vs-l-w)* *L-Der vs L-W*):

    -   **dagsskolan** → **förskolan**

-   A verbal particle of a compound form of a particle verb has been
    added, removed or corrected:

    -   Internet **uppmanar** vår förståelse → Internet **utmanar** vår
        förståelse

    -   att debatten i båda länder är jätte lik varandra , bara
        hantering **avskiljer**  → att debatterna i de båda länderna är
        jättelika varandra , bara hanteringen **skiljer**

    -   tre olika **ställningar** som finns om svenska inom Finland → tre
        olika **inställningar** som finns till svenska i Finland

        Cf. *[7.2](#72-verbal-particles-and-reflexives)* *Verbal particles and reflexives*.

-   A verbal particle has been exchanged for a derivational affix: 

    -   **efterlyser** → **belyser**

**Note**: When the correction of a word tagged with L-Der involves a
change of phrase type or part of speech, the correction is tagged with
S-Type, in addition to L-Der.

-   **norska** bokmål → **norskt** bokmål

-   jag talar **kurdisk** → jag talar **kurdiska**

-   en **nybyggnad** lägenhet → en **nybyggd** lägenhet

-   Jag ska **solen** och bada → Jag ska **sola** och bada

-   Jag behöver pengar för liv och **betalning** av min hus → Jag behöver
    pengar för att leva och **betala** mitt hus

-   Eller det **skapar** kontakter och **trivs**? → Eller **skapar** de
    kontakter och **trivsel**?

-   något ha en \" svart \" avställning **båda** i jobbet och från
    bostad Någon → har en \" svart \" inkomst **både** från jobbet och
    från bostaden

-   vi har precis **flyttad** till Norrby → vi har precis **flyttat** till
    Norrby

**Higher priority than**

-   **O;** when a correction may be interpreted both as derivational
    correction and an orthographic correction, the L-Der tag should be
    applied rather than the O tag.

-   **L-FL;** see *[7.1](#71-non-swedish-words-and-sequences)* *Non-Swedish words and sequences*.

**Lower priority than**

-   **M-Adj/adv; corrections of an adjective form of a word to and
    adverb form of the same verb should be tagged with the specific tag
    M-Adj/adv rather than with L-Der.**

**Discrimination issues**

-   Corrections of verbal particles which are part of phrasal forms of
    particle verbs are not tagged with the L-Der tag, but with the L-W
    tag. (See *[7.2](#72-verbal-particles-and-reflexives)* *Verbal particles and reflexives*.)

-   See *[6.3](#63-l-der-vs-l-w)* *L-Der vs L-W*

-   See *[6.4](#64-l-der-vs-s-comp)* *L-Der vs S-Comp*

### 5.2.2 L-FL (foreign word corrected to Swedish)

The L-FL tag is used for words from a foreign (non-Swedish) language
which have been corrected to a Swedish word. It may also be applied to
words which have certain non-Swedish traits due to influence from a
foreign language.

-   Det fanns flera rum, två kök, **balkony** och trädgård → **balkong**

-   Jag och min **family** → **familj**

-   varför man ens lär sig svenska idag i Finland som beror på
    historiska **event** → varför man ens lär sig svenska idag i Finland
    , vilket beror på historiska **händelser**

-   Bostad i D-hemland är litet het **topik** för att **diskussera** →
    Bostäder i D-hemland är ett lite hett **ämne** att **diskutera**

The L-FL tag is used for corrections with the following characteristics:

-   The word in the original text is recognizable as a word from a
    foreign language *to the annotator* (who is obviously not equally
    proficient in all languages). Alternatively, *the
    annotator* recognizes certain non-Swedish traits in the word which
    are due to influence from a foreign language.

-   The word in the original text may or may not be correctly formed and
    used according to the norms of the assumed influencing language.

**Lower priority than**

-   **O** and **L-Der**; see *[7.1](#71-non-swedish-words-and-sequences)* *Non-Swedish words and sequences*.

**Discrimination issues**

If a corrected word is identifiable as an existing well-established
Swedish word which has been replaced by an altogether different word, it
should not be marked as L-FL, but as L-W, regardless of how likely it is
that the mistake is due to influence from another language. See *[7.1](#71-non-swedish-words-and-sequences)*
*Non-Swedish words and sequences*.

### 5.2.3 L-Ref (anaphoric expressions)

The L-Ref tag is used for anaphoric expressions (particularly pronouns
and pronominal adverbs) which have been corrected in order to have the
grammatical form (gender, number, reflexive/non-reflexive), semantic
content (masculine/feminine, directional/locational etc.), and
specificity which suits its correlate and its textual position.

-   Jag har en bror, **hon** heter xx → **han** heter xx

-   Stämmer det att våra sociala media skapar individualism och
    ensamhet? Eller skapar **det** kontakter och trivs? → Eller
    skapar **de** kontakter ...

    (In cases like this, the L-Ref tag has higher priority than the M-Num tag.)

-   Innan trädet blev borta dem fick fars äpplen och **sin** fru lagade
    saft och mos av äpplena Innan trädet var borta fick de fars äpplen →
    och **hans** fru lagade saft och mos av äpplena

-   Östling skriver om politiker som tycker att obligatorisk
    språkundervisningen och prov på nynorska krävs för att försäkra ett
    minoritets språk som har ett gamal kulturarv knutet till **den** . →
    Östling skriver om politiker som tycker att obligatorisk
    språkundervisning och prov på nynorska krävs för att skydda ett
    minoritetsspråk som har ett gammalt kulturarv knutet till **sig** .

-   " Finns det något som är mer värt än pengar ? " Jag vet faktiskt
    inte , **den** är en svår fråga . → " Finns det något som är mer värt
    än pengar ? " Jag vet faktiskt inte , **det** är en svår fråga .

    (In cases like this, and in the following examples the L-Ref tag has higher priority than the M-Gend tag.)

-   Om man jobbar åtta timmar varje vardag för att få pengar , sedan är
    det lite hycklande att säga något som , " Ja , det finns jo
    viktigare saker i livet ! " **Den** är en tredjedel av din dag ! → Om
    man jobbar åtta timmar varje vardag för att få pengar , är det sedan
    lite hycklande att säga något som : " Ja , det finns ju viktigare
    saker i livet ! " **Det** är en tredjedel av din dag !

-   Jag tycker om Gotland och **den** ligger i Sverige . → Jag tycker om
    Gotland , och **det** ligger i Sverige .

-   I artikeln \" Svenskan tynar i Finland \" ( Forsknings & Framsteg
    2009:2 ) Cecilia Christner Raid om varför man ens lär sig svenska
    idag i Finland **som** beror på historiska event . → I artikeln \"
    Svenskan tynar i Finland \" ( Forskning & Framsteg 2009:2 ) skriver
    Cecilia Christner Riad om varför man ens lär sig svenska idag i
    Finland , **vilket** beror på historiska händelser .

    (In cases like this, and in the following example, the L-Ref tag has higher priority than the L-W tag.)

-   Man kan flyga till Gotland eller åka till Nynäshamn och åka båt
    till **där** → Man kan flyga till Gotland eller åka till Nynäshamn
    och åka båt **dit** .

The L-Ref tag may also be used when a noun which is used anaphorically
has been exchanged for a pronoun, or the other way around, in order for
the specificity of the anaphoric expression to suit its textual
position:

-   Heter Jag Karin och Jag har änmält mig till danskursen och bitalad
    för det men tyvär fick Jag inte tid för att koma . Jag kunde inte
    att komma för jobbar och pl\$ggar Jag tillsamman och **det** passar
    inte med min tiden → Jag heter Karin och jag har anmält mig till
    danskursen och betalat för den , men tyvärr hade jag inte tid att
    komma . Jag kunde inte komma för att jag både jobbar och pluggar ,
    och **kursen** passar inte med mina tider

**Higher priority than**

-   **M-Num**

-   **M-Gend**

-   **L-W**

**Lower priority than**

-   **M-Def**; concerns changes between indefinite and definite forms of
    nouns

### 5.2.4 L-W (wrong word or phrase)

The L-W tag represents the correction category *wrong word or phrase*.
It is used when a word or phrase in the original text has been replaced
by another word or phrase in the normalized version. It is placed on
units which are *exchanged* rather than *corrected*.

The L-W tag is applied when the following conditions hold:

-   At least one of the units (the original unit or the normalized unit)
    is (an attempt at) a word or a fixed phrase.

-   If both the original unit and the normalized unit are one-word
    units, the root morpheme(s) of the category-defining part of the
    stem is corrected, which typically means one of the following:

    -   A word is completely exchanged (no common morpheme).

    -   The second word of a compound is exchanged.

    See *[6.3](#63-l-der-vs-l-w)* *L-Der vs L-W* for further explanations and examples.

-   If at least one of the strings is a multi-word unit, at least one
    lexical morpheme has to be changed (cf. *[6.8](#68-l-w-vs-s-comp)* *L-W vs S-Comp*).

*One word replaced by one word*:

-   Uppfinningen som **transformerade** hela kommunikationsområdet →
    Uppfinningen som **förändrade** hela kommunikationsområdet

-   Jag bor i D-område **på** en lägenhet → Jag bor i D-område **i** en
    lägenhet

-   På det sättet kan kommunen **motionera** alla medborgare att träna →
    På det sättet kan kommunen **motivera** alla medborgare att träna

-   vi solade och badade mycket och träffäde några **personer** från
    flera länder → Vi solade och badade mycket och
    träffade **människor** från flera länder

-   Alla blir **busiga** med sina sociala medier → Alla
    blir **upptagna** med sina sociala medier

    (See *[7.1](#71-non-swedish-words-and-sequences)* *Non-Swedish words and sequences* for further comments on this example.)

-   man väljer att använda engelska stället **av** svenska → man väljer
    att använda engelska i stället **för** svenska

    (The addition of *i* is tagged with S-M.)

*One word replaced by a multi-word expression:*

-   Med detta som bakgrund så kan man konstatera att majoriteten
    av **Finland** på olika missnöjesnivåer avskyr inlärning av svenska
    på grund- och gymnasieskolor → Med detta som bakgrund så kan man
    konstatera att majoriteten av **Finlands befolkning** , på olika
    missnöjesnivåer , avskyr inlärning av svenska på grund- och
    gymnasieskolor

*Multi-word expression replaced by one word:*

-   Jag maner att om vi **har önskemål** kan vi göra nånting utan pengar →
    Jag menar att om vi **vill** kan vi göra nånting utan pengar

*Multi-word expression replaced by another multi-word expression:*

-   Finns många nya lagenheterna i dyrare delar i huvudstaden , men
    detta är **lång distans från räker nummer** → Det finns många nya
    lägenheter i dyrare delar i huvudstaden , men detta är **långt ifrån
    tillräckligt**

    (*This correction is also tagged as S-type, see below.*)

*Phrasal verb replaced by another phrasal verb, both verb and particle
exchanged:*

-   Traditioner ger människorna tid att **stå still** och fundera över
    livet → ... att **stanna upp** och fundera över livet

*Phrasal verb replaced by another phrasal verb, different verb but the
same particle; only the verb is tagged, not the particle:*

-   men på debattsidor debatterar de oftast språkfrågan eftersom dem
    inte **hittar** på något annat att diskutera om → men på debattsidor
    debatterar de oftast språkfrågan eftersom de inte **kommer** på
    något annat att diskutera om

*Verbal particle replaced by another verbal particle, but verb kept; the
verbal particle rather than the whole phrasal verb is tagged with L-W:*

-   Han torkade **bort** bordet → Han torkade **av** bordet

*Compound particle verb replaced by a phrasal verb, both verb and
particle replaced:*

-   Konsekvenserna man skulle få ifall undervisning i svenska blev
    frivillig så skulle mer än hälften av finska
    befolkningen **avskaffa** svenskan som modersmålsundervisning → 
    Konsekvenserna man skulle få ifall undervisning i svenska blev
    frivilligt är att då skulle mer än hälften av den finska
    befolkningen **välja bort** svenskan som modersmålsundervisning

*Phrasal verb replaced by a simple verb*:

-   Men jag bestämde mig själv för att **hänga ihop** båda att studera
    och jobba → Men jag bestämde mig själv för att **kombinera** att både
    studera och jobba

*Fixed expression consisting of a lexical word (e.g. a noun) and a
grammatical word (e.g. a preposition) replaced by another fixed
expression consisting of the same lexical word but another grammatical
word; the grammatical word rather than the full fixed expression is
tagged with L-W:*

-   såsom våra "moderna" språk är ibland en blandning av flera utrotade
    minoritetsspråk som **under** tiden skapade något nytt och unik →
    såsom våra "moderna" språk ibland är en blandning av flera utrotade
    minoritetsspråk som **med** tiden skapade något nytt och unikt

**Note**: When a correction tagged with L-W involves a change of phrase
type/part of speech, the correction is also marked with the additional
tag S-Type.

-   plötsligt bröt muren **sinsemellan**  → plötsligt rasade
    muren **mellan dem**

-   jag behover pengar f\$r **liv** och betalning av min hus → jag behöver
    pengar för **att leva** och betala för mitt hus

-   Tycker om min plats har en **köpa mat** ett , litet centrum en
    förskolan en vårdcentralen → Jag tycker om platsen där jag bor , den
    har en **mataffär** , ett litet centrum , en förskola , en
    vårdcentral

-   Man kan promonera **lång tid** finns det blåser → Man kan
    promenera **länge** när det blåser

-   **Några tider** vi kan titta och lyssna på hur funkar det →
     **Ibland** kan vi titta och lyssna på hur det funkar

-   jag bor **in** lägenhet plan ett → Jag bor **i** en lägenhet på plan
    ett

**Lower priority than**

-   **L-Ref**

**Discrimination issues**

The principle that the L-W tag is placed on strings which
are *exchanged* rather than *corrected* underlies many of the more
specific principles for discriminating between the L-W tag and other
tags, described or referred to below.

-   Corrections consisting in the mere removal or addition of the
    reflexive *sig* or a verbal particle are not tagged with L-W, but
    with S-R or S-M respectively - even if both the bare verb and the
    phrasal verb may be characterized as lexical units. See *[7.2](#72-verbal-particles-and-reflexives)*
    *Verbal particles and reflexives*.

-   **Regarding L-W vs L-FL, see** ***[7.1](#71-non-swedish-words-and-sequences)*** *Non-Swedish words and
    sequences***.**

-   **Regarding the tagging of changes between pronoun and article uses
    of *de* and *dem*, see** ***[6.5](#65-l-w-vs-m-case)*** *L-W vs M-Case***.**

-   **See** ***[6.3](#63-l-der-vs-l-w)*** *L-Der vs L-W***.**

-   See *[6.6](#66-l-w-vs-m-verb)* *L-W vs M-Verb*.

-   **See** ***[6.8](#68-l-w-vs-s-comp)*** *L-W vs S-Comp***.**


## 5.3 M-Morphological corrections


The M tags represent the category *morphological corrections*. It covers
corrections related to inflections. This includes primarily corrections
of individual inflectional forms, but in some cases also corrections of
more complex grammatical constructions closely related to inflectional
forms. The latter concerns basic definiteness constructions (see [5.3.3](#533-m-def-definiteness))
periphrastic comparative and superlative adjective constructions (see
[5.3.4](#534-m-f-wrong-form-correct-grammatical-category) and [5.3.7](#537-m-other)), and tense-related verbal constructions involving
auxiliaries (see [5.3.8](#538-m-verb)).

The category of morphological corrections includes eight sub-categories.

### 5.3.1 M-Adj/adv (adjective corrected to adverb)

The M-Adj/adv tag is used for corrections involving the change of an
adjective to its t-form, when the t-form is called for due to the
adjective being used as an adverb.

-   Användaren mår **dålig** → **dåligt**

-   Hur påverkar detta våra måenden **långsiktig?** → **långsiktigt**

-   Jag tror att man måste hitta balansen mellan rikdom och andra saker
    som är **riktiga** viktiga → Jag tror att man måste hitta balansen
    mellan rikedom och andra saker som är **riktigt** viktiga

The M-Adj/adv is also used for similar changes, when an adjective or
adjective-like word is changed to a morphologically closely related but
distinct adverb form:

-   När jag kommer **första** i 2012 , jag bodde i en social lagenhet
    med 3 andra person → När jag **först** kom 2012 bodde jag i en
    kommunal lägenhet med 3 andra personer

Moreover, the M-Adj/adv tag is used when an adjectival form of the
word *liten* is changed to the adverb form of the same word,
i.e. *lite*. This holds also when the form *litet* is changed to the
form *lite*. Although the form *litet* is occasionally used as an adverb
in standard Swedish, it is too archaic to be used in most of the Swell
text genres, and adverbial uses of the form *litet* are thus normally
corrected to the form *lite* during normalization. Such changes are also
tagged with M-Adj/adv:

-   Bostad i D-hemland är **litet** het topik för att diskussera → 
    Bostäder i D-hemland är ett **lite** hett ämne att diskutera

**Higher priority than**

-   **L-Der**

-   **M-Gend**

### 5.3.2 M-Case

The M-Case tag is used for corrections regarding the choice of case form
for nouns (nominative vs genitive) and pronouns (nominative vs
accusative).

-   50 **kilometer** avstånd  → **kilometers**

-   Som kan bidra till **samhället** utveckling  → **samhällets**

-   Det ger **man** en positiv energi → Det ger **en** en positiv energi

-   Folk hinner inte prata med **de**  → Folk hinner inte prata
    med **dem**

-   Ingen förstår **hon**  → Ingen förstår **henne**

**Discrimination issues**

-   When the form *dem* is changed to the form *de* used as a definite
    article, the correction is tagged as L-W and S-Type, not as M-Case
    (see *[6.5](#65-l-w-vs-m-case)* *L-W vs M-Case*).

    -   den obligatoriska svenskundervisningen i **dem** finska skolorna → 
        den obligatoriska svenskundervisningen i **de** finska skolorna

### 5.3.3 M-Def (definiteness)

The M-Def tag is used for corrections regarding definiteness
constructions. The kinds of corrections which are involved in this
correction category are:

-   Change between indefinite and definite forms of nouns
    (*bok* vs *boken*; *rum* vs *rummet*)

-   Change between, removal of and addition of indefinite and definite
    articles (*en*, *ett*; *den*, *det*, *de*)

-   Change between indefinite and definite forms of adjectives and
    adjective-like pronouns
    (*stor*/*stort* vs *stora*; *egen*/*eget* vs *egna*)

*Examples*

-   Vi gick till McDonalds och åt **maten** → **mat**

-   Jag trivs bättre på **jobb** här  → **jobbet**

-   Jag har läst ditt **mejlet**  → ditt **mejl**

-   min **stor** dag → min **stora** dag

-   De **gränserna** som fanns mellan kvinnor och män har nästan
    försvunnit → De **gränser** som fanns

-   När kommer **den buss**  → När kommer **bussen**

-   Då kommer svenska språket försvinna ur Finska samhället → Då kommer
    svenska språket försvinna från **det** finska samhället

-   Han har egen **rummet** och jag egen → Han har **ett** eget **rum**
    och jag **ett** eget

**Note (1)**: M-Def corrections involving more than one token in one or
both text versions are tagged token by token. See *[4.6](#46-grouping-of-tokens)* *Grouping of
tokens*.

**Note (2)**: The M-Def tag is generally used for removals and additions
of articles, even when the correction is due to a change between the use
of a noun as a countable vs a non-countable noun.

-   Jag tycker att du kan baka kakor för dina arbetskamrater och bjuda
    dem för **en** fika → Jag tycker att du kan baka kakor till dina
    arbetskamrater och bjuda dem på fika

**Higher priority than**

-   **L-Ref**; concerns changes between indefinite and definite forms of
    nouns

-   **S-M**; concerns the addition of articles

-   **S-R**; concerns the removal of articles

**Discrimination issues**

-   When a singular indefinite article is removed from a plural
    indefinite NP, the removed article should be tagged M-Num rather
    than M-Def or S-R. See *[7.5](#75-singular-indefinite-article-removed-from-plural-indefinite-np)* *Singular indefinite article removed
    from plural indefinite NP*.

### 5.3.4 M-F (wrong form, correct grammatical category)

The M-F tag is used when a declension/conjugation form (typically a
suffix) which is used to express a specific grammatical category (e.g.
plural or present tense) has been corrected to a form belonging to
another declension/conjugation expressing the same grammatical category.

The tag is used for the following correction types:

*Nouns*:

-   Correction from one to another plural-associated form (suffix or
    stem changed form):
    **båter** → **båtar**, **huvudproblemer** → **huvudproblem, musar → 
    möss**

*Verbs*:

-   Correction from one to another form associated with present tense:
    jag **lager** mat → jag **lagar** mat

-   Correction from one to another form associated with past
    tense: **böjade** → **böjde, sjungde** → **sjöng**

-   Correction from one to another supine-associated
    form: **kunnit** → **kunnat, drickit** → **druckit**

*Adjectives*:

-   Correction from one to another comparative-associated
    form: **högare** → **högre, långare** → **längre**

-   Correction from one to another superlative-associated
    form: **högast** → **högst, ungast** → **yngst**

-   Correction of the choice between a periphrastic and an inflectional
    comparative or superlative construction: I Sverige är **mer
    kallt** än i xx → I Sverige är det **kallare** än i xx

The tag may also be used for some analogous changes of pronouns:

-   Enligt Hermanssons artikel debatten om huruvida nynorska skulle
    behållas eller om **dens** öde skulle vara upp till folket och
    marknaden att bestämma över resulterar i blandade åsikter → Enligt
    Hermanssons artikel resulterar debatten om huruvida nynorskan ska
    bevaras eller om **dess** öde ska vara upp till folket och marknaden
    att bestämma över i blandade åsikter

-   Jag bo i ett lägenhet med min sambo och **våras** yng dotter → Jag bor
    i en lägenhet med min sambo och **vår** lilla dotter

**Lower priority than**

-   **M-Num**; unsuffixed noun forms will be interpreted as singular
    when corrected to a suffixed plural form, although unsuffixed
    plurals exist. Corrections like *båt* → *båtar* will thus be tagged
    with the M-Num tag and not with the M-F tag.

### 5.3.5 M-Gend (gender)

The M-Gend tag is used to mark corrections of gender forms (neuter vs
non-neuter) of nouns, articles, adjectives, and pronouns with
adjective-like functions.

-   Det är **en** mycket **trevlig** område → Det
    är **ett** mycket **trevligt** område

-   **Den** viktigaste är att ...  → **Det** viktigaste är att ...

-   **Den** första telefonnät →  **Det** första telefonnätet

-   Kommunikationen är **möjligt**  → Kommunikationen är **möjlig**

-   ifall undervisning i svenska blev **frivillig** → **frivilligt**

-   Han har **egen** rummet och jag **egen** → Han har ett **eget** rum
    och jag ett **eget** (cf. the same example in section [5.3.3](#533-m-def-definiteness))

-   **Köken** är **stor** → **Köket** är **stort**

**Note**: Corrections from the distinctly masculine form of adjectives
-*e* to the general/feminine form -*a* are tagged M-Other rather than
M-Gend. See *[5.3.7](#537-m-other)* *M-Other*.

**Lower priority than**

-   **L-Ref**; gender corrections of pronouns which are due to their
    anaphoric reference will be covered by the L-Ref tag.

-   **M-Adj/adv**; changes from the non-neuter form to the neuter form
    of adjectives which are due to the adjective being used as an adverb
    should be tagged M-Adj/adv rather than M-Gend.

### 5.3.6 M-Num (number)

The M-Num tag is used to mark number corrections of nouns, articles,
adjectives, participles, and pronouns with adjective-like functions.

-   Stress kan komma i många **form** → Stress kan komma i
    många **former**

-   Så fort bilder är **tagen** → Så fort bilderna är **tagna**

-   Alla sitter bakom sina **skärmens** sken → Alla sitter bakom
    sina **skärmars** sken

**Note**: When several words in the same NP are changed with regard to
number, the tag M-Num should only be placed on the main word. The other
words are tagged with C, since these corrections are a consequence of
the number change of the main word.

-   därför kommer det att leda till **ett negativt konsekvens** → därför
    kommer det att leda till **negativa konsekvenser**

    The number change from *konsekvens* to *konsekvenser* is tagged M-Num. The change from *negativt* to *negativa* is tagged with C (as consistency changed caused by the adjective depending on the corrected noun) and with M-Gend (since the gender error of the original *negativt* is also eliminated through this change, cf. *[4.5](#45-several-tags-on-the-same-link)* *Several tags on the same link*). The removal of the article *ett* is, for the same reasons, also tagged with both C and M-Gend.

**Higher priority than**

-   **M-F**; unsuffixed noun forms will be interpreted as singular when
    corrected to a suffixed plural form, although unsuffixed plurals
    exist. Corrections like *båt* → *båtar* will thus be tagged with the
    M-Num tag and not with the M-F tag.

**Lower priority than**

-   **L-Ref**; number corrections of pronouns which are due to their
    anaphoric reference are covered by the L-Ref tag.

**Discrimination issues**

-   When a singular indefinite article is removed from a plural
    indefinite NP, the removed article should be tagged M-Num rather
    than M-Def or S-R. See *[7.5](#75-singular-indefinite-article-removed-from-plural-indefinite-np)* *Singular indefinite article removed
    from plural indefinite NP*.

### 5.3.7 M-Other

The M-Other tag is used for corrections involving inflectional
morphology for which none of the other M tags are suited.

The usage of the M-Other tag covers corrections between the
comparational forms of adjectives, including corrections between
non-morphologically related words functioning as different comparational
forms of the same adjective
(e.g. *dålig* and *sämre* or *många* and *fler*):

-   Morfar ville visa de att det finns nånting som är **viktigaste** → 
    Morfar ville visa dem att det finns nånting som är **viktigare**

-   I slutligen kan jag säga utifrån texterna jag läste att det
    finns **många** nackdelar än fördelar med att avskaffa den
    obligatorisk svenskan i Finland → Slutligen kan jag säga , utifrån
    texterna jag har läst , att det finns **fler** nackdelar än fördelar
    med att avskaffa den obligatoriska svenskan i Finland

The M-Other tag is also used for corrections from the distinctly
masculine form -*e* of adjectives to the general/feminine form -*a*:

-   **förre** året anmälde jag till en kurs för simna → **förra** året
    anmälde jag mig till en simkurs

-   min **käre** mamma → min **kära** mamma
 
    (Since the masculine form -*e* is never obligatory, corrections from the feminine/common form -*a* to the masculine form are not made during the normalization, and thus do never occur in the correction annotation process.)

Examples of other uses of the M-Other tag:

-   flera **folker** → mycket **folk**

    The *folker* form is clearly an attempt at creating a plural form with the plural suffix -*er*. However, the M-Num tag cannot be used since *folker* is not a plural form of *folk.* Nor can the M-F tag be used, although plural uses of the form *folk* occur, since the correct usage of *folk* here is a singular usage.

**The M-Other tag has lower priority than all other M-categories.**

### 5.3.8 M-Verb

The M-Verb tag covers corrections regarding inflectional verb forms and
basic tense-related constructions involving auxiliaries.

The verb-related grammatical categories involved are primarily tense,
mode and voice.

The verb forms involved are the non-finite verb forms (infinitive and
supine), the basic tense forms (present and past), the imperative, and
the s-form variants of all these forms (both in passive and other
usages).

The extra-inflectional constructions involved are the tense-related
constructions including auxiliary uses of the
verbs *ha*, *skola* and *komma* and the non-finite verb forms.

The M-Verb tag is thus used for the following correction types:

-   Changes between the following verb forms: infinitive (*dansa*,
    *äta*), supine (*dansat*, *ätit*), present (*dansar*, *äter*), past
    (*dansade*, *åt*), imperative (*dansa*, *ät*), and s-form variants
    of these forms (*dansas, ätas* etc.).

-   Additions and removals of forms of *ha*, *skola* and *komma*, when
    these verbs are used as auxiliaries.

-   Changes from one *ha, skola* or *komma* auxiliary to another.

-   Additions or removals of *att* which are due to changes of
    tense-related constructions involving auxiliary uses of the verbs
    *ha*, *skola* and *komma*.

*Examples*

-   Jag **trivs** där för att jag hade fler vänner → Jag **trivdes** där
    för att jag hade fler vänner

-   Slutligen tror jag att sociala medier **blev** en essentiell del → 
    Slutligen tror jag att sociala medier **har blivit** en essentiell
    del

-   Det betyder inte att vi glomma bort vår tradition → Det betyder inte
    att vi **ska** glömma bort vår tradition

-   Världen **utvecklar** i teknologin i varje minut → 
    Världen **utvecklas** i teknologin i varje minut

-   Om ni behöver något mer för att jag **kan** få pengarna tillbaka
    bara skriv till mig → Om ni behöver något mer för att jag **ska**
    **kunna** få pengarna tillbaka, bara skriv till mig!

-   Tyvärr **ska** jag inte komma på kursen Tyvärr **kommer** jag inte
    **att** komma på kursen

-   Min mormor har **kommat** **att** **bli** jättesjuk → Min mormor har
    **blivit** jättesjuk

**Note (1)**: M-Verb corrections involving more than one token in one or
both text versions are tagged token by token. See *[4.6](#46-grouping-of-tokens)* *Grouping of
tokens*.

**Note (2)**: Corrections between participle forms and supine forms are
tagged L-Der.

*Example*:

-   vi har precis **flyttad** till Norrby → vi har precis **flyttat** till
    Norrby

**Higher priority than**

-   **S-M**; concerns the addition of *ha, skola* and *komma*
    auxiliaries.

-   **S-R**; concerns the removal of *ha, skola* and *komma*
    auxiliaries.

**Discrimination issues**

-   See *[6.6](#66-l-w-vs-m-verb)* *L-W vs M-Verb*

-   Concerning M-Verb vs S-Clause, see *[7.3](#73-clause-corrected-or-created)* *Clause corrected or
    created?*


## 5.4 P-Punctuation corrections

The P tags represent the category of *punctuation corrections*,
including instances of merging or splitting sentences. It has four
sub-categories.

### 5.4.1 P-M (missing punctuation)

The P-M tag is used for corrections involving the addition of a
punctuation mark.

-   Jag har fyra **barn två** pojkar och två flickor → Jag har
    fyra **barn, två** pojkar och två flickor

-   År 1972 togs den sista manuella växeln ur **bruk anger** Björkkvist → 
    År 1972 togs den sista manuella växeln ur **bruk, anger** Björkkvist

-   Det ger en positiv **energi därmed** kan man bli av med stress → Det
    ger en positiv **energi. Därmed** kan man bli av med stress

-   Efter fem dagar kom till mig och **sa vad** vill du mig och **jag sa
    att jag** älskar **dig** → Efter fem dagar kom hon till mig och **sa:
    Vad** vill du **mig? Och** jag **sa: Jag** älskar **dig.**

-   Min mamma lagar så god **mat jag** trivs med hennes mat → Min mamma
    lagar så god **mat. Jag** trivs med hennes mat

**Lower priority than**

-   **O-Comp;** additions of hyphens and spaces between words are
    covered by the O-Comp tag, not by the P-M tag.

**Discrimination issues**

-   Concering additions of spaces and hyphens, see *[7.4](#74-spaces-hyphens-and-dashes)* *Spaces,
    hyphens and dashes*.

-   Concerning the addition of other token-internal punctuation marks,
    see *[6.1](#61-o-vs-punctuation-tags)* *O vs punctuation tags*.

### 5.4.2 P-R (redundant punctuation)

The P-R tag is used for corrections involving the removal of a
punctuation mark.

-   Jag minns inte **exakt . vad** det var med det var gott → Jag minns
    inte **exakt vad** det var men det var gott

**Lower priority than**

-   **O-Comp;** removals of hyphens and spaces between the constituent
    words in a compound are covered by the O-Comp tag, not by the P-R
    tag.

**Discrimination issues**

-   Concering removals of spaces and hyphens, see *[7.4](#74-spaces-hyphens-and-dashes)* *Spaces, hyphens
    and dashes*.

-   Concerning the removal of other token-internal punctuation marks,
    see *[6.1](#61-o-vs-punctuation-tags)* *O vs punctuation tags*.

### 5.4.3 P-Sent (sentence segmentation)

The P-Sent tag is used for corrections involving splitting a sentence or
merging two sentences into one, when this correction involves more than
the pure insertion or removal of a punctuation mark - in the typical
case the adding or removal of a conjunction.

-   Jag heter xxx och jag pratar arabiska och engelska och
    lite **svenska och vi** har tre rum i huset Jag heter xxx och jag
    pratar arabiska och engelska och lite **svenska . Vi** har tre rum i
    huset

    In this example, the P-Sent tag is placed on a link between *och* in the original text and the period in the normalized text. The link between *vi* and *Vi* is tagged with C, as a consistency correction.

### 5.4.4 P-W (wrong punctuation)

The P-W tag is used when a punctuation mark in the original text has
been replaced with another punctuation mark in the normalized text.

-   Mina barn heter **Peter; Maria; Elisabeth** och John → Mina barn
    heter **Peter, Maria, Elisabeth** och John

**Lower priority than**

-   **O-Comp; i**nstances where a space has been corrected to a hyphen
    between the constituent words in a compound are not marked with this
    tag, but with O-Comp or S-Comp. The same holds for instances where a
    hyphen between words has been corrected to a space.

**Discrimination issues**

-   Concerning corrections of spaces, hyphens and dashes, see *[7.4](#74-spaces-hyphens-and-dashes)*
    *Spaces, hyphens and dashes*.

-   Concerning corrections of other token-internal punctuation marks,
    see *[6.1](#61-o-vs-punctuation-tags)* *O vs punctuation tags*.


## 5.5 S-Syntactical corrections
----------------------------

The S tags represent the syntactical correction category. It contains
eleven sub-categories.

### 5.5.1 S-Adv (adverbial placement)

The S-Adv tag is used for corrections involving the placement of an
adverbial.

-   Jag **ofta** är vaken länge på kvällarna → Jag är **ofta** vaken
    länge på kvällarna

-   Å ena sidan **idag** har → Å ena sidan har **idag**

-   Jag är jättetrött eftersom jag sover **inte** på nätterna → Jag är
    jättetrött eftersom jag **inte** sover på nätterna

-   som i sin tur har **tydligt** påverkat → som i sin
    tur **tydligt** har påverkat

-   och **med hela världen** dela sina idéer och tankar → och dela sina
    idéer och tankar **med hela världen**

-   om hur **under 600 år** Finland var en del av Sverige → om hur
    Finland var en del av Sverige **under** **600 år**

**Higher priority than**

-   **S-FinV**

-   **S-WO**

But see also *[7.6](#76-exceptions-to-the-default-ranking-of-the-word-order-tags)* *Exceptions to the default ranking of the word order
tags*.

**Discrimination issues**

-   See *[6.9](#69-s-clause-vs-word-order-tags)* *S-Clause vs word order tags*.

### 5.5.2 S-Clause (basic clause structure)

The S-Clause tag is used for corrections involving changes of the most
basic clause structure. The corrections in this category may be divided
into the three following main types:

1.  The structure of a clause is changed in a way which involves
    changing the primary syntactic function (subject, finite verb,
    object, *egentligt subjekt* 'object-positioned subject' and
    predicative) of one or more of the words/phrases involved, for
    instance:

    - Subject changed to *egentligt subjekt* 'object-positioned subject':

       - För att sammanfatta och svara på frågan om **likheter och
         skillnader** finns mellan nynorskans ställning i Norge och
         svenkans ställning i Finland → För att sammanfatta och svara
         på frågan om **det** finns **likheter och skillnader**
         mellan nynorskans ställning i Norge och svenskans ställning
         i Finland

         The inserted expletive subject *det* is tagged S-Msubj. The movement
         of the phrase *likheter och skillnader* indicates its change of
         function from subject to *egentligt subjekt* 'object-positioned
         subject', and the link between this unit in the original text and the
         same unit in the normalized text is thus tagged S-Clause. (Cf. *[6.13](#613-s-clause-vs-s-msubj)*
         *S-Clause vs S-Msubj* and *[6.9](#69-s-clause-vs-word-order-tags)* *S-Clause vs word order tags*.)

    - Changes between a passive construction and an active construction:

       - I texten **sägs det av henne** att hon efterlyser de som enbart
         talar finska → I texten **säger hon** att hon efterlyser de som
         enbart talar finska

         A link is created between the group unit *sägs det av henne* and the
         group unit *säger hon*. This link is tagged S-Clause, and this
         categorization covers all of the corrections involved, none of which
         should be tagged separately (cf. *[4.7](#47-corrections-of-tokens-included-in-group-units)* *Corrections of tokens included
         in group units*).

    - Subject or object changed to a prepositional complement in an adverbial:

       - **du** blir bättre → det blir bättre **för dig**

         A link is created between *du* and *för dig*. This link is tagged
         S-Clause. The inserted *det* subject is tagged S-Msubj. (Cf. *[6.13](#613-s-clause-vs-s-msubj)*
         *S-Clause vs S-Msubj*.)

       - I Norge har politiker laggt ner stora summar av pengar för att
         försvara språket och håller **det** fast som ett obligatorisk språk
         för att hålla det levande bland ungdomar → I Norge har politiker lagt
         ner stora summor pengar för att försvara språket och håller fast
         **vid det** som ett obligatoriskt språk för att hålla det levande
         bland ungdomar

    - Object predicative changed to an attribute of an object NP:

       - Hon skriver också om att ha svenska **som obligatorisk** i
         Finland visar att alla är ju finnar och att \" finlandssvenska
         \" är bara påhittat → Hon skriver också om att **det att** ha
         **obligatorisk** svenska i Finland visar att alla är ju finnar
         och att \" finlandssvenska \" är bara påhittat

2.  The structure of a phrase or a clause is changed in a way which
    involves a change of the number of clauses involved, for instance:

    - The structure of a noun phrase is changed by changing
      a *framförställt attribut* ('preceding attribute') to
      an *efterställt attribut* ('succeeding attribute') in the form
      of a relative clause:

        - **min plats** → **platsen där jag bor** (Cf. *[7.3](#73-clause-corrected-or-created)* *Clause
            corrected or created?*)

    - An attribute in the form of a relative clause is changed to an
        attribute in the form of a *particip* 'participle':

        - Människor använder pengar eller nånting **som är lika till
          dem** från alltid → Människor har alltid använt pengar eller
          nånting **liknande**

    - A finite clause is changed to a noun phrase:

        - tre personer som har sagt sin åsikt om tvångssvenskan
          och **hur svenskan befinner sig** → tre personer som har sagt
          sin åsikt om tvångssvenskan och** läget för svenskan**

    - A finite clause (or a clear attempt at a finite clause, as in
        the following example) is changed to an infinitive phrase:

        - Men **om man** åka båt bätre för att båten är jatte stor → Men
            **att** åka båt är bättre för att båten är jättestor

    - An infinitive phrase is changed to a finite clause:

        - **Att växa** upp som en flicka så var det väldigt många
          orättvisor man fick vänja sig vid. → **När man växte** upp
          som en flicka så var det väldigt många orättvisor man fick
          vänja sig vid (See *[7.3](#73-clause-corrected-or-created)* *Clause corrected or created?*)

        - Riad pratar om den minskande procent av svensktalare i
          Finland och hur det leds till **några att tycka** att
          svenska ska inte vara ett officiellt språk längre → Riad
          pratar om den minskande procenten svensktalande i Finland
          och hur detta leder till **att några tycker** att svenska
          inte ska vara ett officiellt språk längre

    - A clause is created by adding (at least) a finite verb to a
      "potential clause" which has no verb at all (finite or infinite)
      in the original text. (Cf. *[7.3](#73-clause-corrected-or-created)* *Clause corrected or created?*)

        - Konsekvenserna man skulle få ifall undervisning i svenska
          blev frivillig så skulle mer än hälften av finska
          befolkningen avskaffa svenskan som modersmålsundervisning
          och istället fokusera på finska då dem sällan använder
          svenskan → Konsekvenserna man skulle få ifall undervisning i
          svenska blev frivilligt **är **att då skulle mer än hälften
          av den finska befolkningen välja bort svenskan som
          modersmålsundervisning och istället fokusera på finska då de
          sällan använder svenskan

          (See also the same example further down in this section.)

        -   Hon fördelen med att behålla den obligatoriska svenskan →
    Hon **beskriver** fördelen med att behålla den obligatoriska
    svenskan

        *When the creation of the clause involves the addition of a subject, on top of the addition of a finite verb, the added subject is also tagged with S-Clause* (cf. *[7.3](#73-clause-corrected-or-created)* *Clause corrected or created?*)

        -   Jag studerar på eftermiddag Sfi och förmiddag praktik → Jag studerar
    sfi på eftermiddagen och på förmiddagen **har jag** praktik

        -   och han tycker att misstänksamheten mellan grupperna som befinner
    sig i södra Finland lyser med sin frånvaro → och han tycker att den
    misstänksamhet **som** **finns** mellan grupperna i södra Finland
    lyser med sin frånvaro

3.  The basic clause type (main clause, subordinate clause or main
    clause with question structure) is changed or specified:

    -   A main clause is changed to a subordinate clause, for instance
        by adding a *subjunktion* 'subordinating conjunction':

        -   Konsekvenserna man skulle få ifall undervisning i svenska
            blev frivillig **så** skulle mer än hälften av finska
            befolkningen avskaffa svenskan som modersmålsundervisning
            och istället fokusera på finska då dem sällan använder
            svenskan → Konsekvenserna man skulle få ifall undervisning i
            svenska blev frivilligt är **att då** skulle mer än hälften
            av den finska befolkningen välja bort svenskan som
            modersmålsundervisning och istället fokusera på finska då de
            sällan använder svenskan

            The added *subjunktion* 'subordinating conjunction' *att* indicates that the clause has been changed to a subordinate clause, and *att* is thus tagged S-Clause, while the change of *så* to *då* is tagged C, as a consequence correction. (The added finite verb *är* is also tagged S-Clause, since this addition involves an addition of a clause in the clausal hierarchy. See the same example above.)

-   A subordinate clause is changed to a main clause, for instance by
    removing a *subjunktion* 'subordinate conjunction':

    -   **Om** du skapar något för att inte känner dig ensam Du kan göra
        något för att inte känna dig ensam (Cf. *[6.14](#614-s-clause-vs-s-r)* *S-Clause vs
        S-R*.)

-   An "ordinary" main clause is changed to a main clause with question
    structure:

    -   Jag vill att vet vad är problemet som jag inte kan gå till
        kursen **det finns** ingen plats eller **ni har** stoppade den
        här kurs och ni ska inte har det igen → Jag vill veta vad det är
        för problem som gör att jag inte kan gå på kursen : **Finns
        det** ingen plats eller **har ni** stoppat den här kursen och
        ska inte ha den igen ?

        In this case, the changed placement of the finite verb relative to the subject is marked with an S-Clause tag on the finite verb instead of an S-FinV tag.

-   The relationship between two clauses is specified, for instance by
    the addition of a *subjunktion* 'subordinating conjunction' or
    another *bisatsinledare* ('subordinating connector'):

    -   Sådana känslor gör användaren mår dåligt → Sådana känslor
        gör **att** användaren mår dåligt

    -   Man kan promonera lång tid finns det blåser → Man kan promenera
        länge **när** det blåser

**Discrimination issues**

-   See *[6.7](#67-l-w-vs-s-clause)* *L-W vs S-Clause*.

-   See *[6.9](#69-s-clause-vs-word-order-tags)* *S-Clause vs word order tags*.

-   See *[6.10](#610-s-clause-vs-s-comp)* *S-Clause vs S-Comp*.

-   See *[6.12](#612-s-clause-vs-s-m)* *S-Clause vs S-M*.

-   See *[7.3](#73-clause-corrected-or-created)* *Clause corrected or created?*

-   See *[6.11](#611-s-clause-vs-s-ext)* *S-Clause vs S-Ext*.

### 5.5.3 S-Comp (compound vs multi-word expression)

The S-Comp tag is used for corrections involving the restructuring of
the same lexical words within a multi-word expression. It may also be
used for changes between a multi-word expression and a one-word
expression, when the one-word expression contains a derivational
morpheme with the same semantic function as one of the words in the
multi-word expression.

*Corrections regarding the choice between a compound and a multi-word
expression*:

-   **det vardagliga livet** → **vardagslivet**

-   **livsskillnaden**  → **skillnaden i liv**

-   **svenska undervisningar** →  **svenskundervisning**

-   **avsnittet av texten**  → **textavsnittet**

-   Om det händer att det finns planhalvor så kan det bero på blyghet,
    osäkerhet, rädsla eller **socialfobi** → **social fobi**

    (See *[6.2](#62-o-comp-vs-s-comp)* *O-Comp vs S-Comp* for further discussion of this example.)

-   Hejdlös **sociala medier användning** orsakar ensamhet →
    Hejdlös **användning av sociala medier** orsakar ensamhet

    (See *[6.2](#62-o-comp-vs-s-comp)* *O-Comp vs S-Comp* for further discussion of this example.)

*Corrections regarding the choice between a compound and a phrasal
structure for the combination of a verb and a verbal particle*:

-   Enligt Hyltenstam så kan minoritetsspråk räddas om
    man **inblandar** dem äldre som kan språket → Enligt Hyltenstam så kan
    minoritetsspråk räddas om man **blandar in** de äldre som kan
    språket

*Other corrections involving the restructuring of the same lexical
morphemes within a phrase*:

-   Skillnader är stor av **Sveriges bostad**  → Skillnaderna är stora
    mot **bostäder i Sverige**

-   Hon var **yngre än jag i ett år** → Hon var **ett år yngre än jag**

-   Cecila Christner skriver om hur det svenska språket i skolor blir
    kallad tvångsvenska **i samma tid** svenska har blivit icke populärt
    i Finland → Cecilia Christner skriver om hur det svenska språket i
    skolorna blir kallat tvångssvenska **samtidigt** som svenska har
    blivit impopulärt i Finland

*Changes between a multi-word expression and a one-word expression, when
the one-word expression contains a derivational morpheme with the same
semantic function as one of the words in the multi-word expression*:

-   Cecila Christner skriver om hur det svenska språket i skolor blir
    kallad tvångsvenska i samma tid svenska har blivit **icke
    populärt** i Finland → Cecilia Christner skriver om hur det svenska
    språket i skolorna blir kallat tvångssvenska samtidigt som svenska
    har blivit **impopulärt** i Finland

**Discrimination issues**

-   **See** ***[6.2](#62-o-comp-vs-s-comp)*** *O-Comp vs S-Comp*

-   **See** ***[6.4](#64-l-der-vs-s-comp)*** *L-Der vs S-Comp*

-   **See** ***[6.8](#68-l-w-vs-s-comp)*** *L-W vs S-Comp*

-   **See** ***[6.10](#610-s-clause-vs-s-comp)*** *S-Clause vs S-Comp*

-   **See** ***[7.2](#72-verbal-particles-and-reflexives)*** *Verbal particles and reflexives*

### 5.5.4 S-Ext (extensive correction)

The S-Ext tag is used for extensive, often complex, corrections. The
syntactic structure of the normalized text segment may rather be
described as *created* than as *corrected*, and the correction often
also involves additions or removals of lexical words. The original text
gives a fair indication of an intended meaning (otherwise the correction
would be X-marked), but in most S-Ext cases it gives a poor basis for
assuming a specific syntactic goal structure and/or a specific wording.
In some cases, the wording and the syntactic goal structure may be
fairly self-evident, but the S-Ext tag is chosen simply because the
correction is too extensive or too complex to be covered by the other
S-tags in any meaningful way.

While all normalizations are to be considered interpretations of the
original texts, the S-Ext tag indicates that the range of possible
normalizations is especially wide, and that the particular normalization
chosen thus involves a greater element of subjectivity or randomness.

When categorizing a correction as S-Ext, more specific syntactic
corrections involved in the correction (additions or removals of words,
word order changes, etc.) are not individually tagged. (Cf. *[4.7](#47-corrections-of-tokens-included-in-group-units)*
*Corrections of tokens included in group units*.)

-   **Det därför tycker jag om det är** simma lungt och blåser  → **Jag
    tycker om det för att jag tycker om att** simma lugnt och när det
    blåser

-   Så hur mycket pojkarna bettalad **värt inte deras
    äppelträd** eftersom trädet var viktig för dem → Så hur mycket
    pojkarna betalade **var mindre än vad deras äppelträd var
    värt** eftersom trädet var viktigt för dem .

-   Det är lite bättre i huvudstad , när många manniskor bo tilsammans
    eftersom **de kan e betala för**  → Det är lite bättre i huvudstaden ,
    när många människor bor tillsammans eftersom **det gör att de kan
    betala**

-   Men **har det hänt något problem med mig** → Men **jag har fått ett
    problem**

-   att ta det lugnt och njuta av livet och allt som sker i de, inte
    bara pengarna → att ta det lugnt och njuta av livet och allt som sker
    i det, inte bara **tänka på** pengar (cf. *[6.15](#615-s-ext-vs-s-m)* *S-Ext vs S-M*)

-   Riad skriver om ett positiv framtid för svenska i Finland på allt
    folk har gemensamt kulturell → Riad skriver om en positiv framtid för
    svenskan i Finland **med tanke** på allt folk har gemensamt
    kulturellt (cf. *[6.15](#615-s-ext-vs-s-m)* *S-Ext vs S-M*)

**Discrimination issues**

-   See *[6.11](#611-s-clause-vs-s-ext)* *S-Clause vs S-Ext*.

-   See *[6.15](#615-s-ext-vs-s-m)* *S-Ext vs S-M*.

-   See *[6.16](#616-s-ext-vs-x)* *S-Ext vs X*.

### 5.5.5 S-FinV (placement of finite verb)

The S-FinV tag is used for corrections of a finite verb placement,
unless the correction concerns the ordering between the finite verb and
an adverb, in which case the correction is tagged with the S-Adv tag.

-   Vor du **bor**? → Var **bor** du?

-   I morgon jag **åker**  → I morgon **åker** jag

-   Efteråt man **surfar** på internet → Efteråt **surfar** man på
    internet

-   När jag ätiti, jag **sover** →  När jag ätit, **sover** jag

-   Eller det **skapar** kontakter och trivs? → Eller **skapar** de
    kontakter och trivsel?

**Higher priority than**

-   **S-WO**

**Lower priority than**

-   **S-Adv**

But see also *[7.6](#76-exceptions-to-the-default-ranking-of-the-word-order-tags)* *Exceptions to the default ranking of the word order
tags*.

### 5.5.6 S-M (word missing, other)

The S-M tag is used when a word is missing in the original text and has
been added in the normalized version. This includes the addition of
reflexives and verbal particles. (See *Verbal particles and
reflexives*.)

-   Jag gillar inte tapeterna i min kusins lägenhet men han inte byta
    dem eftersom det är hyresrätt → \... han **kan** inte byta dem \...
    (Cf. *[7.3](#73-clause-corrected-or-created)* *Clause corrected or created?*)

-   Jag trivs mycket bo med dem → jag trivs mycket **med att** bo med dem

-   men känner bara fysiskt närvarande → men känner **sig** bara fysiskt
    närvarande

-   Jag slår ord i ordboken när jag inte vet → Jag slår **upp** ord i
    ordboken när jag inte vet\...

**Lower priority than**

-   **M-Def**; added articles should be tagged M-Def rather than S-M.

-   **M-Verb**; added *ha*, *komma* and *skola* auxiliaries should be
    tagged M-Verb rather than S-M.

-   **S-Msubj**; added subjects should be tagged S-Msubj rather than
    S-M.

**Discrimination issues**

-   Additions of *subjunktioner* ('subordinating conjunctions') are
    tagged S-Clause rather than S-M. See *[6.12](#612-s-clause-vs-s-m)* *S-Clause vs S-M*.

-   Finite verbs which are added as part of creating a whole new clause
    in the normalization should be tagged S-Clause rather than S-M. See
    *[7.3](#73-clause-corrected-or-created)* *Clause corrected or created?*

-   See *[6.15](#615-s-ext-vs-s-m)* *S-Ext vs S-M*.

-   See *[6.17](#617-s-type-vs-s-m-and-s-r)* *S-Type vs S-M and S-R*.

-   See *[7.2](#72-verbal-particles-and-reflexives)* *Verbal particles and reflexives*.

### 5.5.7 S-Msubj (subject missing)

The S-Msubj tag is used to mark corrections involving the addition of a
subject which is missing in a clause in the original text. This includes
cases when the pronoun/*subjunktion* 'subordinating
conjunction' *som* has been inserted as a subject. It also includes
typical instances when a *det* has been inserted due to
*platshållartvånget* 'the placeholder requirement'.

-   Regnar ute  → **Det** regnar ute

-   Det är inte bara arbetet och arbetslivet kan ge stress → Det är inte
    bara arbetet och arbetslivet **som** kan ge stress

-   Det är viktigt att veta vad händer → Det är viktigt att veta
    vad **som** händer

-   I annan text \" Tre röster om svenskans ställning i Finland \"
    Parnass 2013:3 som är skriven av författaren Catharina Söderbergh
    beskriver dem tre olika ställningar som finns om svenska inom
    Finland → I en annan text , \" Tre röster om svenskans ställning i
    Finland \" ( Parnass 2013:3 ) , som är skriven av författaren
    Catharina Söderbergh , beskriver **författaren** de tre olika
    inställningar som finns till svenska i Finland

-   Finns många nya lagenheterna i dyrare delar i huvudstaden →
     **Det** finns många nya lägenheter i dyrare delar i huvudstaden

The S-Msubj tag should be placed on a *det* which has been inserted as a
subject, even when the original clause contains a subject (see *[6.13](#613-s-clause-vs-s-msubj)*
*S-Clause vs S-Msubj*), i.e. also in cases like the following:

-   *Det* is inserted as a subject in the normalized text, and the
    subject in the original text is changed to an *egentligt
    subjekt* ('object-positioned subject'):

    -   på andra sidan finns ***människor som har så mycket pengar att
        de kan köpa halva världen*** →  Å andra sidan finns **det
        *människor som har så mycket pengar att de kan köpa halva
        världen***

        *Det* is tagged with S-Msubj. In this particular example, no additional visible correction (besides the insertion of *det*) corresponding to the change of the original subject to an *egentligt subjekt* ('object-positioned subject') is made, and this correction is therefore not tagged at all (cf. *[4.3](#43-only-visible-corrections-are-tagged)* *Only visible corrections are tagged*).

    -   För att sammanfatta och svara på frågan om *likheter och skillnader*
    finns mellan nynorskans ställning i Norge och svenkans ställning i
    Finland → För att sammanfatta och svara på frågan om **det** finns
    *likheter och skillnader* mellan nynorskans ställning i Norge och
    svenskans ställning i Finland

        The inserted expletive subject *det* is tagged S-Msubj. The movement of the phrase *likheter och skillnader* indicates its change of function from subject to *egentligt subjekt* 'object-positioned subject'. The link between this unit in the original text and the same unit in the normalized text is thus tagged S-Clause. (Cf. *[6.9](#69-s-clause-vs-word-order-tags)* *S-Clause vs word order tags*.)

-   A heavy subject is moved to a position further back in the clause,
    and *det* is inserted in the subject position:

    -   Hon försätter skriva om ***att inte avskaffa den obligatoriska
        svenskan på skolan*** är fördel för ungdomar → Hon fortsätter
        skriva om att **det** är en fördel för ungdomar ***att inte
        avskaffa den obligatoriska svenskan i skolan***

        *The inserted* *det* *is tagged as S-Msubj and the moved subject is tagged as S-WO.*

-   *Det* (possibly followed by *att*) is inserted as a subject before
    an infinitive phrase already functioning as a subject (and the
    infinitive phrase becomes an attribute to *det*):

    -   Hon skriver också om att *ha svenska som obligatorisk i Finland*
        visar att alla är ju finnar och att \" finlandssvenska \" är
        bara påhittat . -\> Hon skriver också om att **det att*** ha
        obligatorisk svenska i Finland* visar att alla är ju finnar och
        att \" finlandssvenska \" är bara påhittat .

        *det* is tagged as S-Msubj, *att* is tagged S-M. The function shift of the infinitive phrase is an "invisible" correction, and is thus not tagged at all (cf. *[4.3](#43-only-visible-corrections-are-tagged)* *Only visible corrections are tagged*).

**Higher priority than**

-   **S-M**

**Discrimination issues**

-   The S-Msubj tag should only be applied in those cases when the
    clause is already present in the original text. When a subject has
    been added as part of a correction involving the creation of a
    clause which was not present in the original text, the subject
    should be tagged as S-Clause, just as the rest of the added or
    changed elements involved in the creation of the clause. See *[7.3](#73-clause-corrected-or-created)*
    *Clause corrected or created?*

-   The S-Msubj tag should however be applied to a *det* which is added
    as a subject to an already present clause even when this clause
    already contains another subject. See examples above and *[6.13](#613-s-clause-vs-s-msubj)*
    *S-Clause vs S-Msubj.*

### 5.5.8 S-Other

The S-Other tag is used for syntactic corrections not covered by any of
the other S-tags. Its usage includes:

-   A negated pronoun is exchanged for a negation and a non-negated
    pronoun:

    -   Det finns platser i världen, där manga har **ingen** att ätta →
        Det finns platser i världen där många **inte** har **någonting**
        att äta

    -   jag önskar att det finns **inget** problem att få min pengar
        tillbaka → jag hoppas att det **inte** finns **något** problem med
        att få mina pengar tillbaka

-   A double negation is corrected to a simple negation:

    -   seden har jag fått att anm\$la till andra kurs *utan* betala
        **ingeting** → sedan har jag fått anmäla mig till en annan kurs
        *utan* att betala **någonting**

**Lower priority than all other S-tags.**

### 5.5.9 S-R (word redundant)

The S-R tag is used when a word is redundant in the original text and
has been removed in the normalized version. This includes the removal of
reflexives and verbal particles. (See *[7.2](#72-verbal-particles-and-reflexives)* *Verbal particles and
reflexives*.)

-   Man behöver inte **att** klä på sig → Man behöver inte klä på sig

-   Det är ett personligt ansvar **för** att välja → Det är ett personligt
    ansvar att välja

-   X-stad är närmare **till** X-land än X-stad → X-stad är närmare X-land
    än X-stad

-   De första mobiltelefonerna kom **i** 1957 → De första mobiltelefonerna
    kom 1957

-   De nya kommunikationssätten har medfört **med** stora möjligheter → De
    nya kommunikationssätten har medfört stora möjligheter

-   sociala medier blev en essentiell del av våra liv som vi inte kan
    slänga **det** i den moderna världen → sociala medier blev en
    essentiell del av våra liv som vi inte kan slänga i den moderna
    världen

-   De promenerade **sig** i parken → De promenerade i parken

-   Hon gav **bort** honom en blomma → Hon gav honom en blomma

**Lower priority than**

-   **M-Def**; concerns the removal of articles.

-   **M-Verb**; concerns the removal of *ha, komma* and *skola*
    auxiliaries.

**Discrimination issues**

-   Removals of *subjunktioner* 'subordinate conjunctions' should be
    tagged S-Clause rather than S-R. See *[6.14](#614-s-clause-vs-s-r)* *S-Clause vs S-R*.

-   Removals of words which are part of restructuring a phrase or a
    clause in a way which removes a clause altogether should also be
    tagged S-Clause rather than S-R. See *[6.14](#614-s-clause-vs-s-r)* *S-Clause vs S-R*.

-   When a singular indefinite article is removed from a plural
    indefinite NP, the removed article should be tagged M-Num rather
    than M-Def or S-R. See *[7.5](#75-singular-indefinite-article-removed-from-plural-indefinite-np)* *Singular indefinite article removed
    from plural indefinite NP*.

-   See *[6.17](#617-s-type-vs-s-m-and-s-r)* *S-Type vs S-M and S-R*.

-   See *[7.2](#72-verbal-particles-and-reflexives)* *Verbal particles and reflexives*.

### 5.5.10 S-Type (change of phrase type/part of speech)

The S-Type tag is used when a word or phrase has been changed to a word
with another part of speech or another phrase type.

The S-Type tag is usually combined with an L-Der or an L-W tag.

*Example, S-Type and L-W*

-   Tycker om min plats har en **köpa mat** ett , litet centrum en
    förskolan en vårdcentralen → Jag tycker om platsen där jag bor , den
    har en **mataffär** , ett litet centrum , en förskola , en
    vårdcentral

    See *[5.2.4](#524-l-w-wrong-word-or-phrase)* *L-W (wrong word or phrase)* for more examples.

*Example, S-Type and L-Der*

-   Jag ska **solen** och bada → Jag ska **sola** och bada

    See *[5.2.1](#521-l-der-word-formation)* *L-Der (word formation)* for more examples.

**Discrimination issues**

-   Whenever the syntactic category of a phrase is changed *only* by the
    addition or removal of one or more words, the S-M and S-R tags
    should be used rather than the S-Type tag, see *[6.17](#617-s-type-vs-s-m-and-s-r)* *S-Type vs S-M
    and S-R*.

### 5.5.11 S-WO (word order, other)

The S-WO tag is used for word order corrections which are not covered by
the S-Adv or the S-FinV categories.

In corrections regarding the relative placement of a phrasal head and a
modifying element (for instance a noun and its attribute), the modifying
element should be marked rather than the phrasal head (e.g. *min* rather
than *bostad* in the example below):

-   Bostaden **min** → **Min** bostad

In cases when the word order change may be interpreted as moving an
element "out of" a normally fairly fixed structure, that element should
be marked rather than an element included in the more fixed structure
(*dem* rather than *upp* in the example below).

-   Man kan inte vänta att lägga **de** upp på social medier → Man kan
    inte vänta med att lägga upp **dem** på sociala medier

In other cases the placement of the tag may be chosen freely between the
elements which have been moved relative to each other, but the
readability of the resulting visualization should be taken into
consideration.

**Lower priority than**

-   **S-Adv**

-   **S-FinV**

But see also *[7.6](#76-exceptions-to-the-default-ranking-of-the-word-order-tags)* *Exceptions to the default ranking of the word order
tags*.

**Discrimination issues**

-   See *[6.9](#69-s-clause-vs-word-order-tags)* *S-Clause vs word order tags*.


## 5.6 Other tags

The final group of tags, collected under the heading *Other*, contains
six tags used for various purposes:

-   The C tag is used for corrections which are necessitated by other
    corrections, but which do not reflect mistakes in the original text.

-   The Cit-FL tag is used for segments of foreign language which have
    not been corrected during normalization.

-   The Com! and OBS! tags are used for notes and comments - the Com!
    tag for comments intended for the future corpus user, and the OBS!
    tag for work notes on pending analyses meant for internal project
    use.

-   The Unid tag is used for "unidentified" corrections, i.e.
    corrections which are not covered by any of the correction
    categories defined in the taxonomy.

-   The X tag is used for unintelligible strings.

Four of these tags, namely Cit-FL, Com!, OBS! and X are available
already during the normalization process, and are normally inserted
already by the normalizer.

### 5.6.1 C-Consistency corrections

The C tag represents consistency corrections, a category which covers
necessary (follow-up) corrections in the normalized text that come as a
result of a previous correction, i.e. originally there was no mistake in
the segment, but due to an introduced correction in the neighboring
context, a correction is necessary in the segment. By using this tag we
indicate that the error was not made originally by the learner.

In some instances it may not be self-evident which one of two related
corrections that should be considered as necessitating the other, but by
marking one of them with C we avoid marking a single mistake in the
original text as two.

-   **Bostaden** min → Min **bostad**

    The shift of word order is marked as a word order correction (S-WO). The change from definite form (*bostaden*) to indefinite form (*bostad*) of the noun is made necessary because of the shift of word order, and is thus marked as a consistency correction (C).

-   Det ger en en positiv **energi därmed** kan man bli av med stress →
    Det ger en en positiv **energi . Därmed** kan man bli av med stress

    The insertion of the full stop is tagged as a punctuation correction (P-M). The capitalization of the following D is made necessary because of the insertion of the full stop, and is thus marked as a consistency correction (C).

-   **Min** bostanden ser ut som lilla centrum med vlere affere →
     **Mitt** bostadsområde ser ut som \...

    The change from *bostanden* to *bostadsområde* is marked as a lexical correction (L-W) and a morphological correction (M-Def). The gender change of the pronoun, from *min* (non-neuter) to *mitt* (neuter) is made necessary because of the change of word (from the non-neuter *bostad* to the neuter *bostadsområde*), and is thus marked as a consistency correction (C).

-   För det första **är** vi **går** skolan från dagsskolan till allika
    nivå för att vi hittar jobb sen tjänar vi lön → För det
    första **går** vi i skolan från förskolan till olika nivåer för att
    vi ska hitta ett jobb , sen får vi lön

    The removal of *är* is marked as S-R, while the movement of *går* to the finite verb position (where it replaces the likewise finite verb *är*) is tagged with C.

-   När jag kommer **första** i 2012 , jag bodde i en social lagenhet
    med 3 andra person → När jag **först** kom 2012 bodde jag i en
    kommunal lägenhet med 3 andra personer

    The link between *första* and *först* is tagged with S-Adj/adv (see this section) **and** with C, which indicates that the word order change is a consequence of the change from adjective to adverb. (An alternative normalization would be to keep the adjective form *första* and add the noun *gången*.)

-   Jag stoppade i lång tid att saga till mina vänner i D-hemland hur
    jag bo här , **vad** extra vi ha här , e.g. tvättstuga → Jag slutade
    för länge sen att säga till mina vänner i D-hemland hur jag bor här
    , **vilka** extra **saker** vi har här , t.ex. tvättstuga

    The addition of *saker* is tagged as S-M, and the correction of *vad* to *vilka* is tagged with C, since it is the congruence with *saker* which determines the choice of pronoun.

### 5.6.2 Cit-FL (cited foreign word judged acceptable in the normalization)

The Cit-FL tag is used for foreign (non-Swedish) words, phrases or text
segments, which have been kept by the normalizer since their usage has
been judged acceptable given the norms of the text type in question.
This may be the case for instance for explicitly marked citations or
intentional code switching appropriate for the genre. The Cit-FL tag is
thus used to mark words and text segments which have *not* been
corrected in the normalized version, but which nevertheless are not
passable as standard Swedish.

Note that the only requirement for applying this code is that the word
or text segment is recognizable as another language than Swedish, and
that the choice to use this other language is judged appropriate for the
genre and the text. No judgement or correction of the word or text
segment is made relative to the norms of the foreign language in
questions. For instance, spelling mistakes are left uncorrected.

The Cit-FL tag is usually added already during normalization.

*Judged as appropriate code switching*:

-   Badrum var **basic** men rent → Badrummet var **basic** men rent

-   gillar du **quiz** **nights**? → gillar du **quiz** **nights**?

*Clearly marked citation of Norwegian passage:*

-   I samma artikel skriver Bengt Östling om man läser några webbsidor
    där norska ungdomar debatterar , förstår man att diskussionen om den
    obligatoriska nynorskan är inflammerad . **\" Ett språk som holdes
    kunstig i live gjennom tvan og finansiering gjennom skatt , og sakte
    men sikkert dör ut ja . Det finns ikke vilje hos folk til å beholde
    nynorsk \"** , lyder det i ett debattinlägg . → I samma artikel
    skriver Bengt Östling att om man läser några webbsidor där norska
    ungdomar debatterar , förstår man att diskussionen om den
    obligatoriska nynorskan är inflammerad . **\" Ett språk som holdes
    kunstig i live gjennom tvan og finansiering gjennom skatt , og sakte
    men sikkert dör ut ja . Det finns ikke vilje hos folk til å beholde
    nynorsk \"** , låter det i ett debattinlägg .

**Discrimination issues**

-   See *[7.1](#71-non-swedish-words-and-sequences)* *Non-Swedish words and sequences*.

### 5.6.3 Com! (comments for the corpus users)

The Com! tag is connected to an *edge comment* field, which is open for
freely composed comments. It is available already during the
normalization process.

The Com! tag is used for comments on specific tokens or text sequences
which are relevant for future users of the corpus, and which are thus
meant to be kept in the published corpus. (Comments regarding the text
as a whole or recurring properties in the text may be added in the
Document comment field, see section [4.9](#49-document-comments).)

The Com! tag may for instance be used to mark text segments which are
copied from the task formulation. If a significant portion of the text
consists of copied text, this should preferably be indicated also in the
Document comment field, in addition to the edge comment field connected
to the Com! tag.

The Com! tag is also used when a string which in the transcribed
original includes a "\$" (representing an unreadable character) has been
assumed to be correct, and thus has not been annotated with a tag
representing any correction category. In such cases the comment
"Original assumed to be correct" is written in the edge comment field.
Cf. *[4.8](#48-annotation-of-strings-including-unreadable-signs-in-transcribed-texts)* *Annotation of strings including unreadable signs in
transcribed texts*.

### 5.6.4 OBS! (notes and pending analyses)

The OBS! tag is, like the Com! tag, connected to an edge comment field,
and is available already during the normalization process.

The OBS! tag is used to mark pending analyses to which the annotator
wants to return, remarks which the normalizer wishes to pass on to the
correction annotator, etc.

### 5.6.5 Unid (unidentified correction)

The Unid tag is used for any type of correction which cannot be covered
by any of the correction categories defined in the taxonomy.

**Lower priority than all other tags**

### 5.6.6 X (unintelligible string)

The X tag is used to mark unintelligible strings in the original text.
The tag is available and usually added already during the normalization
process. The marked original string may be left unchanged in the
normalized version, or the normalizer may replace it with some more or
less wild guess of the intended message.

The X tag may be used both in cases when there is no reasonable
interpretation of the string, and when there are several somewhat
reasonable interpretations, but none of these interpretations may be
settled as better than the other.

-   **En argumentera på är viktigt hur man bor är bor på en bra hem**

-   och vi har 3 rum it huset **dar rum** är meka bra liv med maen
    familija dar huset familjbostder och jag vill **sta** och jog kan
    ante skriv meka ord → och vi har 3 rum i huset . **dar rum** är mycket
    bra liv med min familj där i huset från Familjebostäder och jag
    vill **stanna** och jag kan inte skriva många ord

    The text from which this example is collected has some German or possibly Dutch traits, and a fairly resonable guess is that *dar rum* is meant to be *darum*. Another, less likely, possibility is that *dar rum* is intended to mean *där rum*, but that interpretation necessitates extensive changes in the rest of the text passage in order to create a syntactically functional string. By marking *dar rum* with X and keeping the rest of the sentence unchanged in the normalized text version, the normalization as a whole is better adjusted to the principle of *minimal change*.

    *Stanna* is a reasonable guess about the intention with *sta*, but not well founded enough for the correction to be marked as an orthographic correction. Many other interpretations are obviously also possible.

-   Jag bo i ett lägenhet med min sambo och våras **yng** dotter → Jag bor
    i en lägenhet med min sambo och vår **lilla** dotter

    While the string *yng* suggests that the intended word might be *yngsta*, the rest of the text makes *lilla* appear more likely.

**Discrimination issues**

-   See *[6.16](#616-s-ext-vs-x)* *S-Ext vs X*.


# 6. Discriminating between specific correction categories

## 6.1 O vs punctuation tags


The removal, addition or change of token-internal punctuation is in some
instances tagged as O, and in some instances tagged with the suitable
punctuation tag.

-   Removal or addition of periods from abbreviations is tagged O:

    -   **t.v.** → **tv**

    (*tv* is used as for *television*, not *tills vidare*)

-   Additions of colons between abbreviations (etc.) and suffixes are
    tagged O:

    -   **vdar → vd:ar**

-   Change of punctuation in tokens mainly consisting of numbers is
    generally tagged with the suitable punctuation tag:

    -   Forskning och framsteg **2009.2** → Forskning och framsteg
        **2009:2** (P-W)

    -   **5.5** procent → **5,5** procent (P-W)

Cf. also *[7.4](#74-spaces-hyphens-and-dashes)* *Spaces, hyphens and dashes*.

## 6.2 O-Comp vs S-Comp


Corrections concerning the forming of an expression as a compound or a
multi-word expression are divided into two categories in the SweLL
correction taxonomy: Corrections which are judged to concern the mere
orthographic rendering with or without a space between two words are
marked with the O-Comp tag, while corrections which are judged to
concern the actual choice between a compound and a multi-word expression
are marked with the S-Comp tag. Borderline or unclear cases between
these two categories obviously exist, but for the most part one of the
options is clearly the better one.

The **O-Comp** tag is primarily used for corrections of standard cases
of *särskrivning* (the faulty writing of a compound with a space in
between the two compounded words):

-   Det ligger ett **kultur hus** nära min bostad → **kulturhus**

It may also be used for corrections which involve changing the first
word of the compound into a specific compound form, in addition to the
removal of the space between the two words. In such cases, the
correction is marked with both the O-Comp tag and the L-Der tag:

-   **Kommunikation förändring** → **Kommunikationsförändring**

More rarely, the O-Comp tag may be applied when a multi-word expression
in the original text has been corrected through the adding of a space
between two of the words:

-   **engång** → **en gång**

The **S-Comp** tag is used whenever the correction is more complex than
the mere addition or removal of a space between two words (and possibly
changing the form of the first word of a compound).

-   **det vardagliga livet** → **vardagslivet**

-   **livsskillnaden** → **skillnaden i liv**

-   **svenska undervisningar** → **svenskundervisning**

-   Enligt Hyltenstam så kan minoritetsspråk räddas om
    man **inblandar** dem äldre som kan språket → Enligt Hyltenstam så kan
    minoritetsspråk räddas om man **blandar in** de äldre som kan
    språket

However, in some cases the S-Comp tag is more suitable than the O-Comp
tag, although the correction superficially merely involves the presence
of a space. This is the case when two words may be correctly formed as a
compound (without a space) *and* as a two-word expression (with a
space), and the meaning of the compound version and the two-word version
are either the same or else both plausible in the context. The
correction made is thus not due to the chosen expression being
unthinkable, but due to the other expressions happening to be the
established lexical unit:

-   Om det händer att det finns planhalvor så kan det bero på blyghet,
    osäkerhet, rädsla eller **socialfobi** → **social fobi**

In this case, *socialfobi* is a perfectly well formed compound, but it
is corrected to the two-word expression *social fobi* because this is
the established way to express the intended meaning. The mistake made by
the writer is therefore not judged to be a case of having missed a space
in between two words in a two-word expression, but it is judged to be a
case of the writer actually having chosen the compound expression
instead of the established two-word expression. The correction is thus
marked with the S-Comp tag.

Moreover, in some cases the S-Comp tag may be applied although neither
the original nor the normalized string is a single orthographic word.
This includes cases when the string in the original text may be
interpreted as an instance of a compound, although it includes spaces:

-   Hejdlös **sociala medier användning** orsakar ensamhet →
    Hejdlös **användning av sociala medier** orsakar ensamhet

In this particular case, the string in the original text may be
interpreted as a compound between a two-word phrase (*sociala medier*)
and the word *användning*. According to the norms of written standard
Swedish, such compounds should be written as *sociala
medier-användning* etc. While such a minimal correction is not an
unthinkable solution for the normalization, the normalizer has here
judged a restructuring of the NP as a better solution, and the
correction should be tagged S-Comp.

## 6.3 L-Der vs L-W


When the stem of a one-word unit is completely exchanged or
morphologically restructured, the correction is tagged either with L-Der
or with L-W. (Changes of non-Swedish words to Swedish words are
excepted, these are tagged L-FL, see *[7.1](#71-non-swedish-words-and-sequences)* *Non-Swedish words and
sequences*.)

The following general rule determines which of the L-Der and L-W tags
that should be chosen:

-   If the root morpheme(s) of the category-defining part of the stem is
    kept, the L-Der tag should be chosen. If not, the L-W tag should be
    chosen.

This general rule implies the following:

1.  The word is completely exchanged (no common morphemes) → **L-W**

    -   *transformerade → förändrade*

2.  Only derivational morphemes are corrected (added, removed or
    exchanged) → **L-Der**

    -   *stressiga → stressade*

    -   *ändring → förändring*

    -   *förstöra → störa*

3.  Corrections of the first word of a compound → **L-Der**

    a.  The form of the first word of a compound is corrected → **L-Der**

    -   ***tvångsvenska** → **tvångssvenska***

    -   ***sagabok** → **sagobok***

    b.  The first word of a compound is exchanged → **L-Der**

    -   ***dagsskolan**  → **förskolan***

    -   ***människogrupper → folkgrupper***

4.  Corrections of the second word of a compound

    a.  The second word of a compound is completely exchanged (no common
        morphemes) → **L-W**

    -   *vårsemestern → vårterminen*

    b.  The second word of a compound is changed in a way which also
        involves root morphemes (additions, removals, exchanges) → **L-W**

    -   ***maktfull** → **maktfullkomlig***

    c.  The second word of a compound is changed with regard to
        derivational morphemes (additions, removals, exchanges), but the
        root is kept → **L-Der**

    -   ***nybyggnad** → **nybyggd***

5.  An additional word is added to the word in the original text,
    forming a compound out of a simplex, or a longer compound out of a
    shorter one

    a.  A word is added *before* the original word, forming a compound
        in which the second, i.e. the category-defining, word in the
        normalized version is identical to the word in the original
        version → **L-Der**

    -   *ställning → inställning*

    b.  A word is added *after* the original word, forming a compound in
        which the second, i.e. the category-defining, word in the
        normalized version is *another* than the word in the original
        version → **L-W**

    -   *historian* → *historieskrivningen*

6.  A part of a compound is removed, forming a simplex or a shorter
    compound

    a.  The last, category-defining, part of the compound is kept →
        **L-Der**

    -   *orsaksföljden* → *följden*

    b.  The last, category-defining, part of the compound is removed →
        **L-W**

    -   *fikatid* → *fikat*

    -   *semesterdag* → *semester*

**Note**: Changes from *båda* to *både*, or the other way around, are
tagged as L-Der (and S-Type) rather than as L-W:

-   något ha en \" svart \" avställning **båda** i jobbet och från
    bostad → Någon har en \" svart \" inkomst **både** från jobbet och
    från bostaden

## 6.4 L-Der vs S-Comp

The L-Der tag is exclusively used for changes between *one-word units*
(not necessarily one-token units, since a word may be mistakenly written
as two tokens). Both the original unit and the normalized unit should
thus consist of just one word for the L-Der tag to be applicable.

When the same lexical morphemes are arranged as a multi-word unit in one
text version and as a single word unit in the other text version, the
S-Comp tag should be applied rather than the L-Der tag, even when
derivational morphemes are involved in the correction:

-   Cecila Christner skriver om hur det svenska språket i skolor blir
    kallad tvångsvenska **i samma tid** svenska har blivit **icke
    populärt** i Finland → Cecilia Christner skriver om hur det svenska
    språket i skolorna blir kallat tvångssvenska **samtidigt** som
    svenska har blivit **impopulärt** i Finland

## 6.5 L-W vs M-Case

When the form *dem* is changed to the form *de* used as a definite
article, the correction is tagged as L-W and S-Type, not as M-Case:

-   den obligatoriska svenskundervisningen i **dem** finska skolorna → den
    obligatoriska svenskundervisningen i **de** finska skolorna

## 6.6 L-W vs M-Verb

The L-W tag is normally used for complete exchanges of words (no root
morpheme kept, cf. *[6.3](#63-l-der-vs-l-w)* *L-Der vs L-W*). This includes most exchanges
of auxiliary verbs. Only when a *ha, skola* or *komma* auxiliary is
exchanged for another *ha, skola* or *komma* auxiliary is the M-Verb tag
used instead.

-   *Ha*, *skola* or *komma* auxiliary exchanged for another *ha*,
    *skola* or *komma* auxiliary, tagged M-Verb:

    -   Tyvärr **ska** jag inte komma på kursen → Tyvärr **kommer** jag
        inte **att** komma på kursen

-   Change between a *ha*, *skola* or *komma* auxiliary and another
    verb, tagged L-W:

    -   Jag tror att det **vill** bli bra → Jag tror att det **kommer**
        **att** bli bra

-   Change between other auxiliary verbs, tagged L-W:

    -   Det **måste** inte gå fel → Det **får** inte gå fel

## 6.7 L-W vs S-Clause

Word changes made to change a main clause to a subordinate clause or the
other way around are tagged S-Clause rather than L-W:

-   Jag är jättetrött **därför** sover jag inte på nätterna → Jag är
    jättetrött **eftersom** jag inte sover på nätterna

## 6.8 L-W vs S-Comp

Both the L-W tag and the S-Comp tag may be used for changes between a
one-word unit and a multi-word unit, and for changes between two
multi-word units.

The L-W tag may only be used when at least one lexical morpheme is
different between the two strings:

-   Finns många nya lagenheterna i dyrare delar i huvudstaden , men
    detta är **lång distans från räker nummer** . → Det finns många nya
    lägenheter i dyrare delar i huvudstaden , men detta är **långt ifrån
    tillräckligt** .

If both the original string and the normalized string contain the same
lexical morphemes but with another internal structure, the S-Comp tag
should be applied rather than the L-W tag:

-   **det vardagliga livet** → **vardagslivet**

## 6.9 S-Clause vs word order tags

There are three cases when a word order change should be tagged S-Clause
rather than with one of the word order tags (S-Adv, S-FinV or S-WO).
These three cases are described below.

**Case 1: A unit is moved because its syntactic function has been
changed**

When a phrase is moved because its syntactic function has changed, this
phrase should be tagged S-Clause, instead of a word order tag being
used. For instance, in the following example, the phrase *likheter och
skillnader* is moved relative to the finite verb *finns* because its
syntactic function has changed, which means that *likheter och
skillnader* should be tagged S-Clause rather than the finite verb being
tagged S-FinV:

-   För att sammanfatta och svara på frågan om **likheter och
    skillnader** finns mellan nynorskans ställning i Norge och svenkans
    ställning i Finland → För att sammanfatta och svara på frågan om
    **det** finns **likheter och skillnader** mellan nynorskans
    ställning i Norge och svenskans ställning i Finland

    The inserted expletive subject *det* is tagged S-Msubj. The movement of the phrase *likheter och skillnader* indicates its change of function from subject to *egentligt subjekt* 'object-positioned subject', and the link between this unit in the original text and the same unit in the normalized text is thus tagged S-Clause.

**Case 2: A unit has been moved as part of a change between a main
clause structure and a subordinate clause structure *which is also
indicated by other means***

When a clause is changed from a main clause to a subordinate clause, or
the other way around, the correction is tagged S-Clause.

Many S-Adv and S-FinV corrections concern changes between the word order
typical for main clauses (*fa-ordföljd* '*fa-*word order') and the word
order typical for subordinate clauses (*af-ordföljd* '*af-*word order').
However, Swedish allows some main clauses with *af-*word order and some
subordinate clauses with *fa-*word order. Therefore, a word order change
of this type is not in itself considered to indicate a shift between a
main clause structure and a subordinate clause structure. Such a change
has to be indicated by the removal or the addition of a conjunction, the
change from a co-ordinating to a subordinating conjunction, or the like.

For mere word order changes between an *af-*word order and a *fa-*word
order, the S-Adv and S-FinV tags are used:

-   Jag är jättetrött eftersom jag sover **inte** på nätterna. → Jag är
    jättetrött eftersom jag **inte** sover på nätterna. (**S-Adv**)

-   Jag berättade vad **ville** jag helst göra → Jag berättade vad jag
    helst **ville** göra (**S-FinV**)

When a correction between a main clause structure and a subordinate
clause structure is indicated by a conjunction change/addition or the
like, but *also* involves a word order change, the word order change is
treated as involved in or a consequence of the change of clause
structure:

-   där berättare Matts Lindqvist hatet som finns mot finlandssvenska
    eller svenska språket är **inte** resultat av partiet
    Sannfinländarna → där berättar Matts Lindqvist om **att** hatet som
    finns mot finlandssvenska eller svenska språket **inte** är ett
    resultat av partiet Sannfinländarna

    The addition of *att* is tagged with S-Clause, while the movement of the negation *inte* relative to the finite verb *är* is tagged with C rather than with S-Adv, since this word order change is a consequence of the change from a main clause structure to a subordinate clause structure.

-   Tråkigt att det är tyst och folk hälsar **knappt** på varandra i din
    område → Tråkigt **att** det är tyst och att folk **knappt** hälsar på
    varandra i ditt område

    This example is a parallel to the example above. The addition of *att* is tagged S-Clause and the movement of *knappt* is tagged C.

**Case 3: Change between an "ordinary" main clause structure and a
question structure**

-   Jag vill att vet vad är problemet som jag inte kan gå till kursen
    **det finns** ingen plats eller **ni har** stoppade den här kurs och
    ni ska inte har det igen → Jag vill veta vad det är för problem som
    gör att jag inte kan gå på kursen : **Finns det** ingen plats eller
    **har ni** stoppat den här kursen och ska inte ha den igen ?

    In this case, the changed placement of the finite verb relative to the subject is marked with an S-Clause tag on the finite verb instead of an S-FinV tag.

## 6.10 S-Clause vs S-Comp

The S-Comp tag is only used for restructuring of the same lexical
morphemes within the same phrase and without affecting the primary
syntactic function of the words/phrases involved.

In the following example the object predicative *som obligatorisk* in
the verb phrase is turned into the attribute *obligatorisk* in the
object NP, and the S-Clause tag is thus applied rather than the S-Comp
tag:

-   Hon skriver också om att ha svenska **som obligatorisk** i Finland
    visar att alla är ju finnar och att \" finlandssvenska \" är bara
    påhittat . → Hon skriver också om att **det att** ha **obligatorisk**
    svenska i Finland visar att alla är ju finnar och att \"
    finlandssvenska \" är bara påhittat .

## 6.11 S-Clause vs S-Ext

The distinction between S-Clause and S-Ext corrections is not clear cut,
and borderline cases exist.

The following correction has been tagged with S-Clause on each of the
added tokens (*där*, *man*, *kan*), but is to be considered a borderline
case for an S-Ext classification:

-   Du kan vila på skogen där och finns bad simma → Du kan vila i skogen
    där och det finns bad **där man kan** simma (G54GT3)

This corrections involves:

-   a creation of a clause by adding both a subject and a finite verb

-   a creation of a relationship between the created clause and the rest
    of the sentence, by adding the adverb *där*, thus making the created
    clause into a subordinate clause

The clause which is created in the normalized version is suggested in
the original version only by the infinitive *simma*, and the
relationship between the main clause and the created clause is
completely implicit in the original version. This lack of support for a
specific syntactic organization of the normalized interpretation speaks
in favor of an S-Ext classification of the correction. On the other
hand, the additions in the normalized version are not that semantically
specific or syntactically complex, and both the clause creation (the
addition of the subject and the finite verb) and the creation of a
subordination relationship (the addition of the adverb *där*) are in
themselves standard examples of S-Clause corrections, which speaks in
favor of an S-Clause classification.

## 6.12 S-Clause vs S-M

Additions of *subjunktioner* ('subordinating conjunctions') and other
*bisatsinledare* ('subordinating connectors') are tagged S-Clause rather
than S-M. The additions may indicate a change from a main clause
structure to a subordinate clause structure, or specify an otherwise
unspecified relationship between the clauses in the original version:

-   Sådana känslor gör användaren mår dåligt → Sådana känslor
    gör **att** användaren mår dåligt

-   Man kan promonera lång tid finns det blåser → Man kan promenera länge
    **när** det blåser

-   Konsekvenserna man skulle få ifall undervisning i svenska blev
    frivillig så skulle mer än hälften av finska befolkningen avskaffa
    svenskan som modersmålsundervisning och istället fokusera på finska
    då dem sällan använder svenskan → Konsekvenserna man skulle få ifall
    undervisning i svenska blev frivilligt är **att** då skulle mer än
    hälften av den finska befolkningen välja bort svenskan som
    modersmålsundervisning och istället fokusera på finska då de sällan
    använder svenskan (Cf. this example under *S-Clause*.)

-   I samma artikel skriver Bengt Östling om man läser några webbsidor
    där norska ungdomar debatterar, förstår man att diskussionen om den
    obligatoriska nynorskan är inflammerad → I samma artikel skriver Bengt
    Östling **att** om man läser några webbsidor där norska ungdomar
    debatterar, förstår man att diskussionen om den obligatoriska
    nynorskan är inflammerad

See also *[7.3](#73-clause-corrected-or-created)* *Clause corrected or created?*

## 6.13 S-Clause vs S-Msubj

When *det* is added as subject to a clause, *det* should be tagged
S-Msubj even in those cases when the original clause already contains a
subject. This means that the S-Msubj should be used *instead of* or, in
some instances, *in addition to* the S-Clause tag in these cases.

The S-Clause tag is otherwise used for changes of the primary syntactic
function of a word in a clause, e.g. changing the function of the
original subject. Instances of adding a *det* subject are thus treated
as a special case, in order to have all additions of *det* subjects
tagged with the same tag - S-Msubj.

*Examples*:

-   *du* blir bättre → **det** blir bättre *för dig*

    A link is created between *du* and *för dig*. This link is tagged S-Clause. The inserted *det* subject is tagged S-Msubj. (See the same example under *5.5.2* *S-Clause (basic clause structure)*.)

-   på andra sidan finns ***människor som har så mycket pengar att de
    kan köpa halva världen***  → Å andra sidan finns **det *människor som
    har så mycket pengar att de kan köpa halva världen***

    *Det* is tagged with S-Msubj. In this particular example, no additional visible correction (besides the insertion of *det*) corresponding to the change of the original subject to an *egentligt subjekt* ('object-positioned subject') is made, and this correction is therefore not tagged at all (cf. *[4.3](#43-only-visible-corrections-are-tagged)* *Only visible corrections are tagged*.).

-   För att sammanfatta och svara på frågan om **likheter och
    skillnader** finns mellan nynorskans ställning i Norge och svenkans
    ställning i Finland → För att sammanfatta och svara på frågan om
    **det** finns **likheter och skillnader** mellan nynorskans
    ställning i Norge och svenskans ställning i Finland

    The inserted expletive subject *det* is tagged S-Msubj. The movement of the phrase *likheter och skillnader* indicates its change of function from subject to *egentligt subjekt* 'object-positioned subject', and the link between this unit in the original text and the same unit in the normalized text is thus tagged S-Clause. (Cf. *[6.9](#69-s-clause-vs-word-order-tags)* *S-Clause vs word order tags*.)

Additional examples are given under *5.5.7* *S-Msubj (subject missing)*.

**Note**: The S-Msubj tag should only be applied in those cases when the
clause is already present in the original text. When a subject has been
added as part of a correction involving the creation of a clause which
was not present in the original text, the subject should be tagged as
S-Clause, just as the rest of the added or changed elements involved in
the creation of the clause. See *[7.3](#73-clause-corrected-or-created)* *Clause corrected or created?*

## 6.14 S-Clause vs S-R

Restructuring of phrases and clauses which involve the removal of a
clause should be tagged with S-Clause rather than S-R, for instance:

-   The structure of a noun phrase is changed by changing an attribute
    in the form of a relative clause to an attribute in the form of a
    PP:

    -   och han tycker att misstänksamheten mellan **grupperna <u>som befinner sig i</u> södra Finland** lyser med sin frånvaro → och han tycker att den misstänksamhet som finns mellan **grupperna i södra Finland** lyser med sin frånvaro

        The underlined string, which is removed in the normalized version, is tagged S-Clause (the link runs between the string in the original version and "nothing").

    -   man kan betala **hela avgift <u>kommer från</u> en lagenhet** → 
    man kan betala **hela avgiften <u>för</u> en lägenhet**

        The underlined strings are linked and the link is marked with S-Clause.

The removal of a *subjunktion* 'subordinate conjunction' or another
*bisatsinledare* ('subordinating connector'), indicating the shift from
a subordinate clause structure to a main clause structure, should also
be tagged S-Clause rather than S-R:

-   **Om** du skapar något för att inte känner dig ensam → Du kan göra
    något för att inte känna dig ensam

## 6.15 S-Ext vs S-M

The distinction between S-Ext and S-M is not clear cut, and borderline
cases exist. When the added words may be seen as a correction of a goal
structure which is fairly clearly aimed at in the original text, the S-M
tag should be used. But when the added words are rather a creation of a
structure, the S-Ext tag should be used.

The following examples are borderline cases between S-Ext and S-M
corrections, which have been tagged as S-Ext:

-   att ta det lugnt och njuta av livet och allt som sker i de, inte
    bara pengarna → att ta det lugnt och njuta av livet och allt som sker
    i det, inte bara **tänka på** pengar

    In this case, the added verb becomes the main word in the infinitive phrase of the normalized text, which speaks in favor of considering the structure created rather than corrected.

-   Riad skriver om ett positiv framtid för svenska i Finland på allt
    folk har gemensamt kulturell → Riad skriver om en positiv framtid för
    svenskan i Finland **med tanke** på allt folk har gemensamt
    kulturellt

The following example has however been tagged as S-M, since the added
words are a repetition of the words in the preceding clause, and thus
not subject to interpretation to the same extent as in the examples
above:

-   I Finland och i Norge ungdommar har känslan att de blir tvingat att
    lära ett språk som majoritet av dem ville inte för att språket inte
    längre har eller aldrig har haft ett stort betydelse i samhället I
    Finland och i Norge har ungdomar känslan att de blir tvingade att
    lära sig ett språk som majoriteten av dem inte vill **lära sig** för
    att språket inte längre har eller aldrig har haft en stor betydelse
    i samhället

## 6.16 S-Ext vs X

The S-Ext tag should only be applied in cases when a correction has
actually been made, and when the original text gives fairly sound
support for the interpretation presented in the normalized version. Text
segments which are so difficult to interpret that they are either left
unchanged or normalized on the basis of guesses rather than
interpretations should be tagged with X.

Drawing the line between unintelligible text segments (X) and text
segments with a very fuzzy but still interpretable structure (S-Ext) is
not easy and in many cases a matter of subjective judgement. The
following example represents a borderline case between an X case and an
S-Ext case:

-   Det är lite bättre i huvudstad , när många manniskor bo tilsammans
    eftersom **de kan e betala för**  → Det är lite bättre i huvudstaden ,
    när många människor bor tillsammans eftersom **det gör att de kan
    betala**

The choice to categorize this correction as S-Ext - i.e. as an
interpretation with sound support from the original string - rather
than as an X case - i.e. as a mere guess - is not self-evident.

## 6.17 S-Type vs S-M and S-R

Quite often, the addition or removal of a word also means that the
syntactic category of a phrase is changed. For instance, the addition of
a preposition may turn an NP to a PP, and the removal of a preposition
may result in the opposite transformation. This calls for a
clarification of when to use the S-M and S-R tags and when to use the
S-Type tag.

Whenever the syntactic category of a phrase is changed *only* by the
addition or removal of one or more words, the S-M and S-R tags should be
used rather than the S-Type tag:

-   jag bor in lägenhet plan ett → Jag bor i en lägenhet **på** plan ett
    (**S-M**)

-   Bostad i D-hemland är litet het topik **för** att diskussera →
    Bostäder i D-hemland är ett lite hett ämne att diskutera (**S-R)**

However, when the syntactic category of a phrase involves an addition or
a removal of a word *on top of another correction*, the correction as a
whole (including the addition/removal) is tagged S-Type:

-   jag behover pengar f\$r **liv** och **betalning av** min hus → jag
    behöver pengar för **att leva** och **betala** för mitt hus

    *att leva* in the normalized text is grouped as one unit linked with *liv* in the original text, and the link is exclusively tagged with S-Type.


# 7. Other categorization issues

## 7.1 Non-Swedish words and sequences

There are a number of ways to handle non-Swedish words during
normalization and correction annotation. Many of the fundamental choices
are made during the normalization process rather than during the
correction annotation process.

The first judgement to be made when coming across a word stemming from
another language in the material is naturally whether the word may be
recognized as having been incorporated into written standard Swedish; in
such cases the word is left uncorrected and untagged. This judgement is
made during normalization.

When a word (or sequence) in an original text is recognized as belonging
to a foreign language - or as having traits from a foreign language --
and when this word may *not* be recognized as part of written standard
Swedish, a number of options are at hand:

1.  The word/sequence is judged as a genre appropriate usage of cited
    foreign language (explicitly signaled citations, code switching
    etc.). → Not corrected, tagged Cit-FL during normalization.

2.  The word is not judged as a genre appropriate usage of cited foreign
    language and is thus corrected to a Swedish word during
    normalization:

    a.  The form used may be interpreted as a misspelled Swedish word. →
        Corrected during normalization, tagged O during correction
        annotation: **kaffee** → **kaffe**; **can** → **kan**

    b.  The form used may be interpreted as a Swedish word with an
        incorrect usage of derivational affixes etc. → Corrected during
        normalization, tagged L-Der during correction
        annotation: **national → helgdag**  **nationell → helgdag**

    c.  Neither a nor b applies. → Corrected during normalization, tagged
        L-FL during correction
        annotation: **balkony**  → **balkong**; **family** → **familj**; **gas
        bojler** → **gaskokare**

**Note**: A word in the original text which is identifiable as a Swedish
word, but which is used with another meaning in a way which is likely to
be due to influence from a similar non-Swedish word, should be corrected
and marked as L-W (not as L-FL):

-   Alla blir **busiga** med sina sociala medier. → Alla
    blir **upptagna** med sina sociala medier

In this example, it is likely that the incorrect usage of the correct
Swedish word *busiga* is influenced by the word's similarity to the
English word *busy* - and it is partly based on this assumption that
the writer's intended meaning has been interpreted as \'upptagna\'. But
since *busiga* is a correct Swedish word, with a distinctly Swedish
morphological structure, the correction is tagged as L-W rather than as
L-FL.

## 7.2 Verbal particles and reflexives

Several tags are used for corrections involving phrasal or compound
verbs made up by a verb and verbal particle or a reflexive marker,
primarily O-Comp, S-Comp, L-Der, L-W, S-M and S-R. This section provides
an overview of the usage of these six tags for this category of
corrections.

-   **O-Comp**: A space is removed between a verbal particle and a
    following verb, making up a compound verb:

    -   **upp mana** → **uppmana**

-   **S-Comp**: A compound form of a particle verb is changed to a
    phrasal form, or the other way around:

    -   Enligt Hyltenstam så kan minoritetsspråk räddas om
        man **inblandar** dem äldre som kan språket → Enligt Hyltenstam så
        kan minoritetsspråk räddas om man **blandar in** de äldre som
        kan språket

    -   Tåget **går av** från spår 3 → Tåget **avgår** från spår 3

-   **L-Der**: A particle of a compound particle verb is changed,
    removed or added. Both the original and the normalized string
    consist of one single token. The original string may or may not be
    an existing Swedish word.

    -   Internet **uppmanar** vår förståelse → Internet **utmanar** vår
        förståelse

    -   Han **inhämtade** väskorna från hotellrummet →
        Han **hämtade** väskorna från hotellrummet

    -   Hon **minde** honom om mötet på eftermiddagen →
        Hon **påminde** honom om mötet på eftermiddagen

-   **L-W, placed on the whole phrasal verb**: Either the original
    string or the normalized string (or both) is a phrasal verb, and the
    verb itself is changed, not just the particle/reflexive marker:

    -   Traditioner ger människorna tid att **stå still** och fundera
        över livet → ... att **stanna upp** och fundera över livet.

-   **L-W, placed on the particle**: A verbal particle is replaced by
    another verbal particle, but the verb is kept:

    -   Han torkade **bort** bordet → Han torkade **av** bordet

-   **S-M**: An independent (non-compound) verbal particle or a
    reflexive marker is added:

    -   men känner bara fysiskt närvarande → men känner **sig** bara
        fysiskt närvarande

    -   Jag slår ord i ordboken när jag inte vet → Jag slår **upp** ord i
        ordboken när jag inte vet\...

-   **S-R**: An independent (non-compound) verbal particle or a
    reflexive is removed.

    -   De promenerade **sig** i parken → De promenerade i parken

    -   Hon gav **bort** honom en blomma → Hon gav honom en blomma

# 7.3 Clause corrected or created?

In some cases, the choice of tag is dependent on whether a clause in the
normalized version is present already in the original version or has
been created as part of the normalization.

When a clause is *created in the normalization*, the following applies:

-   Subjects which are added as part of the creation of that clause are
    tagged S-Clause rather than S-Msubj.

-   Finite verbs which are added as part of the creation of that clause
    are tagged S-Clause rather than S-M or M-Verb.

-   Non-finite forms of verbs which are changed to finite forms are
    tagged S-Clause rather than M-Verb.

A clause is considered *created in the normalization* in the two
following cases:

1.  Both the subject and the finite verb of the normalized clause are
    lacking in the original version. (A non-finite verb may be present.)

    -   Jag studerar på eftermiddag Sfi och förmiddag praktik → Jag
        studerar sfi på eftermiddagen och på förmiddagen
        **har** **jag** praktik

        Both *har* and *jag* are tagged as S-Clause, not as S-M and S-Msubj respectively.

-   **Att växa** upp som en flicka så var det väldigt många orättvisor
    man fick vänja sig vid. → **När man växte** upp som en flicka så var
    det väldigt många orättvisor man fick vänja sig vid.

    *Att växa* and *när man växte* are grouped together, and the link between these two group units is tagged S-Clause; no additional tagging is made. Thus, *man* is not tagged S-Msubj, and the change of the infinite verb form *växa* to the finite form *växte* is not tagged M-Verb.

-   **min plats** → **platsen där jag bor**

    *min plats* and *platsen där jag bor* are grouped together, and the link between these two group units is tagged S-Clause; no additional tagging is made. Thus, *jag* is not tagged S-Msubj and and *bor* is not tagged S-M.

-   Dem som tycker att avskaffa den obligatoriska svenskan i skolan i
    Finland är Tuija Nikko och Maria Tolppanen → De som tycker att **man
    ska** avskaffa den obligatoriska svenskan i skolan i Finland är
    Tuija Nikko och Maria Tolppanen

    Both *man* and *ska* are tagged as S-Clause, not as S-Msubj and S-M respectively.

2.  The subject of the normalized clause exists already in the original
    text, but *no verb at all* (finite or infinite) corresponding to or
    part of the VP of the normalized clause is present in the original
    version.

    -   Hon fördelen med att behålla den obligatoriska svenskan →       Hon **beskriver** fördelen med att behålla den obligatoriska svenskan.

        The added finite verb *beskriver* is tagged as S-Clause rather than as S-M.

A clause is considered *corrected* rather than created when none of
these two conditions hold, and the tags S-Msubj, S-M and M-Verb are
applied rather than S-Clause.

-   Jag gillar inte tapeterna i min kusins lägenhet men han inte byta
    dem eftersom det är hyresrätt → \... han **kan** inte byta dem \...

    Here, the added finite verb *kan* is tagged as S-M rather than as S-Clause, since both the subject (*han*) and a non-finite verb (*byta*) is present already in the original version.

## 7.4 Spaces, hyphens and dashes

Only some errors involving spaces, hyphens and dashes are corrected, and
not all of the corrected errors are tagged.

-   The O-Comp tag is used for corrections which involve the removal of
    a space between two words which have been interpreted as making up a
    compound in the normalized text version, or, more rarely, the adding
    of a space between two words. It may also be used for corrections
    regarding the use of hyphens in compounds.

-   The P-R tag is used for removals of hyphens used in other ways, and
    for removals of dashes.

-   The P-M tag is used for added dashes.

-   The P-W tag is used for changes between, on the one hand, a hyphen
    or a dash, and, on the other hand, another punctuation mark (not
    including a space).

However:

-   Instances where a hyphen has been used in the original text where a
    dash would be more appropriate are left uncorrected and should thus
    not appear as corrections to be annotated.

-   Possible errors involving the incorrect placement of *a space before
    a punctuation mark* will not be corrected in the normalization
    process, since spaces are always inserted before punctuation marks
    for the sake of tokenization. Consequently, such errors will not be
    tagged.

-   Possible errors involving the lack of *a space between a punctuation
    mark and the following word* are corrected in the normalization
    process (a space is inserted), but are nevertheless left untagged.

    -   Jog kan ante skriv meka ord .tack → Jag kan inte skriva många ord.
        Tack.

        In this example, a space is inserted between the period and *tack*, and the t in *tack* is changed from lower to upper case. *Tack* will be tagged with O-Cap, but the insertion of the space will not be tagged.

## 7.5 Singular indefinite article removed from plural indefinite NP

When a singular indefinite article is removed from a plural indefinite
NP, the removed article should be tagged M-Num rather than M-Def or S-R;
such a correction concerns number rather than definiteness.

-   kanske där kan du träffa **en** nya vänner → kanske kan du träffa nya
    vänner där

## 7.6 Exceptions to the default ranking of the word order tags

**The three word order tags (S-Adv, S-FinV and S-WO) are in most cases
ranked in the following way:**

1.  **S-Adv**

2.  **S-FinV**

3.  **S-WO**

There are however two exceptions to this default ranking:

**Exception 1: Choose the word order tag which gives the least number of
tags**

When the choice of one word order tag means that one tag suffices, while
the choice of another word order tag requires an additional word order
tag, the single tag should always be chosen rather than the multiple
tags, regardless of the ranking presented above.

*Examples*:

-   Jag berättade vad **ville** jag helst göra → Jag berättade vad jag
    helst **ville** göra

    This correction involves the movement of the finite verb *ville* relative to both the subject *jag* and the adverbial *helst*. The word order tag should be placed on the finite verb, and the S-FinV tag should be chosen. (If the S-Adv tag had been used for the movement of *helst*, an additional S-WO tag would have had to be placed on the subject *jag*.)

-   Jag berättade vad helst ville **jag** göra → Jag berättade vad **jag**
    helst ville göra

    This correction involves the movement of the subject *jag* relative to both the adverbial *inte* and the finite verb *ville*. The word order tag should be placed on the subject, and the S-WO tag should be chosen. (Otherwise both the S-Adv tag and the S-FinV tag would have had to be used.)

**Exception 2: Word order changes which are due to a change of
*fundament* ('pre-finite element') are tagged S-WO**

In some (rare) cases the word order of a clause has been changed not for
the sake of clause-internal correctness, but because the textual flow
demands it. This is then generally done by changing the element in the
*fundament* 'pre-finite position' of the clause. Such corrections are
tagged with S-WO rather than with S-FinV or S-Adv, regardless of the
function of the moved elements. The finite verb should not be marked
with a word order tag as long as this is correctly positioned in the
original clause.

*Example*:

-   **Med min familj** bor **jag** → **Jag** bor **med min familj**

    Here, the subject *jag* has replaced the adverbial *med min familj* in the *fundament* 'pre-finite position' in the normalized version. Superficially, this means that *jag* and *med min familj* have switched places. Both these elements are tagged with S-WO. The finite verb *bor* should not be tagged with a word order tag since it is correctly placed in the original version.
