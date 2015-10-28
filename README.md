# UD_Norwegian

The Norwegian UD treebank is based on the Bokmål section of the Norwegian
Dependency Treebank (NDT), which is a syntactic treebank of Norwegian.
NDT was developed 2011-2014 at the National Library of Norway in collaboration
with the Text Laboratory and the Department of Informatics at the
University of Oslo. NDT has been automatically converted to the UD
scheme by Lilja Øvrelid at the University of Oslo.

NDT contains around 300,000 tokens taken from a variety of genres.
The treebank texts have been manually annotated for morphosyntactic
information. The morphological annotation mainly follows mainly
Oslo-Bergen Tagger (http://tekstlab.uio.no/obt-ny/).  The syntactic
annotation follows, to a large extent, the Norwegian Reference
Grammar, as well as a dependency annotation scheme formulated at the
outset of the annotation project and iteratively refined throughout
the construction of the treebank.  . For more information, see the
references below.

## DATA SPLITS

In creating the data splits, care has been taken to preserve
contiguous texts in the different splits and also to keep a fair
balance of genres in each of the splits. Petter Hohle created the
splits for the Norwegian UD treebank. The splits were created by
concatenating the following files (available with the distribution of
NDT):

Training data (15696 sentences, 180 individual files):

- ap001\_0000 -- ap012\_0002 (53 files)
- bt001\_0000 -- bt005\_0001 (28 files)
- db001a\_0000 -- db013\_0004 (42 files)
- kk001\_0000 -- kk005\_0001 (10 files)
- sp-bm001\_0000 -- sp-bm001\_0008 (9 files)
- vg001\_0000 -- vg002\_0003 (8 files)
- blogg-bm001\_0000 -- blogg-bm003\_0000 (9 files)
- nou001\_0000 -- nou004\_0000 (10 files)
- st001\_0000 -- st005\_0000 (11 files)

Development data (2410 sentences, 26 individual files):

- ap012\_0003 -- ap014\_0002 (7 files)
- bt005\_0002 -- bt005\_0005 (4 files)
- db013\_0005 -- db014\_0002 (5 files)
- kk006\_00001 -- kk007\_0000 (2 files)
- sp-bm002\_0000 -- sp-bm002\_0001 (2 files)
- vg002\_0004 (1 file)
- blogg-bm003\_0001 -- blogg-bm003\_0002 (2 files)
- nou004\_0001 (1 file)
- st005\_0001 -- st005\_0002 (2 files)

Test data (1939 sentences, 26 individual files):

- ap014\_0003 -- ap015\_0002 (7 files)
- bt005\_0006 -- bt006\_0001 (4 files)
- db014\_0003 -- db014\_0007 (5 files)
- kk007\_0001 -- kk008\_0000 (2 files)
- sp-bm003\_0000 -- sp-bm003\_0001 (2 files)
- vg002\_0005 (1 file)
- blogg-bm003\_0003 -- blogg-bm003\_0004 (2 files)
- nou004\_0002 (1 file)
- st005\_0003 -- st005\_0004 (2 files)


## BASIC STATISTICS

Tree count:  20045

Word count:  311277

Token count: 311277

Dep. relations: 35 of which 2 language specific

POS tags: 17

Category=value feature pairs: 31

# TOKENIZATION

# MORPHOLOGY

# SYNTAX

## REFERENCES

Solberg, P.E., Skjærholt, A., Øvrelid, L., Hagen, K. and Johannessen,
J.B. 2014."The Norwegian Dependency Treebank", Proceedings of LREC 2014,
Reykjavik


Documentation status: partial
Data source: automatic
Data available since: UD v1.2
License: CC BY-SA
Genre: news blog nonfiction 
