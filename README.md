# 🛡️ Credit Card Fraud Detection

## 📌 Project Overview
This project focuses on building a credit card fraud detection system using supervised machine learning algorithms. It aims to classify transactions as fraudulent or non-fraudulent using anonymized and scaled features. Three models were implemented and compared: **Logistic Regression**, **Random Forest**, and **XGBoost**.
The dataset has been scaled and anonymized to protect user privacy, but key insights have still been extracted through thorough exploratory data analysis. The project will be continuously refining based on ongoing research, model tuning, and evaluation of emerging techniques in fraud analytics.

---

## 🔍 Process Summary

### 1. Data Exploration & Preprocessing
- Loaded real-world credit card transaction data with anonymized features (`V1` to `V28`) and a binary target (`Class`).
- Verified no missing values.
- Conducted exploratory data analysis (EDA):
  - Histogram of fraud vs. non-fraud transactions.
  - Correlation matrix to check for multicollinearity.
  - Skewness analysis: several features were positively skewed.

### 2. Model Building
- **Logistic Regression**
  - Accuracy: **97%**
  - Strong precision and recall for both classes.
- **Random Forest**
  - Accuracy: **96%**
  - Robust performance, but slightly lower than XGBoost.
- **XGBoost**
  - Accuracy: **99%**
  - Best performance overall, with excellent classification metrics.

### 3. Model Evaluation
- Evaluation metrics used: **confusion matrix**, **precision**, **recall**, **F1-score**, and **accuracy**.
- **XGBoost** outperformed other models, especially on the imbalanced dataset.

---

## ✅ Key Takeaways
- Handling class imbalance and evaluating model performance using multiple metrics are essential in fraud detection.
- XGBoost proved most effective due to its boosting and regularization capabilities.
- EDA provided critical insights into data structure, correlation, and distribution skewness.

---

## 🧪 Technologies Used
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn
- XGBoost
- Jupyter Notebook


