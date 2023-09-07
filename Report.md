<h1>Credit Risk Analysis Report<h1>

<h2>Table of Content<h2>
- [Overview of the Analysis](#overview-of-the-analysis)

##<h2>Overview of the Analysis<h2>

The purpose of this analysis is to develop a predictive model for assessing loan risk. Loan risk assessment is essential for financial institutions to make informed lending decisions. The goal is to build a model that accurately classifies loans as either "healthy" (0) or "high-risk" (1) based on the provided financial information. The primary objective is to identify loans that are at a high risk of defaulting, allowing the lender to manage risk effectively.

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
