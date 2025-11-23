# zepto-ecommerce-sql-analysis
Real-world SQL Data Analytics project using Zepto e-commerce inventory dataset. Includes data cleaning, PostgreSQL setup, complex SQL queries, EDA insights, and business recommendations.
Zepto E-Commerce Inventory Analysis – SQL Project

A complete real-world SQL Data Analytics project using Zepto’s SKU-level inventory dataset.
This project focuses on data cleaning, exploratory data analysis (EDA), business insights, and SQL-based decision support.

🔍 Project Overview

This project analyzes SKU-level inventory data to understand:
Product pricing patterns
Discount strategies
Category-wise value
Weight distribution
Out-of-stock risks
Best-value and worst-value items
It simulates the type of analysis performed in real e-commerce companies.

🛠️ Tech Stack
PostgreSQL
SQL (CTEs, Aggregations, Window Functions)
CSV Data Cleaning
EDA using SQL
PgAdmin / DBeaver

🧹 Data Cleaning Steps
Removed products with missing MRP
Converted paise → rupees
Cleaned inconsistent categories
Standardized weight units (gm, kg)
Removed invalid discount rows

📊 Key SQL Analyses
Highest-value products
Best price-per-gram ranking
Most discounted categories
Out-of-stock high-demand SKUs
Category-wise revenue potential
Weight distribution & product sizing patterns

📈 Business Insights
Identified high-MRP products with low stock (risk area)
Highlighted categories with heavy discount dependency
Revealed best-value items for customer retention
Found pricing gaps where MRP vs selling price varied significantly

📎 Files Included
zepto_v2.csv (Dataset)
Zepto_SQL_data_analysis.sql (Full SQL script)
Supporting documentation notes

🚀 How to Run
Create PostgreSQL database
Import zepto_v2.csv
Run SQL script
Analyze outputs / insights
