# Module 12 Report Template

## Overview of the Analysis

The goal of this analysis was to develop a model for predicting the creditworthiness of borrowers seeking loans, with the outcome variable being loan_status categorized as either 0 for healthy loans or 1 for high-risk loans. Financial information such as loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt were utilized for prediction. The process involved reading the lending data from a CSV file, splitting it into labels (y) based on loan status and features (X) comprising the remaining financial attributes. The balance of the labels was checked using value_counts, and the data was split into training and testing sets using train_test_split. Two methods, namely Logistic Regression and Logistic Regression with resampling, were employed for the analysis.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

For Machine Learning Model 1, when predicting healthy loans (0), the results showed a balanced accuracy score of 0.944 with a confusion matrix indicating a recall and precision of 100%. For high-risk loans (1), the balanced accuracy score remained at 0.944, with a recall of 89% and precision of 87%.

In Machine Learning Model 2, the results for predicting healthy loans (0) yielded a balanced accuracy score of 0.944, with a recall of 99% and precision of 90%. Meanwhile, for high-risk loans (1), the balanced accuracy score stayed the same at 0.944, with a recall of 89% and precision of 99%.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
Choosing between model 1 and model 2 really depends on what we want to achieve, if the goal is to accurately predict label 0 (health loan), then precision and recall are crucial, model 1 is probably the best for class 0 Best choice. However, if the goal is to predict Class 1 (higher risk loans), then accuracy is important and Model 2 has higher accuracy for Class 1. However, I would recommend using model 2 since higher risk loans are more important
