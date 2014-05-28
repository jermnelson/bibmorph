Bibmorph 
========
[Bibmorph](https://github.com/jermnelson/bibmorph) is a command-line 
and Haskell library for converting records and entities between different
bibliographic and metadata vocabularies. This initial version (0.0.1) is 
focused on a Minimum Viable Product where MARC21 records are
converted to [BIBFRAME](http://bibframe.org/) RDF/XML documents using 
Haskell's rich Category theory underpinnings.

This project is Haskell-based and is inspired by the easy-of-use of the
[Pandoc](http://johnmacfarlane.net/pandoc/) in converting files from 
between markup languages and final document formats like PDF and 
Microsoft Word. 

## Usage
To convert a single MARC21 record to the corresponding BIBFRAME RDF/XML,
run the following from the command-line:

`$ bibmorph marc bf -i test.mrc -o test.rdf`
