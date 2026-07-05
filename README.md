# 🛒 E-commerce Sales Analysis & Customer Segmentation | Excel + SQL

## 📌 Project Overview

This project analyzes e-commerce sales data to identify revenue trends, customer purchasing behavior, and product performance. The analysis helps uncover business insights that support inventory planning, sales optimization, and data-driven decision-making.

---

## 🎯 Objectives

- Analyze overall sales performance across products and categories
- Identify top-performing product categories by revenue
- Perform customer segmentation based on purchasing behavior
- Analyze seasonal sales trends and monthly revenue growth
- Track key business KPIs using interactive dashboards
- Support business decisions through SQL-based analytics

---

## 🧠 Business Problem

E-commerce businesses generate large volumes of transactional data every day.

- Which product categories generate the highest revenue
- Which customers contribute the most sales
- How sales change across different time periods
- Which products require inventory attention

An appropriate understanding of this will help businesses optimize marketing strategies, improve inventory planning, and maximize revenue.
---


### Features

- Order ID
- Customer ID
- Product Category
- Product Name
- Quantity
- Unit Price
- Revenue
- Order Date
- Customer Segment
- Region

---

## 🏗️ Data Modeling & SQL Design

The raw transactional dataset was cleaned and transformed into a normalized relational database to reduce redundancy and improve query performance.

### Tables

- customers → customer information
- products → product details
- orders → order-level information
- order_details → purchased products and quantities


---

## 🔍 Key Business Questions

- Which product categories generate the highest revenue?
- Which customers contribute the most sales?
- What percentage of total revenue comes from the top-selling categories?
- Are there any seasonal sales trends?
- Which months generate the highest revenue?
- Which products have the highest sales volume?
- How do different customer segments contribute to revenue?

---

## ⚙️ Analysis Approach

### Data Preparation

- Data cleaning and validation
- Handling missing values
- Standardizing formats
- Database normalization

### SQL Analysis

- Multi-table JOINs
- Revenue calculations
- Aggregations
- GROUP BY and HAVING
- Customer segmentation
- Ad hoc business analysis

### Power BI

- KPI dashboard
- Revenue analysis
- Product performance dashboard
- Customer segmentation dashboard
- Monthly sales trends

---

## 📈 Key Insights

- Top-performing product categories contributed approximately **68% of total revenue**.
- A noticeable **Q4 seasonal sales spike** highlighted increased customer purchasing activity.
- Customer segmentation revealed purchasing patterns useful for targeted marketing.
- Revenue trends helped identify high-performing months and products.
- Interactive dashboards enabled faster reporting and business decision-making.

---

## 🛠️ Tools & Technologies

- MySQL
- SQL (JOINs, GROUP BY, Aggregations, CASE statements)
- Excel


---

## 📁 Repository Structure

```text
├── dataset/
├── sql/
│   ├── schema_and_setup.sql
│   ├── sales_analysis.sql
│   └── customer_segmentation.sql
├── powerbi/
├── screenshots/
└── README.md
```

---

## 🚀 Future Improvements

- Automate the ETL pipeline for incremental data loading.
- Integrate cloud storage and data warehouse solutions.
- Add predictive sales forecasting using machine learning.
- Build real-time dashboards connected to live data sources.
- Expand customer segmentation using RFM analysis.
