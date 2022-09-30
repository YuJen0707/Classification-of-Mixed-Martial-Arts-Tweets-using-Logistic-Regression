# Classification of Mixed Martial Arts' Tweets using Logistic Regression
This is my graduate project from the Department of Data Science at the University of Glasgow.

There are three part of this project:

## MMA_Tweet_snscrape
* Use snscrape to collect the specific data from tweet.
* This project select the Biggest Pay-Per-View Events in UFC History, which is Khabib Nurmagomedov vs. Conor McGregor - UFC279
* The search keywords are: "ufc229 OR ufc OR TheNotoriousMMA OR TeamKhabib"; time: "since:2018-08-23, until:2018-10-07"; language: "English"


## Twitter_Sentiment_Analysis_with_MMA_Data
* Use Sentiment140 from Stanford University to train three different model: Bernoulli Naive Bayes, Linear Support Vector Classification, and Logistic Regression
* Logistic regression (LR) was chosen as our binary classification model based on accuracy.
* Binary classification with the labels: Positive, Negative.
* Our MMA dataset was applied to the LR model to obtain binary classification data set.

## Classifying multi-label comments with Logistic Regression
* Wikipedia comments were used to train a multi-classification model. The dataset is under CC0, with the underlying comment text being governed by Wikipedia's CC-SA-3.0.
* Using LR as a baseline model for multiple classification. 
* The categories of multiple classification: toxic, severe_toxic, obscene, threat, insult, and identity_hate
* Apply the binary classification data set of the baseline model to get the 


### This project draws on the following resources:
* https://www.kaggle.com/competitions/jigsaw-toxic-comment-classification-challenge
* https://www.kaggle.com/datasets/kazanova/sentiment140

I considered using the NB-SVM model and LSTM with a word embedding model to implement this project. However, due to time and hardware equipment constraints, the LR model is a better choice in this case.
