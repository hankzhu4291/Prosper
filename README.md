# Prosper
Exploratory Analysis and Data Visualization on Loan Data from Prosper using using R

========================================================

## Data Description
This [data set](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv) contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, borrower employment status, borrower credit history, and the latest payment information.
There are NA values in the data, so I conducted data cleaning by removing variables with over 25% NA values and rows with NA values. I got 97886 observations with 67 variables. I extracted 10 variables which would be in my exploration.

## Pacakages used
```
library(dplyr)
library(ggplot2)
library(ggcorrplot)
library(gridExtra)
library(GGally) 
```

## Main variables explored
'CreditScoreRangeLower', 'ProsperRating..Alpha.', 'EmploymentStatus', 'IncomeRange', 'StatedMonthlyIncome', 'DebtToIncomeRatio', 'BorrowerRate', 'BorrowerAPR', 'MonthlyLoanPayment', 'BankcardUtilization'
