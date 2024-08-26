# blinkit_analysis_PowerBI

# About
This project revolves around the in-depth analysis of BlinkIT grocery sales data, designed to provide actionable insights through a visually compelling Power BI dashboard. The tool used in this project is Power BI, enabling seamless data integration, analysis, and visualization. The dashboard is aimed at helping stakeholders understand various aspects of sales performance, customer behavior, and product trends, thus empowering data-driven decision-making.

# Purpose Of The Project
To conduct a comprehensive analysis of Blinkit’s sales performance, customer satisfaction, and inventory distribution to identify key insights and opportunities for optimization using various KPIs and visualization in Power BI

# About Data
The dataset used in this project is derived from BlinkIT’s grocery sales records having 12 Columns and 8500+ Rows and includes the following key components:
  - Product Details
  - Sales Data
  - Customer Information
  - Time Dimensions
  - Geographical information

# Business requirements
To conduct a comprehensive analysis of Blinkit’s sales performance, customer satisfaction, and inventory distribution to identify key insights and opportunities for optimization using various KPIs and visualization in Power BI

##KPI’s Requirements
1. Total sales: The overall revenue generated from all item sold
2. Average sales: The average revenue per sale
3. Number of Items: The total count of different item sold
4. Average rating: The average customer rating for item sold

##Charts requirements
1.	Total sales by fat content: 
Objective: Analyze the impact of fat content on total sales
Additional KPI metrics: Assess how other KPIs (Average sales, Number of items, Average rating) vary with fat content.
Chart type: Donut chart
2.	Total sales by item type: 
Objective: identify the performance of different item types in terms of total sales
Additional KPIs Metrics: Assess how other KPIs (Average sales, Number of items, Average rating) vary with fat content.
Chart Type: Bar chart
3.	Fat content by outlet for total sales:
Objective: compare total sales across different outlets segmented by fat content
Additional KPIs metrics: Assess how other KPIs (Average sales, Number of items, Average rating) vary with fat content.
Chart type: Stacked Column chart
4.	Total sales by outlet Establishment
Objective: Evaluate how the age or type of outlet establishment influences total sales
Chart type: Line chart
5.	Sales by outlet size:
Objective: Analyze the correlation between outlet size and total sales
Chart type: Donut/Pie chart
6.	Sales by outlet location:
Objective: Assess the geographic distribution of sales across different locations
Chart type: Funnel chart
7.	All metrics by outlet type:
Objective: Providing a comprehensive view of all key metrics (Total sales, Average sales, Number of items, Average rating)
Chart type: Matrix card

# Approach used
1.	Requirement gathering/ business requirement
2.	Data walkthrough
3.	Data connection
4.	Data cleaning/ quality check (Replacing some values like (LF to Low fat, reg to regular), Check for errors (if any))
5.	Data modelling
6.	Data processing
7.	Dax calculation
8.	Dashboard layouting
9.	Charts development and formatting 
10.	Dashboard / report development
11.	Insights generation

## DAX function used:
1.	For total sales: Used Sum function
Formula used: Total sales = sum(‘blinkit store grocery data’[sales])
2.	For Average sales: Used Average function
Formula used: Average sales = Average(‘blinkit store grocery data’[sales])
3.	Number of Items: Used Countrows function
Formula use: Number of Items = countrows(blinkit store grocery data)
4.	Average rating: used Average function
Formula used: Average rating = Average(‘blinkit store grocery data’[Rating])

# Key Insights:
## Sales Analysis:
1. Average Sales: The average sales per item is approximately ₹141, with a range from ₹31 to ₹267.
2. Sales Distribution: The sales data is moderately spread, with a standard deviation of ₹62, indicating varying sales performance across different products.

## Item Characteristics:
1. Item Variety: There are 1,559 unique items across 16 categories, with Fruits and Vegetables and Frozen Foods being prominent types.
2. Item Weight: Item weights vary widely, ranging from 4.5 kg to 21.35 kg, with an average of 12.85 kg.

## Outlet Characteristics:
1. Outlet Types: The dataset covers 10 different outlets categorized into four types: Supermarket Type1, Supermarket Type2, Supermarket Type3, and Grocery Store.
2. Outlet Sizes: Outlets are classified into three sizes: Small, Medium, and High. Medium-sized outlets are the most common.

## Consumer Behavior:
1. Item Visibility: The visibility of items, which might affect consumer purchases, averages at 0.066, with a few items having almost no visibility.
2. Rating Distribution: Ratings for items are generally high, with an average of 4 out of 5, indicating positive consumer feedback.

## Time Analysis:
Establishment Year: Outlets were established between 2011 and 2022, with a concentration around 2016. This indicates a period of expansion for Blinkit.

This analysis can guide the company in optimizing product offerings, improving outlet performance, and enhancing customer satisfaction.

# Overview of the dashboard
Here is the overview of the dashboard, for the actual interacting dashboard, check the blinkit dashboard file.
![image](https://github.com/user-attachments/assets/6406293d-0cd2-4168-85e3-4ddd6a0ce16a)

