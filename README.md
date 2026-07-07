# 👨‍💼 Employee Attrition Analysis using Machine Learning

## 📌 Project Overview

Employee attrition is a major challenge for organizations. This project analyzes HR data to identify the key factors influencing employee turnover and builds machine learning models to predict whether an employee is likely to leave the company.

The project also includes an interactive Power BI dashboard to help HR teams make data-driven decisions.

---

## 🎯 Objectives

* Analyze employee attrition patterns.
* Identify factors affecting employee turnover.
* Build machine learning models for prediction.
* Compare model performance.
* Create an interactive HR dashboard.

---

## 📂 Dataset

The project uses the **IBM HR Employee Attrition Dataset**, which contains employee information such as:

* Age
* Department
* Job Role
* Monthly Income
* Education
* Business Travel
* Job Satisfaction
* OverTime
* Years at Company
* Attrition (Target Variable)

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook
* Power BI

---

## 📊 Exploratory Data Analysis

The following analyses were performed:

* Employee Attrition Distribution
* Age Distribution
* Monthly Income Analysis
* Attrition by Department
* Attrition by Job Role
* Attrition by Gender
* Attrition by OverTime
* Correlation Heatmap
* Feature Importance Analysis

---

## 🤖 Machine Learning Models

Two classification models were used:

* Logistic Regression
* Random Forest Classifier

### 📈 Model Performance

| Model               | Accuracy     |
| ------------------- | ------------ |
| Logistic Regression | **89.47%**   |
| Random Forest       | **88.10%** ⭐ |

> Replace the above values with your actual model accuracy.

---

## 📌 Key Insights

* Employees working overtime are more likely to leave.
* Lower monthly income is linked to higher attrition.
* Some departments and job roles have higher turnover.
* Younger employees show relatively higher attrition.
* Years at Company and Monthly Income are important predictors.

---

## 📊 Dashboard

The Power BI dashboard includes:

* KPI Cards

  * Total Employees
  * Attrition Count
  * Attrition Rate
  * Average Age
  * Average Monthly Income

* Interactive Visualizations

  * Attrition by Department
  * Attrition by Job Role
  * Attrition by Gender
  * Attrition by OverTime
  * Age Distribution
  * Feature Importance

---

## 📁 Project Structure

```text
Employee-Attrition-Analysis/
│
├── Employee_Attrition_Analysis.ipynb
├── HR-Employee-Attrition.csv
├── Employee_Attrition_Dashboard.pbix
└── README.md
```

---

## 🚀 Future Improvements

* Improve model performance with hyperparameter tuning.
* Handle class imbalance using SMOTE.
* Try advanced models such as XGBoost.
* Deploy the project using Streamlit.

