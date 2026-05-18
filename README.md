### Customer Churn Prediction using Logistic Regression

## Project Overview
This project focuses on predicting customer churn using a Logistic Regression model. The goal of this project is to identify whether a customer is likely to leave the company based on different customer-related features such as contract type, internet service, monthly charges, tenure, and payment methods.

This project helped me understand the complete machine learning workflow including:
- Data preprocessing
- Handling categorical variables
- Feature scaling
- Model training
- Model evaluation
- Coefficient interpretation

--

## Dataset
Dataset used in this project:
- Telco Customer Churn Dataset

## The dataset contains customer information such as:
- Gender
- Senior Citizen
- Contract Type
- Internet Service
- Monthly Charges
- Total Charges
- Tenure
- Churn Status


## Libraries Used:
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn


## Machine Learning Workflow

### 1. Data Preprocessing:
- Removed unnecessary columns
- Handled missing values
- Converted categorical variables into numerical format
- Applied feature scaling


### 2. Exploratory Data Analysis
Performed analysis and visualizations to understand:
- Customer churn patterns
- Correlation between variables
- Distribution of important features


### 3. Model Building
Used Logistic Regression for binary classification because the target variable contains two classes:
- Churn = Yes
- Churn = No


### 4. Model Evaluation
Evaluated model performance using:
- Accuracy Score
- Confusion Matrix
- Classification Report
- ROC Curve


## Key Insights
- Long tenure customers were less likely to churn.
- Fiber optic internet users showed relatively higher churn behavior.
- Feature scaling improved model convergence and performance.
