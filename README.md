GlobalMart Sales Analysis

Data Centralization (ETL), Power BI Report, Visualizations & SQL Queries

Stack

    

Executive Summary:

Link to live Power BI Dashboard (Add the actual link here)

Using Power BI and SQL, I developed an end-to-end Business Intelligence solution that centralizes sales data from multiple sources into an interactive dashboard. The report enables stakeholders to monitor sales performance across different regions, analyze store operations, and track product profitability. Additionally, SQL queries were implemented to extract insights directly from the database for ad hoc analysis.

Key Achievements:

Built an interactive Power BI report from raw sales data.

Extracted, transformed, and loaded (ETL) data from multiple sources.

Designed a star-schema data model for efficient querying.

Created SQL queries to retrieve key business insights.

Automated data retrieval for external analysis.

Note: The data used in this project is fictional and for learning purposes.

Business Problem:

GlobalMart, a multinational retailer with stores across the United Kingdom, Germany, and the US, faced challenges in tracking sales across different locations. Their data was scattered across various sources, making it difficult to analyze trends, monitor revenue, and improve decision-making.

Project Goals:

Centralize sales data into a structured format for easy analysis.

Develop an interactive Power BI report for real-time business intelligence.

Create SQL queries to answer specific business questions efficiently.

Solution & Implementation:

1. Data Centralization & ETL in Power BI

Data was sourced from multiple platforms, including Azure SQL Database and CSV files. Using Power Query, the data was cleaned, transformed, and structured into a star schema for optimized performance.

ETL Pipeline:

 (Add the actual ETL diagram here)

Star Schema Data Model:

 (Add a screenshot of your data model here)

The schema consists of:

Fact Table: orders

Dimension Tables: dim_stores, dim_products, dim_users, dim_date

2. Power BI Report

The Power BI dashboard includes four pages, providing insights into sales performance, customer behavior, product trends, and store operations.

Report Pages:

Executive Summary – High-level overview of key metrics.

Customer Insights – Analysis of customer demographics and purchasing trends.

Product Performance – Sales and profitability by product category.

Store Operations – Sales breakdown by location and store type.

3. SQL Queries & Business Insights

Custom SQL queries were written to extract insights from the PostgreSQL database. 

Project Deliverables

✅ Power BI Dashboard with key business insights.

✅ SQL Queries for ad-hoc business questions.

✅ ETL Process for data transformation.

✅ Star Schema Data Model for optimized performance.

How to Use the Project

Clone this repository:

git clone https://github.com/MaryAbioye/data-analytics-power-bi-report116.git

Open the Power BI report (.pbix file) to explore insights.

Run SQL queries in PostgreSQL to extract business insights.

Modify and extend queries to analyze other data aspects.

License & Acknowledgments

This is an open-source project for learning purposes. All data used is fictional.

Author: Mary Abioye



