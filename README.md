# (Dataset Exploration: Loan Data from Prosper)
## by (Simon Musila)


## Dataset

> Loan Data from Prosper data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.


>Started with Data wrangling which involved assessing data, data cleaning, manipulation and data visualization which was the main work done on the dataset. Dataset was minised to 16 variables but on analysis LoanOriginationDate variable was divided into loanOrigination_month and loanOrigination_year.


## Summary of Findings

Some of the variables that I focused on are the LoanStatus, Term, BorrowerAPR, BorrowerRate will be of help in determining the APR for a borrower, factors affecting the the interest rate. Also to determine the loan status we will have to combine variables like LoanOriginalAmount, LoanStatus, EmploymentStatus, IsBorrowerHomeowner.

Some of the major questions that were identified to help in the visualization included:
- What factors affect the Borrower's interest rate for this loan?
- What factors affect the Borrower's Annual Percentage Rate (APR) for the loan?
- What are the  factors affecting status of the loan?
- What factors affect the different loan type?
- If being a home owner affects the borrowing capacity?
- What factors affect the original loan amount?
- What affect the Term limit for a Loan?

On the exploratory analysis 3 types of visualizations were used which included univariate visualizations, bivariate visualizations, and multivariate visualizations. Each type of visualization helped in guiding on the analysis for the variables of interest. We will discuss some of the findings below:


##### BorrowerAPR and BorrowerRate
From the univariate visualizations, BorrowerAPR and BorrowerRate have almost similar characteristics and the graphs tend to behave the same even when compared separately with different variables. BorrowerRat has a multimodal distribution with several peaks e.g. at 0.15, 0.2, 0.25, 0.3, 0.35 while BorrowerAPR has also a multimodal distribution with similar peaks like the BorrowerRate.
On EmploymentStatus the 'Not Employed' borrowers had a low BorrowerAPR and BorrowerRate of below 0.2



##### LoanOriginalAmount
LoanOriginalAmount is a Multimodal distribution with various peaks. The peaks are at 5000, 10000, 15000, 20000, 25000 and 35000. However, it can be observed low loan amounts were awarded to a huge number of borrowers as compared to a huge sum of 35000. From loanOrigination_year variable, it was observed that 2009 had the lowest amount of loans awarded and increased through the years but 2013 was the highest. loanOrigination_month variable indicated that more borrowers in the months of October, November, December and January and very few borrowers in the month of April.

Borrowers prefered the longterm loans i.e. 36months and 60months. However, 12months have a low BorrowerAPR compared to 36months and 60months during the same period. However, Defaulted Loans of 12months have a very high BorrowerAPR. When borrowers would require Loans with low BorrowerAPR they can go for the 12months Term loans.
BorrowerRate and BorrowerAPR are high when the Term is at 36months and 60months as compared to when it's at 12months. It was also observed that when the LoanOriginalAmount is below 15000, the BorrowerRate and BorrowerAPR are high compared to when its above 20000.

On EmploymentStatus vs LoanOriginalAmount Employed borrowers had access to higher loans compared to other employment status. This could be because of the security for the loans and ability to repay them.


##### LoanStatus
On Loan Status, 36 months Term had more number of borrowers. Consequently, it more number of borrowers who Defaulted, FinalPaymentInProgress, Completed or PastDue. For example Completed, LoanOriginalAmount mean was approximately 6300 and Defaulted, LoanOriginalAmount mean was approximately 7200. Current, LoanOriginalAmount mean was approximately 10360.


##### IncomeRange
Borrowers with low IncomeRange had access to small amount of loans e.g. those with income range of 0 had access to loan amount of mean time 7410 as compared to those with high incomes of 25,000 to 100,000+ who had access to huge amounts of loans.


##### IsBorrowerHomeowner
51.6% of home owners are loan borrowers compared to 48.4% who don't own a home. This small margin means that this variable is not a good determinant to tell whether those who are loan borrowers home owners or not.


## Key Insights for Presentation

#### BorrowerAPR and BorrowerRate
When we talk about Loans, we need to know about the interest rates that the Loan is charging and the BorrowerAPR. We can't talk about loans without this 2 crucial variables hence they have been greatly analysed alongside other variables. Many of the questions of interest mostly revolve around this variables.

##### LoanOriginalAmount
Amount of loan one can access is also a crucial variable. Every borrower would like to know their limits hence we have analysed it to know what affects the loan amount.