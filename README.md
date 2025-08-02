# Credit Risk Analytics

An end-to-end data analytics and machine learning project using the **Home Credit Default Risk** dataset from Kaggle. The goal is to predict the likelihood of a loan applicant defaulting and deliver explainable, actionable insights via a Power BI dashboard.

---

## Problem Statement

Home Credit wants to expand its portfolio by granting loans to more applicants. To minimize risk, they need a system that accurately predicts whether a customer will default. This project involves:

- Data cleaning and preprocessing across multiple related tables
- Feature engineering from multiple sources
- Building a high-performing XGBoost model
- Explaining model decisions using SHAP values
- Creating an interactive Power BI dashboard for business users

---

## Tools & Technologies

- **Python** (Pandas, NumPy, Scikit-learn, XGBoost, SHAP, Seaborn)
- **Power BI** (Dashboard creation and interactivity)
- **Git + GitHub** (Version control and collaboration)

---

## Machine Learning Model

- Algorithm used: **XGBoost Classifier**
- ROC-AUC Score: **0.7629**
- SHAP (SHapley Additive exPlanations) used for feature importance
- Feature engineering from:
  - `bureau.csv`
  - `previous_application.csv`
  - `credit_card_balance.csv`, etc.

---

## Dashboard Preview

| KPI Cards | Risk Distribution | SHAP Insights |                                                                                                                                                                                             
|-----------|-------------------|----------------|                                                                                                                                                                                            
| Total Applicants, Default Rate, Avg Credit | Risk score scatter plot with red/green clusters | Feature importance from SHAP |                                                                                                               

---

## Downloads

> Compressed to meet GitHub size limits.

- 🔗 [ Power BI Dashboard (.pbix)](dashboard/credit_risk_dashboard.pbix)
- 🔗 [ Cleaned Dataset (.csv as ZIP)](notebooks/credit_risk_dashboard_data.zip)
- 🔗 [ SHAP Feature Importance CSV](notebooks/shap_importance_top10.csv)

---

## Folder Structure
credit-risk-analytics/                                                                                                                                                                                                                       
│                                                                                                                                                                                                                                             
├── data/ ← Original raw CSV files (from Kaggle)  Link: https://www.kaggle.com/competitions/home-credit-default-risk                                                                                                                                                                                           
├── notebooks/ ← Python notebooks, SHAP CSV, and compressed data                                                                                                                                                                              
├── dashboard/ ← .pbix dashboard                                                                                                                                                                                                             
├── requirements.txt ← Python dependencies                                                                                                                                                                                                    
└── README.md ← This file                                                                                                                                                                                                                    


---

## Key Insights

1. External sources like `EXT_SOURCE_2` and `EXT_SOURCE_3` are the most predictive features
2. Younger applicants with lower income and fewer credit lines tend to default more
3. SHAP helped expose biases and validate feature selection

---

## Author

**Nagendra U S**  
GitHub: [@NagendraUS03](https://github.com/NagendraUS03)

---

## If you like this project...

Please ⭐️ star the repo and share it! Feedback and contributions are welcome.

