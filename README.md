# 📉 Customer Churn Prediction using Machine Learning

## 📌 Project Overview

This project predicts whether a customer will churn (leave) or not using machine learning models.

---

## 📊 Dataset

* Source: Telco Customer Churn Dataset
* Records: 7043
* Features: Customer demographics, services, billing details

---

## 🧠 Problem Statement

Identify customers who are likely to churn so businesses can take preventive actions.

---

## ⚙️ Steps Performed

### 🔹 Data Cleaning

* Converted TotalCharges to numeric
* Removed missing values
* Dropped customerID column

---

### 🔹 Feature Engineering

* Encoded categorical variables using one-hot encoding
* Converted target variable (Churn: Yes → 1, No → 0)

---

### 🔹 Model Building

* Logistic Regression (baseline)
* Random Forest Classifier (final model)

---

## 📈 Model Performance

### Logistic Regression:

* Accuracy: ~79%
* Recall (Churn): 52%

### Random Forest:

* Accuracy: ~76%
* Recall (Churn): 70% ✅

---

## 🔍 Key Insights

* Dataset is imbalanced (fewer churn cases)
* Random Forest improved churn detection significantly
* Model prioritizes recall to capture more at-risk customers

---

## 📊 Evaluation Metrics

* Precision
* Recall
* F1-score
* Confusion Matrix

---

## 🧰 Technologies Used

* Python
* Pandas
* Scikit-learn
* Matplotlib / Seaborn

---

## 🚀 How to Run

git clone https://github.com/sushmareddy2/Customer_churn_predictions.git
cd Customer_churn_predictions

Open:
notebook/churn_model.ipynb

---

## 📌 Future Improvements

* Hyperparameter tuning
* Try XGBoost / LightGBM
* Deploy model

---

## 👩‍💻 Author

Sushma Reddy
