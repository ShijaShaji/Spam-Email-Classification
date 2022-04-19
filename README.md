# Spam-Email-Classification
The aim of this project is to create a logistic regression classfier from scratch that classifies emails to spam and non-spam emails.
The Spam Email dataset from Kaggle is used in this project . (https://www.kaggle.com/datasets/somesh24/spambase?resource=download) 
The dataset contains more than 5000 rows and 58 columns out of which the last column is the class label.
A spam email has a class label of +1 and a non-spam email has a class label of 0. (This has been scaled as +1 and -1 in the code for ease of understanding)
Most of the attributes indicate whether a particular word or character was frequently occurring in the e-mail. The run-length attributes (55-57) measure the length of sequences of consecutive capital letters.
More information on all attributes can be found on the mentioned kaggle link.
Only numpy and pandas has been used in this project. 
The dataset is split into train data and test data in the ratio 80-20.
All features has been normalised using Gaussian normalisation. 
The logistic regression classifier was able to detect spam and non-spam emails with an accuracy of 0.94. 

