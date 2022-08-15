# Lending Club Case Study

> Lending Club is a finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
  1.If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company.
  2.If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company
   


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)



## General Information

- What is the background of your project?
This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface.
    Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 
    
- What is the business probem that your project is trying to solve?
If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.
    In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 
    
- What is the dataset that is being used?
Loan Data Set: It contains the complete loan data for all loans issued through the time period 2007 to 2011.
   

## Conclusions
- Factor whether an applicant will be Defaulter:
    Continuous Variable:
    1. LOAN_AMOUNT : Charged-off loans tend to have higher loan amounts when compared to fully paid.
    2. INTEREST_RATE : As Interest rate increases the default rate increases steeply.
    3. ANNUAL_INCOME : As the annual income increase the default rate decreases.
    4. DTI : As dti increase the default rate increases.
    
    Categorical Variable:
    1. TERM : 60 months term have a higher default rate than 36 months term.
    2. GRADE : As the Grade decreases (A B C D E F G) default rate increases.
    3. SUB_GRADE : As the Sub Grade decreases (A1 A2 B1 B2.....) default rate increases.
    4. VERIFICATION STATUS : Percent of loan defaulted is higher for verifed borrowers.
    
    Decisive Factor whether an applicant will be Defaulter:
    
    - INTEREST_RATE
    - ANNUAL_INCOME
    - DTI
    - TERM
    - GRADE
    - SUB_GRADE

## Technologies Used
- pandas - 1.3.4
- numpy - 1.20.3
- matplotlib - 3.4.3
- seaborn - 0.11.2
- plotly - 5.8.0
   


## Acknowledgements
This project was Lending club case study for an online advance course.
    - https://www.geeksforgeeks.org/
    - https://seaborn.pydata.org/
    - https://plotly.com/
    - https://pandas.pydata.org/
    - https://learn.upgrad.com/


## Contact
Created by [@ravivijay07] - feel free to contact me!


