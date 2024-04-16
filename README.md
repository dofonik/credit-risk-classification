# credit-risk-classification
Module 20 Challenge - UWA Data Analytics Bootcamp

# Analysis Overview

The "credit_risk_classification.ipynb" main code located in the "Credit_Risk" folder performs an analysis on loan data contained within the lending_data.csv file, located in "Credit_Risk/Resources".

The purpose of the analysis is to train a machine learning model to determine the creditworthiness of borrowers using historical lending data (lending_data.csv).
The desired outcome was to predict if a loan is healthy (0) or high risk (1). This was done by setting "loan_status" as the target variable.

The dataset contains various financial data points of borrowers (other than the target variable): loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt.

Logistic Regression was the algorithm used for the binary classification of the data. The machine learning process involved included data preprocessing, model training and model evaluation.

# Results
The model demonstrated high overall accuracy.

For Healthy Loans (0):
 - Precision: 1.00
 - Recall: 1.00
 - F1-Score: 1.00

For High-Risk Loans (1):
 - Precision: 0.87
 - Recall: 0.89
 - F1-Score: 0.88

Macro Average:
 - Precision: 0.94
 - Recall: 0.94
 - F1-Score: 0.94

Weighted Average:
 - Precision: 0.99
 - Recall: 0.99
 - F1-Score: 0.99

# Summary

The model exhibited good performance in predicting and differentiating healthy loans to high risk loans. Perfect precision and recall was observed for healthy loans, with 87% precision for high-risk loans (similar recall score also observed).

Considering the accuracy of the model when assessing the creditworthiness of borrowers, it is recommended that this model be used. The model has perfect precision when determining healthy loans which is the vast majority of instances in a standard data set. Loans deemed high risk by the model can be double checked seperately if required, as the size of this portion of data will be far reduced compared to the entire dataset.