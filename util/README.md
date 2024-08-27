## Utilities

This repository directory contains scripts and other tools related to
management of the schema definitions defined within the OID Directory
I-D series.

### oiddir-schema-extract.py

`oiddir-schema-extract.py` reads the provided copy of `draft-coretta-oiddir-schema-NN.txt`,
extracts all schema definitions contained therein, and prints them to STDOUT. Users may
modify this script to suit their own needs, and support any other formats desired.

Example:

```
$ ./oiddir-schema-extract.py -t 389ds -f ./draft-coretta-oiddir-schema-02.txt
```
