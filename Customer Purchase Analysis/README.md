# Customer Purchase Analysis for E-commerce Business

This project analyzes customer purchase data for an e-commerce business using Python and pandas. The analysis provides insights into customer behavior, product popularity, and revenue trends.

## Dataset

The dataset contains the following columns:
- **customer_id**: Unique identifier for each customer
- **product_id**: Unique identifier for each product
- **purchase_date**: Date of the purchase
- **quantity**: Number of items purchased
- **price**: Price per item

## Analysis

The analysis includes the following insights:
1. **Total Spent per Customer**: Calculates the total amount spent by each customer.
2. **Total Revenue per Customer**: Identifies the customers who generate the most revenue.
3. **Product Popularity**: Determines the most popular products based on quantity sold.
4. **Top Customers by Quantity**: Identifies customers who purchase the most items.
5. **Monthly Revenue Trends**: Analyzes revenue trends on a monthly basis.

## Key Findings

- **Customer 101** has the highest total spent at **$310**.
- Products **P123** and **P345** are the most popular, with **3 units sold each**.
- **Customer 101** purchased the most items (**5 units**).
- **January 2024** had the highest total revenue at **$340**.

## Usage

To run the analysis:
1. Ensure you have Python and pandas installed.
2. Execute the provided Jupyter Notebook or Python script.
3. The script will generate an Excel file named `sales_data.xlsx` with the raw data.
4. Various DataFrames will be created to present different aspects of the analysis.

## Requirements

- Python 3.x
- pandas library

Install the required library with:
```bash
pip install pandas
