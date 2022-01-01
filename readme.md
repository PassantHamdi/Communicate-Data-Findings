# (Prosper Loan Data Exploration)
## by (Passant Hamdi)


## Dataset

> Prosper Loan data contains 113,937 loans with 81 variables on each loan. We started wrangling and cleaning the dta by removing duplicates,
dropping some of the 81 variables as it is too much we won't be able to explore, then removing all missing data.
> Then converted the loan creation date to datetime data type and extracted the year to use it during the analysis.
> Finally converted the listing category from numeric to object(used the category name instead of index) to be more easier to understand.
> The final data afetr all our cleaning contains 105462 columns(loans) with 39 raws(variables).

## Summary of Findings

> We have some factors that affect the borrower annual percentage rate (APR) which is our main focus.

> 1. The distribution of borrower APR is multimodal, we have more than one peak.
> 2. Most borrowers need loans for debt consolidation.
> 3. The majority of borrowers have full time jobs.
> 4. The number of homeowner borrowers is more than borrowers who don't own homes.
> 5. APR values were icreasing from 2007 to 2011. Then from 2011 till 2014 decreased.
> 6. Since 2009, loan amounts are increasing.
> 7. Borrower APR decreases with large loan amounts.
> 8. The stability of the borrower's job affects the value of APR, the unemployed borrowers have the highest APR values.
> 9. Owning home decreases the value of APR.
> 10. Borrower APR values affect the status of the loan, the completed and current loans have the lowest APR.
> 11. The loan amount increases with the stated monthly income of the borrower.
> 12. The borrower who belong to a group has less APR values.
> 13. When the number of investors increses, the borrower APR decreases.
> 14. The number of investors is the highest when the borrower has full time job.

## Key Insights for Presentation

> For our presentation we are going to use the borrower APR distribution, the relationship between loan status and borrower APR, The interaction between loan original amount, investors and borrower APR and the effect of Loan Term on the Borrower APR over the years