# Prosper_Loan_Udacity_DA

#  Prosper Loan Data Exploration
## by Temitope Ayano


## Dataset

> Dataset: The Prosper Loan Data was used. Prosper was founded in 2005 and was the first peer-to-peer lending marketplace in the United States. Prosper has facilitated more than 21 Dollars billion in loans to over 1.3M people.
> Through Prosper, people can invest in each other in a way that is financially and socially rewarding. Borrowers apply online for a fixed-rate, fixed-term loan between 2,000 and 50,000 dollars. 
> Individuals and institutions can invest in the loans and earn attractive returns. Prosper handles all loan servicing on behalf of the matched borrowers and investors.
> The data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.

## Summary of Findings

> The main feature of interest is Borrower APR. I investigated features that determines the APR. The borrowers status such as Occupation, EmploymentStatus, and Prosper score and their previous loan history helped to provide insight into the Borrower APR.
> I found out that:
* The distribution of borrowersAPR and borrowersRate is normal. The employment status, Income range and occupation revealed that most people who apply for loans are working class with a stable employment, and relatively moderate income. 
* APR is positively correlated with Borrowers Rate and negatively correlated with other numerical variables. The Borrowers APR decreases with increasing prosper score and increasing prosper rating. This may be because borrowers with higher prosper score and prosper rating are more trusted and thus, receives a low(better) APR.
* Loan Original Amount is negatively correlated with APR. Borrowers who took large amount of loans tend to get low APR.
Outside the variable of interest, I noticed that Loan Original amount and Monthly Loan payment are positively correlated. This makes sense, since individuals with high loan amount will have to pay larger amount when paying back every month.
* Recommendation affect the number of investors an individual get.
* Investors is negatively correlated with APR. Borrowers who have large amount of investors tend to get low APR. 
* CurrentDeliquencies is positively correlated with borrower APR. Borrowers who failed to make previous loan repayments on time tends to receive high borrowerAPR. 
* Prosper rating and Term decreases with increasing borrower APR. Borrowers with better rating tends to get long term loan repayment coupled with low APR.
* The Stated monthly income is correlated with Rating and Term.  Borrowers who earn high amount of money tends to get better rating and better loan term.
* Loan Original amount decreases with decreasing Rating and borrow term. Borrowers who borrow large amount of money also get better rating and Loan Term.


## Key Insights for Presentation
> For the presentation, I focused more on the features that influence Borrower APR. I started by taking the distribution of APR variable.
> The Key insights for presentation include:
1. What is the distribution of BorrowerAPR and BorrowerRate?
2. Which is the dominant employment status among borrowers and Term? 
* I made use of barplots to visualize this
3. What is the correlations between features in the data? 
* Heatmaps were used to show how the numerical variables vary with one another.
4. Does ProsperScore affect Borrowers APR? 
* I made use of Violin plot to visualize the relationship between prosper score and APR
5. What is the relationship between the Prosper Rating and other Categorical Variables? 
* I made use of stacked bar plot to visualize the relationship between prosper rating and other categorical variables.
6. Does Prosper Rating affect APR and Term? 
* I made use of clustered bar charts to visualize this multivariable relattionship.
7. Does Prosper Rating affect LoanOriginalAmount and Term?
* I made use of seaborn pointsplot to visualize the relationship between Prosper Rating, Term and Loan original amount
