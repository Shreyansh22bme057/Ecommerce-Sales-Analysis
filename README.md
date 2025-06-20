# 📦 E-commerce Sales Analysis 

A complete end-to-end analytics solution that uses SQL, Excel, and Power BI to analyze and visualize e-commerce sales performance. This project is designed to provide insights into product trends, customer behavior, revenue, and operational performance.

---

## 🔍 Project Overview

This project walks through:
- 📊 Data visualization using **Power BI**
- 🧮 Data preparation and ETL using **SQL**
- 📑 Data storage and organization in **Excel**

---

## 🗂️ Project Structure

├── Ecommerce_Sales_Data.xlsx # Raw sales dataset
├── SQL_Script.sql # SQL script for ETL and analysis
├── Dashboard_Sales.pbix # Power BI dashboard report
└── README.md # Project documentation

yaml
Copy
Edit

---

## 🧾 Dataset Description

The data represents e-commerce sales and includes the following key fields:

- `invoice_id` – Unique identifier per transaction
- `branch`, `city` – Store information
- `customer_type`, `gender`
- `product_line` – Product category
- `unit_price`, `quantity`, `tax_pct`, `total`, `cogs`, `gross_income`
- `date`, `time`, `rating`, `payment`

---

## 🧮 SQL Analysis & ETL

Script: [`SQL_Script.sql`](SQL_Script.sql)

Key Transformations:
- Creating and loading the `sales` table
- Adding derived columns: `time_of_day`, `day_name`, `month_name`
- Data cleaning and enrichment

Key Analyses:
- 🛒 Product trends (e.g., best-selling products)
- 💸 Revenue & cost patterns by month and category
- 📍 City and branch performance
- 👤 Customer segmentation and behavior
- ⏱️ Time-based sales and ratings

---

## 📊 Power BI Dashboard

File: [`Dashboard_Sales.pbix`](Dashboard_Sales.pbix)

The Power BI dashboard includes:
- KPI cards: Revenue, Profit, Average Rating
- Sales trends by month, branch, and product line
- Customer demographics: Gender, Type, Location
- Time and weekday sales patterns
- Filter panels for dynamic exploration

> 📌 Note: Open this file using Power BI Desktop and refresh to load the latest data.

---

## 🛠️ How to Use

### 1. SQL Setup
- Import `Ecommerce_Sales_Data.xlsx` to a database (e.g., MySQL)
- Run `SQL_Script.sql` for cleaning and transformations

### 2. Power BI
- Open `Dashboard_Sales.pbix` with Power BI Desktop
- Ensure the data source links to your dataset (Excel or DB)
- Click **Refresh** to update visuals

---

## 📦 Tools & Technologies

- **Power BI** – Data visualization
- **MySQL / SQL** – Data transformation & querying
- **Excel** – Data storage and lightweight analysis

---
 
