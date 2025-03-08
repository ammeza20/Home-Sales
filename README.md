# Home-Sales
Home Sales Analysis

Overview

This project utilizes Apache Spark and PySpark SQL to analyze home sales data. The dataset is read from a CSV file, transformed using SQL queries, and optimized using caching and Parquet file storage.

Technologies Used

Python

PySpark (Apache Spark)

SQL Queries

Parquet File Format

Jupyter Notebook

Key Tasks

1. Load and Prepare the Data

Initialize Spark session

Read the dataset from a CSV file

Create a temporary SQL table

2. Perform SQL Analysis

Compute average home prices based on bedroom count and view ratings

Filter homes by size, number of floors, and square footage

Determine the most expensive home sold per year

3. Optimize Performance

Cache the dataset for faster querying

Partition the data by date_built and save in Parquet format

Compare query performance using cached vs. non-cached data

Instructions

1. Install Dependencies

Ensure PySpark and required dependencies are installed:

pip install pyspark findspark

2. Run the Notebook

Execute each cell in the Jupyter Notebook sequentially.

3. Verify Outputs

Run SQL queries to analyze home sales.

Use .show() to display results in DataFrame format.

Compare execution times of cached vs. non-cached queries.

File Structure

Home_Sales_starter_code.ipynb: Main Jupyter Notebook with all code

home_sales_revised.csv: Dataset (loaded from AWS S3)

home_sales_partitioned/: Output directory for partitioned Parquet data

Notes

Ensure the dataset is available before running the notebook.

Change the output path for Parquet files if needed.

Contact

For any questions or improvements, feel free to reach out!

