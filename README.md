# Sales Dashboard 2026 | Power BI Project

## Project Overview

Sales Dashboard 2026 is an end-to-end Business Intelligence project developed using Power BI to analyze sales performance, customer behavior, product trends, and category-wise revenue distribution. The dashboard transforms raw transactional data into actionable business insights through interactive visualizations, KPI tracking, and dynamic filtering capabilities.

The project demonstrates the complete Power BI development lifecycle, including data cleaning, transformation, data modeling, DAX calculations, dashboard design, and business insight generation.

---

## Project Objectives

The primary objectives of this project are:

* Monitor overall sales performance.
* Track key business KPIs.
* Analyze customer purchasing behavior.
* Identify top-performing products.
* Compare sales across product categories.
* Analyze sales trends over time.
* Enable interactive business reporting.
* Support data-driven decision-making.

---

## Dataset Information

The project utilizes two datasets:

### Orders Dataset

The Orders table contains transactional sales records including:

* Order ID
* Customer ID
* Product Name
* Product Category
* Quantity
* Unit Price
* Sales Amount
* Order Date
* Country

### Customers Dataset

The Customers table contains customer-related information including:

* Customer ID
* First Name
* Last Name
* Country

---

## Data Cleaning and Transformation

Data preparation was performed using Power Query Editor within Power BI.

### Data Cleaning Activities

The following data cleaning steps were completed:

* Verified and corrected data types.
* Standardized column names.
* Removed inconsistencies from the dataset.
* Validated Customer ID records.
* Ensured data quality for reporting and analysis.

### Data Transformation Activities

The following transformations were performed:

* Merged First Name and Last Name columns using the Merge Columns feature in Power Query.
* Created a new Full Name column for improved customer identification.
* Prepared the data model for reporting and visualization.

Example:

| First Name | Last Name | Full Name   |
| ---------- | --------- | ----------- |
| John       | Smith     | John Smith  |
| Emma       | Wilson    | Emma Wilson |

---

## Data Modeling

A relationship was established between the Customers and Orders tables using Customer ID.

### Relationship Structure

Customers (1) → Orders (*)

### Benefits of Data Modeling

* Enables customer-level sales analysis.
* Supports cross-table filtering.
* Improves reporting efficiency.
* Facilitates advanced analytics and business insights.

---

## DAX Calculations

DAX was used to create business metrics and KPI calculations.

### Measures Created

#### Total Sales

Calculates total revenue generated.

#### Total Orders

Calculates the total number of orders.

#### Total Customers

Calculates the total number of unique customers.

#### Neet Score

A custom DAX column was created to support additional business analysis and scoring requirements.

---

## Dashboard Features

### KPI Cards

The dashboard contains key performance indicators that provide a quick overview of business performance.

KPIs Included:

* Total Sales
* Total Orders
* Total Customers

Current Results:

| KPI             | Value |
| --------------- | ----- |
| Total Sales     | 103K  |
| Total Orders    | 100   |
| Total Customers | 100   |

---

### Quarterly Sales Trend Analysis

**Visualization:** Line Chart

Purpose:

* Monitor sales performance over time.
* Identify growth patterns.
* Compare quarterly revenue.

Insights:

* Q1: 15K
* Q2: 24K
* Q3: 29K
* Q4: 35K

Sales performance demonstrates consistent growth throughout the year.

---

### Product Performance Analysis

**Visualization:** Horizontal Bar Chart

Purpose:

* Identify best-selling products.
* Compare revenue contribution by product.
* Support inventory and sales planning.

Top Performing Products:

* Dell XPS 15
* ThinkPad X1
* Galaxy S24
* HP Spectre x360
* iPad Air 6

---

### Product Category Analysis

**Visualization:** Donut Chart

Purpose:

* Understand category-wise revenue contribution.
* Identify high-performing business segments.

Category Sales Distribution:

| Category   | Sales |
| ---------- | ----- |
| Laptop     | 52K   |
| Smartphone | 24K   |
| Tablet     | 19K   |
| Smart Home | 4K    |
| Accessory  | 4K    |

Key Finding:

The Laptop category generated the highest revenue contribution.

---

## Interactive Dashboard Features

The dashboard includes interactive slicers and filters that allow users to explore data dynamically.

### Filters Available

#### Date Filter

Allows users to analyze sales for selected periods.

#### Country Filter

Available Countries:

* India
* United States
* Germany
* China

#### Product Category Filter

Available Categories:

* Laptop
* Smartphone
* Tablet
* Smart Home
* Accessory

---

## Key Business Insights

* Total sales revenue reached 103K.
* Laptop products contributed the highest revenue.
* Quarterly sales increased consistently throughout the year.
* Dell XPS 15 emerged as the highest-performing product.
* Smartphones and Tablets were major contributors to overall sales.
* Interactive analysis enables deeper customer and product insights.

---

## Skills Demonstrated

### Power BI

* Dashboard Development
* Interactive Reporting
* KPI Design
* Report Optimization
* Data Visualization

### Power Query

* Data Cleaning
* Data Transformation
* Column Merging
* Data Preparation
* Query Management

### Data Modeling

* Relationship Creation
* One-to-Many Relationships
* Customer-Order Data Integration
* Cross-Filtering

### DAX

* Calculated Columns
* Business Metrics
* KPI Calculations
* Data Analysis Expressions

### Business Intelligence

* Sales Analysis
* Customer Analytics
* Product Performance Analysis
* Revenue Analysis
* Business Insight Generation

### Data Visualization

* KPI Cards
* Line Charts
* Bar Charts
* Donut Charts
* Interactive Dashboards

---

## Tools and Technologies Used

| Tool             | Purpose                        |
| ---------------- | ------------------------------ |
| Power BI Desktop | Dashboard Development          |
| Power Query      | Data Cleaning & Transformation |
| DAX              | Business Calculations          |
| CSV Files        | Data Source                    |
| Data Modeling    | Relationship Management        |

---

## Project Workflow

Data Collection

↓

Data Cleaning

↓

Data Transformation

↓

Data Modeling

↓

DAX Calculations

↓

Dashboard Development

↓

Business Insights

---

## Conclusion

Sales Dashboard 2026 demonstrates the practical application of Business Intelligence concepts using Power BI. The project covers the complete analytics workflow from data preparation and modeling to visualization and insight generation. Through interactive reporting and KPI monitoring, the dashboard enables effective analysis of sales performance, customer behavior, and product trends, helping businesses make informed strategic decisions.
