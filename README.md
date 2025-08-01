# Python-projects
# 📊 Telco Customer Churn - Exploratory Data Analysis (EDA)

> A data-driven analysis of customer churn behavior in a telecom company using Python.

---

## 🧠 Overview

Customer churn is a critical metric for telecom companies, reflecting customer dissatisfaction and potential revenue loss. This project performs **Exploratory Data Analysis (EDA)** on a Telco customer dataset to identify **key patterns, risk factors**, and **insights** that may contribute to churn.

The goal is to provide clear, visual, and data-backed observations that can help businesses understand:
- Who is likely to churn?
- What features influence churn?
- How can customer retention be improved?

---

## 📁 Dataset Information

- **Source**: IBM Sample Dataset (commonly used on Kaggle)
- **Rows**: 7,043 customers
- **Target Variable**: `Churn` (Yes/No)
- **Features**: Demographics (gender, senior citizen), service subscriptions, billing info, contract types, etc.

---

## 🔧 Tools & Libraries

- **Python** (Jupyter Notebook)
- `pandas` for data manipulation  
- `matplotlib` & `seaborn` for visualizations  
- `numpy` for numerical operations

---

## 📊 Key Steps Performed

### 1. 🧹 Data Cleaning & Preprocessing
- Handled missing values (e.g., `TotalCharges`)
- Converted data types
- Removed whitespace and ensured consistency

### 2. 📈 Exploratory Data Analysis (EDA)
- Distribution of churn vs non-churn customers
- Gender-wise churn analysis
- Senior citizen churn trends
- Service-wise churn patterns (Internet, Streaming, Security, Backup, etc.)
- Contract type vs churn impact
- Visual comparisons using count plots and grouped bars

### 3. 🔍 Insights Extracted
- Customers with **month-to-month contracts** are significantly more likely to churn.
- **Senior citizens** have a higher churn rate than younger customers.
- Those **not using value-added services** (like tech support or security) show higher churn.
- **Gender and phone service** show little to no influence on churn behavior.

---

## 🧩 Sample Visuals

📌 Churn Distribution by Contract Type  
📌 Churn by Online Security & Tech Support  
📌 Streaming Service Engagement vs Churn  
📌 Gender & Senior Citizen Breakdown  

(Visuals are included in the notebook)

---

## 📌 Final Conclusion

The analysis provides a strong foundation for building churn prediction models and targeting customer retention strategies. The company can focus on:
- Promoting longer-term contracts  
- Bundling useful services (like tech support and security)  
- Identifying senior customers at risk

---

## 🧰 Future Scope

- Build predictive models (Logistic Regression, Decision Trees, Random Forest)
- Perform feature engineering
- Create a Power BI dashboard for executive-level insights

---

## ✍️ Author
Sia Thakur
Aspiring Data Analyst | Python & SQL Enthusiast  
📍 India | 🌐 [LinkedIn Profile Link]  
