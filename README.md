# Zepto vs Blinkit: SQL Business Analysis 🧠📊

This project analyzes and compares two Indian delivery giants — **Zepto** and **Blinkit** — using SQL.  
A total of **12 business questions** are answered through modular SQL views, raw queries, and PowerPoint visuals.

## 📁 Project Structure
* **views_script.sql** → All views created to answer business questions
* **raw_queries.sql** → Raw SQL queries without using views
* **README.md** → This file 😊

## 📊 Dataset Overview
3 tables were created manually and cleaned using Excel:

| Table Name | Description |
| :--- | :--- |
| **customers** | Customer name, age, gender, email, city, state |
| **products** | Product name, brand (Zepto/Blinkit), category, price |
| **orders** | Date, time, total bill, quantity, product & customer IDs |

## 🔍 Key Business Questions Answered
1. Who are the top 5 customers by spend?
2. Which age group + brand generates the highest revenue?
3. What are the most ordered product categories by brand?
4. Age group-wise revenue split (young vs senior)
5. Top 3 selling products in each brand
6. Product categories exclusive to Zepto
7. Year-wise revenue comparison between brands
8. Top 3 cities by orders
9. Bottom 3 states by revenue
10. Month & Year-wise revenue trend
11. Weekend sales by brand
12. Customers with > 2 orders per brand
13. Total repeat orders (brand-wise)

## ⚙️ Technologies Used
* **Excel** – Data cleaning, quantity column generation
* **MySQL** – Joins, Aggregations, Window Functions, Views
* **Power BI** – For dashboard-level visualization

## 🧠 Key SQL Concepts Applied
* **JOIN** (Inner joins between 3 tables)
* **GROUP BY, ORDER BY, HAVING**
* **CASE WHEN** for segmenting age groups
* **RANK() & WINDOW FUNCTIONS**
* **VIEWS** for reusable business logic

## 📌 Output Sample (from PPT)
* 🔹 **Zepto** has stronger sales in Tier-1 cities.
* 🔹 **Blinkit** dominates weekend orders among 18–30 age group.
* 🔹 **Most sold categories:** Beverages & Snacks.
* 🔹 **Repeat customers** contribute 45%+ to total revenue.
