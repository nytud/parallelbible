## TSV files of the Parallel Bible Corpus

The Parallel Bible Corpus is based on the historical text material of the [Old Hungarian Corpus](http://oldhungariancorpus.nytud.hu/en-intro.html), as its database contains all of the Old and Middle Hungarian Bible translations which are available in this corpus. The King James Bible and three Finnish translations are included in the database as well. This repository contains the files of the Parallel Bible Corpus in TSV format. The [Parallel Bible Reader](http://parallelbible.nytud.hu/) is a search application built on the corpus and provides a supplementary search application which makes it possible to study the Bible's verses in several languages and periods in parallel. 

### The naming convention of the TSV files

All TSV files are named following the pattern 'ABBREVIATION_TYPE.tsv', where _ABBREVIATION_ indicates the Bible translation and _TYPE_ shows whether it is in its original orthographic form (_b_ = _betűhű_), in normalized form (_n_ = _normalizált_) or it is a modern translation (_m_ = _modern_).

### The structure of the TSV files

The first three columns of the file contain locus markers:
- 1st column: the abbreviation of the book
- 2nd column: the chapter
- 3rd column: the verse

The 4th column contains the text of the given verse. If one verse has several translations, these are separated by §§. Thus, §§ is not a part of the original translation. In versions which are presented in their original orthographic forms, @@ stands for original line breaks and == marks cases where two distinct words were written as one word in the original resource.

### Resources available as TSV files

The list of available Bible translations can be found on the [Parallel Bible Reader website](http://parallelbible.nytud.hu/info). It can only be found in Hungarian, but we will provide an English translation soon.

### License

The TSV files are published under [CC-BY-SA-4.0 license](https://creativecommons.org/licenses/by/4.0/).
