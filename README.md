# Ecommerce-data-analysis
Project Overview
This project involves performing an Exploratory Data Analysis (EDA) on real transaction data from a UK retailer. The goal is to gain insights from e-commerce transactions, including customer spending patterns, product purchases, and sales trends. The dataset includes various features like product details, customer information, and transaction timestamps.

Key Objectives
Data Cleaning: Handling missing values and removing negative quantities from the dataset.
Data Transformation: Converting the InvoiceDate to a datetime format and extracting useful time-based features like year, month, day, and hour.
Insights Generation:
Calculate total spending for each transaction.
Identify top customers based on their spending.
Visualizations:
Bar charts to analyze the number of orders per month, day, and hour.
Steps Undertaken
Initial Analysis:

Identified the total number of records and columns.
Displayed all column names and their descriptions.
Data Cleaning:

Detected missing values across columns.
Filtered and removed records with negative quantities.
Feature Engineering:

Created a new column Amount_Spent by multiplying Quantity and UnitPrice.
Converted InvoiceDate from string to datetime format.
Extracted Year, Month, Day, and Hour from the InvoiceDate.
Customer Insights:

Identified the top 5 customers based on total money spent.
Data Visualization:

Plotted bar charts to show the distribution of orders per month, day, and hour.
Technologies Used
Python: Pandas, Matplotlib
Data Analysis: Pandas for data cleaning and transformation
Visualization: Matplotlib for bar chart plotting
Conclusion
This project provides valuable insights into e-commerce transactions, helping businesses better understand purchasing behaviors, trends over time, and key customer segments.

