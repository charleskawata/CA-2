# CA-2

## Introduction
This is a machine learning based email spam classifier that uses the Naive Bayes algorithm for classification. The aim of this project is to help users identify spam emails in their inbox.

## Prerequisites
Before you begin, ensure you have the following libraries installed in your system:

1) Numpy
2) Pandas
3) Scikit-learn

## Implementation
1) To start, create a function that will create a dictionary of all the most frequent words in a given data set. 
2) After, create another function that takes a directory of emails as a parameter and outputs a features matrix and spam labels
3) Once you have created these two functions, split the data 70/30 into training and testing data sets
4) Pass in the test and train data to the function created in step 2 to get the features matrix and spam labels for each data set
5) Train the ML model using Gaussian Naibe Bayes Algorithm
6) Test if the model is accurate compared to the predicted values model.predict
7) Find the accuracy of the model
