# E-commerce Sales & Profitability Analysis

## Project Overview

This project focuses on analyzing Madhav-E Commerce Sales data using Power BI, SQL, DAX, and Power Query. An interactive E-Commerce Sales & Profitability Analysis Dashboard was developed to evaluate sales performance, profitability, customer behavior, geographic performance, and payment methods.

The dataset contains 500 orders, generating ₹437,771 in total revenue and ₹36,963 in total profit, with an overall profit margin of 8.44%.

The dashboard provides insights into:

Overall sales and profitability
State-wise revenue and profit
Customer and city performance
Category and sub-category performance
Loss-making sub-categories
Monthly profit trends
Payment-mode analysis

The main objective of the project was to transform raw e-commerce data into meaningful business insights and support data-driven decision-making.

## Business Problem

The business lacked a centralized view of sales and profitability performance. The objective was to analyze e-commerce data to identify high-performing and loss-making states, categories, sub-categories, customer segments, and monthly trends. The analysis also aimed to identify high-volume but low-profit areas and provide data-driven insights to support better business decisions.

## Tools Used
- Power BI
- SQL
- DAX
- Power Query

## Dataset

The dataset used in this project is the Madhav-E Commerce Sales dataset, sourced from Kaggle.

It contains e-commerce sales and transaction-level information, including:
Order details
Customer information
Order date
State and city
Product category and sub-category
Sales amount
Profit
Quantity
Payment mode
The dataset was cleaned and prepared using SQL and Power Query before being analyzed in Power BI.

#!/bin/bash
curl -L -o ~/Downloads/madhav-e-commerce-sales-dataset.zip\
  https://www.kaggle.com/api/v1/datasets/download/amitkumar209/madhav-e-commerce-sales-dataset
  
## Dashboard Pages

1. Sales Overview
2. Geographic Analysis
3. Customer & City Analysis
4. Profitability & Transaction Analysis
5. Low Margin & Monthly Profit Analysis

## Key KPIs

Revenue: ₹437,771
Profit: ₹36,963
Orders: 500
Quantity: 5,615
AOV: ₹875.54
Profit Margin: 8.44%

## Key Business Insights

- Maharashtra generated the highest revenue.
- Madhya Pradesh generated the highest absolute profit.
- Andhra Pradesh and Rajasthan were loss-making states.
- Several subcategories had negative profit margins.
- Electronics generated the highest category revenue.
- Clothing had a higher margin than Electronics.

## Business Recommendations

- Investigate loss-making sub-categories and review their pricing and cost structure.
- Analyse high-revenue but low-margin states to identify profitability improvement opportunities.
- Review loss-making states at the product and transaction level.
- Investigate high-volume products generating low or negative profits.
- Develop strategies to improve repeat customer activity.
- Monitor monthly profitability and investigate periods with weaker performance.

## Dashboard Screenshots

[📊 View Full Dashboard Screenshots (PDF)](./E-Commerce-Sales-Dashboard-Screenshots.pdf)
