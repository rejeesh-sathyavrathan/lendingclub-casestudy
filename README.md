# Lending Club Case Study
> Identify critical parameters to determine possibility of Charged Off loan applications by performing Exploratory Data Analysis on historic data.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
Lending Club is a marketplace for personal loans that matches borrowers who are seeking a loan with investors looking to lend money and make a return. 

When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
 - If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
 - If the applicant is not likely to repay the loan, i.e., he/she is likely to default, then approving the loan may lead to a financial loss for the company

Company wants to understand the driving factors (or driver variables) behind loan default, i.e., the variables which are strong indicators of default.  The company can utilize this knowledge for its portfolio and risk assessment. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Avoid loans with Grade D, E, F, G.
- Avoid when interest rate is more than 14.9.
- Prefer loans with 30 months as term.
- Avoid loans with amount more than 24,650
- Avoid loans when applicant has an annual income less than 3854

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- python - 3.9.1.3
- pandas
- seaborn
- matplotlib.pyplot

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was inspired by the teaching staff at Upgrad and IIITB


## Contact
Created by rejeesh.sathyavrathan@gmail.com and vvs55457@gmail.com - feel free to contact us!