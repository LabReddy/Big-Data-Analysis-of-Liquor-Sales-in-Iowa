# Big-Data-Analysis-of-Liquor-Sales-in-Iowa

This repository contains the analysis project for the "Big Data - BUAN 6346" course. The objective of this project is to identify actionable business insights through the analysis of liquor sales data from Iowa, utilizing Hadoop, PySpark, and Hive for data processing and Tableau for visualizations.

Project Overview
This analysis aims to derive meaningful business insights by exploring liquor sales data, specifically focusing on Iowa Class "E" liquor licenses from January 2021 to January 2022. The project leverages big data tools and technologies to handle datasets exceeding 1GB, aiming to uncover patterns and correlations that could aid strategic business decisions.

Dataset Description
The dataset, named Liquor_sales, was sourced from Kaggle and consists of approximately 3 million records spread across 24 columns detailing liquor purchases. This comprehensive data includes transactional details like store and product specifics, financials, and geographic locations.

Key Columns
invoice_and_item_number: Unique identifier for transactions
date: Date of order
store_number and store_name: Information about the store ordering the liquor
category_name, item_description: Details of the liquor ordered
state_bottle_cost, state_bottle_retail: Pricing information
bottles_sold, sale_dollars: Sales data
volume_sold_liters, volume_sold_gallons: Liquor volume data
Tools Used
Data Loading: Flume or Sqoop for importing data into Hadoop.
Data Processing and Analysis: Apache Hadoop and Apache Spark.
Visualization: Tableau for creating dynamic visualizations to illustrate findings.
Business Questions
Stores and Categories Performance: How do store order volumes and product sales volumes correlate with total dollar sales at both store and product levels?
Pricing Strategy: How does pricing affect the volume and profitability of liquor sales? What are the optimal price points for various categories to enhance revenue?
Vendor and Category Profitability: Which vendors and product categories contribute most to profitability, and how can this information improve vendor negotiations and inventory decisions?
