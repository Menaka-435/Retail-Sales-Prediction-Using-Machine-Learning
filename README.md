# Retail Sales Prediction Using Machine Learning

## Project Overview
This project implements a comprehensive machine learning system for **transaction-level retail sales forecasting**. Using a real-world dataset of over 50,000 transactions collected from ten shopping malls in Istanbul (2021–2023), the system predicts the total sales amount per transaction.  

The workflow includes:
- Rigorous **data preprocessing**
- Advanced **feature engineering**
- Dimensionality reduction via **PCA**
- Ensemble modeling using **Random Forest** and **XGBoost**
- Model interpretability through **SHAP values**

The XGBoost model emerged as the best-performing model, achieving **RMSE ≈ 37.79 TL** and **MAE ≈ 3.18 TL**, providing actionable insights for retail decision-making.

---

## Team Information
| Name | Role |
|------|
| Ponduru Vaishnavi | Data Preprocessing & EDA 
| Menaka Naga Sai Pothina | Feature Engineering & Modeling 
| Rikithaa Sai Dakoju | Model Evaluation & SHAP Analysis 
| Dasireddy Bharath reddy | Documentation & Deployment 

---

## Features
- **Data Cleaning:** Handling duplicates, missing values, and outliers.
- **Feature Engineering:**
  - Temporal features (year, month, day of week)
  - Customer behavioral features (average spending)
  - One-hot encoding for categorical variables
- **Dimensionality Reduction:** PCA to reduce from 48 to 22 features.
- **Modeling:** Random Forest and XGBoost regressors with hyperparameter tuning.
- **Interpretability:** SHAP analysis to identify key contributors to sales.

---

## Dataset
- **Source:** Collected from 10 shopping malls in Istanbul, Turkey (2021–2023)
- **Number of Records:** 50,000+
- **Key Attributes:**
  - `invoiceno`, `customerid`
  - `gender`, `age`
  - `type`, `quantity`, `price`
  - `shoppingmall`, `paymentmethod`, `invoicedate`
- **Target Variable:** `totalsales` (quantity × price)


