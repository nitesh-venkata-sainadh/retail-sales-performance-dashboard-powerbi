# 📊 Retail Sales Performance Dashboard (Power BI)

*Executive-level retail revenue dashboard built using Power BI with star schema modeling and DAX measures.*

## 📌 Project Overview

This project analyzes retail sales performance from 2015–2018 to identify revenue trends, regional contribution, and top-performing product categories. The goal was to build an executive-level dashboard to support business decision-making.

## 🏗 Data Modeling  

I structured the data using a star schema model to keep the design scalable and organized.

- 1 Fact table: Fact_Sales
- 3 Dimension tables: Dim_Date, Dim_Customer, Dim_Product
- One-to-many relationships
- Created a separate Date table to support time-based analysis (YTD, monthly trends)
<img width="1253" height="701" alt="image" src="https://github.com/user-attachments/assets/6282a851-df66-4ad3-a429-5ea3937ee73a" />


## 📈 KPIs Created

- Total Sales
- Sales (YTD)
- Total Orders
- Average Order Value
- Average Revenue per Customer

These metrics help evaluate both overall performance and customer-level contribution.

## 📊 Dashboard Highlights

I have created five visuals they are:
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
- Top 10 products contribute significant share

## 🛠 Tools used
- Power BI
- Power Query
- DAX
- Star Schema Modeling

## 📁 Dataset

Superstore Sales Dataset (Kaggle)
