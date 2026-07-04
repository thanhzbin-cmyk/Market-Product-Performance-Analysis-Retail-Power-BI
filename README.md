# Market Product Performance Analysis/Retail/PowerBI
A Power BI dashboard analyzing global retail sales to identify top markets and product categories, supporting data-driven expansion and strategy. It covers the full pipeline: data transformation, relationship modeling, and interactive visualization in Microsoft Power BI Desktop.

## 📑 Table of Contents

**Project Overview**
- Background & Business Problem
- Project Objectives
- Dataset Overview

**Design Thinking Process**

**Project Workflow**
- Data Collection & Data Cleaning
- Data Transformation
- Data Modeling
- Visualization Development & Insights
- Business Recommendations

# Project Overview #

## 1. Background & Business Problem
**Business Context**

A global retail company operates across multiple international markets and product categories. As the business continues to expand, Senior Management needs a clear view of business performance to support market expansion and product strategy decisions.

**Senior Management wants to understand**

- How is the company's overall business performance?
- Which markets should receive further investment?
- Which product categories should be prioritized?
- Where should resources be reduced or optimized?

**The analysis focuses on**

- 7 Geographic Markets: LATAM, US, EU, APAC, EMEA, Africa, Canada
- 3 Product Categories: Technology, Furniture, Office Supplies
- 3 Business Tables: Orders, People, Returns
- Key Metrics: Revenue, Profit, Profit Margin, Orders, AOV, Return Rate, YoY Growth

## 2. 🎯Project Objective

- Analyze overall business performance using sales and profitability metrics.
- Compare market performance to identify expansion opportunities.
- Evaluate product category performance to support portfolio decisions.
- Monitor year-over-year business growth across different dimensions.
- Build an interactive multi-page dashboard for management reporting.

## 3. Dataset Overview

The project is built on the Global Superstore dataset, consisting of 1 fact table and 2 dimension tables.

- Orders (Fact Table): Stores sales transaction records.
- People (Dimension Table): Contains sales representative information by region.
- Returns (Dimension Table): Records returned orders for return analysis.

# Project Workflow #

## 1. Data Collection & Data Cleaning ##
The Global Superstore dataset was imported into Power BI and prepared using **Power Query**. Basic data validation was performed by verifying data types, reviewing missing values where necessary, checking for duplicate records, and ensuring data consistency before building the data model and dashboard.

## 2.Data Transformation ##
The dataset was transformed to improve analytical performance and support interactive reporting. This included separating the raw data into **fact and dimension tables**, creating reusable **DAX measures** for business KPIs, and building a **date hierarchy** for year-, quarter-, month-, and day-level analysis. These transformations provided a scalable foundation for data modeling and dashboard development.

## 3. Data Modeling ##
  A **Snowflake Schema** was designed to optimize reporting performance and simplify business analysis. The Fact_Orders table serves as the central fact table and is connected to multiple dimension tables, including Product, Customer, Date, Country, Region, People, Ship Mode, and Returns. This dimensional model improves query performance, reduces data redundancy, and provides a scalable foundation for interactive Power BI reporting.
<img width="1474" height="856" alt="image" src="https://github.com/user-attachments/assets/bc2dc65f-b05a-4cc0-95dc-41afc71b5ab1" />



