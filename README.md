## 🛒 Flipkart Sales Data Analysis using SQL

### 📌 Project Overview

This project demonstrates how SQL can be used to analyze and extract meaningful insights from an **E-commerce sales dataset**.
The queries cover data retrieval, filtering, aggregation, joins, subqueries, views, and performance optimization.

---

### 🎯 Objective

To practice and understand how to manipulate structured data using SQL for real-world business analysis.

---

### 🗂 Dataset Used

**Flipkart Sales Dataset**

**Key Columns:**

* Order ID
* Product Name
* Category
* Quantity Sold
* Total Sales (INR)
* Profit (INR)
* Customer Rating
* Payment Method
* Region
* Order Date

---

## 🔹 SQL Concepts Implemented

### ✅ 1. SELECT, WHERE, ORDER BY, GROUP BY

Used to retrieve, filter, sort, and summarize data.

**Examples:**

* Filter products by category
* Sort products by highest sales
* Calculate total sales per category

**Insights:** Helped identify top-performing categories and products.

---

### ✅ 2. JOINS (INNER, LEFT, RIGHT)

Used to combine data from multiple tables such as orders and product details.

**Examples:**

* INNER JOIN to match orders with product information
* LEFT JOIN to keep all orders even if product details are missing

**Insights:** Enabled combining related data for deeper analysis.

---

### ✅ 3. Subqueries

Used nested queries to compare values with averages and totals.

**Examples:**

* Find products with sales above average
* Identify high-performing products

**Insights:** Helped detect products performing better than overall trends.

---

### ✅ 4. Aggregate Functions (SUM, AVG)

Used to compute business metrics.

**Examples:**

* Total revenue generated
* Average customer rating
* Total profit by region

**Insights:** Provided key performance indicators for business decisions.

---

### ✅ 5. Views for Analysis

Created views to simplify repeated analysis.

**Examples:**

* Monthly sales summary view
* Customer spending summary

**Benefits:**

* Simplifies complex queries
* Improes reusability
* Saves analysis time

---

### ✅ 6. Query Optimization using Indexes

Indexes were created on frequently searched columns.

**Examples:**

* Index on Category
* Index on Order Date

**Benefits:**

* Faster query execution
* Improved performance on large datasets

---

## 📊 Key Business Insights Derived

✔ Top-selling product categories
✔ Regions generating highest profit
✔ Most used payment methods
✔ Monthly sales trends
✔ High-performing products

---

## ⚠ Challenges Faced

* Numeric columns imported as text (VARCHAR)
* Resolved using **CAST()**, **REPLACE()**, and data cleaning

---

## 🛠 Tools Used

* SQL Server / MySQL (any RDBMS)
* CSV dataset

---

## 📚 Learning Outcomes

✔ Data filtering & sorting
✔ Writing complex queries
✔ Business data analysis
✔ Performance optimization
✔ Real-world SQL problem solving

---

## 🚀 Future Improvements

* Connect SQL with Power BI for dashboards
* Automate reports using stored procedures
* Perform advanced analytics using Python

---

⭐ This project strengthened my understanding of SQL and its role in real-world data analysis.
