# E-Commerce Sales & Profitability Dashboard

An interactive Power BI dashboard analyzing sales, profit, targets, and customer 
performance for an e-commerce retailer operating across India (FY 2018-19).

## Overview
This project transforms raw order-level data into a two-page executive dashboard, 
covering sales trends, category/sub-category profitability, target achievement, 
and top customer analysis.

Data was cleaned and aggregated using **Python (Pandas)** and **SQLite**, with 
pre-computed views exported as CSVs for Power BI modeling.

## Dashboard Pages

**1. Sales & Profitability Overview**
- KPIs: Total Sales, Total Profit, Unique Orders, Profit Margin %, Average Order Value
- Monthly sales trend (FY 2018-19)
- Sales by Category (pie chart)
- Sales by Category & Sub-Category (stacked bar)
- Top 5 States & Cities by Sales

**2. Targets, Customers & Profitability Deep-Dive**
- KPIs: Total Customers, Unique Customers, Profit Per Order, Target Achievement Rate
- Monthly Actual vs Target Sales (combo chart)
- Top 10 Customers by Sales & Profit (with conditional formatting for loss-making customers)
- Top 5 Sub-Categories by Profit Contribution
- Profit Contribution by Category & Sub-Category (treemap)

## Tech Stack
- **Python** (Pandas) — data cleaning & transformation
- **SQLite** — aggregation views (SQL)
- **Power BI** — dashboard & data visualization

## Data Source
Synthetic e-commerce order dataset (List of Orders, Order Details, Sales Target) 
covering April 2018 – March 2019.
