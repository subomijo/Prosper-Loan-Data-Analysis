# PROSPER LOAN DATA ANALYSIS
## by (Oyewole Subomi)


## Overview of the Dataset

In this project Exploratory Data Analysis (EDA) and Explanatory Data Analysis is carried out on a dataset from Prosper. Prosper is America’s first marketplace lending platform, with over $9 billion dollars in funded loans. This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower income, borrower rate (or interest rate), current loan status, borrower credit history, borrower employment status, the latest payment information and much more.

I decided to create a seperate dataframe with my features of interest and it consists of 113,937 observations and 19 features. They include;

Listing Number - The number that uniquely identifies the listing to the public as displayed on the website.
Term - The length of the loan expressed in months.
Loan Status - The current status of the loan: Cancelled, Chargedoff, Completed, Current, Defaulted, FinalPaymentInProgress, PastDue. The PastDue status will be accompanied by a delinquency bucket.
Borrower APR - The Borrower's Annual Percentage Rate (APR) for the loan.
Borrower Rate - The Borrower's interest rate for this loan.
Prosper Rating - The Prosper Rating assigned at the time the listing was created between AA - HR. Applicable for loans originated after July 2009.
Listing Creation Date - The date the listing was created.
Listing Category - The category of the listing that the borrower selected when posting their listing.
Prosper Score - A custom risk score built using historical Prosper data. The score ranges from 1-10, with 10 being the best, or lowest risk score. Applicable for loans originated after July 2009.
Borrower State - The two letter abbreviation of the state of the address of the borrower at the time the Listing was created.
Occupation - The Occupation selected by the Borrower at the time they created the listing.
Eployment Status - The employment status of the borrower at the time they posted the listing.
Is Borrower Home Owner - A Borrower will be classified as a homowner if they have a mortgage on their credit profile or provide documentation confirming they are a homeowner.
Income Range - The income range of the borrower at the time the listing was created.
Loan Original Amount - The origination amount of the loan.
Loan Origination Date - The date the loan was originated.
Quarter - Created from the loanoriginationdate column, this is the quarter of loan origination.
Year - Created from the loanoriginationdate column, this is the year of loan origination
Average Credit Score - Created from the creditscorerangeupper and creditscorerangelower columns, this is the average value of the borrower's credit score as provided by a consumer credit rating agency.


## Summary of Findings

>  The Borrower APR had almost the same trend as the Borrowers rate. From the exploration of the loan, the data set reveals that the higher the Borrower Rating, the higher the Borrower's APR, and collecting loans for longer periods will increase the Borrower's APR. Most loans were collected for 3 years(12 months) and the Borrowers APR average was mostly around 0.2%. In addition, the homeowner distribution was almost even, and of the population who collected the highest loans, the homeowners dominated the range. Overall the Borrower APR will be crucial to consider when given out loans!


## Key Insights for Presentation

> Analysis showed that most borrowers(75%) took a loan term of 36 months and borrower apr was a crucial determinant in loan amounts taken.
