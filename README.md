# Customer-churn-prediction
End-to-end customer churn prediction using Python, Pandas, Scikit-learn, Logistic Regression, and Random Forest.
# Customer Churn Prediction

## 📌 Project Overview

Customer churn refers to customers discontinuing their
relationship with a company.

The objective of this project is to build a machine learning
model that predicts whether a customer is likely to churn.

This project uses customer demographic, service, contract,
and billing information to predict customer churn.

---

## 🎯 Problem Statement

The company wants to identify customers who are likely to leave
the service so that appropriate retention strategies can be
implemented.

This is a binary classification problem.

Target variable:

- 0 → Customer will not churn
- 1 → Customer will churn

---

## 📊 Dataset

Dataset: Telco Customer Churn

Source: Kaggle

The dataset contains 7043 customer records.

Important features include:

- Gender
- Tenure
- MonthlyCharges
- Contract
- InternetService
- PaymentMethod
- Churn

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 🔄 Project Workflow

1. Data Collection
2. Data Understanding
3. Data Cleaning
4. Exploratory Data Analysis
5. Feature Engineering
6. Categorical Encoding
7. Feature Scaling
8. Train-Test Split
9. Model Training
10. Model Evaluation
11. Feature Importance
12. Business Insights

---

## 🧹 Data Preprocessing

The following preprocessing steps were performed:

- Checked missing values
- Converted `TotalCharges` to numerical format
- Removed invalid/missing records
- Converted the target variable into binary format
- Removed unnecessary columns
- Applied one-hot encoding to categorical variables
- Applied feature scaling where required

---

## 📈 Exploratory Data Analysis

The following relationships were analyzed:

- Churn distribution
- Contract type vs churn
- Monthly charges vs churn
- Internet service vs churn
- Payment method vs churn
- Tenure vs churn

---

## 🤖 Machine Learning Models

The following classification algorithms were evaluated:

### 1. Logistic Regression

Used as the baseline classification model.

### 2. Random Forest

Used to capture nonlinear relationships between
customer characteristics and churn.

---

## 📏 Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

Recall is particularly important because the company
would want to identify as many potential churn customers
as possible.

---

## 🔍 Feature Importance

Random Forest feature importance was used to identify
the features that contribute most to churn prediction.

---

## 💡 Business Insights

The analysis can help identify customer segments with
higher churn risk.

Potential retention strategies include:

- Targeting month-to-month customers
- Providing incentives for long-term contracts
- Investigating customers with high monthly charges
- Identifying customers with short tenure
- Improving services for high-risk customer segments
