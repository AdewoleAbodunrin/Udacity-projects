# (Dataset Exploration Title)
## by (your name here)


## Dataset

There are 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. 

Out of the 81 varibales, I will be focussing on 14 keys variables that will enable me draw the needed inference. This variables include the following:

* Listing Key	
* Term	
* Loan Status	
* Borrower APR	
* Borrower Rate	
* Employment Status	
* CreditScore RangeLower	
* CreditScore RangeUpper	
* Current Credit Lines	
* Inquiries Last 6 Months	
* Bankcard Utilization	
* Debt To In comeRatio	
* Stated Monthly Income	
* Loan Original Amount	
* Proper_ratings

Although I Suspect, Creditscore, Bankcard utilisation, Debt to income Ratio , proper_rating wil be essential in answering my questions



## Summary of Findings


## Conclusions

The prosper loan data used for the project. To facilitate the analysis, I cleaned the raw data. First, Given that the variables were many, I streamlined my data to 15 variables (Listing Key, Term ,Loan Status ,Borrower APR ,Borrower Rate ,Employment Status ,Credit Score Range Lower , Credit Score Range Upper ,Current Credit Lines ,Inquiries Last 6Months ,Bank card Utilization , DebtToIncomeRatio , Stated Monthly Income ,Loan Original Amount and Proper_ratings. I removed the inconsistent Prosper ratings(“NC”) and filled null values for all the variables with their mean.

#### Univariate Exploration:

I examined each variable individually. The Borrower rate and Borrower APR data seems to be evenly distributed and thus no correction was made. Based on the exploration, I was able to discover outliers in Credit Score, Bank card Utilisation, debt to income ratio, original loan amount and slated monthly income variables. These outliers were replaced with mean of the data. In addition to the above, to further aid the analysis, I reclassified loan status with past due and final payment in progress as defaulted and completed respectively. And finally for simplicity reclassified Not available employment status as other.

#### Bivariate analysis:

I explored the relationship between 2 pairs of numeric variables at a time and discovered the following key findings from the data; the higher the credit score of a borrower, the lower the borrower interest rate and the higher the possibility of the borrower receiving higher loan amount; The higher the Bank credit card utilisation rate, the lower the credit rate score ratings for that borrower. Finally, the higher the slated monthly income the higher the likelihood of having a high loan amount approved. In addition, to the above, I examined the relationship between some categorical variables and numeric variables and discovered the following key insights: there is a high likelihood that a borrower with high proper ratings will have a high credit score ratings; the higher the prosper ratings, the higher the loan amount approved and the lower the interest rate charged the borrower; there is a high possibility that employed or self-employed borrower is likely going to be given a higher loan amount compared to an unemployed borrower.

#### Multivariate Exploration: 
In order to be able to undertake the analysis clearly, I took a random sample of the total loan data with a size of 1500. The Multivariate exploration further confirmed the bivariate analysis insights: An employed borrower with higher prosper ratings will likely be awarded a higher loan amount and also charged a lower interest rate; and borrower with a higher credit score and prosper ratings, will be be granted a higher the loan amount and also lower charged a lower interest rate.




## Key Insights for Presentation

* The employed individuals with higher prosper ratings were awarded more loan amount and with lower interest rate.
* The higher the credit score and the prosper ratings, the higher the loan amount granted and also the lower the  interest rate


