# E-Commerce Sales Analysis Dashboard - README

This repository contains the **FUTURE_DS_01.pbix** file, a comprehensive Power BI dashboard developed as part of the **Data Science & Analytics Internship** at **Future Interns**. The project focuses on transforming raw transactional data into actionable business insights for an online retail environment.

## Project Overview
The primary objective of this dashboard is to analyze e-commerce sales performance to help business stakeholders understand purchasing patterns, identify high-value regions, and optimize inventory management.

## Data Source
The analysis is based on the **E-commerce Data** dataset from Kaggle, which contains over 500,000 transactions from a UK-based non-store online retailer. 
* **Key Attributes**: Invoice Number, Stock Code, Description, Quantity, Invoice Date, Unit Price, Customer ID, and Country.

## Key Features & Visualizations
The dashboard provides a multi-dimensional view of business health through the following visuals:
* **Executive KPIs**: High-level cards displaying **Total Revenue**, **Total Quantity Sold**, **Distinct Order Count**, and **Total Unique Customers**.
* **Sales Trends**: A time-series line chart illustrating monthly and daily sales fluctuations to identify peak periods.
* **Geographic Distribution**: A map visual highlighting sales performance across different countries, pinpointing the most profitable regions.
* **Product Analysis**: A bar chart showcasing the **Top 10 Best-Selling Products** by revenue and quantity to inform stock replenishment.
* **Category Performance**: Insights into which product categories drive the highest margins.

## DAX Measures & Data Transformation
To ensure data accuracy and depth, the following techniques were applied:
* **Data Cleaning**: Utilized **Power Query** to handle missing Customer IDs, remove negative quantities (returns), and format date fields for time-intelligence functions.
* **Calculated Columns**: Created a `Total Sales` column by multiplying `Quantity` and `Unit Price`.
* **Measures**: Developed DAX measures for Year-over-Year (YoY) growth, Average Order Value (AOV), and cumulative sales.

## Tools Used
* **Power BI Desktop**: For data modeling, DAX implementation, and report authoring.
* **Power Query**: For ETL (Extract, Transform, Load) processes.
* **Kaggle Dataset**: As the primary source of transactional data.

## How to Use
1.  Download and install [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
2.  Open the `FUTURE_DS_01.pbix` file.
3.  Use the **Slicers** (Date Range, Country, Category) on the left or top panel to filter the entire report dynamically.
4.  Hover over data points to view detailed **Tooltips**.
