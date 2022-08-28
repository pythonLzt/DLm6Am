Dependency:

python==3.7.12

numpy==1.21.5

torch==1.6.0+cu101, torchvision==0.7.0+cu101

pandas==1.1.0

Usage:

python test.py -test_fasta test.fasta -out_dir out


Notes: 

1. The script test.py is used to predict m6Am sites from a given file with fasta format containing RNA sequences, in which potential modification sites within those sequences can be identified using sliding-window. 

2. test_fasta: an input file containing query RNA sequences with fasta format.

3. out: the name of output directory.
