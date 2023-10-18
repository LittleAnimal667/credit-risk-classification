# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* The purpose of this analysis is to build a logistic regression model to predict a lendee's likelihood of defaulting on their loan and determine whether that model is accurate enough to use.

* To build this model, a dataset of historical lending activity from a peer-to-peer lending services company was used.

*  The analysis considers various features from the dataset, including loan status, loan amount, interest rate, income, debt, debt-to-income ratio, derogatory marks on the loan, and the number of open accounts. These features are used to predict the likelihood of a loan resulting in default.

* To determine the risk of a loan, we first read into the data and separate the data into labels and features.  We then review each new dataframe to see that there's no missing data and they are matched correctly before splitting the dataset into what will be used for testing and what will be used for training the models in order to determine which is more accurate.  Defining and training the logistic regression model to test the split features and create predictions.  Finally we look at a confusion matrix and print a classification report to be able to answer which regression model is the best fit for the question of whether future loans will result as high risk or healthy.

* The logistic regression model is defined and trained using the training dataset to make predictions. The analysis includes the use of evaluation metrics, such as a confusion matrix and a classification report, to assess the model's performance and determine its accuracy in predicting high-risk loans.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.

## Summary

* Performance varies according to the problem at hand.  In our specific case, for healthy loans, the precision model attains an exceptional accuracy, surpassing 99%.  However, this isn't the case for high-risk loans, instead, the recall model demonstrates 99% accuracy for high-risk loans.  Given the scenario, accurate prediction of high-risk loans takes precedence, making the use of the recall model advisable.