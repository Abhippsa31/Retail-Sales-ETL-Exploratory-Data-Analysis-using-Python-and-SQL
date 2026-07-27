# Retail-Sales-ETL-Exploratory-Data-Analysis-using-Python-and-SQL
An end-to-end Data Analytics project demonstrating the complete workflow of **Extract, Transform, Load (ETL)**, **SQL Analysis**, **Statistical Analysis**, and **Exploratory Data Analysis (EDA)** using the Sample Superstore dataset.

## 🚀 Project Overview

This project analyzes retail sales data to uncover business insights related to sales performance, profitability, customer segments, and regional trends. The workflow includes data cleaning, feature engineering, SQL-based analysis, statistical analysis, and data visualization.

---

## 🎯 Objectives

- Perform an end-to-end ETL process using Python.
- Clean and transform raw retail sales data.
- Load the processed dataset into an SQLite database.
- Analyze business performance using SQL queries.
- Perform Exploratory Data Analysis (EDA).
- Generate actionable business insights through statistical analysis and visualizations.

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- SQLite
- SQL
- Matplotlib
- Seaborn
- Google Colab

---

## 📂 Dataset

**Dataset:** Sample Superstore

The dataset contains approximately **10,000 retail sales records** with the following attributes:

- Ship Mode
- Segment
- Country
- City
- State
- Postal Code
- Region
- Category
- Sub-Category
- Sales
- Quantity
- Discount
- Profit

---

## ⚙️ ETL Process

### Extract
- Imported the retail sales dataset into Python using Pandas.

### Transform
- Removed duplicate records.
- Verified missing values.
- Renamed columns for consistency.
- Converted categorical variables to appropriate data types.
- Created additional features:
  - Profit Margin
  - Revenue Per Item
  - Loss Indicator
  - Discount Level

### Load
- Stored the cleaned dataset in an SQLite database for SQL-based analysis.

---

## 📈 SQL Analysis

The project includes SQL queries to analyze:

- Total Sales
- Total Profit
- Sales by Category
- Profit by Category
- Sales by Region
- Profit by Region
- Top Cities by Sales
- Top Sub-Categories
- Average Discount
- Profit Margin Analysis
- Loss Analysis

---

## 📊 Exploratory Data Analysis

Performed EDA using Python to identify business patterns through:

- Summary Statistics
- Correlation Analysis
- Distribution Analysis
- Sales by Category
- Profit by Category
- Regional Performance
- Customer Segment Analysis
- Top Cities Analysis
- Top Sub-Categories
- Discount vs Profit Relationship
- Outlier Detection

---

## 💡 Key Insights

- Technology generated the highest overall sales revenue.
- The West region achieved the highest sales and profitability.
- Higher discount levels were generally associated with lower profit margins.
- Consumer customers contributed the largest share of total sales.
- Several high-value sales transactions were identified as outliers.
- A small number of cities accounted for a significant proportion of overall revenue.

---
## 📌 Conclusion

This project demonstrates a complete end-to-end data analytics workflow, including ETL, SQL analysis, statistical analysis, and exploratory data analysis. By transforming raw retail sales data into meaningful business insights, the project showcases practical skills in Python, SQL, data cleaning, feature engineering, and data visualization that are commonly applied in real-world business intelligence and analytics roles.

---

