# Prosper Loan Data
## by Ramy Gendy


## Dataset
> Dataset name: Loan Data from Prosper

> Dataset Source: https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1554486256021000

> Prosper Data Dictionary to Explain Dataset's Variables can be found in: https://www.google.com/url?q=https://docs.google.com/spreadsheet/ccc?key%3D0AllIqIyvWZdadDd5NTlqZ1pBMHlsUjdrOTZHaVBuSlE%26usp%3Dsharing&sa=D&ust=1554486256024000

> In this project, I will explore a dataset of Prosper Loan data, first do some data wrangling and cleaning, and then move on to different types of exploration to find relationships between different variables moving forward to our conclusion

>There are 113,937 loans in the dataset with 81 characteristic. Most variables are numeric in nature, where some are categorical, boolean, also variables like EmploymentStatus ,Occupation are considered as factor variables. IsBorrowerHomeowner ,CurrentlyInGroup are binary variables .LoanStatus ,and BorrowerState are ordered factor variables. also other variables have a lot of null values, such as variables prosperrating and prosperscore, and some variables are not of much use, such as listingkey, listingnumber, of other identifiers.

## Summary of Findings

> borrower rate, credit score, income range, listing type, debt to income ratio and state are the main variable resposible for Defaulting loans in the model. 


## Key Insights for Presentation

> In the presentation, key insight focus on the correlation between dataset's variables and main interest: The Default.
Firstly by introducing the Default Variable, then plotting the correlations. used the box plots of default and borrower rate. Then showed the correlation between default and income group using bar chart. In the end, A grid box plot was used to show the relationship between default, credit score range lower, and borrower rate.
