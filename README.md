# Prosper Loan Data Exploration 
## by Opetunde Adepoju


## Dataset

Prosper is a P2P lending platform that allows investors to choose among personal loans to invest in. They do that by considering a number of factors, which include a custom calculated Prosper Score that represents the risk for each loan. The higher the score, the lower the risk, and the lower the interest rates paid by the borrower to the investors.

This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.


## Summary of Findings

In this notebook, I wanted to find out which features were the best indicators for predicting the highest rate of return.

In the univariate exploration, I visualized and addressed minor quality and tidiness issues for the following features:

### Numerical Features
1. Estimated Returns
2. Actual Returns
3. Debt to Income Ratio

### Categorical Features
1. Income Range
2. Credit Grade
The Actual Returns for the dataset was engineered from a simplified version of Prosper's Net Annualized formula.

The bivariate exploration revealed the numerical categories did not have any obvious correlations. When comparing the estimated returns with the income range and credit grade, it became apparent that the credit grade is a much better predictor for returns than the income range. The credit grade spanned every income range, however I noticed that borrowers with higher incomes often received better credit ratings.

The multivariate exploration revealed again that the credit rating was the best primary predictor for estimated returns. When introducing the loan status, loans that have been completed or are current followed a linear correlation between estimated and actual returns.


## Key Insights for Presentation

For the presentation, I focus on the journey of exploring the features of interest to discover which loan features are most important to higher returns.

I begin with introducing the features of interest one by one, followed by how they relate to one another and eventually how they correlate with estimated returns and actual returns.
