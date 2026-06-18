For GitHub, the README should be concise, professional, recruiter-friendly, and focused on business impact. It should not read like a college report.

# sales-analytics-customer-performance-excel  

## Overview

This project presents an end-to-end Sales Analytics and Customer Performance Reporting solution developed using Microsoft Excel, Power Query, Power Pivot, and Data Modeling techniques. The objective was to transform raw sales transactions into actionable business insights through a structured Business Intelligence workflow.

The solution enables stakeholders to analyze sales performance across customers, products, divisions, and markets while supporting data-driven decision-making through interactive analytical reports.

---

## Business Problem

AtliQ Hardware operates across multiple international markets and serves a diverse customer base. As transaction volumes increased, the organization required a centralized reporting system capable of:

* Monitoring sales performance across multiple years.
* Identifying top-performing customers and products.
* Evaluating market-wise and division-wise growth.
* Supporting strategic business decisions through data-driven insights.
* Providing scalable and efficient reporting using a dimensional data model.

---

## Project Objectives

* Build a scalable sales analytics solution using Excel.
* Perform ETL operations to clean and transform raw data.
* Design a Star Schema data model for efficient reporting.
* Analyze customer, product, market, and division performance.
* Generate business insights and recommendations from sales data.
* Develop professional management reports for decision-making.

---

## Dataset Overview

The project utilizes transactional sales data along with supporting dimension tables.

### Data Volume

| Table              | Records |
| ------------------ | ------: |
| Fact Sales Monthly | 799,962 |
| Dim Customer       |     189 |
| Dim Product        |     298 |
| Dim Market         |      23 |
| Dim Date           |   1,066 |

---

## Tools & Technologies

* Microsoft Excel
* Power Query
* Power Pivot
* Data Modeling
* Pivot Tables
* DAX Measures
* Conditional Formatting

---

## ETL Process

### Extract

Imported raw sales and master data into Power Query.

### Transform

Performed data cleaning and transformation activities including:

* Removal of missing values
* Data validation and standardization
* Column formatting
* Data quality checks
* Creation of a dedicated Date Dimension table

### Load

Loaded transformed tables into the Excel Data Model for reporting and analysis.

---

## Data Model

A Star Schema architecture was implemented to improve analytical performance and scalability.

### Fact Table

* fact_sales_monthly

### Dimension Tables

* dim_customer
* dim_product
* dim_market
* dim_date

The model enables flexible slicing and filtering across multiple business dimensions while maintaining efficient report performance.

---

## Reports Developed

### Customer Performance Report

Analyzed customer-level sales performance across multiple years and measured year-over-year growth.

**Key Metrics**

* Net Sales 2019
* Net Sales 2020
* Net Sales 2021
* Growth Percentage

---

### Division Performance Report

Evaluated revenue contribution and growth across business divisions.

**Key Insights**

* PC Division recorded the highest growth rate.
* P & A Division generated the highest revenue contribution.
* N & S Division demonstrated stable growth.

---

### Market Performance Report

Analyzed sales trends across global markets.

**Focus Areas**

* Revenue contribution by market
* Growth comparison across regions
* Identification of high-performing markets

---

### India Market Performance Report

Performed detailed customer-level analysis within the Indian market.

**Focus Areas**

* Top revenue-generating customers
* Customer growth analysis
* Market-specific performance evaluation

---

### Top Products Analysis

Identified products with the strongest revenue growth and business impact.

**Focus Areas**

* Product performance ranking
* Growth percentage analysis
* Revenue contribution analysis

---

## Key Business Insights

### Revenue Growth

Total company sales increased significantly from 2020 to 2021, demonstrating strong business expansion and market penetration.

### Customer Performance

Amazon, AtliQ Exclusive, and AtliQ e Store emerged as the highest revenue-generating customers.

### Market Leadership

India was identified as the largest market by revenue contribution, followed by the USA and South Korea.

### Product Growth

Several products experienced exceptional year-over-year growth, indicating strong market demand and successful product positioning.

### Division Analysis

The PC division demonstrated the strongest growth trajectory among all business divisions.

---

## Business Recommendations

* Increase strategic investment in high-performing markets such as India and the USA.
* Strengthen relationships with key customers contributing significant revenue.
* Expand marketing and inventory allocation for high-growth products.
* Replicate successful strategies from top-performing markets across emerging regions.
* Continue leveraging dimensional reporting for operational and strategic decision-making.

---

## Project Outcomes

* Built a complete sales analytics solution using Excel.
* Processed and modeled nearly 800,000 sales records.
* Implemented a Star Schema architecture using Power Pivot.
* Developed multiple business-focused analytical reports.
* Generated actionable insights across customers, products, divisions, and markets.
* Demonstrated practical Business Intelligence and Data Analytics skills in a real-world business scenario.

---

## Skills Demonstrated

* Data Cleaning
* ETL Development
* Power Query
* Power Pivot
* Data Modeling
* Star Schema Design
* Business Intelligence
* Sales Analytics
* Customer Analytics
* KPI Reporting
* Data Visualization
* Business Reporting
* Microsoft Excel

---

## Repository Structure

```text
sales-analytics-excel-project/
│
├── README.md
├── Sales_Analytics_Report.pdf
├── Excel_Workbook/
│   └── Sales_Analytics.xlsx
│
├── Reports/
│   ├── Customer_Performance_Report.pdf
│   ├── Division_Performance_Report.pdf
│   ├── Market_Performance_Report.pdf
│   ├── India_Market_Report.pdf
│   └── Top_Products_Report.pdf
│
└── Images/
    ├── Data_Model.png
    ├── Customer_Performance.png
    ├── Market_Performance.png
    ├── Division_Report.png
    └── Top_Products.png
```

## Conclusion

This project demonstrates the complete lifecycle of a Business Intelligence solution—from data extraction and transformation to dimensional modeling, performance analysis, and business reporting. By leveraging Excel's advanced analytics capabilities, the solution provides meaningful insights that support strategic decision-making and organizational growth.

A small improvement: rename the repository to **sales-analytics-customer-performance-excel** or **excel-sales-analytics-bi-project**. Those names look much stronger to recruiters than "Sales Analytics Practice".

