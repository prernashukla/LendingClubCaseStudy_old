# Lending Club Case Study
---
## Case study assignment by IIIT Bangalore and Upgrad
---
> Solving this assignment will give you an idea about how real business problems are solved using EDA. In this case study, apart from applying the techniques you have learnt in EDA, you will also develop a basic understanding of risk analytics in banking and financial services and understand how data is used to minimise the risk of losing money while lending to customers.
> Developed as part of the Exloratory Data Analysis Module required for Executive Post Graduate Program in Machine Learning and AI - IIIT,Bangalore.
---

## Table of Contents
* [General Information](#general-information)
* [Methodology](#methodology)
* [Repository contents](#repository-contents)
* [Conclusions](#conclusions)

## General Information
- Lending club company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface.
- Lending loans to *‘risky’* applicants is the largest source of financial loss (called credit loss). There are two types of risks associated with the bank’s decision:
> - If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company.
> - If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.
- Borrowers who default cause the largest amount of loss to the lenders.

**Objective:**
The aim is to understand the **driving factors (or driver variables) behind loan default**, i.e. the variables which are strong indicators of default using EDA.

## Methodology
1) Data Sourcing and Understanding
2) Data Cleaning and Manipulation
3) Univariate Analysis
4) Segmented Univariate Analysis
5) Bivariate Analysis
6) Multivariate Analysis

## Repository contents
| File | Description |
|:-----|:------------|
| Python notebook | It contains the complete detailed code along with plots to analyse the given data for finding the driving factors.|
| PDF | Summarized the analysis in a presentation |
| README.md | This filed briefs about the project. |
| loan.csv | The lending club loan dataset. |
| Data_Dictionary.xlsx | Meaning of the variables in the loan dataset. |
| imp_loan_data.csv | Contains the filtered important loan data. |

## Conclusions
**To assess if the applicant might default**
- Look into the grade of the applicant.
- Validate the purpose of the loan.
- Look into annual income, installment and revolving utilization rate.
- Look into the status of defaulters from the applicant’s state.

**To avoid defaulters (either by rejecting or taking some measures)**
- Based on the assessment and driving factors, control the percentage of loan approved.
- Promote more short term loans by attractive interest rates.
- Reduce the interest rate for long term loans.
- Reduce the interest rate to below 15% for people with less than 100000 as their annual income.
- Reduce the loan amount approved for experience people.
- For people with OTHER home ownership, if they have high installments, either reduce/reject the loan amount.
- Reject loans to people with more derogatory who might tend to bankrupt.

## Contact
Created by [@shruthipv96] - feel free to contact me!
