# 📊 Retail Sales Performance Dashboard (Power BI)

*Executive-level retail revenue dashboard built using Power BI with star schema modeling and DAX measures.*

## 📌 Project Overview

This project analyzes retail sales performance from 2015–2018 to identify revenue trends, regional contribution, and top-performing product categories. The goal was to build an executive-level dashboard to support business decision-making.

## 🏗 Data Modeling  

The data was structured using a star schema model to improve scalability, clarity, and query performance.
- 1 Fact table: facts_Sales
- 3 Dimension tables: dim_date, dim_customer, dim_product
- One-to-many relationships
- Created a separate Date table to support time-based analysis (YTD, monthly trends)
<img width="1306" height="738" alt="image" src="https://github.com/user-attachments/assets/4c4859be-84c2-4700-94c6-e7dff244a75b" />


## 📈 KPIs Created

- Total Sales
- Sales (YTD)
- Total Orders
- Total Customers
- Average Order Value
- Average Revenue per Customer

These metrics help evaluate both overall performance and customer-level contribution.

## 📊 Dashboard Highlights

The dashboard includes the following key visuals:
- Monthly revenue trend analysis
- Revenue contribution by region
- Revenue by product category
- Top 10 products by revenue
- Interactive filters by Year and Segment
<img width="1278" height="719" alt="image" src="https://github.com/user-attachments/assets/f65c7b57-34ce-4cff-9b49-6497343a17f4" />

## 📌 Key Business Insights
- West region generates the highest overall revenue contribution
- Technology is the top-performing category, contributing the largest portion of total revenue
- Sales show a noticeable increase toward the end of the year, especially in Q4
- The top 10 products account for a significant share of total revenue

## 🛠 Tools Used
- Power BI
- Power Query
- DAX
- Star Schema Modeling

## 📁 Dataset

Superstore Sales Dataset (Kaggle)
