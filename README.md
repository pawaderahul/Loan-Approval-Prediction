# Loan Approval Prediction using various classification techniques


## Problem Statement: 
    Predict Loan Eligibility for Dream Housing Finance company.
    
## Description:
     Dream Housing Finance company deals in all kinds of home loans. They have presence across all urban, semi urban and rural areas. Customer first applies for home loan and after that company validates the customer eligibility for loan.
     Company wants to automate the loan eligibility process (real time) based on customer detail provided while filling online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others. To automate this process, they have provided a dataset to identify the customers segments that are eligible for loan amount so that they can specifically target these customers.


## Data Dictionary
Train file: CSV containing the customers for whom loan eligibility is known as 'Loan_Status'
Test file: CSV containing the customer information for whom loan eligibility is to be predicted

Variable: Description
Loan_ID: Unique Loan ID
Gender: Male/ Female
Married Applicant married: (Y/N)
Dependents: Number of dependents
Education: Applicant Education (Graduate/ Under Graduate)
Self_Employed: Self employed (Y/N)
ApplicantIncome: Applicant income
CoapplicantIncome: Coapplicant income
LoanAmount: Loan amount in thousands
Loan_Amount_Term: Term of loan in months
Credit_History: credit history meets guidelines
Property_Area: Urban/ Semi Urban/ Rural
Loan_Status (Target): Loan approved (Y/N)


## Framing Problem¶
      For now, we can categorize our Machine Learning System as:
          1. Supervised Learning Task- we are given labled training data(e.g. we alredy know some of the Loan_status)
          2. Classification task- our model is expected to predict the Loan_status using given features.

## Dataset:
     1. [train data](https://github.com/pawaderahul/Loan-Approval-Prediction/blob/main/train.csv)
     2. [test data](https://github.com/pawaderahul/Loan-Approval-Prediction/blob/main/test.csv)

## [Data Preprocessing](https://github.com/pawaderahul/Loan-Approval-Prediction/blob/main/DataPreprocessing.ipynb)

## ML Models
    [Logistic Regression](https://github.com/pawaderahul/Loan-Approval-Prediction/blob/main/LogisticRegression.ipynb)
    [Random Forest](https://github.com/pawaderahul/Loan-Approval-Prediction/blob/main/RandomForest.ipynb)
    [XGBoost](https://github.com/pawaderahul/Loan-Approval-Prediction/blob/main/XGBoost.ipynb)


