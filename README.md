# Credit Worthiness Classification

# Overview

This project focuses on predicting a customer's credit worthiness using Machine Learning techniques. The goal is to classify applicants based on their financial and personal information to assist in credit risk assessment and lending decisions.

# The project includes:
<ul>
    <li> Data Cleaning and Preprocessing </li>
    <li> Exploratory Data Analysis (EDA) </li>
    <li> Feature Engineering </li>
    <li> Data Transformation and Encoding </li>
    <li> Model Training </li>
    <li> Hyperparameter Tuning using GridSearchCV </li>
    <li> Model Evaluation and Comparison </li>
</ul>

# Dataset Features :

The dataset contains applicant information such as:

Checking Account Balance
Credit Duration
Credit History
Loan Purpose
Loan Amount
Savings Account Balance
Employment Duration
Installment Rate
Property Information
Age
Housing Type
Number of Existing Credits
Credit Score (Target Variable)

Data Preprocessing

The following preprocessing techniques were applied:

Numerical Features
Log Transformation:
Camt (Loan Amount)
Cdur (Credit Duration)
Standard Scaling:
Age
Installment Rate
Number of Credits

Categorical Features
One-Hot Encoding
Target Variable
Label Encoding

Exploratory Data Analysis

The project includes:

Distribution Analysis
Box Plots
Correlation Heatmaps
Category-wise Pie Charts
Missing Value Inspection
Duplicate Record Detection

Machine Learning Models
1. Logistic Regression
Baseline Classification Model
Hyperparameter Optimization using GridSearchCV
2. Decision Tree Classifier
Tree-based Classification
Hyperparameter Optimization using GridSearchCV
3. Random Forest Classifier
Ensemble Learning Approach
Hyperparameter Optimization using GridSearchCV
Hyperparameter Tuning

GridSearchCV was used with 5-Fold Cross Validation to find the optimal parameters for each model.

Parameters tuned include:

Regularization Strength (C)
Penalty Types
Maximum Tree Depth
Split Criteria
Number of Estimators
Minimum Samples Split
Minimum Samples Leaf
Feature Selection Methods
Evaluation Metrics

Models were evaluated using:

Accuracy Score
Classification Report
Precision
Recall
F1 Score
Confusion Matrix
ROC-AUC Analysis

Technologies Used
Python
NumPy
Pandas
Matplotlib
Seaborn
Scikit-Learn
Jupyter Notebook

Project Structure
├── creditworthiness.ipynb
├── README.md
├── dataset/
│   └── CreditWorthiness.xlsx
├── images/
│   ├── numerical_features_distribution.png
│   └── cat_plot.png


Installation

git clone https://github.com/your-username/credit-worthiness-classification.git

cd credit-worthiness-classification

pip install -r requirements.txt

Future Improvements
XGBoost Implementation
LightGBM Implementation
Feature Selection Techniques
Model Explainability using SHAP
Deployment using Flask or Streamlit

