# 📊 Task 3: Customer Churn Prediction (Bank Customers)
📌 Internship

DevelopersHub Corporation
Data Science & Analytics Internship

# 🎯 Objective

The objective of this task is to build a machine learning classification model to predict whether a bank customer is likely to leave (churn) or stay. The goal is to analyze customer behavior and identify key factors influencing churn.

# 📂 Dataset

The dataset used for this task is the Churn Modelling Dataset:

Churn Modelling Dataset

It contains customer information such as:

Credit Score
Geography
Gender
Age
Balance
Number of Products
Has Credit Card
Estimated Salary
Exit status (Target Variable)
# 🛠️ Tools & Libraries Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
# 📊 Project Workflow
1. Data Loading
Dataset loaded using Pandas (read_csv)
Initial structure explored using .head(), .shape, and .info()
2. Data Cleaning
Removed irrelevant columns such as:
RowNumber
CustomerId
Surname
Checked and confirmed absence of missing values
3. Data Preprocessing
Gender was encoded using Label Encoding
Geography was encoded using One-Hot Encoding
Converted all categorical variables into numerical format
4. Exploratory Data Analysis (EDA)

Basic analysis was performed to understand patterns in the dataset such as:

Customer distribution across geography
Relationship between features and churn behavior
Impact of financial attributes on customer retention
5. Model Training

A Random Forest Classifier was used to train the model:

Training set: 80%
Testing set: 20%
Model parameters: 100 estimators
6. Model Evaluation

The model was evaluated using:

Accuracy Score
Confusion Matrix
Classification Report
7. Feature Importance Analysis

Feature importance was extracted from the Random Forest model to identify which factors most influence customer churn.

# 📈 Results
The model achieved good accuracy in predicting customer churn.
Feature importance analysis revealed key drivers of churn behavior.
Random Forest performed well for this classification problem.
# 🔑 Key Insights
Age and credit score are strong indicators of churn.
Balance and account activity significantly influence customer retention.
Geography plays a role in churn probability.
Some features (like surname) have no predictive value.
# 🚀 Conclusion

This task demonstrates how machine learning can be used in the banking sector to predict customer churn and improve retention strategies. Data preprocessing, encoding, and feature importance analysis were key steps in building an effective model.

# Author

DevelopersHub Data Science Intern
Faiza Memon
