![alt text](coffee.jpg)
# Coffee Shop Sales Analysis

## Client Information
- **Client:** Starbucks

- **Location:** Houston, Texas




## Project Meeting
- **Date:** June 29, 2024

## Objectives

### Problem Statement
We aim to analyze key performance indicators (KPIs) to measure how well the business is performing. The KPIs will focus on total sales, total orders, and total quantity sold..

### KPI Measurements

#### 1. Total Sales Analysis
1. **Calculate the total sales for each respective month.**
2. **Determine the month-on-month increase or decrease in sales.**
3. **Calculate the difference in sales between the selected month and the previous month.**

#### 2. Total Order Analysis
1. **Calculate the total number of orders for each respective month.**
2. **Determine the month-on-month increase or decrease in the number of orders.**
3. **Calculate the difference in the number of orders between the selected month and the previous month.**

#### 3. Total Quantity Sold Analysis
1. **Calculate the total quantity sold for each respective month.**
2. **Determine the month-on-month increase or decrease in the total quantity sold.**
3. **Calculate the difference in the total quantity sold between the selected month and the previous month.**

## Chart Requirements
To provide more granular descriptions for products, we need the following visualizations:

### 1. Calendar Heat Map
1. **Implement a calendar heat map that dynamically adjusts based on the selected month from a slicer.**
2. **Each day on the calendar will be color-coded to represent sales volume, with darker shades indicating higher sales.**
3. **Implement tooltips to display detailed metrics (sales, orders, quantity) when hovering over a specific day.**

### 2. Sales Analysis by Weekdays and Weekends
1. **Segment sales data into weekdays and weekends to analyze performance variations.**
2. **Provide insights into whether sales patterns differ significantly between weekdays and weekends.....**

### 3. Sales Analysis by Store Location
1. **Visualize sales data by different store locations.**
2. **Include month-over-month (MOM) difference metrics based on the selected month in the slicer.**
3. **Highlight MOM sales increase or decrease for each store location to identify trends.**

### 4. Daily Sales Analysis with Average Line
1. **Display daily sales for the selected month with a line chart.**
2. **Incorporate an average line on the chart to represent the average daily sales.**
3. **Highlight bars exceeding or falling below the average sales to identify exceptional sales days.**

### 5. Sales Analysis by Product Category
1. **Analyze sales performance across different product categories.**
2. **Provide insights into which product categories contribute the most to overall sales.**

### 6. Top 10 Products by Sales
1. **Identify and display the top 10 products based on sales volume.**
2. **Allow users to quickly visualize the best-performing products in terms of sales.**

### 7. Sales Analysis by Days and Hours
1. **Utilize a heatmap to visualize sales patterns by days and hours.**
   - Create a new column in the transaction table: `Hour = HOUR(Transactions[transaction_time])`.
   - Move the hour to rows and display the days.
   - Move day name to row > total sales (values) > cell element > background color (on) (fx).
2. **Implement tooltips to display detailed metrics (sales, orders, quantity) when hovering over a specific day-hour.**

This analysis will provide a comprehensive understanding of sales performance and help identify key areas for improvement.
