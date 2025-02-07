# Retail-sales-analysis

# Introduction

This project aims to derive meaningful insights from retail transaction data spanning two time periods: 2009-2010 and 2010-2011. The analysis seeks to answer key business questions related to sales trends, customer purchasing behavior, product performance, and market potential.

# Objectives

This analysis addresses the following questions:
1. How do sales vary across months, quarters, and years?
2. What are the key customer purchasing behaviors?
3. Which products are top sellers, and which underperform?
4. Which countries have the highest sales volume and growth potential?

#  Skills Demonstrated

Data cleaning and transformation using Power Query
Data modeling and analysis with DAX (calculated columns and measures)
Time intelligence analysis
Data modelling
Data visualization using Power Bi

# Dataset

The dataset was sourced from a GitHub repository. It consists of two CSV tables containing: number of items purchase in each transaction, the unit price of each product, date and time of transactions, country of transaction, unique customer and transaction identifiers 

# Data Transformation and Cleaning

Data preparation was conducted using Power Query in Power BI, with the following steps:
Appended the 2009-2010 and 2010-2011 datasets into a unified dataset
Removed duplicates and filtered out transactions with zero or negative prices and quantities
Trimmed unnecessary spaces from text fields
Assigned appropriate data types to each column

# Data Analysis and modelling 

Created a date table using DAX, extracting year, month, and quarter for time-based analysis.
Conducted an RFM (Recency, Frequency, and Monetary) analysis to segment customers based on purchasing behavior.
Established a star schema with the retail transactions table as the fact table, and supporting dimension tables including the RFM table, date table, and customer segment table.
The DAX code used for this report can be found here (link).

# Visualization

Developed measures for key performance metrics such as total quantity sold, total revenue, and average revenue.
Interactive dashboards and visualizations in Power BI illustrate the findings (link to report).

#   Key Insights
Sales Performance: A total of 11 million products were sold, generating £17.74 million in revenue across the two time periods.

Seasonality Trends: The fourth quarter consistently outperformed other quarters, generating £6.5 million in sales, with November emerging as the highest-performing month (£2.3 million in sales).

Annual Growth: Sales peaked in 2010, contributing £8.7 million in revenue.

Customer Behavior:
•	39.5% of purchases were made by repeat buyers. 

•	24% of purchases were made by new customers.

•	7.5% of purchases were attributed to high-value customers.

Geographic Insights: The UK was the leading market, contributing £14.7 million in sales. Other high-performing markets included EIRE, the Netherlands, Germany, and France.

Product Performance:
The top-performing products were Regency Cake Stand Tier 3, White Hanging Heart T-Light Holder, and Paper Craft Little Birdie.

Regency Cake Stand Tier 3 generated £286,486 from 24,914 purchases.

White Hanging Heart T-Light Holder and Paper Craft Little Birdie had high sales volumes (93,640 and 80,995 units, respectively), generating £252,073 and £168,470 in revenue.

Items such as Pink Heart Christmas Decoration and Set of 12 Coloring Pencils Doily recorded negligible sales.

# Conclusion and Recommendation
By leveraging Power Query and Power BI, this project transformed raw data into actionable insights, enabling data-driven decisions to optimize operations and drive growth. 
Based on the findings, retail stakeholders could:
1.	Implement loyalty programs to enhance retention and encourage repeat purchases.
2.	Prioritize high-performing products and consider discontinuing low-demand items to optimize inventory.
3.	Leverage seasonal trends for strategic campaigns, especially during Q4 and November.
4.	Invest in growth markets like France and Germany, while re-engaging declining markets like the UK and EIRE.
This project showcases the power of data analytics in optimizing retail operations and driving business growth.

