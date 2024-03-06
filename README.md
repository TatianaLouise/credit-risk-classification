# credit-risk-classification
## Overview of the Analysis

This project analyzes the creditworthiness of loan applicants using various techniques to train and evaluate a logistic regression model. Financial information such as loan size, interest rate, borrower income, debt-to-income ratio, number of credit accounts, derogatory marks, total debt, and loan status were taken from the data, scaled using a StandardScaler, and used in the machine learning process to make predictions on whether the borrower would be a healthy loan or high-risk loan.

## Results

Accuracy score: 99%

Healthy loans:
- Precision: 100%
- Recall: 99%
- F1-Score: 100%

High-risk loans:
- Precision: 85%
- Recall: 91%
- F1-score: 88%

## Summary

The logistic regression model is astoundingly accurate in evaluating healthy loans when considering the precision, recall, and F1-Score. Although the precision for identifying high-risk loans is lower at 85%, this is still considered to be a dependable method to evaluate creditworthiness of borrowers.