# Machine-Learning
Project: CA 02 - Spam eMail Detection using Naive Bayes Classification Algorithm\
Programmer: Caroline Otten\
Contact: cotten1@lion.lmu.edu\
\
# Assignment Description
In this exercise we shall train the model with set of emails labelled as either from Spam or Not Spam. There are 702 emails equally divided into spam and non spam category. Next, we shall test the model on 260 emails. We shall ask model to predict the category of this emails and compare the accuracy with correct classification that we already know.

\
# import packages 
  #import os\
  #import numpy as np \
  #from collections import Counter \
  #from sklearn.naive_bayes import GaussianNB\
  #from sklearn.metrics import accuracy_score\
  \

# Please Note: 
This code was written on Google Colab. To upload data, replace the file path in the following code to the data with the path to where you have stored the data:\
  #load data\
  TRAIN_DIR = '/content/drive/My Drive/2021/Machine Learning/CA 02/Data (2)/train-mails'\
  TEST_DIR = '/content/drive/My Drive/2021/Machine Learning/CA 02/Data (2)/test-mails'\
\
# Conclusion 
The Naive Bayes considers the independence in features. For example it assumes the occurrence of one word/ feature is independent of other. But in real life it may not be so ( occurrence of morning is high after Good).

