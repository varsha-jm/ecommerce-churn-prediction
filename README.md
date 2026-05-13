# 🛒 E-Commerce Customer Churn Prediction

> Predicting which customers are likely to churn before they leave.
> Built an XGBoost model achieving **0.98 AUC** using customer behaviour data.

![Python](https://img.shields.io/badge/Python-3.x-blue)
![XGBoost](https://img.shields.io/badge/XGBoost-ML-orange)
![PowerBI](https://img.shields.io/badge/PowerBI-Dashboard-yellow)
![pandas](https://img.shields.io/badge/pandas-Data-green)

---

## 📌 Problem Statement

Customer churn is a major challenge for e-commerce businesses.
This project builds a machine learning model to identify at-risk customers early, enabling businesses to take proactive retention actions before customers leave.

**Dataset:** E-Commerce Dataset by Ankur Sahu (Kaggle)

**Records:** 5,630 customers  
**Features:** 20 + engineered features

---

## 📊 Dashboard

![Dashboard](dashboard/dashboard_screenshot.png)

---

## 🔍 Key Findings

- 16.84% of customers in the dataset churned
- Customers with tenure under 3 months showed the highest churn rates
- Customers who complained were significantly more likely to churn
- `Tenure` and `DaySinceLastOrder` were strong churn indicators
- Engineered features improved churn prediction performance

---

## 🤖 Model Results

| Model | AUC | F1 Score |
|---|---|---|
| Logistic Regression | ~0.78 | ~0.55 |
| Random Forest | ~0.84 | ~0.68 |
| **XGBoost (Tuned)** | **0.98** | **0.85** |

> Final XGBoost model tuned using GridSearchCV and validated using cross-validation.

---

## 📁 Project Structure

```text
churn-project/
├── notebooks/
│   ├── 01_EDA.ipynb
│   ├── 02_preprocessing.ipynb
│   └── 03_modelling.ipynb
├── data/
│   ├── raw/
│   └── processed/
├── dashboard/
│   ├── customer_churn_dashboard.pbix
│   └── dashboard_screenshot.png
└── README.md
```

---

## 🛠 Tech Stack

Python · pandas · NumPy · scikit-learn · XGBoost · matplotlib · seaborn · Power BI

---

## 👩‍💻 Author

**Varsha J M**  
2nd Year AI & DS Student  
Sri Krishna College of Technology, Coimbatore

---

*Built as part of a data science portfolio project.*
