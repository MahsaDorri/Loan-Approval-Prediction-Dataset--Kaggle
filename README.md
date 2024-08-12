# Loan-Approval-Prediction-Dataset--Kaggle
This repository contains the code and analysis for predicting loan approval using various machine learning models. The dataset used for this project includes several features related to the applicant's financial information, employment status, and credit history. The goal is to build models that can accurately predict whether a loan application will be approved or rejected.

# Project Overview
Dataset
The dataset used in this project includes the following features:

No. of Dependents: Number of people dependent on the applicant.
Education: Educational background of the applicant (Graduate/Not Graduate).
Self-Employed: Whether the applicant is self-employed (Yes/No).
Income Annum: Annual income of the applicant.
Loan Amount: Amount of loan requested.
Loan Term: Duration of the loan.
CIBIL Score: Credit score of the applicant.
Residential Assets Value: Value of residential assets owned by the applicant.
Commercial Assets Value: Value of commercial assets owned by the applicant.
Luxury Assets Value: Value of luxury assets owned by the applicant.
Bank Asset Value: Total value of assets held in the applicant's bank.
Loan Status: Target variable indicating whether the loan was approved or rejected.
# Project Steps
Data Preprocessing:

# Handled missing values.
Encoded categorical variables (e.g., Education, Self-Employed, Loan Status).
Removed outliers using the 3-sigma rule.
Scaled numerical features using StandardScaler.
Modeling:

Implemented various machine learning models including:
Logistic Regression
Decision Tree Classifier
Random Forest Classifier
Gradient Boosting Machine (GBM)
XGBoost
Neural Networks (MLPClassifier)
Each model was trained, tested, and evaluated for accuracy, confusion matrix, and classification report.
Model Comparison:

Compared the performance of all models based on their accuracy scores.
Sorted and displayed the models from the best to worst performer.
Results
The models were evaluated based on their predictive accuracy. The top-performing models were XGBoost and Random Forest, indicating that ensemble methods are particularly effective for this dataset.
