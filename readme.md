# (Prosper Loans Data Exploration)

## by Conor Parke


## Prosper Loan Dataset

The dataset explored for this project was a dataset belonging to Prosper containing 113,937 loans with 81 variables for each loan recorded. The data contained information about the Borrowers credit and risk ratings, loan amounts, loan listing categories, employment status, Income Ranges, APR and Interest rates, loan term among many others. The dataset originated in CSV format. As part of the data wrangling process, the number of data columns was reduced down from 81 to 23, containing only variables that I felt were worthy for exploring further. I replaced the Listing category numbers with their respective meanings to make the data easier to interpret, while I also had to convert the LoanOriginationDate into datetime format in order to create a time series line plot in the bivariate exploration section.    


## Summary of Findings

*When exploring the dataset, I found that the Borrower's falling into the high-income ranges were borrowing the largest amounts from the lender. This was expected, as those with high incomes are more readily able to make loan repayments, no matter how large the amount.

*The Borrowers with high monthly incomes were associated with the highest Prosper ratings, AA, A, B. It is understandable that wealthier Borrower's would have lower risk ratings with their loans, since there is a stronger likelihood that they will make all repayments without issue, since their monthly income is higher. 

*When measuring the Prosper Rating against the Loan amount, it was clear that Borrowers whose loans have received top risk ratings could borrow larger amounts from Investors. Better off Borrowers with good records on credit repayments are classified as low risk, as a result the lender is more comfortable lending larger amounts to such Borrowers. I will Investigate this further in the presentation. 

*Credit Ratings of Borrowers have a direct impact on the Annual percentage rates charged on their loans. Those with excellent credit ratings have a lower APR value compared to those with low-mid level ratings. Borrowers with a good record of past credit repayments appear to be somewhat rewarded by being offered lower Annual Percentage rates on their loans.

*The relationship between the Interest Rate, APR and Loan Amount was explored and showed a clear negative correlation between both rates and the loan amount. It was evident that the greater the loan amount borrowed, the lower both the Rates will be as a result. The APR and Interest is always higher for smaller loan amounts, as the lender makes their profit by increasing the Interest charged on such loans that are also short term. I will examine this further in the explanatory presentation.

*The lender appears to favor lending larger loan Amounts across Longer loan terms, and most borrowers who are in this category have all high Prosper risk ratings. The lender not only generates steady income for themselves and the Investors for long term loans, but they are also lower risk. I will explain this further with visuals in my explanatory presentation.

*The APR, BorrowerRate and LenderYield's are all interlinked by their almost identical patterns in the histogram distributions of each. The APR will always be slightly greater than the Interest rate, as it also considers broker fees on the loan, while the Lender's Yield is equal to the Interest rate minus the servicing fees, the Lenders Yield is the net profit that the Investor earns on the loan, which is the Interest rate charged by Prosper.



## Key Insights for Presentation

For the presentation I focused on the different factors that affect the Loan amount and rates for Borrowers. I began by showing the Prosper risk rating against the Loan amount and how they are correlated. I then showed the impact of credit grades on APR, and how having a better credit ratings typically leads to have lower interest on the loan. The prosper ratings effect on the relationship between Loan amount and APR was discussed, followed by the effect of the borrowers income range on the loan amount.     
