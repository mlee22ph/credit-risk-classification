# credit-risk-classification

## File for submission
* credit_risk_classification.ipynb - main source  located in ./Credit_Risk
* lending_data.csv - main data file located in ./Resources
  

## Overview of the Analysis


*    This analysis is about the use of Logistic Regression to predict whether a loan is healthy or not based on historic data which contains such information like
loan_size, interest_rate, borrower_income, debt_to_income, num_of_accounts, derogatory_marks and total_debt. When a loan is healthy,
the loan_status is set to 0, and if it is unhealthy or high risk then the loan_status will be 1.
*    The process starts with preparing the data by separating the Features Data, which are the input data used for the prediction, and the Target Data, which are the result pattern needed to be predicted.
After securing the Feature and Target Data, need to split the Train and Test data using the SKLearn train_test_split function.
*    Create a Logistic Regression Model which will be used to train the training data. After training the model, use the test data to make a prediction.
Check the results of the prediction, first by creating a confusion matrix which will show an overview of the results showing values for True Negative, False Negative, False Positive and True Positive.
Then check the accuracy , precision and recall value to get a more clear understanding of the results.


## Results

* Logistic Regression Model

    The following values were the result of the classification report.
The Healthy Loan had perfect Precision and Recall with a value of 1.0. While the High Risk Loan had a Precision of 0.87 and Recall of 0.89, which is not bad.
The high Precision shows that the model was able to catch the True Positives from the data. While the high Recall shows that the model was able to catch the actual True Positives.
The Accuracy of both Healthy and High Risk Loans are very high as well with 0.99. This shows that the model was very accurate overall.

  
  
## Summary

* I highly recommed this model because of its exceptional performance. I would think that the high number of train and test data helped the model to be this accurate, even with just using the default number of iterations for the LogisticRegression function.



