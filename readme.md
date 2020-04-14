# Exploratory Analysis of Loan Data from Prosper
## by Himanshu Taneja


## Dataset

> This dataset includes more than 100,000 entries for loan borrowers with 81 attributes including loan amount, monthly income, loan status, delinquency, credit value and many others.
> The main feature that was taken into consideration was the Borrower APR.

## Summary of Findings

>  ### The results of Univariate Exploration are:
> - The Variables explored in this section  showed the basic distribution in the dataset. <br>
> - It appears that more borrowers have been taking loans for an amount under 15k. <br>
> - Where people generally have a credit limit under 100k. <br>
> - The stated monthly income also seems to lie under 20k for majority of lenders. <br>
> - The dataset has outliers in most variables which might affect our analysis. <br>
> - However, the distribution of our prime factor in consideration, the borrower APR seems multimodel. <br>

> ### The results of Bivariate Exploration are:
> - The Heat Map pulled out significant correlations to be established amongst the variables. <br>
> - The BorrowerAPR is negatively correlated to the ProsperScore indicating that a person with a better prosper score will reciever lower APR. <br>
> - Lower amount of loan was associated with higher APR value. <br>
> - Prosper Rating suggests that the APR value decreases as the ratings get better. Stated Monthly Income does not seem to have any major effect on the APR value. <br>
> - The available bank credit was positively correlated with major variables which indicates that more credit relates to higher incomes and loan amounts. <br>
> - The borrowers with better employment status tend to having higher loan amounts. <br>

> ### The results of Multivariate Exploration are:
> - It was observed that the relationship between Borrower APR and Loan Amount turned from being slightly negative to slightly positive with the betterment in Prosper Rating. <br>
> - The loan amounts increased with the increase in term and rating. The increase in loan amounts with increasing term was exponentially higher for better ratings. <br>
> - The most interesting and surprising observation was with the APR value when analyzed with term and rating. It decreased linearly for ratings HR till C with the increase in term and linearly increased with the ratings B till AA. <br>

## Key Insights for Presentation

> The primary focus of my analysis was to define the factors affecting the Borrower APR. I started by exploring the distribution of APR and then I explored the distribution of various factors that might affect the APR such as Monthly Income, Loan Amount, and Prosper Score. Then I studied the relations between various variables and their cumulative effect on determing the APR value for a borrower.
