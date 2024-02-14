# Lending Club Case Study
>Lending Club is a consumer finance marketplace for personal loans that matches borrowers who are seeking a loan with investors looking to lend money and make a return.

It specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant's profile.

Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed.

In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.

The core objective of the excercise is to help the company minimise the credit loss. There are two potential sources of credit loss are:

1. Applicant likely to repay the loan, such an applicant will bring in profit to the company with interest rates.** Rejecting such applicants will result in loss of business**.
2. Applicant not likely to repay the loan, i.e. and will potentially default, then approving the loan may lead to a financial loss* for the company.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- The goal is to identify the risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA using the given dataset, is the aim of this case study.

If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. The company can utilise this knowledge for its portfolio and risk assessment..
-
- Identifying the risky loan applicants
- Loan data set
- Step1: Data cleaning
- Step2: Univariant data analysis
- Step3: Multivariant data analysis
- Results

## Conclusions
- Conclusion 1 - Observations with charged off loan, there is a more porbability of defaulting when
	1. Applicants in RENTAL home
	2. Applicants with income 30k to 50k
	3. When loan status is not verified
	4. Who takes loan at higher interest rate
	5. Who use the loan to clear other loans
- Conclusion 2 from the analysis 
	1. loans taken for home improvement
	2. home ownership is mortgage
	3. with higher interest rate like 21 to 24%
	4. loans taken for smaller business
	5. loans taken by people with lower grades


## Technologies Used
- python - version 3.2.2
- pandas - version 2.2.0
- numpy - version 1.26.3
- seaborn - Version 0.13.2
- Jupyter Notebook - Version 7.0.5
- JupyterLab - Version 4.0.10
- Anaconda - Version 2.1.4
- matplotlib - Version 3.5.1


## Acknowledgements
- This project was inspired by Anand
- This project was based on https://learn.upgrad.com/course/5796/segment/42776/264187/807543/4058681


## Contact
Created by [@githubusername] - feel free to contact me!


