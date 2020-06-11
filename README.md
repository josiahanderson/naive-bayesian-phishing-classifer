## Bernoulli Naive Bayesian classifier to detect phishing websites

An implementation of a Bernoulli Naive Bayesian classifier for website phishing data
by Josiah R. Anderson


University of California, Riverside
Winter 2020
CS 235 Data Mining Techniques


Bayes' Theorem:
P(class∣data) = (P(data∣class) * P(class)) / P(data)


Step-by-Step Bernoulli Naive Bayesian classifier:
https://iq.opengenus.org/bernoulli-naive-bayes/

Data set:
https://www.kaggle.com/akashkr/phishing-website-dataset


This project contains the following files:
bayes.py
project_phishing_dataset_cleaned.csv


The bayes.py script is written in Python 3.6 and requires no arguments.
Parameters may be edited (such as CSV location, training set percentage, 
smoothing factor, etc.) at the top of the script.


Required libraries:
pandas
sklearn
