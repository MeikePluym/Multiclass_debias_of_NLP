# Multiclass_debias_of_NLP
This repository contains the code for the debiasing techniques from the paper "Towards More Equitable NLP: Investigating Multi-Sensitive
Attribute Debiasing Methods for Contextualised Models".

The directory 'multiclass_loss_function' contains all the code for the Loss method discussed in the paper, and the directory 'multiclass_inlp_rlace' contains the code 
for both the INLP and R-LACE methods.

Each of the directories contains a jupyter notebook file for the preprocessing of the data, as well as the training data file and training data word lists required for the
preprocessing of the data. The debiasing methods and the model evaluation are also in the form of jupyter notebook files. All files run top-to-bottom and allow for
parameter setting/model identification in one of the first cells.

An additional requirements.txt file is added to the two directories. This file contains the version of the python modules used.

The code in this repository partly uses code written by Ravfogel et al. (2020) and Kaneko and Bollegala (2021).
