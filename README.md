# Credit Card Financial Report - Power BI Dashboard

## Overview

This project presents an interactive Power BI dashboard designed to analyze credit card financial data. Utilizing transaction and customer data from a SQL database, the dashboard provides real-time insights into key performance metrics and trends, enabling data-driven decision-making.

## Features

-   **Real-time Insights:** Interactive dashboard for monitoring transaction and customer data.
-   **Key Performance Metrics:** Tracking revenue, transaction amounts, counts, interest, activation rates, and delinquency rates.
-   **Trend Analysis:** Visualizing week-over-week (WoW) and year-to-date (YTD) trends.
-   **Customer Segmentation:** Analyzing revenue contributions by gender.
-   **Card Type Analysis:** Identifying the contribution of different credit card types to overall transactions.
-   **Geographic Analysis:** Visualizing revenue contributions by state.
-   **Actionable Insights:** Sharing findings with stakeholders to support strategic decision-making.

## Project Insights

**Week 53 (31st Dec) WoW Change:**

-   Revenue increased by 28.8%.
-   Total Transaction Amount increased by 25.9%.
-   Total Transaction Count increased by 3.2%.

**Year-to-Date (YTD) Overview:**

-   Overall Revenue: $57M
-   Total Interest: $8M
-   Total Transaction Amount: $46M
-   Revenue Contribution by Gender:
    -   Male: $31M
    -   Female: $26M
-   Credit Card Type Contribution:
    -   Blue & Silver: 93% of overall transactions.
-   Geographic Contribution:
    -   TX, NY, CA: 68% of overall transactions.
-   Overall Activation Rate: 57.5%
-   Overall Delinquent Rate: 6.06%

## Project Steps

**Step 1: Import Data to PostgreSQL Database**

-   Prepare CSV data files.
-   Create tables in PostgreSQL.
-   Import CSV data into PostgreSQL tables.

**Step 2: Creation of Dashboard using Power BI Desktop**

-   Load dataset into Power BI Desktop using "Get Data" from PostgreSQL.
-   Perform data cleaning and apply data transformations using Power Query Editor.
-   Create measures using DAX functions for complex calculations.
-   Design and create visualizations in the report based on business rules.

## Dependencies

-   Power BI Desktop
-   PostgreSQL Database
-   CSV data files

## Usage

1.  **Data Acquisition:** Ensure the PostgreSQL database is populated with the required credit card transaction and customer data.
2.  **Power BI Setup:** Open the provided PBIX file in Power BI Desktop or connect your own Power BI report to the PostgreSQL database.
3.  **Interactive Exploration:** Use the dashboard's interactive features, such as slicers and filters, to explore the data and gain insights.
4.  **Analysis:** Analyze the visualizations to understand trends and patterns in credit card financial data.
5.  **Reporting:** Share the insights and findings with stakeholders to support decision-making.

# Credit Card Customer Report
![Cust](https://github.com/user-attachments/assets/9cff2626-f48a-4b74-9f86-13f17ba10a1e)

# Credit Card Transaction Report
![cust2](https://github.com/user-attachments/assets/ee5dfa64-3869-45b3-8119-9758b7c15b82)




  
