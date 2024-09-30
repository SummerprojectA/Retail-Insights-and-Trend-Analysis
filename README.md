# Retail Sales Data Analysis

This project involves analyzing Walmart's sales data to answer key business questions regarding sales performance, revenue trends, and product line analysis. The dataset includes information on branches, cities, product lines, payment methods, and customer details. The analysis is conducted using Python (Pandas) with a focus on Exploratory Data Analysis (EDA) to provide data-driven insights.

## Problem Statements
1. **Performance of Sales and Revenue at the City and Branch Level**
    - Investigate the sales trends across different cities and branches.
    - Provide insights on which cities and branches are generating the most revenue.

2. **Average Price of Items Sold at Each Branch**
    - Calculate and compare the average selling price of products across branches within cities.

3. **Month-over-Month Performance Analysis of Sales and Revenue**
    - Evaluate the sales performance month-over-month across different product lines, gender, and payment methods.
    - Identify focus areas to improve sales for April 2019.

## Exploratory Data Analysis (EDA)
- **Data Cleaning**: Handled missing values, transformed date and time columns, and ensured proper data types.
- **Data Visualization**: Used Matplotlib and Seaborn to visualize key metrics like sales trends, average pricing, and product performance.
- **Statistical Summary**: Generated descriptive statistics to summarize the distribution of sales, quantity, and unit prices.
- **Correlation Analysis**: Performed correlation analysis between different product lines, payment methods, and customer demographics.

## Key Insights
- **City & Branch Level Analysis**: Identified top-performing cities and branches based on sales and revenue generation.
- **Price Insights**: Provided branch-wise insights on the average price of items sold.
- **Product Line & Customer Demographics**: Analyzed sales performance across product lines, segmented by gender and payment methods.
- **Focus Areas for Improvement**: Highlighted areas where sales performance can be improved, particularly in April 2019.

## Tools and Technologies Used
- **Python**: Data analysis using Pandas for data manipulation and exploratory analysis.
- **Jupyter Notebook**: Interactive environment for coding and visualizing data.
- **Matplotlib & Seaborn**: Libraries used for generating visualizations to represent sales trends, pricing, and customer behavior.

## Dataset
The Walmart sales dataset contains the following fields:
- **Invoice ID**: Unique identifier for each transaction.
- **Branch**: Identifier for the branch where the sale occurred.
- **City**: The city where the branch is located.
- **Customer Type**: Whether the customer is a member or a regular customer.
- **Gender**: The gender of the customer.
- **Product Line**: The product category the item belongs to.
- **Unit Price**: Price of a single item.
- **Quantity**: Number of units sold.
- **Date**: The date of the transaction.
- **Time**: The time of the transaction.
- **Payment Method**: The payment method used (Cash, Credit card, or E-wallet).
- **Rating**: Customer rating of the purchase experience.
