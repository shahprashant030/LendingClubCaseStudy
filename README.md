# Credit Risk Analytics
> This project involves an in-depth analysis of a loan dataset from a consumer finance company. It aim to identify patterns and factors that indicate whether a loan applicant is likely to default on the loan, enabling the lending company to make informed lending decisions and minimize credit loss.



## Table of Contents
* [General Information](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- **Project Description**: This project involves analyzing loan data from a consumer finance company to mitigate credit risk. The objective is to leverage exploratory data analysis (EDA) and machine learning to identify patterns and indicators of loan default, enabling the company to make informed lending decisions.

- **Business Context**: The lending company specializes in providing various loans to urban customers. It faces the challenge of assessing loan applicants' creditworthiness to minimize credit loss. This involves managing two key risks:
   1. **Risk of Non-Approval**: Rejecting loans to creditworthy applicants leads to missed business opportunities.
   2. **Risk of Default**: Approving loans to applicants likely to default results in financial losses.
   
   By using data analytics, the company aims to predict loan defaults, optimize lending decisions, and mitigate credit risk effectively.

- **Key Business Problems Addressed**:
   1. **Identifying Loan Default Risk**: Develop a predictive model to identify applicants at risk of default.
   2. **Optimizing Lending Decisions**: Make informed decisions about loan approvals, rejections, or modifications based on applicant profiles and historical loan data.

- **Dataset**: The dataset used for analysis is "loan.csv," containing loan application data from 2007 to 2011.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
After going though the analysis we came to the the conclusion that there are various key factors that can decide if a customer is more likely to default. Customer is more likely to default when :
- Applicants having house_ownership as 'RENT'
- Applicants who use the loan to clear other debts
- Applicants who receive interest at the rate of 13-17%
- Applicants who have an income of range 31201 - 58402
- Applicants who have 20-37 open_acc
- Applicants with employement length of 10
- When funded amount by investor is between 5000-10000
- Loan amount is between 5429 - 10357
- Dti is between 12-18
- When monthly installments are between 145-274
- Term of 36 months
- When the loan status is Not verified
- When the no of enquiries in last 6 months is 0
- When the number of derogatory public records is 0
- When the purpose is 'debt_consolidation'
- Grade is 'B'
- And a total grade of 'B5' level.
- Applicants taking loan for 'home improvement' and have income of 60k -70k
- Applicants whose home ownership is 'MORTGAGE and have income of 60-70k
- Applicants who receive interest at the rate of 21-24% and have an income of 70k-80k
- Applicants who have taken a loan in the range 30k - 35k and are charged interest rate of 15-17.5 %
- Applicants who have taken a loan for small business and the loan amount is greater than 14k
- Applicants whose home ownership is 'MORTGAGE and have loan of 14-16k
- When grade is F and loan amount is between 15k-20k
- When employment length is 10yrs and loan amount is 12k-14k
- When the loan is verified and loan amount is above 16k
- For grade G and interest rate above 20%


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas - version 1.5.3
- matplotlib - version 3.7.0
- numpy - version 1.23.5
- seaborn - version 0.12.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by upGrad
- upGrad learning platform
- References:
   - https://stackoverflow.com/
   - https://stackexchange.com/
   - https://towardsdatascience.com/an-extensive-guide-to-exploratory-data-analysis-ddd99a03199e
   - https://www.analyticsvidhya.com/blog/2021/10/handling-missing-value/
   - https://pynative.com/pandas-drop-na-columns-from-dataframe/
   - https://www.numpyninja.com/post/automated-eda-exploratory-data-analysis-and-data-cleaning-in-python-using-dataprep 
- This project was based on 
   - [Youtube tutorial](https://www.youtube.com/watch?v=F-X82zhIfBo&ab_channel=KrishNaik)
   - [Kaggle tutorial](https://www.kaggle.com/code/spscientist/a-simple-tutorial-on-exploratory-data-analysis)


## Contact
Created by [@shahprashant030] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->