# Predicting-Employee-Attrition-Using-HR-Data

Employee Attrition Prediction

Author: Linh Huynh
Course: DSC550 – Data Mining, Bellevue University

1. Project Overview

This project predicts employee attrition (employee turnover) using machine learning. The goal is to identify employees who may leave the company so HR teams can take early actions to improve retention. 

Term Project.Final- LHuynh

2. Dataset

IBM HR Analytics Employee Attrition & Performance Dataset
Source: Kaggle

1,407 rows

35 features

Target variable: Attrition

Key variables include job satisfaction, environment satisfaction, monthly income, job role, and years at company.

3. Methods

Project workflow:

Data cleaning and preprocessing

One-hot encoding of categorical variables

Train-test split (80/20)

SMOTE for class imbalance

Model training and evaluation

Models used:

Logistic Regression

Random Forest

XGBoost

4. Results

All models achieved over 80% accuracy.

Logistic Regression performed best with a better balance of precision and recall for detecting employees likely to leave.

5. Tools

Python

Pandas

Scikit-learn

XGBoost

Matplotlib / Seaborn

6. Author

Linh Huynh

MS Data Science – Bellevue University
