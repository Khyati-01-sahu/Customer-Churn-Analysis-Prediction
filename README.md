# Customer-Churn-Analysis-Prediction
Customer Churn Analysis & Prediction Using Python
Project Overview
Customer churn refers to customers discontinuing a company’s service. Retaining existing customers is more cost-effective than acquiring new ones. This project analyzes customer behavior and builds a machine learning model to predict churn, enabling proactive customer retention strategies

Objectives
Perform exploratory data analysis (EDA) to understand churn patterns
Identify key factors influencing customer churn
Build and evaluate a churn prediction model
Generate business insights to reduce churn

Dataset
Source: Telco Customer Churn Dataset
Records: ~7,000 customers
Target Variable: Churn (Yes / No)

Key features include:
Customer demographics
Service usage details
Contract and billing information
Monthly and total charges

Technologies Used
Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn

Exploratory Data Analysis
Key insights from EDA:
Customers with shorter tenure are more likely to churn
Month-to-month contracts show the highest churn rates
Higher monthly charges increase churn probability

Model Building
Model Used: Logistic Regression
Data preprocessing:
Missing value treatment
Categorical encoding
Feature scaling
Train-test split: 80-20

Model Evaluation
Accuracy Score
Confusion Matrix
Precision, Recall, F1-score
Recall was prioritized to correctly identify churn-prone customers.

Key Business Insights
Long-term contracts reduce churn risk
High monthly charges increase churn probability
Tenure is a strong negative predictor of churn
