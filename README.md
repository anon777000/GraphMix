# GraphMix

## Requirements 
This code is tested with Python 3.6.3 and requires following packages (see requirements.txt list of all the packages):

torch==1.1.0

numpy==1.16.3

pandas==0.24.1

Pillow==5.3.0

scikit-learn==0.21.2

scipy==1.2.1

seaborn==0.9.0

six==1.12.0

tqdm==4.32.2


# How to run 

For reproducing results of GraphMix(GCN) of Table1(B) in the paper, go to directory GraphMix/semisupervised/codes and run the following commands. This will reproduce:

Cora 83.94±0.57

Citesee 74.72±0.59

Pubmed 80.98±0.55


`python run_cora.py`

`python run_citeseer.py`

`python run_pubmed.py`



