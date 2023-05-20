# RandomSeqGenerator

Author: Murat Buyukyoruk

Associated lab: Wiedenheft lab

        RandomSeqGenerator help:

This script is developed to generate random DNA or RNA sequence based on user defined GC%. 

tqdm is required to provide a progress bar since some multifasta files can contain long and many sequences.
        
Syntax:

        python RandomSeqGenerator.py -n 100 -l 500 -gcr 0.5-0.7 -t DNA

seq_fetch dependencies:
	
	tqdm                                                refer to https://pypi.org/project/tqdm/
	
Input Paramaters (REQUIRED):
----------------------------
	-n/--num		number		Specify number of sequences to generate.

	-l/--len		length		Specify number of sequences to generate.

	-gcf/--gc_fix		All GC%	        Specify desired gc content for all sequences (i.e., 0.5).
	
	-gcr/--gc_range		All GC%	        Specify desired gc content range (i.e., 0.4-0.5).
	
	-t/--type           	Type            DNA or RNA.
	
Basic Options:
--------------
	-h/--help		HELP		Shows this help text and exits the run.

	
