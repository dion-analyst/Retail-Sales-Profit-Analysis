# Retail Sales & Profit Analysis

## Project Overview

This project analyzes the Sample Superstore dataset from 2014–2017 to evaluate sales performance, profitability, customer behavior, regional performance, and operational efficiency.

Microsoft Excel was used for data preparation, while Microsoft Power BI and DAX were used to develop interactive dashboards and generate business insights to support data-driven decision-making.

## Business Problem

Retail businesses generate thousands of sales transactions across different products, customer segments, and geographic regions. While sales volume provides an overview of business performance, it does not fully explain profitability, customer behavior, regional performance, or operational efficiency.

This project analyzes historical retail sales data to identify key performance trends, evaluate profitability, and uncover opportunities for business improvement.

## Project Objectives

The analysis aimed to:

- Analyze overall sales, profit, and order performance
- Evaluate product category and product-level performance
- Identify customer and regional sales trends
- Assess operational performance through shipping methods and discount analysis
- Develop actionable business recommendations based on the findings

## Dataset

**Dataset:** Sample Superstore  
**Period:** 2014–2017  
**Data Type:** Transaction-level retail sales data

The dataset contains information related to:

- Order Date
- Sales
- Profit
- Quantity
- Discount
- Category
- Sub-Category
- Region
- State
- Segment
- Ship Mode

The dataset was obtained from a publicly available Kaggle dataset.

## Tools & Technologies

| Tool | Purpose |
|---|---|
| Microsoft Excel | Data review, preparation, and initial analysis |
| Microsoft Power BI | Data modeling, visualization, and dashboard development |
| DAX | KPI calculations and analytical measures |

## Analytical Workflow

The project followed a structured business intelligence workflow:

1. **Business Understanding** – Defined the objectives and key business questions
2. **Data Preparation** – Reviewed data quality, validated data types, and prepared the dataset
3. **Data Modeling** – Created a Calendar table, established relationships, and developed DAX measures
4. **Dashboard Development** – Built interactive Power BI dashboards for different areas of business performance
5. **Business Analysis** – Interpreted trends, patterns, and performance differences
6. **Executive Insights & Recommendations** – Translated findings into actionable business recommendations

## Dashboard

The Power BI report consists of four analytical pages:

### 1. Executive Overview

Provides a high-level view of business performance through key performance indicators, sales trends, regional performance, product categories, and customer segments.

**Key Metrics:**

- Total Sales: ~$2.30M
- Total Profit: ~$286K
- Total Customers: 793
- Total Orders: ~5K
- Average Order Value: ~$459

### 2. Product Performance Analysis

Evaluates product categories, sub-categories, sales, profit, and profitability.

**Key Findings:**

- Technology generated the highest sales and profit.
- Furniture generated strong sales but relatively lower profit.
- A small number of products contributed a significant share of total profit.
- Higher sales volume did not necessarily translate into higher profitability.

### 3. Customer & Regional Analysis

Examines customer segments and geographic performance.

**Key Findings:**

- The Consumer segment represented the largest customer segment.
- The West region achieved the highest sales and profit.
- Sales were concentrated in a relatively small number of high-performing states.
- Regional profitability varied despite differences in sales volume.

### 4. Sales Operational Analysis

Analyzes shipping methods, discounts, and operational performance.

**Key Findings:**

- Standard Class was the most frequently used shipping method.
- Higher discount levels were generally associated with lower profitability.
- Discount levels varied across product categories.
- Shipping methods showed differences in sales contribution and operational performance.

## Key Business Findings

The analysis identified several important business insights:

- Revenue exceeded **$2.30M**, generating approximately **$286K in profit**.
- **Technology** was the strongest-performing product category.
- The **Consumer segment** contributed the largest share of sales.
- The **West region** was the strongest-performing region in terms of sales and profit.
- Higher discount levels were generally associated with lower profitability.
- Strong sales performance did not always translate into strong profit margins.

## Strategic Recommendations

### 1. Prioritize High-Performing Product Categories

Increase marketing efforts and inventory investment in Technology products due to their strong sales and profitability.

### 2. Improve Furniture Profitability

Review pricing structures, supplier costs, and discount policies for Furniture products to improve profit margins without significantly affecting sales.

### 3. Expand Successful Regional Strategies

Identify the business practices contributing to the West region's success and adapt them to lower-performing regions.

### 4. Optimize Discount Policies

Establish discount guidelines that maintain customer competitiveness while minimizing unnecessary reductions in profit, particularly for lower-margin products.

### 5. Continue Data-Driven Performance Monitoring

Use interactive dashboards and KPI monitoring to identify performance trends early and support informed decision-making.

## Key Takeaways

The analysis demonstrates that strong revenue does not necessarily indicate strong profitability. Technology emerged as the strongest-performing product category, while the Consumer segment and West region were major contributors to overall business performance.

The findings also highlight the importance of managing discount strategies, improving lower-margin product performance, and continuously monitoring business KPIs through data-driven dashboards.

## Project Files

The repository contains the following project materials:

- `README.md` – Project documentation
- `Data/` – Dataset files
- `Excel/` – Excel analysis and data preparation
- `PowerBI/` – Power BI dashboard
- `Report/` – Detailed business intelligence report
- `Images/` – Dashboard screenshots

## Conclusion

This project demonstrates how Excel, Power BI, and DAX can be combined to transform transactional retail data into meaningful business insights.

The analysis goes beyond reporting sales figures by evaluating profitability, product performance, customer segments, regional trends, and operational factors. The resulting insights provide opportunities for improved pricing, discount management, regional strategy, and product performance.
