# Business Insights for Technology Hardware Company - Project Overview

## Project Goal
This Power BI project aims to provide a comprehensive view of year-over-year (YoY) company performance from multiple perspectives while offering insights into overall product and customer performance. The analysis focuses on Atliq Hardware, a technology hardware company, and employs key performance indicators (KPIs) to assess the company’s standing. The primary objectives of the analysis are to 1) drive company growth and increase net sales, 2) improve profitability, and 3) optimize the product portfolio. Based on the findings, recommendations will be provided to help achieve these goals.

Atliq Hardware has a wealth of data related to finance, sales, marketing, supply chain, and product offerings that is not being effectively utilized. This project leverages this data to uncover valuable insights that will contribute to Atliq Hardware’s overall success.

Insights and recommendations are provided for these following areas:
- **YoY Profit & Loss Statement**:
- **Sales Analysis**:
  - **Product Performance**:
  - **Customer Performance**:
- **Supply Chain Forecast Accuracy Trend**:

  An interactive Power BI dashbaord with additional insights and analysis can be found [here](https://app.powerbi.com/view?r=eyJrIjoiZTUyYWY3MjUtNzI5Ny00MmY0LThlN2YtNDgxYTljOWIwZDg4IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9).
  
  SQL queries used to answer specific business quesions requested by management for ad hoc analysis can be found [here](https://github.com/student320/Business_Insights/blob/main/Business_Insights.sql).



## Company Background
Atliq Hardwares is a technology hardware company that sells multiple categories of electronic products through channels such as retailers, distributors, and direct sales, catering to well-known companies worldwide. Atliq's business model involves both business-to-business (B2B) and business-to-consumer (B2C) sales; however, the largest portion of revenue comes from B2B transactions. The company focuses on selling in-demand products and maintaining strong customer relationships, which are crucial for its operations.

## Data Model and Entity Relationship Diagram (ERD)
The analysis is based on the following datasets:

- dim_customer: Contains information on customer details, including customer code, name, and other demographic or business attributes.
- dim_market: Provides market-related data, including regions, sub-zones, and other geographical or market segmentation details.
- dim_product: Holds details about products, such as product code, category, and other product-specific attributes.
- fact_sales_monthly: Contains monthly sales data, including sales quantities, revenue, and other relevant sales metrics.
- fact_forecast_monthly: Includes forecasted sales data for upcoming periods, with estimated quantities and revenue predictions.
- freight_cost: Data related to shipping and transportation costs incurred during product delivery.
- gross_price: Contains information on the gross price of products before any deductions or adjustments.
- manufacturing_cost: Tracks the costs associated with producing goods, including materials, labor, and overhead.
- post_invoice_deductions: Includes deductions applied after invoicing, such as discounts or returns.
- pre_invoice_deductions: Contains deductions applied before invoicing, like early payment discounts or promotional offers.

Atliq Hardware's data model can be seen below with a total row count of 1,858,329 records.  

The data model ERD can be found [here](https://lucid.app/lucidchart/5b5eb739-3350-4fd0-a3fe-c15e840668a5/view)


![image](https://github.com/user-attachments/assets/101500fb-b627-45b7-9a58-24bab7d953b7)
![image](https://github.com/user-attachments/assets/29f7704c-28eb-4ea5-aedf-df519e6a38e9)


## Executive Summary

**Overview of Insights**
Up to and including the 2021 fiscal year, the company has remained in its growth phase and has not yet reached profitability. The primary focus has been on increasing market share and building brand recognition. In 2021, the company experienced significant expansion, with net sales increasing by 207.43% year-over-year (YoY), while the gross margin percentage remained robust, with only a slight decrease of 1.65%. The following sections will provide a more in-depth analysis of additional factors impacting performance and present recommendations for the company's future strategy.

Below is a snapshot from the Power BI report dashboard of the **YoY Profit and Loss Statement** for the fiscal year of 2021.  
The full interactive dashboard is available [here](https://app.powerbi.com/view?r=eyJrIjoiZTUyYWY3MjUtNzI5Ny00MmY0LThlN2YtNDgxYTljOWIwZDg4IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9).

![image](https://github.com/user-attachments/assets/b01e9230-6eb1-480f-9dda-cc6dcc5a15cf)

**Sales Analysis**
**Customer Performance**
**Product Performance**
**Supply Chain Forecast Evaluation**

## Recommendations





