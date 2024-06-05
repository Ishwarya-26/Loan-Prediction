# Loan-Prediction
## Introduction
This project is about the development of a machine learning model to predict loan approvals for JKM Bank to assist in identifying potential loan customers from their existing applicants data.
## About Dataset
The datset is downloaded from Kaggle.This dataset contains information about loan applicants for an imaginary bank called JKM, such as income, age,credit card average etc.

## Data Description
ID:	Customer ID		

Age:	Customer's age in completed years	

Experience:	#years of professional experience							

Income:	Annual income of the customer ($000)							

ZIPCode:	Home Address ZIP code.							

Family:	Family size of the customer	

CCAvg:	Avg. spending on credit cards per month ($000)		

Education:Education Level. 1: Undergrad; 2: Graduate; 3: Advanced/Professional		

Mortgage:	Value of house mortgage if any. ($000)			

Personal Loan: Did this customer accept the personal loan offered in the last campaign?							

Securities Account:	Does the customer have a securities account with the bank?					

CD Account:	Does the customer have a certificate of deposit (CD) account with the bank?						

Online:	Does the customer use internet banking facilities?			

CreditCard:	Does the customer use a credit card issued by UniversalBank?							


## Problem Statement
Develop a machine learning model to predict whether a loan application will be approved or not, based on the applicant's details.
## How this model helps the JKM bank?
1. The bank can focus its advertising on those who most likely to take loan
2. With the model's help,the bank can potentially speed up the loan application process for good customers.
## Feature and target variable
### Feature variable
Customer Demographics: Age, Family size, ZIP code

Financial Information: Experience, Income, Mortgage value, Credit card average spending

Customer Profile : Education level, Securities account, CD account, Online banking usage, Credit card usage with the bank

### Target variable:
Personal Loan
## Conclusion
Used a Logistic Regression model to classify loan applications as approved or rejected. The model achieved an accuracy of 0.944 on the test set, indicating a good ability to correctly classify a large proportion of applications.
