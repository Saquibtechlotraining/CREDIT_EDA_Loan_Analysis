# Project Title: Credit EDA Loan Analysis
### Project Overview - 
#### This project focuses on applying Exploratory Data Analysis (EDA) within the banking and financial services sector, with a specific emphasis on risk analytics. The primary goal is to utilize data analysis techniques to minimize financial losses while making lending decisions.

### Business Understanding:
#### Lending institutions often face challenges when assessing loan applications from individuals with limited or no credit history, leading to potential defaults. In this scenario, imagine working for a consumer finance company specializing in urban lending. The objective is to leverage EDA to uncover data patterns that ensure deserving loan applicants are not unfairly rejected.

### Business Objectives:
#### The key objectives of this case study are as follows:
#### ① Identify patterns that indicate whether a client may struggle to repay installments.
#### ② Utilize these patterns to inform lending decisions, which may include loan denial, reduced loan amounts, or offering higher-interest  loans to higher-risk applicants.
#### ③ Ensure deserving applicants are not denied loans.

## Table of Contents
### 1. Load the Data  
### 2. Import All Necessary Python Libraries
### 3. Perform Data Cleaning and Preparations
### 4. Outliers Analysis
### 5. Loan Application Status
### 6. Gender Distribution
### 7. Gender-based Loan Application Status
### 8. Count of Contract Types by Education
### 9. Credit Amount by Number of Children
### 10. Income Distribution by Income Type
### 11. Five key result of this project
### 12. Project Link

## Platform for EDA:- 
#### Jupyter notebook   ![icons8-jupyter-20](https://github.com/Saquibtechlotraining/CREDIT_EDA_Loan_Analysis/assets/91885135/7607b9bb-19e0-4ab6-98d8-3cd71cf7a20f)

