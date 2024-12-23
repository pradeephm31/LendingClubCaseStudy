# Project Name
> Lending Club Case Study


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- Problem Statement
    -  &nbsp;&nbsp;&nbsp;&nbsp;The consumer finance company faces a critical challenge in making loan approval decisions that minimize financial risks. When an applicant applies for a loan, the company needs to assess whether the applicant is likely to repay the loan. Approving loans to applicants who are likely to default results in significant financial losses, while rejecting loans from creditworthy applicants means missed business opportunities.
    -  &nbsp;&nbsp;&nbsp;&nbsp;The primary concern for the company is identifying "risky" applicants—those who are most likely to default. These defaulters cause the largest amount of credit loss. To address this, the company aims to analyze past loan data to identify patterns that predict whether an applicant is likely to default. By uncovering these patterns, the company can take proactive measures, such as denying loans to high-risk applicants, adjusting loan amounts, or charging higher interest rates. This data-driven approach will help the company reduce credit loss and better manage its loan portfolio, ensuring financial stability.

- Data Set
    - Loan Data Set was considered which has all the attributes of the Loan provided along with Loan Status 
	 
- Approach for analysis
1. Data Understanding and Cleaning	
   - This step involves understanding the dataset, cleaning the data, handling missing values, and preparing the dataset for analysis.

2. Univariate/Bivariate for Numerical
   - In this step, we analyze individual variables (univariate) and relationships between two numerical variables (bivariate).

3. Bivariate for Categorical Data
   - This part focuses on analyzing the relationship between categorical variables.

      


## Conclusions
- Outcome from Numerical Filed Anlaysis
  - int_rate (Interest Rate)indicates that Loans with higher int_rate have more risk of getting Defaulted
  - dti Debt to Income Ratio indicates that higher dti ratio are at higher risk of getting Defaulted
  - annual_inc  (Annual Income) even though the correlation is not very prominent but still lower annual_inc have higher risk of getting Defaulted
  - loan_amt (Loan Amount) even though the correlation is not very prominent but still higher loan_amt have higher risk of getting Defaulted

- OutCome from Categorical Analysis
  - The following Categorical Variables have a considerable impact on Loan getting Defaulted
	- term , Higher Term like 60 months are at a higher risk of getting defaulted
    - grade and sub_grade , lower the grade then higher is the risk of getting defaulted
    - purpose , the purpose named “small business” has a higher probability of getting defaulted in comparison to other purposes
    - addr_state , the state 'NE' has a higher probability of getting defaulted though the count of samples considered are very less
    - pub_rec_bankruptcies, higher the number of publicly recorded bankruptcies relates to higher risk of getting Defaulted
	 
  -	The following Categorical Variables do not have a significant or prominent impact on Loan getting Defaulted
	- emp_length
    - home_ownership
    - verification_status
    - pub_rec
    - issue_d

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas - version 2.2.2
- numpy - version 1.26.4
- matplotlib - version 3.8.4
- seaborn - version 0.13.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by EDA Course and Lecture Notes as part of IIIT-B PG Program in a ML and AI



## Contact
Created by [@pradeephm31 and @engineeramangupta] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->