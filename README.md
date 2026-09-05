# Amazon-Sales-Performance-Analysis

Amazon Sales Performance Analysis using Excel with data cleaning, PivotTables, KPIs, interactive slicers, and dashboard visualizations.

## Project Overview

This project analyzes one month of Amazon e-commerce order-level data using Microsoft Excel. The objective is to transform raw sales data into meaningful business insights through data cleaning, preprocessing, PivotTables, KPIs, interactive slicers, and dashboard visualizations.

## Business Questions

- Which products generate the highest total sales?
- Which categories perform best?
- Which customer locations show strong or weak sales performance?
- Which payment methods are most popular?
- What percentage of orders are delivered, cancelled, and pending?

## Dataset

The dataset contains 250 order records and 11 columns, including:
- Order ID
- Date
- Product
- Category
- Price
- Quantity
- Total Sales
- Customer Name
- Customer Location
- Payment Method
- Status

  ## Data Cleaning & Preprocessing

The raw dataset was checked and prepared in Microsoft Excel before analysis.

### Data Cleaning

- Checked for duplicate Order IDs using Excel's Remove Duplicates feature. No duplicate Order IDs were found.
- Checked all 11 columns for missing values. No missing values were found.
- Verified that the Date column contains valid Excel dates.
- Verified that Price, Quantity, and Total Sales are numeric values.
- Checked text fields using TRIM and PROPER functions.
- Checked category and customer location values for consistency.
- Validated Total Sales against Price × Quantity for all 250 records. The validation returned 0 mismatches.

### Data Preprocessing

- Created a Month field using the Date column.
- Created a Day of Week field using the Date column.
- Created an Order Status Flag to group the original Completed status as Delivered, along with Cancelled and Pending statuses.

## PivotTable Analysis

PivotTables were created in Excel to analyze sales performance from different business perspectives.
The analysis includes:
- Category-wise Total Sales
- Product-wise Total Sales
- City-wise Total Sales
- Payment Method Usage
- Order Status Distribution
- Top Customers by Total Spending

## Dashboard & KPIs

An interactive Excel dashboard was created to provide a clear overview of Amazon sales performance.

### Key Performance Indicators

- Total Sales: ₹243,845
- Total Orders: 250
- Average Order Value: ₹975.38
- Delivered Orders: 88
- Cancelled Orders: 77

### Dashboard Visualizations

- Total Sales by Category
- Total Sales by Product
- Sales by Customer Location
- Order Status Breakdown
- Payment Method Distribution

### Interactive Filters

The dashboard includes slicers for:
- Category
- Customer Location
- Order Status
- Month

## Key Insights & Findings

- Electronics was the top-performing category with total sales of ₹129,950.
- Refrigerator was the highest-performing product with total sales of ₹78,000.
- Miami recorded the highest sales among customer locations with ₹31,700, while San Francisco recorded the lowest with ₹16,195.
- PayPal was the most-used payment method with 60 orders, representing 24% of total orders.
- Out of 250 orders, 88 were delivered (35.2%), 77 were cancelled (30.8%), and 85 were pending (34.0%).

## Tools & Skills

- Microsoft Excel
- Data Cleaning
- Data Preprocessing
- Excel Formulas
- PivotTables
- KPI Analysis
- Interactive Slicers
- Data Visualization
- Business Insights

## Project Files

- `amazon_sales_data 2025.csv` — Original raw dataset
- `Amazon_Sales_Cleaned.xlsx` — Cleaned dataset, PivotTables, and interactive Excel dashboard
- `README.md` — Project documentation

## Project Workflow

1. Loaded and understood the raw Amazon sales dataset.
2. Checked and cleaned the data for duplicates, missing values, formatting, and consistency.
3. Created calculated fields for Month, Day of Week, and Order Status Flag.
4. Created PivotTables for category, product, location, payment method, order status, and customer analysis.
5. Created KPI cards for Total Sales, Total Orders, Average Order Value, Delivered Orders, and Cancelled Orders.
6. Built an interactive Excel dashboard using charts and slicers.
7. Derived business insights and recommendations from the analysis.
