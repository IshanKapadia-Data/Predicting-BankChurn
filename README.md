# 🏦 Bank Customer Churn Prediction

---

## 📋 Project Overview

This project predicts **bank customer churn** using machine learning models.  
The objective is to **identify customers likely to leave the bank**, enabling proactive retention strategies and improving customer engagement.

---

## 🗃️ Dataset Description

The dataset contains **10,000 customer records** with the following features:

- **Credit Score**
- **Country**
- **Gender**
- **Age**
- **Tenure**
- **Balance**
- **Number of Products**
- **Active Member**
- **Estimated Salary**
- **Churn** *(Target Variable: 1 = Churn, 0 = No Churn)*

---

## 📊 Exploratory Data Analysis (EDA) Highlights

- **Churn Rate:** ~20% of customers have churned.
- **Country:** Higher churn observed among **German customers**.
- **Age:** Older customers showed a higher likelihood of churn.
- **Products Number:** Customers with only **1 product** were more likely to churn.
- **Active Member Status:** **Active members** were less likely to churn.

---

## 🧩 Models Trained & Evaluated

| Model                  | Accuracy | Precision | Recall | F1 Score | ROC AUC |
|------------------------|----------|-----------|--------|----------|---------|
| Logistic Regression    | 71.20%  | 38.44%   | 69.04% | 49.38%   | 0.768   |
| Random Forest (Default)| 85.35%  | 73.36%   | 43.98% | 54.99%   | 0.849   |
| **Tuned Random Forest**| **83.55%**  | **58.82%**   | **63.88%** | **61.25%**   | **0.859**   |

🏆 **Best Performing Model:** Tuned Random Forest  
- Tuned using **RandomizedSearchCV** with cross-validation  
- Achieved **ROC AUC of 0.86** on the test set  
- Balanced performance with good trade-off between recall and precision  

---

## 🔥 Top Features Driving Churn

- **Age**
- **Number of Products**
- **Balance**
- **Estimated Salary**
- **Credit Score**
- **Active Member Status**
- **Country (Germany)**

---

## ✅ Key Business Insights

- Target **older customers** and those with **only 1 product** for retention programs.
- Focus on **high balance accounts** who are at risk of churning.
- **German customers** represent a key churn segment.
- **Active customer engagement programs** could reduce churn.

---

## 🛠️ Tools & Technologies Used

- **Python (Pandas, NumPy)**
- **Matplotlib, Seaborn** for Data Visualization
- **Scikit-learn** for Machine Learning
- **Imbalanced-learn** for Handling Class Imbalance

---

## 👨‍💻 **Author**  
**Ishan Kapadia** — Data Scientist




