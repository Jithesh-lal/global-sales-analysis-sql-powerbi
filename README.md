# global-sales-analysis-sql-powerbi
End-to-end sales analytics project using PostgreSQL and Power BI featuring data cleaning, transformation, KPI analysis, and interactive dashboard visualisation.


# Global Sales Analysis Dashboard | PostgreSQL + Power BI

## Project Overview

This project analyses multi-country retail sales data using PostgreSQL and Power BI. The workflow includes data cleaning, transformation, KPI generation, SQL-based business analysis, and interactive dashboard creation.

The project focuses on extracting actionable business insights related to sales performance, profitability, products, store locations, and sales representatives.

---

## Tools & Technologies

* PostgreSQL
* Power BI
* SQL
* Data Cleaning & Transformation
* Data Visualisation

---

## Dataset Information

The dataset contains sales records from multiple countries:

* Canada
* China
* India
* Nigeria
* UK
* US

### Key Columns

* Transaction ID
* Date
* Country
* Product Name
* Category
* Price Per Unit
* Quantity Purchased
* Cost Price
* Discount Applied
* Payment Method
* Customer Age Group
* Customer Gender
* Store Location
* Sales Representative

---

## Project Workflow

### 1. Data Consolidation

Merged six country-wise datasets into a single master table using SQL `UNION ALL`.

### 2. Data Cleaning

Performed:

* Missing value checks
* Duplicate detection
* Data correction using `UPDATE`
* Calculated columns creation

### 3. Feature Engineering

Created:

* Total Amount
* Profit

### 4. Business Analysis

Generated insights for:

* Revenue by country
* Profitability analysis
* Top-selling products
* Best sales representatives
* Highest-performing store locations
* Overall sales KPIs

### 5. Dashboard Development

Built an interactive Power BI dashboard featuring:

* Revenue trends
* Profit analysis
* Country-wise sales
* Product performance
* Sales representative analysis
* Store location insights

---

## SQL Analysis Performed

### Data Cleaning

* Missing value checks
* Duplicate identification
* Updating null and incorrect values

### KPI Calculations

* Total Revenue
* Total Profit
* Average Sales
* Maximum & Minimum Sales

### Business Queries

* Top 5 Best-Selling Products
* Best Sales Representatives
* Highest Revenue Generating Countries
* Top Performing Store Locations

---

## Key Insights

* Identified top-performing countries by revenue and profit
* Analysed highest-selling products during the selected period
* Evaluated sales representative performance
* Compared profitability across store locations

---

## Dashboard Preview

(Add screenshots here)

---

## Files Included

* Power BI Dashboard (`.pbix`)
* SQL Queries
* Dashboard Screenshots
* README Documentation

---

## Author

Jithesh Lal
