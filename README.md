# ecommerce-customer-segmentation
End-to-end customer segmentation project using MySQL, Python, and Power BI
> End-to-End Customer Segmentation Project

>Project Status: 🚧 In Progress 🚧

This repository tracks the step-by-step development of a full-stack data science project: building an automated customer segmentation pipeline using MySQL, Python, and Power BI.


 🎯 Business Problem

The goal of this project is to help a (simulated) e-commerce marketing team move from "one-size-fits-all" marketing to highly targeted, data-driven campaigns. To do this, they need to know:
* Who are our most valuable "Champion" customers?
* Who are our "At-Risk" customers we might lose?
* What are the purchasing behaviors of different customer segments?

> My Project Plan

This project is being built in three distinct phases:

1. The Database (MySQL) - ✅ Complete!

> Goal: Build a professional-grade, relational database to store and manage all raw e-commerce data.
> Status: I have successfully designed and deployed a database in MySQL. I have created the table schemas ('customers', 'order', 'order_items', `order_payments') and am in the process of loading over 100,000 rows of transaction data from the Olist CSV files.

 2. The AI Model (Python) - ⏳ Next Step

> Goal: Connect to the live database, analyze the data, and build a machine learning model to segment customers.
> Actions Planned:
    * Connect to the MySQL DB using Python (with SQLAlchemy).
    * Perform RFM (Recency, Frequency, Monetary) analysis.
    * Train a K-Means clustering model to create distinct customer segments.
    * Write these new segments back into a 'customer_segment' table in the database.

3. The Dashboard (Power BI) - 📋 Planned

> Goal: Visualize the insights for a non-technical manager.
> Planned Actions:
    * Connect Power BI directly to the live MySQL database.
    * Build an interactive executive dashboard.
    * The dashboard will allow filtering all sales, products, and revenue by the new AI-generated customer segments.



>> 🔧 Tech Stack (So Far)

> Database: MySQL
> Database Management: MySQL Workbench
> Version Control: Git & GitHub
> (Planned): Python (Pandas, scikit-learn), Power BI

