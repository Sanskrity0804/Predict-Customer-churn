# 📊 Customer Churn Prediction with Machine Learning

This project aims to predict customer churn using machine learning techniques. Churn prediction helps businesses identify customers who are likely to stop using their services, allowing them to take proactive measures to retain these customers.

## 🚀 Project Overview

- **Objective:** Predict whether a customer will churn (leave) based on their demographic, service usage, and account information.
- **Dataset:** Telco Customer Churn Dataset (`churn.csv`)
- **Algorithm:** Logistic Regression
- **Accuracy Achieved:** 82% on test data

---

## 📂 Dataset Information

The dataset contains **7043 rows** and **21 columns** including:

- **Demographic data:** Gender, SeniorCitizen, Partner, Dependents
- **Services signed up:** PhoneService, InternetService, OnlineSecurity, TechSupport, StreamingTV, etc.
- **Account information:** Contract, PaymentMethod, MonthlyCharges, TotalCharges
- **Target variable:** `Churn` (Yes/No)

---

## 🔧 Technologies Used

- **Python 3.x**
- **Pandas** & **NumPy**
- **Matplotlib** & **Seaborn** for visualization
- **Scikit-learn** for machine learning and evaluation metrics

---

## 📊 Exploratory Data Analysis (EDA)

- Visualized customer churn distribution
- Analyzed churn patterns across **gender**, **internet service type**, and **contract type**
- Examined distributions of numerical features like **tenure** and **MonthlyCharges**

---

## 🔄 Data Preprocessing

- Removed unnecessary columns (e.g., `customerID`)
- Converted categorical variables using **Label Encoding**
- Scaled numerical features using **StandardScaler**
- Split data into **training (80%)** and **testing (20%)** sets

---

## 🤖 Model Building & Evaluation

- Applied **Logistic Regression** for classification
- Evaluated using:
  - **Accuracy:** 82%
  - **Precision, Recall, F1-Score**
- Addressed class imbalance by carefully analyzing the churn class distribution

---

## 📈 Results

| Metric      | Value    |
|------------ |--------- |
| Accuracy    | 82%      |
| Precision   | 85% (No Churn), 69% (Churn) |
| Recall      | 91% (No Churn), 56% (Churn) |
| F1-Score    | 88% (No Churn), 62% (Churn) |

---

## 💡 Future Improvements

- Try advanced models: **Random Forest, XGBoost, or LightGBM**
- Handle class imbalance using **SMOTE** or **class weighting**
- Use **SHAP or LIME** for model explainability
- Deploy the model as a **web app using Streamlit or Flask**
