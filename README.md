# Madhav Ecommerce Sales Analysis

This project analyzes an online ecommerce store operating across India. It explores sales performance, customer purchasing patterns, order trends, and category-wise profitability using two datasets:

- Orders.csv: order metadata such as order ID, order date, customer name, state, and city
- Details.csv: transaction-level details such as amount, profit, quantity, category, sub-category, and payment mode

The analysis is presented through a Power BI dashboard and is designed to help understand business performance across regions and product categories.

## Project Overview

The dataset contains information about customer orders, product categories, payment preferences, and sales generated across multiple Indian cities and states. The project focuses on identifying:

- sales contribution by state
- customer purchasing behavior
- average monthly profit
- quantity contribution by category
- payment mode trends

## Repository Structure

```text
Madhav-Ecommerce-Sales-/
├── Orders.csv
├── Details.csv
├── Madhav_PowerBI.pbix
├── Madhav Store Dashboard.png
├── README.md
└── .gitignore (if present in your repo)
```

## Dataset Description

### Orders.csv
Contains customer and order metadata.

Columns include:
- Order ID
- Order Date
- CustomerName
- State
- City

### Details.csv
Contains transaction-level product and sales data.

Columns include:
- Order ID
- Amount
- Profit
- Quantity
- Category
- Sub-Category
- PaymentMode

## Business Questions Answered

This project helps answer questions such as:

- Which states contribute the most sales?
- Which customers made the highest purchases?
- What is the average profit by month?
- Which product categories have the highest quantity sold?
- Which payment methods are most widely used?

## Dashboard

A Power BI dashboard is included in the repository:

- Madhav_PowerBI.pbix
- Madhav Store Dashboard.png

The dashboard summarizes sales trends and highlights key business insights visually.

## Tools Used

- Microsoft Power BI
- CSV datasets
- Excel / data exploration workflows

## How to Use

1. Open the CSV files in Excel or Power BI.
2. Load Orders.csv and Details.csv into Power BI.
3. Establish a relationship between Order ID in both datasets.
4. Use the provided dashboard or build additional visuals to explore metrics.
5. Use the project to analyze sales patterns, category performance, and regional trends.

## Key Insights

Some of the main analysis points in the project include:

- sum of amount by state
- customer purchase amounts
- average profit by month
- quantity sold by category

## Author

This project was developed as a sales analytics and dashboarding exercise for ecommerce data across India.

## License

This repository does not currently include a license file. If you plan to share or reuse this project publicly, consider adding a license.
