# 📊 Telco Customer Churn Analysis & Prediction

![Python](https://img.shields.io/badge/Python-3.12-blue)
![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow)
![Scikit--Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

# 🚀 Project Highlights

- 📈 Analyzed **7,032 telecom customer records** to identify churn patterns.
- 🧹 Performed comprehensive **data cleaning, preprocessing, and feature engineering**.
- 📊 Conducted detailed **Exploratory Data Analysis (EDA)** to uncover customer behavior.
- 🤖 Built and compared **Logistic Regression** and **Random Forest** classification models.
- 🎯 Achieved **80.38% Accuracy** and **0.845 ROC-AUC** using Logistic Regression.
- 📉 Developed an **interactive Power BI dashboard** with KPIs, slicers, and business insights.
- 💡 Generated actionable recommendations to improve customer retention.

---

# 📌 Project Overview

Customer churn is one of the biggest challenges faced by subscription-based businesses. Retaining existing customers is significantly more cost-effective than acquiring new ones.

This project analyzes customer behavior using the **IBM Telco Customer Churn Dataset** to identify the major factors influencing customer churn and develops machine learning models capable of predicting customers who are likely to leave.

The project combines:

- 📊 Exploratory Data Analysis (EDA)
- 🤖 Machine Learning
- 📈 Power BI Dashboard
- 💼 Business Recommendations

to support data-driven decision making.

---

# 💼 Business Problem

Telecommunication companies lose significant revenue when customers discontinue their services.

The primary objectives of this project are to:

- Understand customer churn behavior.
- Identify key churn drivers.
- Build predictive models.
- Recommend business strategies to improve customer retention.

---

# 🎯 Project Objectives

- Perform data cleaning and preprocessing.
- Conduct exploratory data analysis.
- Identify important churn factors.
- Build predictive machine learning models.
- Compare multiple classification algorithms.
- Visualize business insights using Power BI.
- Recommend strategies to reduce customer churn.

---

# 📂 Dataset Information

**Dataset:** IBM Telco Customer Churn Dataset

- Total Records: **7,043**
- Original Features: **21**
- Target Variable: **Churn**

After preprocessing:

- Removed **11 incomplete records**
- Final Dataset: **7,032 customers**

---

# 📁 Project Structure

```text
Telco-Customer-Churn/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── models/
│
├── notebooks/
│   ├── 01_EDA.ipynb
│   └── 02_Machine_Learning.ipynb
│
├── dashboard/
│   └── Telco_Churn.pbix
│
├── images/
│
├── reports/
│
├── README.md
│
└── requirements.txt
```

---

# 🛠 Tools & Technologies

### Programming

- Python

### Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

### Business Intelligence

- Power BI

### Development Environment

- Jupyter Notebook

---

# 🔄 Project Workflow

```text
Raw Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Feature Engineering
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Machine Learning
      │
      ▼
Model Evaluation
      │
      ▼
Power BI Dashboard
      │
      ▼
Business Recommendations
```

---

# 📊 Exploratory Data Analysis

The following analyses were performed:

- Overall Churn Distribution
- Gender vs Churn
- Senior Citizen Analysis
- Partner Analysis
- Dependents Analysis
- Contract Type Analysis
- Customer Tenure Analysis
- Monthly Charges Analysis
- Internet Service Analysis
- Payment Method Analysis
- Tech Support Analysis
- Online Security Analysis
- High-Risk Customer Segment Analysis
- Contract Type vs Internet Service
- Correlation Analysis

---

# 🤖 Machine Learning Models

The following classification models were developed:

- Logistic Regression
- Random Forest Classifier

Model evaluation metrics:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix
- ROC Curve
- Cross Validation

---

# 📈 Model Performance

| Model | Accuracy | Precision | Recall | F1 Score | ROC-AUC |
|-------|---------:|----------:|--------:|---------:|--------:|
| Logistic Regression | 80.38% | 64.76% | 57.49% | 60.91% | 0.836 |
| Random Forest | 78.54% | 61.92% | 50.00% | 55.33% | 0.815 |

## 🏆 Best Performing Model

**Logistic Regression**

Average Cross Validation ROC-AUC

**0.845**

---

# 🔍 Important Churn Drivers

The machine learning models identified the following features as major contributors to customer churn:

- Contract Type
- Customer Tenure
- Monthly Charges
- Internet Service
- Tech Support
- Online Security
- Payment Method

---

# 📊 Power BI Dashboard

The interactive dashboard includes:

- Executive KPI Cards
- Customer Churn Overview
- Contract Type Analysis
- Internet Service Analysis
- Customer Retention Drivers
- Interactive Filters (Slicers)
- Business Recommendations

### Dashboard Preview

> *(Dashboard screenshots will be added after final formatting.)*

---

# 📌 Key Business Insights

- Customers with Month-to-Month contracts have the highest churn rate.
- Churn is highest during the first year of service.
- Fiber Optic customers experience significantly higher churn than DSL customers.
- Customers paying via Electronic Check are more likely to churn.
- Lack of Tech Support and Online Security is strongly associated with higher churn.
- Customers with longer tenure are significantly less likely to churn.

---

# 💡 Business Recommendations

- Encourage customers to migrate to One-Year or Two-Year contracts.
- Improve onboarding and engagement during the first 12 months.
- Promote Tech Support and Online Security plans.
- Review Fiber Optic pricing and service quality.
- Encourage automatic payment methods through discounts or incentives.

---

# 📦 Project Outputs

- Cleaned Dataset
- Machine Learning Dataset
- Trained Logistic Regression Model
- Feature Scaler
- Model Comparison Report
- Power BI Dashboard
- Business Insights
- Business Recommendations

---

# ▶️ How to Run

Clone the repository:

```bash
git clone https://github.com/yourusername/Telco-Customer-Churn.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run:

1. **01_EDA.ipynb**
2. **02_Machine_Learning.ipynb**
3. Open the **Power BI Dashboard (.pbix)**

---

# 📚 Dataset Source

IBM Telco Customer Churn Dataset

Available through IBM Sample Datasets and Kaggle.

---

# 🚀 Future Improvements

- Deploy the model using Streamlit
- Develop a real-time churn prediction API
- Automate model retraining
- Integrate live business dashboards

---

# 👨‍💻 Author

**Amit Sharma**

Aspiring Data Analyst

### Skills

- Python
- SQL
- Excel
- Power BI
- Machine Learning
- Data Visualization

---

## ⭐ If you found this project helpful, consider giving it a star.