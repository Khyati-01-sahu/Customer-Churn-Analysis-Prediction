# Customer-Churn-Analysis-Prediction
Customer Churn Analysis & Prediction Using Python
Project Overview
Customer churn refers to customers discontinuing a company’s service. Retaining existing customers is more cost-effective than acquiring new ones. This project analyzes customer behavior and builds a machine learning model to predict churn, enabling proactive customer retention strategies

Objectives
<br>
Perform exploratory data analysis (EDA) to understand churn patterns
Identify key factors influencing customer churn
Build and evaluate a churn prediction model
Generate business insights to reduce churn

Dataset
<br>
o Source: Telco Customer Churn Dataset
o Records: ~7,000 customers
o Target Variable: Churn (Yes / No)

Key features include:
<br>
o Customer demographics
o Service usage details
o Contract and billing information
o Monthly and total charges

Technologies Used
<br>
o Python
o Pandas, NumPy
o Matplotlib, Seaborn
o Scikit-learn

Exploratory Data Analysis
<br>
Key insights from EDA:
o Customers with shorter tenure are more likely to churn
o Month-to-month contracts show the highest churn rates
o Higher monthly charges increase churn probability

Model Building
<br>
Model Used: 
o Logistic Regression
Data preprocessing:
o Missing value treatment
o Categorical encoding
o Feature scaling
Train-test split: 80-20

Model Evaluation
<br>
o Accuracy Score
o Confusion Matrix
o Precision, Recall, F1-score
o Recall was prioritized to correctly identify churn-prone customers.

Key Business Insights
o Long-term contracts reduce churn risk
o High monthly charges increase churn probability
o Tenure is a strong negative predictor of churn
