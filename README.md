# Task 6: Sales Trend Analysis Using Aggregations

## Project Overview

This project focuses on analyzing monthly sales revenue and order volume using SQL with the dataset `Sales_DataSet.csv`. The analysis was conducted using SQLite to uncover sales trends over the years 2016 and 2017.

## Tools & Technologies

- SQLite  
- DB Browser for SQLite  
- SQL  

## Dataset Description

- **Order Date**: The date an order was placed (original format: MM/DD/YYYY)  
- **Sales**: The revenue generated from each transaction  
- **Order ID**: A unique identifier assigned to each order  

## Objective

To analyze monthly sales trends by applying aggregation functions such as:

- `SUM()` to calculate total monthly revenue  
- `COUNT(DISTINCT Order_ID)` to calculate total monthly order volume  

## Tasks Completed

- Reformatted date from MM/DD/YYYY to YYYY-MM-DD to ensure compatibility with SQLite date functions  
- Utilized `strftime()` to extract the year and month from the order date  
- Grouped data by year and month to compute:
  - Total sales revenue per month  
  - Number of unique orders per month  
- Filtered the results to include only data from the years 2016 and 2017  
- Sorted the output chronologically using `ORDER BY`  

## Outcome

The resulting query provides a clear view of monthly sales performance, supporting further business analysis and reporting.
