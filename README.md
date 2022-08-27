Dependency:

Python3.7

numpy==1.21.5

torch==1.6.0+cu101, torchvision==0.7.0+cu101

pandas==1.1.0

Usage:

python test.py -test_fasta test.fasta -out_dir out


Notes: 

1. The script test.py is used to predict m6Am sites from a given file with fasta format containing RNA sequences (41 bp) in which sequence center is A. 

2. test_fasta: a input file containing query RNA sequences.

3. out: the name of output directory
