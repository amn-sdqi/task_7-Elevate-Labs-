# task_7-Elevate-Labs-

# Sales Summary Analysis with SQLite and Python

## Overview

This project demonstrates a basic sales data analysis using:
- SQLite database (embedded with Python)
- SQL queries executed through Python's sqlite3 library
- Data visualization using matplotlib and pandas

It connects to a small database, retrieves simple sales statistics, and visualizes them through a bar chart.

## Dataset

The dataset consists of a table `orders` with the following columns:
- order_id (integer)
- order_date (date)
- amount (float, sale amount in USD)
- product_id (integer)

A mock dataset of 1000 orders was used to simulate a real-world scenario.

## Tools and Libraries

- Python 3.x
- sqlite3
- pandas
- matplotlib

No external database setup is required because SQLite is built into Python.

## How It Works

1. Connect to Database
   - Load or create a SQLite database (`sales_data.db` or `online_sales_large.db`).

2. Run SQL Queries
   - Extract basic sales metrics like:
     - Total quantity sold
     - Total revenue
     - Sales by month or product

3. Load into Pandas
   - Read the SQL query output directly into a pandas DataFrame for easier manipulation.

4. Display and Visualize
   - Print the DataFrame.
   - Plot a basic bar chart to visualize revenue trends.