## Load the Data 
### Access and understand these dataset.
#### • 'application_data.csv': Contains client information at loan application time, including payment difficulties
 File Part-1 [Click Here](https://github.com/Saquibtechlotraining/CREDIT_EDA_Loan_Analysis/blob/main/application_data.part1.rar)

 File Part-2 [Click Here](https://github.com/Saquibtechlotraining/CREDIT_EDA_Loan_Analysis/blob/main/application_data.part2.rar)

#### • 'previous_application.csv': Provides details of the client's previous loan data, indicating whether previous applications were approved, cancelled, refused, or unused.
File Part-1 [Click Here](https://github.com/Saquibtechlotraining/CREDIT_EDA_Loan_Analysis/blob/main/previous_application.part01.rar)

File Part-2 [Click Here](https://github.com/Saquibtechlotraining/CREDIT_EDA_Loan_Analysis/blob/main/previous_application.part02.rar)

File Part-3 [Click Here](https://github.com/Saquibtechlotraining/CREDIT_EDA_Loan_Analysis/blob/main/previous_application.part03.rar)

#### • 'columns_description.csv': A data dictionary explaining variable meanings and significance.

File [Click Here](https://github.com/Saquibtechlotraining/CREDIT_EDA_Loan_Analysis/blob/main/columns_description.csv)

## Import All Necessary Python libraries:-
#### In this step, we import the required Python libraries such as :-
##### ‣ Numpy          ![icons8-numpy-20](https://github.com/Saquibtechlotraining/CREDIT_EDA_Loan_Analysis/assets/91885135/1a004217-9d23-4376-9af6-01438e766187)
##### ‣ Pandas         ![icons8-pandas-20](https://github.com/Saquibtechlotraining/CREDIT_EDA_Loan_Analysis/assets/91885135/f811ea01-608a-4c1e-8e7b-b249e0d67aa7)
##### ‣ Matplotlib     ![matplotlib-tutorial (1)](https://github.com/Saquibtechlotraining/CREDIT_EDA_Loan_Analysis/assets/91885135/d1f0c134-4ca5-4b9e-a950-4729954e9154)
##### ‣ Seaborn        ![fd110d80-63d1-11eb-9ae4-de7c23c9dedc (1)](https://github.com/Saquibtechlotraining/CREDIT_EDA_Loan_Analysis/assets/91885135/ad304a7c-1be0-4af5-9b50-a3079c829b3e)

## Perform Data Cleaning and Preparations
#### • Data cleaning is crucial for ensuring data quality. We remove columns containing more than 10% null values.
#### • Unwanted columns were deleted, retaining only the 'AMT_ANNUITY' columns for analysis.

## Outliers Analysis
#### • The 'AMT_INCOME_TOTAL' column was analyzed to understand income distribution and potential discrepancies.
#### • Identified outliers in the income data which may need further investigation.

## Loan Application Status
#### • Calculated the percentage of approved, canceled, refused, and unused loan applications based on data from the previous application CSV file.
#### • Visualized the distribution of loan application statuses using a pie chart.
![download (1)](https://github.com/Saquibtechlotraining/CREDIT_EDA_Loan_Analysis/assets/91885135/c3b9e115-6d1b-4492-8b1c-0de15dce28fc)

## Gender Distribution
#### • Calculated the percentage of male and female loan applicants to understand the gender distribution among applicants.
#### • Visualized the gender distribution using a pie chart.
![download (2) (1)](https://github.com/Saquibtechlotraining/CREDIT_EDA_Loan_Analysis/assets/91885135/40f8d76f-cde9-482d-bc58-b929ef17d0a0)

## Income Range Analysis
#### • Created an 'AMT_Income_Range' variable to categorize income ranges based on income levels.
#### • Provided insights into applicant income distribution. 

## Gender-based Loan Application Status
#### • Analyzed the count of approved, refused, canceled, and unused loan offers for both male and female applicants.
#### • Visualized the results to compare loan application statuses between genders.

![download (6) (1)](https://github.com/Saquibtechlotraining/CREDIT_EDA_Loan_Analysis/assets/91885135/2d42fcb2-1540-4410-9fe5-6f9cb1660344)
## Count of Contract Types by Education
#### • Counted the occurrences of each 'name_contract_type' within each 'name_education_type'.
#### • Visualized the counts to understand the relationship between contract types and education.
![download (5) (2)](https://github.com/Saquibtechlotraining/CREDIT_EDA_Loan_Analysis/assets/91885135/af22fcf9-e024-441b-8abb-24ab31639d3d)



## Credit Amount by Number of Children
#### • Analyzed the credit amount for loan applicants based on the number of children they have.
#### • Visualized the distribution of credit amounts for different numbers of children.
![download (4) (1)](https://github.com/Saquibtechlotraining/CREDIT_EDA_Loan_Analysis/assets/91885135/0eaeead7-d106-446e-9925-844b207c7827)

## Income Distribution by Income Type
#### • Analyzed the distribution of income based on income type.
#### • Visualized the income distribution for different income sources.
![download (3) (1)](https://github.com/Saquibtechlotraining/CREDIT_EDA_Loan_Analysis/assets/91885135/632142c3-2d89-42d9-bc43-4e22655099e2)

## Five key result of this project:-
#### ① Risk Patterns Identification: The analysis successfully identified patterns in the data that indicate clients who may struggle to repay installments, enabling the lending institution to assess and manage credit risk effectively.
#### ② Gender-based Disparities: Gender-based analysis highlighted differences in loan application outcomes between male and female applicants, shedding light on potential gender biases in lending decisions.
#### ③ Income Range Insights: The creation of 'AMT_Income_Range' provided insights into the income distribution of applicants, allowing for tailored loan products based on income levels.
#### ④ Analysis of income types and their corresponding total income.
#### ④ Contract Types and Education: The analysis revealed the relationship between contract types and education levels, assisting in the development of targeted lending strategies for different educational backgrounds.
#### ⑤ Family Size Impact: The examination of credit amounts in relation to the number of children showed how family size can influence loan requests, informing risk assessments for applicants with dependents.
