# Retail Sales Snowflake Warehouse Connected to Power BI

## Project Overview
This project demonstrates an end-to-end retail sales analytics solution using Snowflake as a cloud data warehouse and Power BI for visualization.

The goal is to transform structured retail data into actionable insights through interactive dashboards.

---

Video Preview:
https://drive.google.com/file/d/1sHhhVdNdje1cgvVQM7OCWQWAEKWQpmVw/view?usp=sharing

---

## Business Objectives
- Monitor sales and profitability
- Identify top-performing products and regions
- Analyze customer behavior and value
- Track operational metrics like returns and discounts
- Support data-driven decision-making

---

## Data Architecture

Warehouse: Snowflake  
Schema Type: Star Schema  

Tables:
- Customer Dimension
- Product Dimension
- Store Dimension
- Employee Dimension
- Date Dimension
- Sales Fact Table

---

## Dashboard Overview

### Page 1: Executive Overview

This page highlights overall business performance.

KPIs:
- Total Sales: 1.42M
- Total Profit: 424.55K
- Profit Margin: 29.94%
- Total Orders: 2K
- Avg Order Value: 1K
- Customer Count: 489

Key Visuals:
- Monthly Sales & Profit Margin Trend
- Sales by State
- Sales by Subcategory
- Product-wise Sales and Profit

Key Insights:
- Strong overall profitability with ~30% margin
- Mid-range and premium products drive most revenue
- Major sales concentration in top cities
- Certain products show declining profitability

---

### Page 2: Details Analytics

This page focuses on deeper analysis.

KPIs:
- Customer Count
- Return %
- Sales & Profit Metrics

Key Visuals:
- Customer Lifetime Value (Top 10)
- Profit vs Discount Scatter Plot
- Sales by Channel
- Product-wise Return %

Key Insights:
- High-value customers contribute a large share of revenue
- Discounts negatively impact profitability
- Business heavily relies on online sales channel
- Return rates require further investigation

---

## Features
- Interactive slicers (City, Segment, Metric selection)
- Drill-down capability
- Dynamic KPI tracking
- Advanced visualizations (scatter, combo charts)

---

## Tools & Technologies
- Snowflake (Cloud Data Warehouse)
- SQL (Data Modeling)
- Power BI (Dashboarding & Visualization)

---

## How to Use

1. Create Snowflake database and tables
2. Load dataset using SQL scripts
3. Open Power BI file (.pbix)
4. Connect to Snowflake
5. Refresh data to view dashboards

---


## Conclusion

This project showcases how modern data tools like Snowflake and Power BI can be combined to build scalable analytics solutions and generate meaningful business insights.

---

## Author
Shakaut Hassain
Data Analyst (2 Years+ Experience)
