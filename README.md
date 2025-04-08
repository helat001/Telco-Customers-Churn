#  Customer Churn Prediction – Python Project

**Author**: Houcine E  
**Project Type**: Machine Learning & Data Analysis  
**Presentation**: 🎥 [Watch the Video](#) *(Link will go here)*

---

##  Project Overview

This project explores customer churn using a Telco dataset. I built an end-to-end machine learning pipeline using Python, focusing on preprocessing, exploratory data analysis, XGBoost modeling, and SHAP explainability.

---

##  Project Structure


---

##  Key Insights

###  Churn Distribution
Only 27% of customers in the dataset churned, while 73% stayed.

![Churn Distribution](churn_distribution.png)

---

###  Tenure vs. Churn
Churned customers had a median tenure of 10 months, while retained ones averaged 40 months.

![Tenure vs Churn](tenure_vs_churn.png)

---

###  Correlation Matrix


![Correlation Matrix](correlation_matrix.png)

---

###  Feature Importance (XGBoost)
XGBoost ranked MonthlyCharges, TotalCharges, and Tenure as the most important features

![Feature Importance](feature_importance.png)

---

###  SHAP Summary Plot
SHAP values show that short tenure, month-to-month contracts, and high monthly charges consistently increase churn probability.

![SHAP Summary](Shap_summary.png)



---

##  Business Recommendations
Three recomendations based on visuals and model insights to reduce customer churn.

 1. Encourage Long term contracts:
    - A month to month contract was the top predictor of churn on the Shap Summary plot and feature importance graph.
    - Incentivize long term contracts by discounts for switching to a 1 or 2 year plan.
    
 2. Strenghten onboarding for new customers:
    - From the boxplot "Tenure vs Churn", most churners were customers with less than a year with the company. And tenure is a key churn 
    driver.
    - Must have an onboarding startegy with tailored support to customers to reduce early churn.
   
 3. Promote Add-on Services:
    - Shap summary plot shows that a lack of services like tech support and online security contributes to higher churn.
    - Maybe these services make the customers feel more engaged and increase their satisfaction.
    - Offer free trials for these services or bundle them in plans for a discount can reduce churn.
   
   ---

##  Model & Tools Used

- **Model**: XGBoost Classifier  
- **Explainability**: SHAP  
- **Metrics**: Accuracy  
- **Tools & Libraries Used**: `pandas`, `numpy`, `seaborn`, `matplotlib`, `scikit-learn`, `xgboost`, `shap`
 
