# Cyber-Bullying-Tweet-Classification

This project involved analyzing tweets.

By understanding the words involved in the tweet, we are going to predict whether a tweet is a cyberbullying tweet or not and if it is a cyberbullying tweet then predicting nature of the cyberbullying into 6 Categories:

Age

Ethnicity

Gender

Religion

Other Cyberbullying

Approach:-

Installing the required libraries and importing the data set using pandas was the first step.
Initial review of the data and checked the provided data set for any missing values.
Preformed Preprocessing of text which involved :
~ Removing emoji
~ Converting text to lowercase, removing (/r, /n characters), URLs, non-utf characters, Numbers, punctuations, stopwords
~ Removing Contractions
~ Cleaning Hashtags
~ Filter Special characters
~ Removing Multi-space characters
~ Stemming
~ Lemmatization

Handling Duplicates and removing them
Performed Exploratory Data Analysis
Train and test split
tf-idf Vectorization
Trying different base models :- ~ Logistic Regression
~ Support Vector Classifier
~ Naive Bayes Classifier
~ Decision Tree Classifier
~ Random Forest Classifier
~ Ada Boost Classifier
Fine Tuning Support Vector Classifier
Model Evaluation and Saving the mode
Libraries Used : pandas, numpy, matplotlib, seaborn, stats, scipy, re, pickle, string, image, collections, statsmodel, flask, nltk, emoji


Kaggle :https://lnkd.in/dTe7PCqx
