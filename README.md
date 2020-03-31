# Prediciton-of-fungal-peptide
This code uses Skit-learn library to predict the anti-fungal nature of protein peptide, using Random forest classifier.

pred.py contains the code which run the prediction model , filters the dataset and trains over it.
train.csv and test.csv are the csv files which contains the data. train file contains three columns with index, label and protein sequence. test csv only contains index and sequence.

rest all files are being created using the feature extraction such as dipeptides percentage , atom percentage , tripeptide percentage , protein peptides percentages.

For this repo I used the web https://webs.iiitd.edu.in/raghava/pfeature/ for creating these files. otherwise it is easy to code them.

Thank you.
