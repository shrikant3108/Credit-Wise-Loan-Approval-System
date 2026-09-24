# Credit-Wise-Loan-Approval-System
A Machine Learning classification project that predicts whether a loan application is likely to be approved based on applicant and financial information.

Project Overview

This project implements a complete machine learning workflow for loan approval prediction, including:

Data loading and preprocessing
Missing-value handling
Categorical feature encoding
Feature correlation analysis
Feature engineering
Train-test splitting
Feature scaling
Machine learning model training
Model evaluation
Loan approval prediction for new applicant data
Machine Learning Models

The project compares three classification algorithms:

Logistic Regression
K-Nearest Neighbors (KNN)
Gaussian Naive Bayes

The models are evaluated using:

Accuracy
Precision
Recall
F1-Score
Confusion Matrix
Classification Report
Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Jupyter Notebook
Data Preprocessing

The dataset is processed using:

Mean imputation for numerical missing values
Most-frequent imputation for categorical missing values
Label Encoding for selected categorical features
One-Hot Encoding for categorical variables
StandardScaler for feature scaling
Removal of the unused Applicant_ID feature

Feature engineering is also applied to selected financial features before model training.

Prediction

The trained model can be used to predict loan approval for a new applicant.

Example output:

YES Loan will be Provided

or

Sorry Loan will not provided

Project Structure
Smart-Loan-System/
│
├── Shrikant_vijay_kharde_Smart_Loan_System.ipynb
├── loan_approval_data.csv
└── README.md
Objective

The objective of this project is to demonstrate how machine learning classification algorithms can be applied to financial application data to build a basic automated loan approval prediction system.
