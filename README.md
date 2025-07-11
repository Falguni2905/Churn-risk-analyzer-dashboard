# 📊 Customer Churn Risk Analyzer Dashboard

> Built using **Power BI + Logistic Regression (Python)**  
> Designed to predict customer churn and visualize actionable business insights.

---

## 🔍 Project Overview

This project identifies customers at risk of churning in a telecom company using machine learning (Logistic Regression) and presents the results through an interactive Power BI dashboard.

It combines:
- Data science (Python)
- Data storytelling (Power BI)
- Business insight generation

---

## 📂 Project Structure

customer-churn-risk-analyzer/
├── data/
│ └── telco_churn_with_predictions.csv
├── notebooks/
│ └── data_cleaning.ipynb
├── dashboard/
│ └── Churn_Dashboard.pbix
├── images/
│ └── churn_dashboard_preview.png 
└── README.md

---

## 🧠 Machine Learning Workflow (Python)

- **Data Cleaning**: Removed nulls, encoded categorical variables
- **Model Used**: Logistic Regression
- **Target Variable**: `Churn`
- **Features Used**: Demographics, internet services, contracts, billing
- **Output**: 
  - `Churn_Predicted` (0 or 1)
  - `Churn_Probability` (likelihood of churning)

> The final CSV (`telco_churn_with_predictions.csv`) was imported into Power BI.

---

## 📊 Power BI Dashboard Features

| Visual                | Purpose                                         |
|-----------------------|-------------------------------------------------|
| 📍 Donut Chart        | Churned vs Not Churned                         |
| 📊 Bar Chart          | Churn by Contract Type                         |
| 💡 KPI Card           | Avg. Churn Risk Score                          |
| 📋 High-Risk Table     | Top churn risk customers (with heat coloring) |
| 🎛️ Slicers            | Gender, Contract, Tenure, Internet, Senior     |

---

## 💡 Key Insights

- **64%** average churn risk detected across customer base.
- **Month-to-Month** contracts have 3× higher churn rate than others.
- High-churn customers often pay more than ₹80/month and lack service add-ons.
- Senior Citizens with no tech support show higher churn tendencies.

---

## 🛠 Tools & Technologies

- **Python** (Pandas, Sklearn, Jupyter Notebook)
- **Power BI Desktop**
- **Machine Learning**: Logistic Regression

---

## 📥 How to Run

1. Open `data_cleaning.ipynb` to view Python ML process
2. Load `telco_churn_with_predictions.csv` into Power BI
3. Open `Churn_Dashboard.pbix` in Power BI Desktop
4. Use slicers to explore churn trends

---

## 📈 Perfect For

✅ Data Analyst Portfolio  
✅ Consulting/Analytics Interviews  
✅ Business Intelligence Demo Projects

---

## 📣 Connect With Me

*Built with curiosity, code, and a passion for solving real business problems.*

> [www.linkedin.com/in/falguniborkar29]

 ## 📄 Dashboard Preview
 
👉 [View Full Dashboard (PDF)] github.com/Falguni2905/Churn-risk-analyzer-dashboard

![Dashboard Screenshot](https://github.com/Falguni2905/Churn-risk-analyzer-dashboard/raw/main/Images/churn_dashboard_screenshot.png)
