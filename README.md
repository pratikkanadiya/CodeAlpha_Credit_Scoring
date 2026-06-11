# Credit Worthiness Classification

# Overview :

This project focuses on predicting a customer's credit worthiness using Machine Learning techniques. The goal is to classify applicants based on their financial and personal information to assist in credit risk assessment and lending decisions.

# The project includes :
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
<ul>
    <li>Checking Account Balance</li>
    <li>Credit Duration</li>
    <li>Credit History</li>
    <li>Loan Purpose</li>
    <li>Loan Amount</li>
    <li>Savings Account Balance</li>
    <li>Employment Duration</li>
    <li>Installment Rate</li>
    <li>Property Information</li>
    <li>Age</li>
    <li>Housing Type</li>
    <li>Number of Existing Credits</li>
    <li>Credit Score (Target Variable)</li>
</ul>

# Data Preprocessing :

The following preprocessing techniques were applied:
<ul>
    <li>Numerical Features</li>
        <ul>
            <li>Log Transformation : Camt (Loan Amount), Cdur (Credit Duration) </li>
            <li>Standard Scaling : Age, Installment Rate, Number of Credits</li>
        </ul>
    <li>Categorical Features</li>
        <ul>
            <li>One-Hot Encoding</li>
            <li>Target Variable</li>
            <li>Label Encoding</li>
        </ul>
</ul>

# Exploratory Data Analysis :

The project includes:
<ul>
    <li>Distribution Analysis</li>
    <li>Box Plots (Outlier Detection)</li>
    <li>Correlation Heatmaps</li>
    <li>Category-wise Pie Charts</li>
    <li>Missing Value Inspection</li>
    <li>Duplicate Record Detection</li>
</ul>

# Machine Learning Models :
<ol>
    <li>Logistic Regression</li>
        <ul>
            <li>Baseline Classification Model</li>
            <li>Hyperparameter Optimization using GridSearchCV</li>
        </ul>
    <li>Decision Tree Classifier</li>
        <ul>
            <li>Tree-based Classification</li>
            <li>Hyperparameter Optimization using GridSearchCV</li>
        </ul>
    <li>Random Forest Classifier</li>
        <ul>
            <li>Ensemble Learning Approach</li>
            <li>Hyperparameter Optimization using GridSearchCV</li>
            <li>Hyperparameter Tuning</li>
        </ul>
</ol>

# GridSearchCV was used with 5-Fold Cross Validation to find the optimal parameters for each model.


# Models were evaluated using :
<ul>
    <li>Accuracy Score</li>
    <li>Classification Report</li>
    <li>Precision</li>
    <li>Recall</li>
    <li>F1 Score</li>
    <li>Confusion Matrix</li>
    <li>ROC-AUC Analysis</li>
</ul>

# Technologies Used :
<ul>
    <li>Python</li>
    <li>Numpy</li>
    <li>Pandas</li>
    <li>Matplotlib</li>
    <li>Seaborn</li>
    <li>Scikit-Learn</li>
    <li>Jupyter Notebook</li>
</ul>

# Project Structure
├── creditworthiness.ipynb<br>
├── requirements.txt<br>
├── README.md<br>
├── dataset/<br>
│   ├──CreditWorthiness.xlsx<br>
├── images/<br>
│   ├── distribution.png<br>
│   ├── pie_chart.png<br>
│   ├── heatmap.png<br>
│   ├── ROC_AUC_Testdata<br>
│   ├── ROC_AUC_Traindata<br>




# Installation :

pip install -r requirements.txt


# Future Improvements :
<ul>
    <li>XGBoost Implementation</li>
    <li>LightGBM Implementation</li>
    <li>Feature Selection Techniques</li>
    <li>Model Explainability using SHAP</li>
    <li>Deployment using Flask or Streamlit</li>
</ul>

