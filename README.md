# Retail-Business-Forecasting-Dashboard
Power BI dashboard for analyzing retail business performance and forecasting future sales using machine learning.
# 🧠 Retail Business Performance Dashboard – Power BI Project

A complete end-to-end **Business Intelligence project** using Power BI that analyzes a retail company's performance over the years **2015, 2016, and 2017**, and applies **Machine Learning forecasting models** to predict revenue, profit, and quantity trends until **end of 2019**.


---

## 📌 Project Overview

This project provides deep insights into sales, customer behavior, product performance, order returns, and business targets. It consists of:

- **Data Cleaning & Preparation** using Power Query
- **Data Modeling** (Star and Snowflake Schema)
- **Interactive Dashboards** for key metrics
- **Churn Analysis**, **YoY Growth**, and **Forecasting** using time series models

---

## 🗂️ Data Sources

- Calendar
- Customers
- Product Category
- Product Subcategory
- Product
- Returns
- Sales 2015, Sales 2016, Sales 2017
- Territories

All sales tables were **appended into a single unified fact table**: Total Sales.

---

## 🛠️ Tools & Techniques Used

- Power BI (Power Query, Data Modeling, DAX, Visualization)
- Star & Snowflake Schema
- Time Series Forecasting (ML)
- KPI Cards, Slicers, Drill-through
- DAX Measures and Calculated Columns

---

## 🔧 Data Modeling

- Two fact tables: Total Sales and Returns
- Clean relationship setup using:
  - Star Schema for performance
  - Snowflake Schema for dimension details
- Relationships: mostly One-to-Many, minimal Many-to-One

<img width="1878" height="811" alt="Screenshot 2025-07-19 230955" src="https://github.com/user-attachments/assets/be386ace-6ff7-496f-9355-2cff7ddda528" />

---

## 📊 Dashboard Pages & Key Insights

### 1. 📌 Summary Page
- **Total Revenue:** 24.91M
- **Total Price:** 24.60M
- **Profit:** 10.58M
- **Customers:** 18.02K
- **Profit Margin:** 43%
- **Top Region (by profit):** Australia
- **Year-wise:**
  - 2015: 2.6M Profit, 6.4M Revenue
  - 2016: 4M Profit, 9.3M Revenue
  - 2017 (until June): 4M Profit, 9.2M Revenue

<img width="1453" height="814" alt="Screenshot 2025-07-27 122147" src="https://github.com/user-attachments/assets/fbbdff8c-65b8-456e-8144-1358595f3bd7" />

---

### 2. 🚴 Product Analysis
- **Top-selling product:** Bikes
- **Worst performing:** Components (0 sales over 3 years)
- **Year-over-Year (YoY) Growth:**
  - 2016: +45.85%
  - 2017: -1.49%
- **Total Quantity Sold:** 84K
- **Bulk Orders (>1):** 15K
- **Total Orders:** 25K

<img width="1444" height="811" alt="Screenshot 2025-07-27 122202" src="https://github.com/user-attachments/assets/48d9190c-3aa5-4aa8-8af6-ec28650645b0" />

---

### 3. 👥 Customer Insights
- **Total Customers:** 18.02K
- **Repeat Customers:** 15K
- **Churned Customers (purchased only once):** 3,012

<img width="1458" height="806" alt="Screenshot 2025-07-27 122705" src="https://github.com/user-attachments/assets/c6772826-f7df-4d62-a79c-e8f39c421bbe" />

---

### 4. 🔁 Returned Orders
- **Returned Orders:** 1,809
- **Returned Quantity:** 1,828
- **Return Revenue:** 765.28K
- **Return Rate:** 7%
- **Return Revenue % of Total:** 3%
- **Highest Return Year:** 2017

<img width="1450" height="807" alt="Screenshot 2025-07-27 122226" src="https://github.com/user-attachments/assets/69dedb10-5d0c-4f55-a57c-faff5df9ac67" />

---

### 5. 🎯 Business Target Page
- **Revenue Goal:** +1.5× from previous year
- **Profit Goal:** +1.2× from previous year

<img width="1449" height="819" alt="Screenshot 2025-07-27 122242" src="https://github.com/user-attachments/assets/17e45033-ccd0-4adc-9edf-72a9d812dda4" />


---

## 🔮 Forecasting (Time Series ML)

Using Machine Learning to forecast key business KPIs until the end of **2019**:

| Metric       | 2017 (EoY) | 2018 (Forecast) | 2019 (Forecast) |
|--------------|------------|----------------|----------------|
| 📈 Profit     | 5.63M      | +36.4%         | +50%           |
| 📦 Quantity   | 70K        | 182K           | 250K           |

<img width="1463" height="803" alt="Screenshot 2025-07-27 122303" src="https://github.com/user-attachments/assets/ebddde51-4164-4f10-94cc-a085a5487adc" />

➡️ The trend shows consistent quarterly and yearly growth, indicating strong future performance if the pattern continues.

---

## 📁 Files Included

- .pbix file (Power BI dashboard)
- README.md (Project documentation)
- Exported snapshots (optional)
- Sample data schema (if public)

---


