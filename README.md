If you've done much bare-metal programming, you've probably become 
accustomed to rifling through PDF files and transcribing a bunch of 
constants into your header files.

This is absurd. Give us something machine readable.

This repository is a collection of machine-readable (YAML) descriptions 
for things like the memory maps of various systems, instruction set 
encodings, etc.

* `specs` contains the actual spec/datasheets
* `doc` contains documentation. Of particular note:
  * `bibliography.txt` provides information about the sources from which 
    the information in `specs` was pulled.

The contents of this repository is in the public domain (CC0, see 
COPYING for details).
