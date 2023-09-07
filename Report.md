# Credit Risk Analysis Report

## Table of Content
- [Overview of the Analysis](#overview-of-the-analysis)
- [Results](#results)
- [Summary](#summary)

## Overview of the Analysis

The purpose of this analysis is to develop a predictive model for assessing loan risk. Loan risk assessment is essential for financial institutions to make informed lending decisions. The goal is to build a model that accurately classifies loans as either "healthy" (0) or "high-risk" (1) based on the provided financial information. The primary objective is to identify loans that are at a high risk of defaulting, allowing the lender to manage risk effectively. To understand the distribution of the loan_status variable, you can use value_counts() to count the number of loans in each category. This information helps assess the class balance, which can be important when building a predictive model, as imbalanced classes may require special handling.

**Financial Information**

loan_size: The size or amount of the loan applied for.
interest_rate: The interest rate associated with the loan.
borrower_income: The income of the loan applicant.
debt_to_income: The debt-to-income ratio (DTI) of the applicant.
num_of_accounts: The number of financial accounts the applicant has.
derogatory_marks: The count of derogatory marks on the applicant's credit report.
total_debt: The total debt amount the applicant owes.

**Prediction Target**

loan_status: This binary variable indicates whether the loan is "healthy" (0) or "high-risk" (1).

**Stages of the Machine Learning Process**

- Choose machine learning algorithms suitable for binary classification.
- Spilt the data into training and testing sets.
- Create a Logistic Regression Model with the orginal data.
- Predict alogistic regression model with resample training data.

**Method Used**

Two techniques used for this problem were logistic regression and resampling methods. Reason logistic regression was used is because of it being a straighforward algorithm for binary classification. Due to the class imbalance, resampling methods was used to increase the minority class (high-risk loan) to obtain a balanced dataset. 

## Results


## Summary
