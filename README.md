## Project Name: Lending Club Case Study

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information

### Problem Statement
* Find the driving factors which lead to the defaulted loans which are major source of loss for the company.

### Business Understanding 
* Lending Club is a finance company that specializes in lending to urban customers.
* When receiving a loan application, the decision to approve hinges on the applicant's profile.
* The bank faces two risk scenarios in the decision-making process:
- If the applicant is expected to repay, denying the loan results in lost business for the company.
- If the applicant is likely to default, approving the loan could lead to financial loss for the company.

### Data Set
* The data set is a csv file with the loan data for the Lending Club.

## Technologies Used
* pandas - Ver 2.0.3
* numpy – Ver 1.25.2
* matplotlib – Ver 3.7.1
* seaborn – Ver 0.13.1
* scipy – Ver 1.11.4
* IPython – Ver 7.34.0

## Process
* Step 1: Data Cleaning 1  
* Step 2: Univariate Analysis
* Step 3: Segemented Univariate Analysis
* Step 4: Bivaraiate/Multivariate Analysis
* Step 5: Results 

## Conclusions
Certainly! Here's a more formal presentation of the key findings from the exploratory data analysis (EDA) of the loan dataset, categorizing factors by their impact on loan default:

* Factors with Minor Impact
o Higher loan amount (above $16,000)
o Higher instalment amount (above $327)
o Lower annual income (below $37,000)
o Higher debt-to-income ratio (above 15%)
o Applicant’s address state (e.g., NV, SD, AK, FL)
o Loan issue month (Dec, May, Sep)
* Factors with Heavy Impact
o Higher interest rate (above 13%)
o Higher revolving line utilization rate (above 58%)
o Repayment term of 5 years
o Loan grade & sub-grade (D to G)
o Missing employment record
o Loan purpose (small business, renewable energy, educational)
o Derogatory public records (1 or 2)
o Public bankruptcy records (1 or 2)
* Factors with Combined Impact
o High loan amount & interest rate for lower income group
o High instalment and longer repayment term
o Home ownership (other) and loan purpose (car, moving, or small business)
o Residential state and loan purpose
o Income group and loan purpose
This EDA identifies these factors as the most impactful drivers for loan default, providing valuable insights into risk assessment and decision-making processes within the lending industry.


## Acknowledgements
This project was inspired by UpGrad IITB Programme as a case study for the Machine Learning and Artificial Intelligence course.

## Contact
Created by [@HarshRDJ, @SarvajeetLuthra] - feel free to contact me!

## Licence
This project is open source and available without restrictions.
