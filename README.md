# Project Report

##### Tools: SQL

##### Type: Data Cleaning, Exploratory Data Analysis

## Table of Contents
1. [Home](#Project-Report)
2. [Background](#Background)
3. [Executive Summary](#Executive-Summary)
4. [Data Source](#Data-Source)
5. [Analysis](#Analysis:-Insight-Deep-Dive)
6. [Recommendations](#Recommendations)
7. [Clarifying Questions, Assumptions, and Caveats](#Clarifying-Questions,-Assumptions,-and-Caveats)

## Background

This report presents an exploratory data analysis of a coffee shop’s sales data specifically focusing on the month March. The primary objective is to analyze revenue trends, transaction patterns, and product performance. This study aims to provide an initial understanding of sales performance before deeper analytical insights and a dashboard are developed.


## Executive Summary
- Total revenue for March: $98.83k
- Month-over-month sales change: 
  - February-March: 29.8% increase
  - March-April: [placeholder]
- Total number of transactions in March: [Placeholder for value]
  - February-March: [placeholder]
  - March-April: [placeholder]
- Highest and Lowest average sales days: 
  - Lowest: [Placeholder]
  - Highest: [Placeholder]
- Top-selling product category: Barista Espresso
- Peak sales hour: An average of: 11.3k sales occur each hour between 7am to 10am

## Data Source
The dataset used for this analysis contains 149,116 transaction records spanning from January to June 2023. Each transaction consists of:
- transaction_id: Unique identifier for each transaction
- transaction_date: Date of transaction
- transaction_time: Time of transaction
- transaction_qty: Quantity of items purchased
- store_id: Unique identifier for store
- store_location: Store location
- product_id: Unique identifier for product
- unit_price: Price per unit of product
- product_category: Category of the product
- product_type: Type of product
- product_detail: Specific details about the product

#### Data cleaning and processing were performed using MySQL:

- converting string-based date values into proper datetime formats
- checking for duplicates, missing, or inconsistent entries.

## Analysis: Insight Deep-Dive

### 1. Total Sales in March
  - Total revenue: $98.83k
  - Total transactions: $21.23k
  - Average revenue per transaction: $4.66
    
### 2. Month-over-Month Sales Performance
  - Revenue change from February to March: 29.8% increase
  - Revenue change from March to April: [placeholder]
  - Change in the number of transactions from February to March:
  - Change in the number of transactions from March to April: 
  - Possible reasons for increase/decrease: ??
    - Daylight hours?
    - Winter vs spring?
    - Daylight savings? March xxx
   
### 3. Monthly Sales Breakdown
  - Total quantity of items sold in March: 30.4k
  - Month-over-month change in quantity sold: 29.1% increase
  - Top-selling product category: Barista Espresso
  - Top 5 products for the month: 
      1. Barista Espresso
      2. Brewed Chai tea
      3. Hot chocolate
      4. Gourmet brewed coffee
      5. Brewed herbal tea

### 4. Daily Revenue Trends
  - Highest and lowest revenue days: 
    - Lowest: $2.49k on Wednesday March 29 2023
    - Highest: 3.67k on Monday March 27 2023
  - Average Day of Week Sales: (day_name, sales_status, total_sales)
    - Monday:
    - Tuesday:
    - Wednesday:
    - Thursday
    - Friday:
    - Saturday:
    - Sunday:
      
### 5. Revenue by Day of the Week
  - Total revenue by weekday vs. weekend: 
    - Weekday: 73.3k
    - Weekend: 25.5k
  - Percentage of sales occurring on weekends: 
    - Weekday: 74.23%
    - Weekend: 25.77%
- Best/worse performing day of the week: 
    - Best: Fridays
    - Worse: Tuesdays

### 6. Store Location Performance
  - Revenue by store location: 
    - Hell's Kitchen: $33.1k
    - Lower Manhattan: $32.9k
    - Astoria: $32.8k

### 7. Hourly Sales Analysis
Total revenue for each hour of the day:

Peak sales hour: 7 am to 10am between 9k and 13k sales. 

## Recommendations

Based on the exploratory analysis, the following preliminary recommendations can be made:
- Target high-sales hours: Adjust staffing and inventory to match peak demand hours.
- Leverage top-selling products: Promote and stock up on high-demand products.
- Optimize weekend strategies: Increase promotions or special offers to maximize weekend sales.
- Investigate low-sales days: Identify causes for weak performance on specific days and explore corrective actions.

## Clarifying Questions, Assumptions, and Caveats

### Assumptions:
- The analysis assumes that all transactions are recorded accurately.
- External factors such as holidays, promotions, or economic conditions were not accounted for.
- Further data validation may be required to ensure consistency across store locations.

### Questions for Stakeholders:
- Are there any seasonal promotions or special events that might have influenced sales?
- Do different store locations have varying pricing strategies?
- What are the peak hours for customer foot traffic versus online orders?
- Are there known supply chain issues affecting product availability?
- Are there loyalty programs or discounts that impact revenue calculations?

### Missing Information:
- Customer demographics and purchasing behavior insights.
- Inventory levels to correlate with sales trends.
- Operational details, such as staffing levels during peak times.


(insert linebreak or footer) 
This report serves as an initial exploration of the coffee shop’s sales data. Future analysis will include a more in-depth study, visualizations, and a Dashboard to provide actionable insights for business strategy.
