
# Effects of Loan Characterics on Borrower's APR and RATE
## by Muthukumar Palavesam


## Dataset

> Prosper is America’s first marketplace lending platform, with over 10 billion dollars in funded loans.This Exploratory Data Analysis scope covers loan information for over a 100,000 people between the years 2006 and 2013.This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, borrower employment status, borrower credit history, and the latest payment information

- [Datset Link](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv)
- [Data Dictionary Link](https://www.google.com/url?q=https://docs.google.com/spreadsheet/ccc?key%3D0AllIqIyvWZdadDd5NTlqZ1pBMHlsUjdrOTZHaVBuSlE%26usp%3Dsharing&sa=D&ust=1554484977407000)

## Summary of Findings

> After analyzing the BorrowerRate,BorrowerAPR, ProsperScore, ProsperRating, HomeownerStatus and CreditScoreRangeUpper, 
 - I found that the  BorrowerRate started decreasing constantly since 2011
 - ProsperScore,CreditScoreRangeUpper,ProsperRating were found to be negatively correlated to Borrower's APR
 - Higher prosperscore (score from 0 to 11) is showing as lower APR.That is it gave the strongest negative relationship with borrower's APR
 - ProsperRating and BorrowerAPR were analyzed.The APR for the borrower reduces drastically from a ‘High Risk (HR)’ to an ‘AA’ rating. if you see the results, it goes from a median APR of 35.8% for High Risk all the way to a median value of 9% for ‘AA’.
 - Homeowner customer getting lower interest rate

## Key Insights for Presentation

- Borrowers interest rate increased from 2005-2006,Decreased from 2006-2007.After 2007 interest rate constantly shoot up for few years, then reached its peak in 2011 which then started decreasing constantly.
- The APR for the borrower reduces drastically from a ‘High Risk (HR)’ to an ‘AA’ rating. 
- Higher prosperscore had a lower APR. This make sense because the borrower with higher rating tend to be more reliable and therefore given lower BorrowerAPR
- Homeowner customer getting lower interest rate. This makes sense because If someone has a house,might be more confident that the customers will have conditions to pay back.
- BorrowerAPR decreases as ProsperScore increases. This proves the point that cbscore upper limit and ProsperScore negatively correlated to BorrowerAPR.
