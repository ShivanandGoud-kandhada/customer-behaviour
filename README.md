# 🛒 Customer Behavior Analytics (SQL + Python + Power BI)

### Turning Raw Data into Actionable Business Insights

---

## 📌 Problem Statement

Businesses often struggle to identify:

* Who their most valuable customers are
* Which products drive the most revenue
* Whether discounts actually improve sales

This project analyzes **3,900+ customer transactions** to uncover insights that help improve **revenue, retention, and decision-making**.

---

## 🎯 Key Insights

* 💰 Discount users contribute significantly to total revenue → pricing opportunity
* 🔁 Repeat customers show higher likelihood of subscription → loyalty potential
* 🏆 Top products dominate category sales → focused marketing can boost ROI
* 👥 Certain age groups generate the majority of revenue → targeted campaigns

---

## 🔄 End-to-End Workflow

### 🧹 1. Data Cleaning & EDA (Python)

📁 `notebooks/eda_customer_behavior.ipynb`

* Handled missing values (ratings imputed using median)
* Created new features:

  * `age_group`
  * `purchase_frequency_days`
* Explored:

  * Purchase distributions
  * Customer demographics
  * Product trends

---

### 🧠 2. SQL Analysis

📁 `sql/queries.sql`

* Revenue analysis
* Customer segmentation (New / Returning / Loyal)
* Top products using ranking (window functions)
* Discount impact analysis

---

### 📊 3. Power BI Dashboard

📁 `dashboard/customer_behavior_dashboard.pbix`

Interactive dashboard covering:

* Sales overview
* Customer segmentation
* Product performance

---

## 📸 Dashboard Preview

### Sales Overview

![Sales Overview](images/dashboard1.png)

### Customer Segmentation

![Customer Segmentation](images/dashboard2.png)

### Product Performance

![Product Performance](images/dashboard3.png)

---

## 📂 Project Structure

```plaintext
customer-behavior-analytics-sql-powerbi/
│── README.md
│── data/
│     ├── cleaned_shopping_data.csv
│
│── notebooks/
│     ├── eda_customer_behavior.ipynb
│
│── sql/
│     ├── queries.sql
│
│── dashboard/
│     ├── customer_behavior_dashboard.pbix
│
│── reports/
│     ├── project_report.pptx
│
│── docs/
│     ├── problem_statement.md
│
│── images/
│     ├── dashboard1.png
│     ├── dashboard2.png
│     ├── dashboard3.png
```

---

## 🛠️ Tools & Technologies

* Python (Pandas, Data Cleaning, EDA)
* SQL (PostgreSQL)
* Power BI

---

## 💡 Business Impact

* Enables **targeted marketing strategies**
* Improves **customer retention** using behavioral insights
* Optimizes **discount strategies**
* Highlights **high-performing products & segments**

---

## 🚀 How to Use

1. Open Jupyter Notebook → explore EDA
2. Run SQL queries on dataset
3. Open Power BI dashboard
4. Review insights and recommendations

---

## 🔮 Future Improvements

* Customer churn prediction
* Cohort analysis
* Customer lifetime value (LTV) modeling

---

## 👨‍💻 Author

**Shivanand Goud**
Aspiring Data Analyst

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub!
