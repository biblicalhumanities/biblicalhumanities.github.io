---
layout: page
title: Dashboard
permalink: /dashboard/
---
This dashboard primarily lists data resources that are centrally important for digital biblical humanities and available now. Unless otherwise stated, they provide their data under open licenses. There are multiple versions of some of these resources, we attempt to point to the best authoritative source.  For Greek resources, [Perseus](https://opengreekandlatin.github.io/First1KGreek/) is well worth consulting as well.

If you believe a resource should be added to this page, please contact us (see the bottom of any page on this site for contact information).


### Base texts

- *Nestle 1904 Greek New Testament*
  - [Diego Santos](https://sites.google.com/site/nestle1904/faq) (.odt, .pdf): Text of the Nestle 1904 Greek New Testament. Used in morphologically tagged texts and treebanks listed below. This text is also available in a cleaner XML in the [Nestle1904](https://github.com/biblicalhumanities/Nestle1904) repository.
- *SBL Greek New Testament*
  - [SBLGNT](http://sblgnt.com/) (XML, OSIS, text, several other formats): High quality critical text created by Logos Software and the Society of Biblical Literature. Note the [license](http://sblgnt.com/license/), which imposes conditions on downstream works that use it.
- *Greek New Testament - Byzantine Text*
  - [ByzantineText.com](https://byzantinetext.com/study/editions/): Robinson-Pierpoint Byzantine text, a Majority Text (and other Greek texts).
- *Bunning Heuristic Prototype (BHP)*
  - [Bunning Heuristic Prototype](https://greekcntr.org/resources/), generated from early manuscripts algorithmically.  See [this documentation](https://greekcntr.org/resources/BHP_Introduction.pdf). [BHP data available at CNTR website](https://greekcntr.org/resources/BHP_Data.txt) or on [GitHub](https://github.com/greekcntr/BHP).
- *Codex Sinaiticus*
  - [Codex Sinaiticus](https://www.codexsinaiticus.org/en/): Codex Sinaiticus, presented on an impressive website that offers [downloads](https://codexsinaiticus.org/en/project/transcription_download.aspx) of their XML data.
- *Swete's Septuagint*
  - [OpenGreekAndLatin](https://github.com/OpenGreekAndLatin/septuagint-dev) Machine-corrected version of Swetes Septuagint.
- *Migne's Patrologia Graeca*
  - [OpenGreekAndLatin](https://github.com/OGL-PatrologiaGraecaDev)  Massive collection of Church Fathers. See description on [Wikipedia](https://en.wikipedia.org/wiki/Patrologia_Graeca).
- *Cramer's Catenae*
  - [OpenGreekAndLatin](https://github.com/OpenGreekAndLatin/catenae-dev) (XML): For each verse, lists any comments that the early Fathers made on that verse.
- *Sefaria*
  - [Sefaria](https://github.com/Sefaria/Sefaria-Export) (JSON): A wonderful collection of Jewish texts containing Tanakh, Commentaries (Rashi, Ibn Ezra, etc.), Midrash, Targums, Talmud, Kabbalah, a lexicon, and a Hebrew grammar.

### Textual Variants and Conjectural Emendations

- *CNTR Transcriptions*
  - [Center for New Testament Restoration](https://greekcntr.org/resources/) transcriptions of all textual variants before AD 400, done by Alan Bunning.  Also available as a web page: [Manuscripts](https://greekcntr.org/manuscripts/).
- *Amsterdam Database of New Testament Conjectural Emendation* 
  - [The Amsterdam Database of New Testament Conjectural Emendation](http://ntvmr.uni-muenster.de/nt-conjectures-attribution), data available [here](http://ntvmr.uni-muenster.de/community/vmr/api/projects/ntconjectures/admin/sql/scripts/).  Also available as a web page [here](http://ntvmr.uni-muenster.de/nt-conjectures).


### Morphologically Tagged Texts

In addition to texts mentioned below, check [Perseus](https://opengreekandlatin.github.io/First1KGreek/) for morphologically tagged texts.

- *Nestle 1904 Greek New Testament*
  - [biblicalhumanities](https://github.com/biblicalhumanities/Nestle1904) (CSV):  Nestle 1904, tagged using MorphGNT conventions.
- *SBLGNT Greek New Testament*
  - [MorphGNT](https://github.com/morphgnt/sblgnt) (Plain text in columns):  SBLGNT, done by MorphGNT, the first initiative to produce truly open high quality morphologies for the Greek New Testament.
- *Westcott-Hort*
  - [Westcott-Hort](http://scrolltag.com/westcott_and_hort.html): Westcott-Hort, as edited by Joshua Grauman.
- *Tischendorff Greek New Testament*
  - [MorphGNT](https://github.com/morphgnt/tischendorf) (Plain text in columns): Tischendorff, done by MorphGNT.
- *Bunning Heuristic Prototype (BHP)*
  - [Bunning Heuristic Prototype](https://greekcntr.org/resources/), generated from early manuscripts algorithmically.  See [this documentation](https://greekcntr.org/resources/BHP_Introduction.pdf). [BHP data available at CNTR website](https://greekcntr.org/resources/BHP_Data.txt) or on [GitHub](https://github.com/greekcntr/BHP).
- *Rahlf's Septuagint*
  - [CCAT LXX](http://ccat.sas.upenn.edu/gopher/text/religion/biblical/lxxmorph/) (Plain text in columns). Not freely licensed, see [this license](http://ccat.sas.upenn.edu/gopher/text/religion/biblical/lxxmorph/0-readme.txt) and [this user agreement](http://ccat.sas.upenn.edu/gopher/text/religion/biblical/lxxmorph/0-user-declaration.txt).
  - [Unbound Bible](http://unbound.biola.edu/).  Downloadable texts in a variety of formats, including Unicode and morphology.
- *Swete's Septuagint*
  - An openly licensed morphologically tagged Swete's Septuagint is under development.  Contact [James Tauber](mailto:jtauber@jtauber.com) for details.
- *Coptic Scriptorium*
  - [Coptic Scriptorium](http://data.copticscriptorium.org/) (XML): Coptic corpus with morphology and phrasing. Freely licensed, data available on Github.
- *Hebrew Old Testament*
  - [Shebanq](https://shebanq.ancient-data.org) (SQL): Hebrew Old Testament, SQL database data.


### Treebanks

- *Nestle 1904 Greek New Testament*
   - [Global Bible Initiative](https://github.com/biblicalhumanities/greek-new-testament/tree/master/syntax-trees/nestle1904) (XML): High quality treebank using HPSG constituent grammar.
   - [Lowfat](https://github.com/biblicalhumanities/greek-new-testament/tree/master/syntax-trees/nestle1904-lowfat) (XML): Lowfat trees transformed from GBI trees to make them easier to query. XML text.
- *SBLGNT Greek New Testament*
   - [Global Bible Initiative](https://github.com/biblicalhumanities/greek-new-testament/tree/master/syntax-trees/sblgnt) (XML): High quality treebank using HPSG constituent grammar.
   - [Lowfat](https://github.com/biblicalhumanities/greek-new-testament/tree/master/syntax-trees/sblgnt-lowfat) (XML): Lowfat trees transformed from GBI trees to make them easier to query.
- *Tischendorff Greek New Testament*
   - [PROIEL](https://github.com/proiel/proiel-treebank) (XML): High quality dependency trees in an eclectic and expressive format. Part of a parallel corpus of old Indo-European Bible translations, including Greek, Armenian, Gothic, Old Church Slavonic, and Latin.
- *Hebrew Old Testament*
  - [Shebanq](https://shebanq.ancient-data.org) (SQL): Hebrew Old Testament, SQL database data.

### Discourse Analysis

- *Levinsohn's Greek New Testament Discourse Features*
  - [Levinsohn](https://github.com/biblicalhumanities/levinsohn): Stephen Levinsohn's complete discourse features markup of the Greek New Testament (UBS4/NA27). Released by SIL International and Paul O’Rear, and recognized as the [2016 Dataset of the Year](http://biblicalhumanities.org/2017/01/27/BH2016-award.html).

### Lexicons

- *Abbott-Smith*
  - [Translatable Exegetical Tools](https://github.com/translatable-exegetical-tools/Abbott-Smith) (TEI XML): Probably the best quality lexicon in the public domain.
- *Dodson*
  - [biblicalhumanities](https://github.com/biblicalhumanities/Dodson-Greek-Lexicon) (CSV, XML): This lexicon has simple glosses and short definitions. Originally developed by Jeffrey Dodson, released to the public domain.
- *Liddell-Scott-Jones*
  - [Perseus Lexica](https://github.com/PerseusDL/lexica) (TEI XML): The Great Scott, a massive and extremely useful lexicon. The version currently used on Perseus, converted to Unicode, can be found [in Giuseppe Celano's repository](https://github.com/gcelano/LSJ_GreekUnicode). (The smaller "Middle Liddell" is also available from Perseus.)
- *Mounce Lexicon*
  - [Mounce (copy)](https://github.com/jcuenod/dictionary) (JSON): Mounce's Concise Greek-English Dictionary of Biblical Greek ([original repo](https://github.com/billmounce/dictionary) no longer extant).
- *Strong's Dictionary*
  - [OpenScriptures](https://github.com/openscriptures/strongs) (XML): One of the most commonly used lexicons, keyed to Strong's Numbers for easy cross reference. Greek and Hebrew.
- *Hebrew Lexicon*
  - [Shebanq](https://shebanq.ancient-data.org) (XML): A Hebrew lexicon from the Shebanq project.

### Grammars and Paradigms
- *Greek Syntax*
  - [Rydberg-Cox](http://www.perseus.tufts.edu/hopper/dltext?doc=Perseus%3Atext%3A1999.04.0052)(XML): Jeffrey A. Rydberg-Cox, Overview of Greek Syntax. Extremely useful summaries of Greek syntax, easily integrated into a reading environment.
- *Greek Paradigms*
  - [Masternarde](http://ucbclassics.dreamhosters.com/ancgreek/AGTdownload.zip) (HTML, PDF): Ancient Greek Tutorials, by Donald J. Mastronarde with the assistance of the Berkeley Language Center of the University of California, Berkeley. ©1999-2005 The Regents of the University of California. Copyright prevents free distribution, but this can be useful for producing resources.
- *Gesenius' Hebrew Grammar*
  - [Gesenius](https://en.wikisource.org/wiki/Gesenius'_Hebrew_Grammar): An old classic reference grammar.

### Commentaries, Secondary Literature, and Other Resources

- *Lace*
  - [Lace](http://heml.mta.ca/lace/index.html)(hOCR): Contains a massive number of Greek texts in hOCR format, including several scholarly commentaries on the Greek text of each New Testament book, Septuagint resources, Cramer's Catenae, Migne, the Sophocles lexicon, and many other resources that are just begging for the community to adopt and do manual editing.
- *Bible Support*
  - [Bible Support](http://www.biblesupport.com/e-sword-downloads/) (e-Sword modules): Contains some very useful [commentaries](http://www.biblesupport.com/e-sword-downloads/category/3-commentaries/)
  and [dictionaries](http://www.biblesupport.com/e-sword-downloads/category/7-dictionaries/).
