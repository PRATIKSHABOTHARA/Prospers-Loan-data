# Prospers-Loan-data

## Investigation Overview
Prosper is a financial company that matches investors and borrowers in a financially and socially rewarding way.
The goal of this data analysis project is to understand the factors that are related to loan status.

## Dataset Overview
There are 113,937 loans in the dataset with 81 features. Most variables are numeric and categorical in nature.
The dataset features can be split into two main categories:

- Borrower information
- Loan performance information

The independent variables of interest are:
ProsperScore,ListingCategory,EmploymentStatus,EmploymentStatusDuration,IsBorrowerHomeowner,CurrentCreditLines,
OpenRevolvingAccounts,DebtToIncomeRatio,IncomeVerifiable,LoanOriginalAmount

# Summary of Findings
- In the exploration, I found several interesting relationships between the dependent variable (LoanSatus) and these selected borrowers features: Prosper score or borrower risk, original loan amount, and debt to income ratio. I presented  the loan statuses distribution and its relationship with the variables listed above.
- Analyzing the distribution of all Prosper's Employment status we notices that almost 60 % borrows are employed , 23 % are full time and all other are less than 7%.
- 80% of the loans are in current or completed state, where as more than 10 % are is charged off stage.
  4% in defaulted and 1% in past due (all grouped togethe
- The original loan amount had amazing relation with the chosen variable of interest during the bivariate exploratory study.
- Additionally, current loans have a higher original loan amount than the other statuses. Here, I would recommend further investigation alongside Prosper's business analysts.
- Surprisily, borrowers how are employed and have full-time jobs have most of the defaulted and charged-off loans and borrowers with higher prosper score completed their loans
- Additionally, employed borrowers had the highest amount of charged-off loans that borrowers under the remaining employment status, which was the opposite of my expectations.

