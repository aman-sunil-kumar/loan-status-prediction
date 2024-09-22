# Credit Scoring Project: Loan Repayment Prediction

# Credit Scoring Project

This project aims to predict loan repayment outcomes using machine learning techniques. The project builds a credit scoring model based on features like applicant income, co-applicant income, loan amount, credit history, and other borrower attributes. The final model is deployed to help financial institutions make informed decisions about loan approvals, pricing, and other credit-related decisions.

## Project Overview

The main objective is to use the dataset to develop a credit scoring model that predicts the likelihood of loan repayment. The project focuses on exploratory data analysis, feature engineering, model building, and evaluation.

### Key Steps:
1. **Data Preprocessing**: 
   - Handling missing values in `LoanAmount`, `Loan_Amount_Term`, and `Credit_History`.
   - Encoding categorical variables like `Gender`, `Married`, `Education`, and `Property_Area`.
   - Scaling numerical variables such as `ApplicantIncome` and `CoapplicantIncome`.
2. **Exploratory Data Analysis (EDA)**:
   - Understanding the relationship between features and the loan status (`Loan_Status`).
   - Identifying key trends and correlations.
3. **Modeling**:
   - Building a logistic regression model to predict `Loan_Status`.
   - Hyperparameter tuning and model evaluation using metrics like accuracy, precision, recall, and F1-score.
4. **Model Evaluation**:
   - Evaluating the model performance using a confusion matrix and ROC-AUC score.
   - Deploying the model for potential use in production environments.

## Dataset

The dataset includes the following key features:

- **Loan_ID**: Unique loan identifier.
- **Gender**: Applicant's gender (Male/Female).
- **Married**: Applicant's marital status (Yes/No).
- **Dependents**: Number of dependents (0, 1, 2, 3+).
- **Education**: Applicant's education level (Graduate/Not Graduate).
- **Self_Employed**: Whether the applicant is self-employed (Yes/No).
- **ApplicantIncome**: Applicant's income.
- **CoapplicantIncome**: Co-applicant's income.
- **LoanAmount**: Loan amount requested.
- **Loan_Amount_Term**: Term of the loan in months.
- **Credit_History**: Credit history (1 for clear history, 0 otherwise).
- **Property_Area**: Urban, Semi-Urban, or Rural area where the property is located.
- **Loan_Status**: Whether the loan was approved (Y) or not (N).

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/credit-scoring-project.git
