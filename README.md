# Retail Sales Analysis using Python

## Project Overview

This project analyzes retail sales data to identify sales trends, customer behavior, product performance, regional performance, profitability, discounts, and returns.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab

## Dataset

- 25,025 raw order records
- 25,000 unique orders after cleaning
- 120 products
- 2,999 unique customers
- 2,200 return records

## Data Cleaning

- Checked dataset structure and data types
- Identified and handled missing payment methods
- Removed duplicate orders using Order_ID
- Validated negative and invalid values
- Validated Sales and Profit calculations
- Calculated sales mismatch percentage

## Analysis Performed

- Sales and Profit KPIs
- Average Order Value
- Profit Margin
- Sales by Region
- Sales and Profit by Category
- Monthly Sales Trends
- Top 10 Products by Sales
- Top 10 Products by Profit
- Customer Segment Analysis
- Top 10 Customers
- Discount vs Profit
- Return Analysis
- Product Profit Margins
- Sales-Profit Correlation
- Year-over-Year Sales and Profit Analysis

## Key Insights

- West was the highest-sales region.
- Electronics was the highest-profit category.
- Smartphone 07 was the top product by sales and profit.
- Consumer customers generated the highest sales and order volume.
- Damaged Product was the most common return reason.
- Higher discount levels were associated with lower total profit.
- 2025 sales changed by -0.45% compared with 2024.
- 2025 profit changed by -1.47% compared with 2024.
- Overall return rate was 8.8%.

## Project Structure

```text
retail-sales-python-analysis/
│
├── retail_sales_analysis.ipynb
├── retail_orders_cleaned.csv
└── README.md
