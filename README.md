# Global-Superstore
Consolidated business intelligence solution providing deep insights into sales performance, returns, regional trends, and product profitability using Power BI and data modelling techniques.

## 📌 Overview

This project presents a dynamic Power BI dashboard built using the *Global Superstore* dataset. The goal is to provide end-to-end visibility into key business metrics such as revenue, profit, order trends, customer insights, and product performance across various geographies and categories. It supports data-driven decision-making by offering clear visual narratives and actionable KPIs.

## 🎯 Problem Statement

Global retail chains often struggle to monitor sales, profits, and customer returns across diverse regions and product categories. This dashboard addresses the challenge by consolidating disparate data sources (sales, returns, customer info, employees, products) into a unified visual platform, enabling:

- Real-time insights on sales and returns
- Regional performance comparisons
- Product-level profitability tracking
- Operational efficiencies via shipping and discount analysis

## 🧩 Dataset Description

The dashboard uses multiple interconnected datasets:

- `Sales.csv`: Primary sales transactions with order-level details
- `Returns.csv`: Returned orders for refund analysis
- `Customer Details.csv`: Customer demographics and segments
- `Product Details.csv`: Product hierarchy and pricing
- `Employee.csv`: Sales representatives and their regions
- `Territories.csv`: Market and region segmentation
- `Calendar.csv`: Date hierarchy for time-based analysis

> All data has been anonymized for educational purposes.

## 🧼 Data Cleaning & Transformation

Performed in Power Query (Power BI) and included:

- Removal of null and duplicate values  
- Joining tables using common keys (e.g., `Order ID`, `Customer ID`)  
- Creation of date hierarchy using the calendar table  
- Custom columns for metrics such as **Profit Margin**, **Average Discount**, and **Return Rate**

## 📊 Key Metrics Visualized

- **Total Revenue:** $12.64M  
- **Total Orders:** 25K  
- **Total Profit:** $1.47M  
- **Average Order Value:** $504.99  
- **Profit Margin:** 11.61%  
- **Total Returns:** 1,173  
- **Most Sold Subcategory:** Binders  
- **Top-Grossing Segment:** Technology  

## 🌍 Geographic Analysis

Mapped revenue and profit by:

- **Country**
- **City**
- **Regional Market (APAC, EU, LATAM, US, etc.)**

## 📈 Dashboard Features

- KPI Cards for performance highlights  
- Drill-down by category, sub-category, and product  
- Filters by region, ship mode, and segment  
- Time-series graphs by quarter/year  
- Visuals for return analysis and discount impact  
- Cross-filtering between visuals for interactivity

## ⚙️ Tools & Technologies

- **Power BI Desktop**  
- **Power Query**  
- **DAX (Data Analysis Expressions)**  
- **Custom Visuals & Maps**

## 💡 Insights & Use Cases

- Identify underperforming products or regions  
- Track impact of discounts on revenue and profit  
- Monitor returns to improve operational efficiency  
- Support executives with strategic decision-making tools.