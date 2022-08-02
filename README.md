# DLm6Am
DLm6Am is a deep-learning-based framework to predict m6Am-containing sequences and visualize saliency map for sequences.

# Dependency
Python==3.7.1
numpy==1.21.5
torch==1.6.0+cu101

# Usage
predict m6Am-containing sequences
The script test.py is used to predict if a given sequence contain m6Am sites. The required arguments
1.test_fasta: a fasta file for test samples ( the length of sequences should be 41bp)
2.out_dir: the path of output directory

This script ouput the trained model and prediction result in the out_dir.

python test.py -test_fasta test.fasta -out_dir out
