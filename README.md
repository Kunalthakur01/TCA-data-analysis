# TCA-data-analysis
📊 Customer Churn Analysis
📌 Overview

This project focuses on analyzing customer churn data for a telecom company.
The main objective is to identify patterns and factors that influence customer retention and to build predictive models to forecast churn.

📂 Dataset

File: Customer Churn.csv

Rows: 7,043

Columns: 21

Target Variable: Churn (Yes / No)

Features:

Customer demographics (Gender, SeniorCitizen, Partner, Dependents)

Account details (Tenure, Contract type, Payment method)

Services subscribed (PhoneService, InternetService, Streaming, Security)

Billing information (MonthlyCharges, TotalCharges)


Yes
🛠 Project Workflow

Data Cleaning

Handling missing values

Converting data types (e.g., TotalCharges to numeric)

Exploratory Data Analysis (EDA)

Distribution of churn vs. non-churn customers

Impact of contract type, tenure, and monthly charges

Feature Engineering

Encoding categorical variables

Scaling numerical features

Model Building

Logistic Regression

Random Forest Classifier

XGBoost

Model Evaluation

Accuracy, Precision, Recall, F1-score

Confusion Matrix

ROC Curve & AUC Score

Insights & Recommendations

Identify high-risk churn segments

Suggest retention strategies


📊 Results

Best performing model: Random Forest with ~XX% accuracy

Key churn indicators:

Month-to-month contracts have higher churn rate

Higher monthly charges lead to more churn

Customers with fiber optic internet churn more than DSL users

📌 Technologies Used

Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost)

Jupyter Notebook
