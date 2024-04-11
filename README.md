# COOKIE-SALES

### Table of Contents

-[Project Overview](#project-overview)

-[Data Sources](#data-sources)

-[Recommendations](#recommendations)


#  PROJECT OVERVIEW

This project is all about analyzing monthly cookie sales data to gain valuable insights into our performance. We're aiming to explore different aspects of sales data, not just total revenue but also quarterly sales figures. Furthermore, we want to understand which products are bringing in the most profit, giving us a full picture of our sales performance.


## DATA SOURCES

The main dataset utilized for this analysis is the "cookie sales.csv" file, which provides comprehensive details about each sale conducted on a monthly basis.


### TOOLS

- Power bi
- D.A.X

### POWER BI

- Data Transformation
- Data Modeling
- Data Preparation
- Visualization


## D.A.X

This calculated field computes the total revenue generated from cookie sales. It sums up the product of the unit price and quantity sold for each cookie transaction.

- DAX Formula:

- **Total Revenue = SUMX('Sales', 'Sales'[Unit Price] * 'Sales'[Quantity])**


### EXPLORATORY DATA ANALYSIS

During the EDA process, we investigated the sales data to address critical inquiries, including:

- Determining the profit per product in each region.
- Identifying the monthly unit sales and profits.
- Analyzing the unit sales per product.
- Calculating the quarterly cost, profit, and revenue per cookie.


### RESULT/FINDINGS

- Profit margins vary by product and region.
- Sales and profits fluctuate monthly.
- Certain products sell more than others.
- Costs, profits, and revenues per cookie vary quarterly.


## RECOMMENDATIONS

1. Use sales data for better forecasting and inventory management.
2. Promote top-selling products and optimize underperforming ones.
3. Review financial metrics quarterly for performance insights.
4. Engage customers with loyalty programs and targeted promotions.
5. Collect customer feedback for future improvements.


## LIMITATIONS

   Seasonal variations may skew sales data, affecting year-round insights.

