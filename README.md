# MBC-638-Data-Analysis-and-Decision-Making
Project for the subject MBC638- Data analysis in Excel
Data source: http://www.creditriskanalytics.net/
Dataset: Home Equity Loans

Data Description(from source):
The data set HMEQ reports characteristics and delinquency information for 5,960 home equity loans. A home equity loan is a loan where the obligor uses the equity of his or her home as the underlying collateral. The data set has the following characteristics:
◾ BAD: 1 = applicant defaulted on loan or seriously delinquent; 0 = applicant paid loan

◾ LOAN: Amount of the loan request

◾ MORTDUE: Amount due on existing mortgage

◾ VALUE: Value of current property

◾ REASON: DebtCon = debt consolidation; HomeImp = home improvement

◾ JOB: Occupational categories

◾ YOJ: Years at present job

◾ DEROG: Number of major derogatory reports

◾ DELINQ: Number of delinquent credit lines

◾ CLAGE: Age of oldest credit line in months

◾ NINQ: Number of recent credit inquiries

◾ CLNO: Number of credit lines

◾ DEBTINC: Debt-to-income ratio

Data Analysis and results:
The given data was analysed using Excel and StatTools. Preliminary data exploration showed that the dependent variable BAD is binary variable with value 1 if applicant defaults and 0 if not. Correlation was used to select the variables that were the most relevant to the analysis. As the dependent variable has only 2 discrete values, Logistic Regression was performed. The results generated are:



IMPLICATION 1:
When we increase the value of the loan amount from its 25th percentile to its 75th percentile, the probability of a borrower defaulting on the loan decreases by 0.7% while keeping all other factors constant.

CONCLUSION: 
Borrowers with higher loan amounts have a lower chance of defaulting on Home equity loans


IMPLICATION 2:
When we increase the age of the oldest credit line from its 25th percentile to its 75th percentile, the probability of a borrower defaulting on the loan decreases by 3.6% while keeping all other factors constant.

CONCLUSION:
Borrowers with better credit history have a lower chance of defaulting on Home equity loans

IMPLICATION 3: 
The probability of a person defaulting on a loan increases by 12% if the person has a sales job as opposed to a self employed person.

CONCLUSION:
A borrower with a sales job is 12% more likely to default on a home equity loan.

IMPLICATION 4:
When we increase the age of the oldest credit line from its 0th percentile to its 100th percentile the difference between the probability of defaulting on a loan for people who take a loan for home improvement and those who take a loan for debt consolidation is 3.86%

CONCLUSION:
Borrowers with a better credit history who take a loan for home improvement have a 3.86% lower chance of defaulting as compared to borrowers who take a loan for debt consolidation. 
