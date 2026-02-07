# Superstore-Sales-Performance-Dashboard-power-BI-
#powerbi-superstore-dashboard/README.md

**Overview**

This project is an end-to-end Business Intelligence solution built using Power BI to analyze and monitor Superstore sales performance.
It covers the complete BI workflow — from *raw data cleaning* and *transformation* to *data modeling*, *DAX calculations*, and *interactive dashboard* development.

The dashboard enables stakeholders to explore sales, profitability, customer behavior, and trends over time using dynamic visuals and filters.

**Objective**

To provide a centralized, interactive dashboard that supports **data-driven decision-making** by analyzing sales performance across products, locations, customers, and time.

**Tools & Technologies**

Power BI
Power Query (Data Cleaning & Transformation)
DAX (Measures & Calculations)
Data Modeling (Star Schema)

**Data Preparation & Cleaning**

The raw dataset was cleaned and transformed using Power Query by:

Removing extra spaces using Trim and Clean

Replacing inconsistent and invalid values

Formatting columns for consistency

Converting columns to appropriate data types

Ensuring data quality for accurate analysis

**Data Modeling**

A star schema data model was designed to improve performance and clarity:

Tables Used:
Fact Table (Sales Transactions)
Customer Dimension
Product Dimension
Location Dimension
Order Dimension
Measures Table
Primary keys were identified in each dimension table and used as foreign keys in the fact table.
Relationships were established and validated to ensure accurate filtering and aggregation across visuals.

**DAX Measures**

Custom DAX measures were created to calculate key metrics, including:

Total Sales

Total Profit

Total Quantity Sold

Total Orders

Total Customers

These measures power the KPIs and analytical visuals across the dashboard

**Dashboard Features & Visuals**

***KPI Cards displaying***

Total Sales

Total Profit

Total Quantity

Total Orders

Total Customers

**Clustered Bar Charts showing:**

Total Sales by Product Category

Top 10 Cities by Sales

Bottom 10 Cities by Sales

Trend Analysis:

Monthly sales trends using a line chart to identify patterns and seasonality

##Interactive Slicers:

Month

Shipping Mode
These allow users to dynamically explore performance across different dimensions.

**Key Insights**

Sales performance varies significantly across product categories and cities

A small number of cities contribute a large proportion of total revenue

Monthly trends reveal clear peak and low sales periods

Shipping mode influences order volume and overall sales performance

