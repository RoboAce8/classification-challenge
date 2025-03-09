# classification-challenge
Module 13 Challenge

## Purpose
### The provided dataset contains information about emails, with two possible classifications: spam and not spam. The intent is to creat two different classification models fit to the dataset to detect spam and determine which model performs better. The two types of classifiers are: Logisitic Regression Classifier and Random Forrest Classifier

## Prediction
### I think that the Random Forest Classifier model will perform better. I don't think that the difference between a regular email and spam is linear. Based on spam detection that I have seen on my own emails, it often gets it wrong and classifies spam as regular emails or regular emails as spam.

## Results
### The Random Forrest Classifier performed about 2.5% better than the Logistic Regression Classifer. This does match my prediction. Both of them have an accuracy above 90% and the Logistic Regression Classifier model did train faster. With the size of this dataset the training time wasn't significant, but with a larger data set, the Logistic Classifier is accurate enough that it could be used to save training time vs the Random Forrest Classifier.