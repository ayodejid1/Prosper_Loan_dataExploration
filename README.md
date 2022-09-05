# PROSPER LOAN DATA
## by Anibaba Ayodeji


## Dataset

> This is a Python project script wirtten to perform exploratory and Explanatory data analysis on Prosper Loan Data provided as an option by udacity to pick as a data source. it contains information on peer to peer loans facilitated by credit company Prosper, there are 113,937 loans with 81 variables. For the purpose of this investigation I've taken the following variables:
['Term', 'LoanStatus', 'BorrowerRate','ProsperRating (numeric)','ProsperRating (Alpha)','ProsperScore', 'ListingCategory (numeric)', 'EmploymentStatus','BorrowerState','Occupation','IsBorrowerHomeowner','DelinquenciesLast7Years', 'StatedMonthlyIncome', 'TotalProsperLoans', 'LoanOriginalAmount','LoanOriginationDate','LoanNumber','LoanOriginationQuarter' ,'Recommendations','CurrentDelinquencies', 'Investors']

## Summary of Findings

> From my findings we should continue to give loans to employed applicants , most especially those with business reasons because our data supports that;
    1. 10k is our average loan
    2. There is little to no correlation between OriginalLoanAmount and StatedMonthlyIncome meaning it might not determine the amount of         loan disbursed to a loanee.
    3. The average loan amount disbursed is not equal in pair of states.
    4. Many of the loans are still active.
    

## Key Insights for Presentation

> This distribution of OriginalLoanAmount appears to be a normal distribution which then tells us mean=median=mode according to statistics, we can then say $10k is the most given out loan amount.

> Disbursement of Loans rose at a steeply growing rate up until 2013 where we witnessed a slight drop in the early part of the year but then rose from there on to set a record breaking disbursement rate up until early 2014 which then disbursement started to reduce drastically.

> Considering the Top 5 states in different pairs 6 out pf 10 pairs p-Value is closer to 1 meaning we have to stick to our null hypothesis they do not have the same averages which is the truth considering different factors that can affect this like employment status, ecomomy of the state and many more.

> Across these categories their averages are different except from 'auto' and also i observe that Business reasons have the highest amount recieved loans and completed at the same time which is a good note for our credit system. we can focus more on given people with loan request for Business reasons.

## List Of Software Used

1. Jupyter Notebook
2. Library Used
    *Numpy Librabry
    *Pandas Library