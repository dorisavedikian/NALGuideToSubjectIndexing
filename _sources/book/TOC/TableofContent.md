---
jupytext:
  text_representation:
    extension: .md
    format_name: myst
    format_version: 0.13
    jupytext_version: 1.11.5
kernelspec:
  display_name: Python 3
  language: python
  name: python3
---

# Table of Contents

```{contents}
:local:
```

## Basic Indexing Guidelines

1.)	Determine what you are indexing (*“indexing”* or *“annotating”*) based on the title, journal name and abstract (*“article”*). 

2.)	The NAL thesaurus (*“NALT”*) is the sole source for annotations, with concepts being added, modified, defined, redefined and deprecated, as needed. 

3.)	All articles must have at least three concepts to be processed. While there is no upper limit, that does not mean that every possible concept must be added. 

4.)	Look for the “magic sentence” when the author(s) (*“author”*) starts talking about what they are doing and/or will be describing in the article. Do not index what has been done in the past, will be done in the future or is mentioned as background information or speculation. 

5.)	Be aware that similar phrases or related concepts/terms (*“RTs”*) have different meanings and hierarchies. Review definitions, scope notes, Broader Concepts/Terms (*“BTs”*), Narrower Concepts/Terms (*“NTs”*), and Entry-Level (or hidden/alternate) Terms to ensure that you are selecting the appropriate concept(s). 

6.)	Do not fixate on a term. Do not add concepts merely because they are in the title, journal name and/or article. Determine whether the concept is relevant to the article and is the best term to cover what the author is discussing or doing. 

7.)	The broadest, top-level concepts should not be used if narrower concepts are applicable and/or there are more than three concepts. 

8.)	Use the narrowest concept possible but only if it describes the entire article and does not omit equal concept(s) not captured by a *NALT* concept. 

9.)	Review annotated concepts to determine if all are necessary or better ones come to mind. 

## The Agricola Database

AGRICOLA (AGRICultural OnLine Access) is a bibliographic database of over 5 million citations to the agricultural literature, created by the National Agricultural Library (NAL) and its cooperators.  Previous versions of the indexing guidelines contain the history of Agricola, NAL Thesaurus (NALT) and past indexing practices – see the bibliography for those.

