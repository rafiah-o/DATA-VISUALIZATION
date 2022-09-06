# ProsperLoanData Exploration
## by Opeyemi Rafiat Fasasi


## Dataset
The ProsperLoanData contains information about loans, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.
The dataset can be found here: https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1581581520570000

The data wrangling steps taken are:
- Used .head(), .shape and .info() to understand the structure of the data
- Renamed the columns of some variables using .rename()
- Changed the datatypes of some variables using .astype() and to_datetime()
- Selected the columns needed for the analysis.

## Summary of Findings
I plotted several univariate, bivariate and multivariate visualizations to understand the relationship among the variables. See the summary of my findings below;
- I discovered that the modal prosper rating is 4 and there is a strong relationship between loan original amount and the monthly payment, as an increase in the the amount leads to increase in the monthly payment.
- The majority of loans has 36 months term and the income range and loan amount don't really determine loan term as for each prosper rating,
36months was the modal term.
- Also, the income range seems to have an effect on prosper rating, as majority of loans in the highest rating 7 has modal income of $100,000+


## Key Insights for Presentation
For the presentation, I focused on how LoanOriginalAmount, Term and MonthlyLoanPayment relates to the Prosper Rating. I used histogram to show the distribution of Loan Original amount and used countplot to show the distribution of loan terms across each prosper rating. I also used barplot to show the monthly loan payment across each rating.


