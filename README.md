# customer-churn-prediction
End-to-end customer churn prediction and business insights using machine learning


# Customer Churn Prediction

## 🧠 Problem Statement
Customer churn refers to customers leaving a company’s services. For telecom companies, predicting churn is critical to retaining customers and reducing revenue loss. This project aims to analyze customer behavior and build a machine learning model to predict customer churn.

---

## 📦 Dataset
- IBM Telco Customer Churn dataset  
- Contains customer demographics, service usage, contract details, billing information, and churn labels.

---

## 🧰 Approach
1. **Exploratory Data Analysis (EDA)**  
   - Studied churn distribution  
   - Analyzed churn patterns across contract type, tenure, payment methods, and services  

2. **Data Cleaning & Preprocessing**  
   - Fixed incorrect data types  
   - Handled missing values  
   - Encoded categorical variables  
   - Prepared data for machine learning  

3. **Model Training & Validation**  
   - Trained Logistic Regression and Random Forest models  
   - Applied feature scaling  
   - Evaluated models using Accuracy, Precision, Recall, and ROC-AUC  
   - Used cross-validation to ensure reliability  

4. **Feature Importance & Business Insights**  
   - Identified key drivers of churn  
   - Translated model outputs into actionable business insights  

---

## 📊 Key Insights
- Customers on **month-to-month contracts** have a higher churn rate.
- Customers with **shorter tenure** are more likely to churn.
- **Higher monthly charges** increase churn risk.
- Customers using **electronic check** payment methods show higher churn.
- Customers with **additional services** (online security, tech support) are less likely to churn.

---

## 📈 Results
- Built a validated churn prediction model with strong ROC-AUC performance.
- Logistic Regression provided interpretable results, while Random Forest captured non-linear patterns.
- Cross-validation confirmed the model’s stability and reliability.

---

## 🛠️ Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib  
- Google Colab  

---

## 📁 Notebooks
- `01_eda.ipynb` — Exploratory Data Analysis  
- `02_data_cleaning.ipynb` — Data Cleaning & Preprocessing  
- `03_model_validation.ipynb` — Model Training, Validation & Business Insights  

---

## ✅ Outcome
Developed an end-to-end machine learning solution to predict customer churn and derive business-driven insights to support customer retention strategies.
