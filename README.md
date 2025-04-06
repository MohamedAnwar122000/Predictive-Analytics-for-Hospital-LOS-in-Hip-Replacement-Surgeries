# 🏥 Predictive Analytics for Hospital LOS in Hip Replacement Surgeries

## 📊 Project Overview
This project leverages machine learning and data visualization to forecast the Length of Stay (LOS) for patients undergoing hip replacement surgeries. Using real-world hospital discharge data from New York State, the project aims to enhance healthcare efficiency and patient care by developing predictive models and an interactive Power BI dashboard.

---

## 🎯 Project Purpose
The goal is to:
- Identify key factors influencing LOS.
- Build and evaluate machine learning models to predict LOS categories.
- Develop Power BI dashboards to compare hospital performance in terms of LOS and cost.

---

## 📁 Dataset
The dataset is sourced from [Kaggle - Health Care Analytics](https://www.kaggle.com/datasets/frozenwanderer/health-care-analytics) and includes 26,278 patient records and 30 features such as:
- Patient demographics
- Procedure & diagnosis details
- Severity and risk scores
- Total cost and LOS

---

## 🧠 Machine Learning Models
The following models were developed and compared:
- Random Forest (RF)
- Gradient Boosting Decision Trees (GBDT)
- Support Vector Machine (SVM)
- Extreme Gradient Boosting (XGBoost)

**🔍 Best Performing Model:**  
`XGBoost` achieved the highest average ROC score (0.93) and was selected for final deployment.

---

## 🧪 Key Analysis Objectives
- What features most influence LOS?
- Which ML model predicts LOS best?
- How do hospitals differ in LOS and cost efficiency?

---

## 🛠 Tools and Techniques Used
- **Python (Google Colab):** Data cleaning, EDA, feature selection (Boruta), and ML model development.
- **Power BI:** Interactive dashboards for LOS, cost analysis, and hospital comparison.
- **Feature Engineering:** LOS binning, label encoding, feature scaling.
- **Model Evaluation:** ROC curve, AUC analysis.

---

## 📊 Dashboard Highlights
1. **LOS Comparison Dashboard** – Analyze LOS trends per hospital.
2. **Cost Comparison Dashboard** – Visualize average cost per discharge.
3. **Hospital Profile Dashboard** – Comprehensive hospital-level performance metrics.

---

## 📌 Key Insights
- Extreme severity and risk levels significantly increase LOS.
- High LOS and cost are often clustered in specific geographic regions.
- Hospitals with higher surgical volumes tend to have lower average LOS.

---

## 🧩 Future Work
- Incorporate additional features like post-op recovery metrics.
- Apply deep learning models for improved accuracy.
- Expand to multi-regional or real-time datasets for broader application.

