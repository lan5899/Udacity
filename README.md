## Blog:

I brief the analysis about the data in this blog:

https://medium.com/@581999lannguyen/prosper-loan-data-analysis-48a92667c92e

## Installations

- Numpy
- Pandas
- matplotlib
- seaborn
- warnings

## File Descriptions

LanNH7.ipynb: contain the analysis and code.

prosperLoanData.csv is the datasets.

# Loan status investigation

## by Hoang Lan

## Dataset

> Dataset contains 81 columns with 113.937 values. After data description, I chose the necessary variables to investigate such as ListingKey, ListingCreationDate, CreditGrade, LoanStatus, BorrowerState, TotalProsperLoans, IncomeVerifiable, IncomeRange, DebtToIncomeRatio. Then, missing values need to be removed or replaced with suitable values. Next step, I filtered dataset with current loan to narrow the desired insights.

## Summary of Findings

> With loan status, completed loan is the highest part. Charged off loan stands second. Defaulted is the third one. And customers are mainly living in CA. Besides, the cancelled status has the lowest mean of debt per income ratio, while the mean of completed status is just 0,18. Moreover, the verifiable income occurs higher than unverifiable income and they have possitive impact on loan status and borrow status. That means the higher users in each bar are, the higher verifiable income occurs.

> In conclusion, the status of loan is not affected by verifiable income or debt per income ratio because completed status has high unverifiable incomes. Obviously, past due bars are no unverifiable incomes. So we need to ensure pastdue loan payback and check deeply our users who have unverifiable incomes.

## Key Insights for Presentation

> The presentation is about which elements affect on loan. After visualization, the findings are (1) where are customers living? (2) the distribution of debt per income ratio, (3) Impacts of debt per income ratio on loan status, (4) whether verifiable status have impacts on loan status. However, in the slide, I focus on following points: (3) Impacts of debt per income ratio on loan status, (4) whether verifiable status have impacts on loan status. The left point can be show with other suitable topics.
