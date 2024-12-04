# Bank-Marketing-Advance-Python-Project
Overview
This project focuses on analyzing a large dataset containing customer application information from a financial institution. The goal is to extract insights, identify trends, and support decision-making processes such as credit scoring, customer segmentation, and risk assessment.
#
Dataset Information#
Rows: 49,999#
Columns: 122
Size: 46.5+ MB
Data Types:
Numeric: 64 columns (e.g., income, credit amount, annuity)  
Categorical: 42 columns (e.g., contract type, gender, document flags)
Object (Strings): 16 columns (e.g., property ownership, employment details)
Key Columns
SK_ID_CURR: Unique ID for each customer.
TARGET: Binary target variable indicating default status:
1: Client with payment difficulties.
0: Client with no payment difficulties.
NAME_CONTRACT_TYPE: Type of loan (e.g., Cash loans, Revolving loans).
AMT_CREDIT: Total credit amount for the loan.
AMT_INCOME_TOTAL: Annual income of the client.
CNT_CHILDREN: Number of children the client has.
FLAG_OWN_CAR: Whether the client owns a car.
FLAG_OWN_REALTY: Whether the client owns property.
AMT_REQ_CREDIT_BUREAU_X: Frequency of credit inquiries (various timeframes).
Objectives
Descriptive Analysis:
Understand customer demographics and loan preferences.
Identify correlations between income, credit amount, and default rate.

Risk Analysis:
Segment customers based on risk factors like income stability and credit history.
Assess document and property ownership flags for default probability.
Steps Undertaken
Data Cleaning:
Handle missing values in columns like AMT_REQ_CREDIT_BUREAU_*.
Normalize numerical variables for better comparisons.
Exploratory Data Analysis (EDA):
Visualize income distributions, loan amounts, and default rates.
Analyze categorical distributions (e.g., gender, contract type).
Feature Engineering:
Create derived variables like Debt-to-Income Ratio (DTI).
Group clients based on demographic or financial characteristics.
Modeling:
Apply classification algorithms (e.g., Logistic Regression, Random Forest).
Evaluate model performance using metrics like ROC-AUC and F1-Score.
Visualization:
Generate plots and dashboards to communicate findings effectively.
Potential Outcomes
Identification of high-risk customers based on predictive modeling.
Insights into how demographic and financial variables impact loan performance.
Recommendations for improving loan approval strategies and minimizing defaults.












