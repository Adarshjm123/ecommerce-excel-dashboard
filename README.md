# E-commerce Sales & Operations Dashboard (Excel)

## Overview
This project presents an end-to-end data analysis of an e-commerce dataset (Olist) using Microsoft Excel. The goal was to transform raw transactional data into actionable business insights related to sales performance, product contribution, and delivery operations.

The dashboard enables stakeholders to understand trends, identify inefficiencies, and support data-driven decision-making.

---

## Objectives
- Analyze overall revenue performance  
- Identify top-performing product categories  
- Understand monthly sales trends and seasonality  
- Evaluate delivery performance and delays  
- Study the impact of delivery on customer satisfaction  

---

## Dataset
The dataset used is the **Olist Brazilian E-commerce dataset**, which includes:

- Customers  
- Orders  
- Order Items  
- Payments  
- Products  
- Reviews  

---

## Tools & Technologies
- Microsoft Excel  
- Power Query (Data Cleaning & Transformation)  
- Power Pivot (Data Modeling)  
- Pivot Tables & Charts  

---

## Data Preparation
- Removed duplicates and handled missing values  
- Converted data types (dates, numbers, text)  
- Created calculated columns:
  - Delivery Days  
  - Order Month  
  - Delivery Status (Fast, Normal, Delayed, Not Delivered)  
- Cleaned product category names for readability  

---

## Data Modeling
Relationships were created using Power Pivot:

- Customers → Orders  
- Orders → Order Items  
- Orders → Payments  
- Order Items → Products  
- Orders → Reviews  

This enabled multi-table analysis and accurate aggregation of metrics.

---

## Key Performance Indicators (KPIs)
- Total Revenue: ₹1,35,91,643  
- Total Orders: 99,441  
- Average Delivery Time: (update based on your value)  

---

## Key Insights

### 1. Revenue Trend
- Sales peak during May–August  
- Significant drop observed in September–October  

**Insight:** Business shows clear seasonality  

---

### 2. Product Category Contribution
- Top 5 categories contribute ~40% of total revenue  
- Many categories contribute less than 1%  

**Insight:** Revenue is moderately concentrated with a long-tail distribution  

---

### 3. Delivery Performance
- Fast deliveries: ~63%  
- Delayed deliveries: ~25%  
- Not delivered: ~3%  

**Insight:** A significant portion of orders are delayed, indicating operational inefficiencies  

---

### 4. Delivery vs Customer Ratings
- Fast → 4.0  
- Normal → 4.5  
- Delayed → 4.4  
- Not Delivered → 1.8  

**Insight:**  
Delivery delays do not significantly impact customer ratings, but undelivered orders drastically reduce satisfaction  

---

## Dashboard Features
- KPI cards (Revenue, Orders, Delivery Time)  
- Monthly revenue trend analysis  
- Top product category comparison  
- Delivery performance distribution  
- Delivery impact on customer ratings  

---

## Challenges
- Handling missing delivery data  
- Managing multiple related tables  
- Interpreting unexpected results  
- Cleaning non-English category names  

---

## Conclusion
This project demonstrates how Excel can be used for end-to-end data analysis. The analysis highlights key business insights, including revenue patterns, product performance, and operational inefficiencies.

A key finding is that delivery completion has a stronger impact on customer satisfaction than delivery speed.

---

## Future Improvements
- Implement the dashboard in Power BI  
- Add forecasting models  
- Perform customer segmentation  
- Include regional analysis  

---
## Project Files
Excel File: [Download Here](https://docs.google.com/spreadsheets/d/1o2hnhJAHhfdyjzHecSh83L_LjIU191FU/edit?usp=sharing&ouid=104832432565324009257&rtpof=true&sd=true)

## Dataset
Dataset used: Olist E-commerce Dataset (Kaggle)

https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce
--- 

## Author
Adarsh  
Data Analyst | Excel & Data Analytics  
