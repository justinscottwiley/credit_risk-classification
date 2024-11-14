# Module 12 Report Template

## Overview of the Analysis



* The goal of the analysis is to see if you can train a Machine Learning Model from a dataset to predict if several loans are healthy or high-risk.
  
* The data that was given was from information such as loan size, interest rate, debt to income.
   
* Describe the stages of the machine learning process you went through as part of this analysis.
  1. Prepare data
  2. Seperate the data to features such as columns with X and Y or as Labels
  3. train test split the data
  4. pick the ml model for classification as logistic regression
  5. Fit the model with training data
  6. Use the model to make make predictions with the test data
  7. Evaluate the results
     
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).
from sklearn.metrics import confusion_matrix, classification_report

## Results

* Machine Learning Model 1:
    * Accuracy: 0.99
    * Precision Class 0: 1.00, Class 1: 0.85
    * Recall Class 0: 0.99, Class 1: 0.91

## Summary

* Which one seems to perform best? How do you know it performs best?
    The Logistic Regression model performed well when predicting the outcome of the healthy loans. the presicion was rating at 99%
    High risk loans would need to be tested and evaluated with more data sets top confirm that it can perform at a higher status.

