# 📊 Power BI Sales Dashboard

## 📌 Project Overview
An interactive Power BI dashboard built on MySQL sales data to analyze
revenue, orders, categories, customers, and monthly trends.

This project demonstrates:
- SQL data modeling
- Power BI data connections
- DAX measures
- Interactive dashboards

---

## 🧰 Tech Stack
- Database: MySQL
- Visualization: Power BI Desktop
- Language: SQL, DAX
- OS: Windows

---

## 🗂️ Dataset
Source tables:
- customers
- orders
- order_items
- products

SQL Views:
- sales_fact
- monthly_revenue
- category_revenue

---

## 📈 Dashboard Features
- Total Revenue KPI
- Total Orders KPI
- Revenue by Category
- Monthly Revenue Trend
- Orders by Month
- Interactive slicers (Month, Category, City)

---

## 🧮 Key DAX Measures
```DAX
Total Revenue =
SUM ( Sales_Fact[revenue] )

Total Orders =
DISTINCTCOUNT ( Sales_Fact[order_id] )
