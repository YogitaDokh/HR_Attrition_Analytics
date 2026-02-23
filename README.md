# 🧠 HR Analytics | Employee Attrition Risk Prediction

## 📌 Executive Summary
Employee attrition poses a significant strategic and financial risk to organizations through increased recruitment costs, productivity disruption, and loss of institutional knowledge. This project delivers an end-to-end HR analytics solution that leverages exploratory data analysis, machine learning, and model explainability to proactively identify employees at high risk of leaving.

The solution not only predicts attrition likelihood but also uncovers the key organizational drivers behind employee turnover, enabling HR leaders to implement targeted retention strategies.

---

## 🎯 Business Objectives
- Quantify and monitor overall attrition patterns  
- Identify high-risk departments, roles, and salary bands  
- Build a predictive model to flag employees likely to resign  
- Improve minority-class detection using imbalance handling techniques  
- Provide interpretable insights to support HR decision-making  
- Develop an executive-ready Power BI dashboard  

---

## 🛠️ Technology Stack
**Programming & Analysis**
- Python (Pandas, NumPy)
- Data Visualization (Seaborn, Matplotlib)

**Machine Learning**
- Scikit-learn
- Logistic Regression
- Random Forest
- SMOTE (class imbalance handling)

**Model Explainability**
- Feature Importance
- SHAP 

**Business Intelligence**
- Power BI Dashboard

---

## 🔬 Analytical Approach
The project follows a structured CRISP-DM inspired workflow:

1. **Data Understanding & Cleaning**  
   - Data quality checks, type corrections, and preprocessing  

2. **Exploratory Data Analysis (EDA)**  
   - Department-wise attrition  
   - Compensation analysis  
   - Promotion impact assessment  

3. **Feature Engineering**  
   - Creation of tenure- and compensation-based indicators  

4. **Class Imbalance Treatment**  
   - SMOTE oversampling  
   - Class-weighted models  

5. **Predictive Modeling**  
   - Logistic Regression (baseline)  
   - Random Forest (final model)  
   - Threshold tuning for recall optimization  

6. **Model Evaluation**  
   - Accuracy, Precision, Recall, F1-Score  
   - ROC-AUC analysis  
   - Confusion matrix interpretation  

7. **Model Explainability & Insights**  
   - Feature importance analysis  
   - Business interpretation of drivers  

8. **Business Intelligence Layer**  
   - Interactive Power BI dashboard  
   - HR action recommendations  

---

## 📈 Expected Business Value
- Early warning system for employee churn  
- Targeted retention interventions  
- Reduced replacement and training costs  
- Improved workforce stability  
- Data-driven HR strategy formulation  

---

## ✅ Project Outcome
A production-ready attrition prediction framework that combines predictive modeling with actionable HR intelligence to support proactive talent retention.

---
