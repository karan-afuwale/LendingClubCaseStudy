# Lending Club Case Study
This project involves working with the loan marketplace, which offers loans to customers.

Similar to many lending institutions, the primary financial challenge for this marketplace is managing credit loss, which occurs when loans are granted to high-risk applicants who either default or abscond with the funds. Credit loss represents the financial setback experienced by lenders when borrowers fail to repay their loans. In this context, 'charged-off' customers are identified as defaulters.

The goal of this case study is to utilize exploratory data analysis (EDA) to identify high-risk loan applicants. By recognizing these risky borrowers, the marketplace can reduce the incidence of credit loss and minimize financial risks.


## Table of Contents
* [Objectives](#objectives)
* [Data cleanup and manupulation](#data-cleanup-and-manupulation)
* [Technologies Used](#technologies-and-tools-used)
* [Conclusions](#conclusions)
* [How to run](#how-to-run)
* [Team](#team)
* [Contact](#Contact)


## Objectives
The objective of this study is to identify the key factors that contribute to loan defaults—specifically, the variables that are strong predictors of borrower default. By pinpointing these high-risk indicators, we can better manage and reduce loans to such applicants, thereby minimizing credit loss. The focus of this case study is to leverage exploratory data analysis (EDA) to uncover these critical driver variables and enhance our understanding of default risk.


## Data cleanup and manupulation
- Understanding data, data types, missing values and outliers
- Dropping the columns with more than 50% of missing values and with single values
- Remove all the rows with unwanted loan status (Current as it doesn’t signify any roles here)
- Remove %, hyphens (-), converting variables to date time , int and float
- Remove outliers
- Converting some numerical variables to ordered categorical (Binning)


## Technologies and tools Used
- Python - Version 3.11.7
- numpy - Version 1.26.4
- pandas - Version 2.1.4
- matplotlib - Version 3.8.0
- seaborn - Version 0.13.2
- Jupyter Notebook - Version 7.0.8
- Anaconda - Version 24.7.1


## Conclusions
To enhance the verification process and mitigate risks associated with loan defaults, consider the following points:

1. **Reduce Non-Verified Applicants**
   - Strengthen the Verification Process : By decreasing the number of "Non-verified" applicants, the risk of defaults can be significantly mitigated.

2. **Consider Factors During the Evaluation Process**
   - Integrate various risk factors such as:
     - **Employment Length**
     - **Loan Term**
     - **Credit Grade**
   - This integration will provide deeper insights into loan risk assessment.

3. **State and Purpose-Based Restrictions**
   - Implement policies for:
     - **High-Risk Geographic Regions**
     - **Specific Loan Purposes**, especially debt consolidations.

4. **Variables with Negative Correlations**
   - Include negatively correlated variables in the evaluation process:
     - **Annual Income vs. Debt-to-Income Ratio (DTI)**
     - **Interest Rate vs. Employment Length**


## Team
- [Akshay Handoo](https://www.linkedin.com/in/akshay-handoo-88b9b5150/)
- [Karan Afuwale](https://www.linkedin.com/in/karan-afuwale-06380114/)
