# Predicting-BankChurn

# 🏦 Bank Customer Churn Prediction

This project aims to predict whether a customer will churn (i.e., leave the bank) using historical customer data. It demonstrates a full machine learning pipeline from exploratory data analysis (EDA) to model evaluation and real-time prediction using Python and scikit-learn.

---

## 📂 Project Overview

Customer churn significantly impacts revenue in the banking industry. By identifying at-risk customers, banks can implement targeted strategies to retain them. This project:

- Analyzes customer behavior and demographics
- Builds predictive models to classify churn
- Evaluates performance using standard ML metrics
- Accepts new user input to predict churn probability

---

## 📈 Tools & Technologies

- **Languages**: Python
- **Libraries**: pandas, numpy, matplotlib, seaborn, scikit-learn
- **Models**: Logistic Regression, Random Forest Classifier

---

## 📊 Dataset Features

The dataset includes the following features:

| Feature | Description |
|--------|-------------|
| `credit_score` | Customer's credit score |
| `country` | Country of residence |
| `gender` | Customer gender |
| `age` | Age of customer |
| `tenure` | Years as a bank customer |
| `balance` | Account balance |
| `products_number` | Number of bank products used |
| `credit_card` | Has credit card (1 = Yes, 0 = No) |
| `active_member` | Is an active member (1 = Yes, 0 = No) |
| `estimated_salary` | Estimated salary |
| `churn` | Target variable (1 = Churned, 0 = Retained) |

---

## 📌 Project Workflow

1. **Data Preprocessing**
   - Missing value check
   - One-hot encoding of categorical features
   - Feature scaling

2. **Exploratory Data Analysis**
   - Churn distribution
   - Visualizations by gender, country, product usage
   - Correlation heatmap

3. **Model Training**
   - Logistic Regression with balanced class weights
   - Random Forest Classifier with feature importance plot

4. **Model Evaluation**
   - Accuracy, Precision, Recall, F1 Score
   - Confusion Matrix and ROC AUC

5. **User Prediction**
   - Users can input customer data
   - Both models output churn prediction and probability

---