The goal of indexing articles for Agricola is to capture information related to agriculture and USDA topic areas (see https://www.usda.gov/topics for more information). 

Articles included in Agricola have been published in peer-reviewed journals and ideally are authored by individuals from one of the following categories:
* [USDA and its agencies, centers and research programs](https://www.usda.gov/our-agency/agencies)
* Other related government and non-government departments, agencies and organizations (e.g., Food & Drug Administration (FDA), US Agency for International Development (US AID), state and local agricultural agencies, Center for Produce Safety and National Dairy Council)
* International, foreign and non-governmental organizations (e.g., UN Food and Agriculture Organization (FAO), European Food Safety Authority, Ontario Ministry of Agriculture, Food and Rural Affairs and World Organization for Animal Health)
* Universities and research institutions 

> See [Supplement A](SupplementA) for types of articles not typically indexed for Agricola. 


## MARC Format

MARC (MAchine-Readable Cataloging) is used to define three fields that appear in Agricola records; a fourth field for subject category codes is no longer used. While MARC fields may appear on some external platforms, they are largely transparent in the indexing process. NAL systems that manage both human-indexed and machine-indexed articles automatically assign the appropriate field for each term.    

> __650__  NALT terms 

> __651__  Geographical terms 

> __653__ Identifiers (this field is limited to machine-indexed articles and is automatically populated by the system, as needed)


## The NAL Thesaurus (NALT)

The [***NALT***](https://agclass.nal.usda.gov/) is the controlled vocabulary and sole source of terms/concepts for indexing articles. These terms can be organisms (taxonomic or common names), products, phenomena, particular objectives or perspectives, facilities, activities, operations, equipment, processes, techniques, geographic names, environmental conditions and the elements that affects any of these. 
 
 ```{margin} *NALT Core* 
 (subscheme with 13,791 frequently-used concepts including 4,396 agriculturally important organisms (taxa), and structural updates)
```
 ```{margin} *NALT Full*
(*NALT Core* plus 48,000+ additional agricultural related organisms and several thousand less-frequently used concepts for a total of 76,933 concepts)
```
There are two options, ***NALT Core*** and ***NALT Full***.

When considering proposal of a new term, always ask:
* Will this term be used often enough to justify its addition to NALT?
* Does this term represent a concept which can be consistently and reliability differentiated from any other concept?

### _Proposing a new term:_
*	Consult relevant, authoritative resources (e.g., AGROVOC, CAB thesaurus) first when proposing a new term. Consider other specialized resources in (e.g., MESH, AlgaeBase), dictionaries, handbooks, monographs, textbooks and number of postings of the proposed concept in relevant databases. Do not use all-purpose dictionaries. See [Supplement B](SupplementB) for some additional resources.
+++
*	Changes include adding or deprecating (removing from preferred/accepted terminology) concepts, modifying hierarchies and adding/amending definitions or scope notes. Justification and additional comments should be neutral and business-like. Recommend term during Golden Sets review (see [Work Flow](Workflow) below)
+++
*	If the proposed term is already included in another thesaurus, suggest the term as it appears in that thesaurus to maintain consistency. If the term is in several thesauri in different forms (e.g., hyphenation, capitalization), recommend the one that follows NALT naming convention (see below) with other forms included as entry-level terms.
+++
*	Follow conventions of capitalization used in NALT, i.e., capitalize formal names, geographical terms and acronyms, use lower case for non-specific places or things, etc.
    * Examples of capitalization: **USDA Forest Service, Mississippi Delta region, Internet of Things,** ***Daboia russelii,*** **DDT (pesticide), COVID-19 infection**
    * Examples of lower case: **forests, river deltas, information technology, reptiles, organochlorine pesticides, infectious diseases**
+++
*	Consider spelling variants, synonyms, and quasi-synonyms before proposing a new term.
    *	Example: For “Nutrient solution concentration and collection time in phytomass production, content, yield and chemical composition of essential oil of rosemary”{cite}`JoPN_2018`, NALT does not have a term to cover specifically “essential oil of rosemary”.  Consider proposing **rosemary oil** (CABI thesaurus term) as a preferred term, with **essential oil of rosemary, rosemary essential oil and Rosmarinus officinalis essential oil** (among others) as potential entry-level terms.
    *	Example: For “Effects of Coffee and Its Components on the Gastrointestinal Tract and the Brain–Gut Axis”{cite}`Nutrients_20`, *NALT* has __coffee (beverage)__ and __gastrointestinal system__ but not “brain-gut axis” or another term that covers that concept. Propose __brain-gut axis__ (existing MESH term, “interactive network between the gastrointestinal tract (gut) and the brain principally mediated through the enteric nervous system ...”) as the preferred term __with brain and gut axis, brain-gut-microbiome axis, gut and brain axis, gut-brain axis__ and other variations as entry-level terms.
+++
*	Terms should always be nouns, noun phrases (phrase formed by a noun and all its modifiers and determiners), or gerunds (a word that is derived from a verb but functions as a noun).
    *	nouns – __cattle, farms, hematophagy, loci__
    *	noun phrases – __antibrowning agents, artificial flavorings, old animals, red light__
    *	gerunds – __allografting, farrowing, milking, plowing__
+++
*	Exclude prepositions in noun phrases unless doing so violates accepted English usage or official naming convention, may be misleading in its connotation or could have an ambiguous meaning, or the proposal is already a standard, accepted term. 
    *	entry-level term __resistance to lodging__ -> preferred term __lodging resistance__
    *	entry-level term __alternatives to animal testing__ -> preferred term __animal use alternatives__ 
    *	preferred terms __appropriate level of protection, brain as food, fluorescence recovery after photobleaching__ and __Bay of Bengal__
+++
*	Adjectives are used only with nouns as part of noun phrases (see above), not as independent terms.
+++
*	Use the singular form for processes, properties, attributes and unique things. Use plural for classes of objects, e.g., common names for organisms, groups of things.
    *	singular – __brain, jasmone, food supply chain, subsurface drainage, yellow fever__
    *	plural – __animal organs, oxylipins, supply chain disruptions, drainage systems, Flavivirus infections__
+++
*	Use natural word order. If appropriate, propose the inverted form as an entry-level term.
    *	__agricultural development__, not __developing agriculture__ or __development of agriculture__
    *	__climate change__, not __changing climate__ 
    *	__food processing__, not __processing food__ or __processing of food__
+++
*	Avoid punctuation, including hyphens, if possible. Some exceptions include (but are not exclusively) taxonomic names, chemical compounds, scientific terms and accepted terms from other thesauri. 
    *	__1-aminocyclopropane-1-carboxylate deaminase__
    *	__3’ untranslated region__
    *	__blood-brain barrier__
    *	__Fusarium oxysporum f. sp. radicis-lycopersici__
    *	__public-private partnerships__
+++
*	Use scientific terminology rather than lay/colloquial terminology. 
    *	__neoplasms__, not cancer
    *	__renal calculi__, not kidney stones
    *	__tibia__, not shinbone

### _Creating hierarchy and relationships:_
*	Supply at least one BT (preferably an existing NALT term) for each proposed term. The relationship between a proposed term and its BT should be generic (i.e., the BT is a class of concepts of which the proposed term is a member or is a part/whole relationship). If the proposed term is already in another thesaurus, use that hierarchy if the same or similar terms are already in NALT.
    *	proposed term __rosemary oil__ – BT __essential oils__ (or other appropriate NALT term)
    *	proposed term __brain-gut axis__ – BT __neurophysiology__ (or other appropriate NALT term)
+++
*	Providing NTs and RTs is optional but these should be valid or proposed NALT terms. If the latter, submit the proposals concurrently and indicate this in the submission.
+++
*	A term is assumed to include any of its common definitions. Indicate if certain definitions are to be excluded from the scope of the term or if an uncommon definition will be used. 
    *	__mineralization__ (BT __chemical reactions__, breakdown of organic compounds to their inorganic (i.e., mineral) forms) versus __bone mineralization__ (BT __bone formation__)
    *	__phytotoxins__ (any toxins or poisons that are produced by a plant) versus __phytotoxicity__ (any substance that is toxic or poisonous to a plant). Some dictionaries and thesauri reverse the definitions or treat the two terms as synonyms of each other. 
+++
*	If the proposed term is the same or similar to a common word or name, add a qualifier to distinguish it from the common word. If uncertain, search the Internet for possible conflicts. 
    *	__Alabama (Lepidoptera)__ versus the state of __Alabama__ 
    *	__Alexa (Faboideae)__ versus the personal name “Alexa” or Amazon’s virtual assistant technology 
    *	__Damascus (goat breed)__ versus the capital of __Syria__
    *	__does (females)__ versus third person present form of the verb “do”
    *	__spat (shellfish)__ versus past participle of the verb “spit” 
+++
*	If a term has different meanings in different hierarchies, create separate terms with clarifying words, scope notes and/or definitions. 
    *	__fuels__ (BT __energy resources__) versus __fuels (fire ecology)__ (BT __fire ecology__)
    *	__fertilization (soils)__ (preferred term __fertilizer application__) versus __fertilization (reproduction)__
    *	__ponding (natural)__ (BT __hydrology__) versus __ponding (water management)__ (BT __water management__)
+++
*	Indicate the source of the term, definition, scope notes and/or hierarchy for follow-up. If possible, provide documentation (e.g., websites, governing authority) supporting the change. 

```{note}
Requests will be reviewed by the indexing team for validity and necessity during the Golden Sets review. Priority will be given to terms related to agriculture and/or USDA topic areas. Generally, annotations using stop words, consisting of full sentences, or highlighting single words to represent phrases will not be added as preferred or entry-level terms. 
```

(Workflow)=
## Work Flow

Due to changes in the system being used to process records for Agricola/PubAg, everyone on the indexing team receives the same projects with the same articles but no terms. 

Everyone annotates the appropriate terms highlighting a word or phrase in the abstract and selecting the corresponding *NALT* concept, focusing on quality control (see [Subject Analysis](SA)). 

After everyone has completed the same project, that project and the individually-annotated terms will be consolidated into a single “Golden Set” project for a final review by the indexing team, who will (as a group) accept, reject, add and/or modify concepts. Terms (and how they are annotated) will be accepted based on the best match to the *NALT* concept. Whenever possible, terms will be accepted using the same highlighted word or phrase across all or most abstracts. 

If necessary, the team also determines whether an article meets the criteria for inclusion in Agricola (see Supplement A) or should be rejected and deleted from the Golden Set. 

The team will also consider highlighted annotations that are not currently in *NALT* as preferred or entry-level terms for addition to *NALT*. Candidate terms will be added to the CSE Resources for that project and will be categorized as such but will not be used to annotate other articles. 

(SA)=
## Subject Analysis
### Methodology and Techniques
### Basics for Using Taxonomic Names
### Geographic Descriptors




## Other

```{note}
This is a note!
```

```{warning} This is an example
of a warning directive.
```

```{tip} This is an example
of a tip directive.
```

```{caution} This is an example
of a caution directive.
```

```{attention} This is an example
of an attention directive.
```

```{danger} This is an example
of a danger directive.
```

```{error} This is an example
of an error directive.
```

```{hint} This is an example
of a hint directive.
```

```{important} This is an example
of an important directive.
```