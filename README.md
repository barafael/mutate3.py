A simple mutation script
==========================
This is a simple python script for performing mutation testing. It can generate mutants for C programs.

Usage
------------
python mutate3.py <file-to-mutate.c> [output-mutant-file-name.c]

* Comments are automatically removed from the mutant by invoking cpp. It is possible to skip that step, but then this tool might introduce mutations in comments.
