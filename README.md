# 💳 CreditGuard: A Smarter Risk Evaluation System for Home Loan Approval

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](#)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](#)
[![Machine Learning](https://img.shields.io/badge/ML-Binary_Classification-brightgreen.svg)](#)

🔗 **Dataset**: [CreditGuard (Google Drive)](https://drive.google.com/drive/folders/1gRrQt18iVD2EkYrz2xGfut7kUltN_5Ej)

---

## 🔍 Overview

Access to home loans remains a barrier for many individuals, especially those with limited or non-traditional credit histories. Traditional credit scoring methods often overlook financially responsible individuals, restricting financial inclusion and economic mobility.

**CreditGuard** solves this by using intelligent, data-driven machine learning to predict loan defaults more accurately and fairly—enabling inclusive, transparent lending decisions.

---

## 🎯 Project Objective

Develop a high-precision predictive model to:
- Identify likely loan defaulters.
- Minimize false rejections of creditworthy applicants.
- Support fair, data-backed credit decisions.

---

## 🧠 Technical Approach

A **supervised binary classification** system:
- `0` → Loan repaid
- `1` → Loan not repaid

### 🔧 End-to-End Pipeline Includes:
- Data integration
- Adaptive preprocessing
- Anomaly detection
- Model training & evaluation

---

## 🧩 Key Features & Achievements

- **🔗 Data Integration Pipeline**  
  Unified six heterogeneous datasets into a consolidated applicant profile, enriched with behavioral and temporal insights.

- **🧽 Adaptive Preprocessing**  
  Employed:
  - MICE imputation for missing data
  - Outlier handling
  - Dynamic encoding strategies

- **🚩 Anomaly Detection**  
  Used **Isolation Forest** to flag suspicious entries, improving data integrity.

- **🧠 Ensemble Modeling**  
  Benchmarked:
  - `XGBoost`
  - `Random Forest`
  - `Logistic Regression`
  - `SVM`

- **📊 Evaluation Framework**  
  Evaluated models with:
  - ROC-AUC
  - Precision, Recall, F1-Score
  - Feature Importance for transparency

---

## 📁 Dataset Description

| Dataset | Description |
|--------|-------------|
| `application_train` / `application_test` | Core datasets. `TARGET` column denotes default status. |
| `bureau` | Previous credits from other institutions. |
| `bureau_balance` | Monthly credit status history. |
| `previous_application` | Historical loan applications to Home Credit. |
| `POS_CASH_BALANCE` | Monthly data on POS/cash loans. |
| `credit_card_balance` | Monthly credit card usage and balances. |
| `installments_payment` | Detailed repayment history for previous loans. |

---

## 🏷️ Keywords

`Credit Risk` · `Loan Eligibility` · `Financial Inclusion` · `Binary Classification` · `XGBoost` · `SVM` · `Random Forest` · `MICE` · `SHAP` · `Anomaly Detection` · `ROC-AUC` · `Feature Importance`

---

## 🚀 Future Work

- 🧪 Explore **deep learning** for behavioral credit scoring  
- 🛠️ MLOps pipeline for scalable **deployment**  
- 📜 Generate **explainability reports** with SHAP values

---

> 💡 *CreditGuard is a step toward democratizing credit access by combining intelligent algorithms with interpretable outcomes.*
