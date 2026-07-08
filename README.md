# 🛍️ Consumer Behavior Analytics Dashboard

An end-to-end Business Intelligence project that analyzes retail customer purchasing behavior using **Python**, **PostgreSQL**, and **Power BI**. The project transforms raw customer transaction data into interactive dashboards that provide actionable business insights.
<img width="1741" height="903" alt="dashboard" src="https://github.com/user-attachments/assets/99ce66cb-f1f6-46c6-8287-e90a90624578" />

---

## 📖 Project Overview

This project focuses on analyzing consumer purchasing patterns to help businesses understand:

- Customer demographics
- Revenue trends
- Product category performance
- Customer subscriptions
- Purchase behavior
- Sales performance

The dataset was cleaned and transformed using Python, stored in PostgreSQL, and visualized using Power BI to create an interactive dashboard.

---

## 🛠️ Tech Stack

- 🐍 Python (Pandas, NumPy)
- 🗄️ PostgreSQL
- 📊 Power BI
- 📒 Jupyter Notebook
- 🧹 Data Cleaning & Preprocessing
- 📈 Business Intelligence & Data Visualization

---

## 📂 Project Structure

```
Consumer-Behavior-Analytics/
│
├── data/
│   └── customer_shopping_behaviour.csv
│
├── notebooks/
│   └── Consumer-Behaviour-Analysis.ipynb
│
├── dashboard/
│   └── Customer_Behavior_Dashboard.pbix
│
├── images/
│   ├── dashboard.png
│   └── dashboard_preview.png
│
├── report/
│   └── Consumer_Behavior_Report.pdf
│
└── README.md
```

---

## 📊 Dashboard Features

### KPI Cards

- Number of Customers
- Average Purchase Amount
- Average Review Rating

### Visualizations

- Revenue by Category
- Sales by Category
- Revenue by Age Group
- Sales by Age Group
- Subscription Status Distribution

### Interactive Filters

- Subscription Status
- Gender
- Product Category
- Shipping Type

---

## 📈 Key Insights

- 👥 **3,900** customer records analyzed.
- 💰 Average purchase amount is **$59.76**.
- ⭐ Average customer review rating is **3.75/5**.
- 👕 Clothing generates the highest revenue.
- 🛍️ Young Adults contribute the largest share of sales.
- 📬 Only **27%** of customers have active subscriptions, presenting an opportunity for improved customer retention.

---

## ⚙️ Data Processing Workflow

1. Load raw customer dataset
2. Handle missing values
3. Rename and standardize columns
4. Export cleaned dataset
5. Import into PostgreSQL
6. Perform SQL analysis
7. Connect Power BI to PostgreSQL
8. Build interactive dashboard

---

## 🧹 Data Cleaning

Performed using **Pandas**

- Converted column names to lowercase
- Replaced spaces with underscores
- Renamed columns for SQL compatibility
- Checked missing values
- Verified data types
- Prepared dataset for PostgreSQL import

---

## 💻 Example SQL Query

```sql
SELECT
    category,
    SUM(purchase_amount) AS revenue
FROM customer
GROUP BY category
ORDER BY revenue DESC;
```

---

## 📸 Dashboard Preview

> *(Insert dashboard screenshot here)*

```
images/dashboard.png
```

---

## 🚀 Future Improvements

- Customer segmentation using clustering
- Predictive sales forecasting
- Customer Lifetime Value (CLV)
- RFM Analysis
- Recommendation System
- Time-series sales analysis

---

## 🎯 Learning Outcomes

This project strengthened my skills in:

- Data Cleaning
- SQL Querying
- PostgreSQL
- Power BI
- Dashboard Design
- Business Intelligence
- Data Visualization
- Analytical Thinking

---

## 👩‍💻 Author

**Rachana Medehal**

- GitHub: https://github.com/MRachana1999
- LinkedIn: *(Add your LinkedIn URL)*

---

⭐ If you found this project helpful, consider giving it a star!
