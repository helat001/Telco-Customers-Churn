# Telco-Customers-Churn
churn-prediction/
│
├── data/
│   ├── telco_churn.csv                # Raw data
│   └── cleaned_churn_data.csv         # Preprocessed data
│
├── images/
│   ├── churn_distribution.png
│   ├── tenure_vs_churn.png
│   ├── correlation_matrix.png
│   ├── feature_importance.png
│   └── shap_summary.png
│
├── churn_analysis.ipynb              # Main analysis notebook
├── requirements.txt                  # Python packages used
├── .gitignore                        # Optional: ignore unnecessary files
└── README.md                         # Polished project description

# 📊 Customer Churn Prediction – Python Project

**Author**: Houcine E  
**Project Type**: Machine Learning & Data Analysis  
**Presentation**: 🎥 [Watch the Video](#) *(Upload your video and paste link here)*

---

## 🔍 Project Overview

This project explores customer churn using a Telco dataset. We build an end-to-end machine learning pipeline using Python, focusing on preprocessing, exploratory data analysis, XGBoost modeling, and SHAP explainability.

---

## 📁 Files & Structure

- `churn_analysis.ipynb` → Main Jupyter Notebook  
- `data/` → Raw & cleaned CSV files  
- `images/` → Visualizations (EDA, model explainability, etc.)  
- `requirements.txt` → Python libraries used  
- `README.md` → This file  

---

## 📊 Key Visuals

Here are some key insights from the analysis:

- **Churn Distribution**: Only ~27% of customers churned  
- **Tenure**: Short-tenure customers (under 12 months) churn the most  
- **Top Features**: `Contract`, `MonthlyCharges`, and `Tenure` are key churn predictors  
- **SHAP Summary**: Month-to-month contracts, high bills, and short tenure increase churn risk  

---

## ⚙️ Model & Tools Used

- **Model**: XGBoost Classifier  
- **Explainability**: SHAP  
- **Metrics**: Accuracy (with attention to class imbalance)  
- **Tech Stack**: `pandas`, `sklearn`, `xgboost`, `shap`, `seaborn`, `matplotlib`

---

## 📈 Business Recommendations

- Encourage long-term contracts (reduce churn from month-to-month users)  
- Improve early onboarding and retention in the first 90 days  
- Offer loyalty discounts to high-paying customers  
- Promote auto-pay to reduce manual churn  
- Upsell bundled services (tech support, online security)

---

## 📦 Installation

```bash
pip install -r requirements.txt
