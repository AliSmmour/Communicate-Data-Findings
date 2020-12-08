# Prosper Loan Dataset

## Dataset

The data consisted of Loan data of approximately 99,000 loans. the dataset included 81 attributes but i decrease it to 15 attributes. The dataset can be found [here](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1554486256021000),
with feature documentation available [here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit).


## Summary of Findings

In the exploration, I found that The borrower APR is negatively correlated with the loan original amount, that when an increase in loan amount the decrease in borrower annual percentage rate. It also shows that at different size of the loan amount, the APR has a large range, but the range of APR decrease with the increase of loan amount.and A surprising interaction is that the borrower APR and loan amount is negatively correlated and I was shocked by the result of Loan Amount Vs Monthly loan payment and BorrowerAPR impact because I know if you pay more per month, then you will pay off the loan more quickly so APR is less.

The main variables of interest,  Loan Amount in the dataset. and Borrower APR.


## Key Insights for Presentation

- Loans amount in the dataset takes on a very large range of values, from about 0 dollars at the lowest, to about 35,000 dollars at the highest. The distribution of loans amount takes a skewed to the right shape. (most loans are less than 5000 dollars).

- The BorrowerAPR for the loans looks like bimodal one centered at about 0.18 and the other about at 0.3 but there are huge change at 0.36.

- Most of the loan status is current and the second status is complete. This may be an indication that the data may be somewhat dated. 

- Distribution of Overall loan amount over time (months)
The total loans Amount in each year witnessing a sharp decline after March and a return to the increase in August.

- Loan amount and its relation with Borrower APR is a negative relationship when an increase in loan amount the decrease in borrower's annual percentage rate. And their is a huge range for rate values in Borrower ARP for the approximately same amount.

- Loan amount and its relation with MonthlyLoanPayment is a strong positive relationship when an increase in loan amount the increase in payment per month and its look like the monthly loan payment are dependent on the amount.

- EmploymentStatus VS Term show 2 point

The First one: Most classes (category) take a loan is Employed, and the least is not employed.
The Second one: 36 months loans are the most distributed term, and the least is 60 months.

- The loan amount and their relation with APR decrease within all terms but 36 are more regression. but we can see the distribution for 12 are more scattered than 36 and 60. In 12 term loan most of it under 10,000 dollars and in 36, 60 between 0 - 25,000 dollars for both of them. And we can say no powerful impact of terms on APR and amount relation.

- The increasing in loan, increase the monthly loan payment and also increases the Borrower APR This means the 3 combinations have a positive relationship with each other and I was shocked by the result because I know if you pay more per month, then you will pay off the loan more quickly so APR is less.
