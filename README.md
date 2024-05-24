# Superstore Sales Analysis with Power BI
## Project Description
This project delves into the sales data of a fictional superstore using Power BI to uncover potential areas for profit improvement. By conducting a thorough Exploratory Data Analysis (EDA), we aim to identify trends, patterns, and relationships within the dataset that could inform data-driven business decisions.

## Key Objectives

- Understand Sales Performance: Explore the overall sales performance of the store, analyzing trends across various dimensions like product categories, regions, segments, ship methods, and order dates.
- Identify Profit Margins: Investigate product profitability, delving into factors that influence profit margins such as discounts, order quantities, and sales channels.
- Uncover Weaknesses: Pinpoint areas with lower profitability. This could involve products, categories, customer segments, or regions that might require targeted strategies to boost sales or optimize pricing.
- Formulate Data-Driven Recommendations: Based on the findings of the EDA, propose actionable insights and recommendations to enhance profitability. These might include product promotions, adjustments to pricing strategies, or targeted marketing campaigns.

## Datasource:
Dataset:[[dataset](https://drive.google.com/file/d/1lV7is1B566UQPYzzY8R2ZmOritTW299S/view)]

## Data Preparation:

Completed the Data transformation in Power Query and the dataset is then loaded into Microsoft Power BI Desktop for visualization.

## Dataset Description:
Sample superstore dataset contains `13 columns and 9995 rows` of observation. Dataset includes columns like:

- Ship Mode: Shipping method used for the order (e.g., Standard Class, Second Class, First Class, Same Day).
- Segment: Customer segment (e.g., Consumer, Corporate, Home Office).
- Country: Country where the order was shipped.
- City: City where the order was shipped.
- State: State where the order was shipped.
- Postal Code: Postal code of the shipping address.
- Region: Region where the order was shipped (e.g., East, West, Central, South).
- Category: Product category (e.g., Furniture, Office Supplies, Technology).
- Sub-Category: Sub-category of the product (e.g., Binders, Phones etc).
- Sales: Sales amount for the order.
- Quantity: Quantity of products ordered.
- Discount: Discount applied to the order.
- Profit: Profit earned from the order.

# Methodology and Tools
- Data Source: I have utilized the publicly available Sample Superstore dataset, which provides a rich set of sales-related data.
- Power BI: As the primary data visualization and exploration tool, Power BI facilitated the creation of interactive dashboards and reports to analyze the data from various angles.

# Exploratory Data Analysis (EDA):
- Data Cleaning and Preprocessing: There are no missing values, inconsistencies, and data quality issues present in the dataset.
- Descriptive Statistics: Summarized KPIs like sales, profit, discounts, and quantities to gain an initial understanding of the data.
- Data Visualization: Created visuals like bar charts to identify patterns, trends, and relationships within the data.
- New column: profit_margin = (profit/sales)*100. So, now the dataset contains '13 columns and 9995 rows'

## Data Visualization (Dashboard):
Dashboards created in Microsoft Power BI Desktop:

Overview:
![overview dashboard img](https://github.com/sonali-guptaa/customer_retention_analysis/assets/151986702/6b7b279b-25c1-42a4-80eb-07c65332eaee)

Sales Analysis Dashboard:
![sales analysis dashboard img](https://github.com/sonali-guptaa/customer_retention_analysis/assets/151986702/aaad38d8-0860-45c7-8397-da630c4c5a4f)

Profit Analysis Dashboard:
![3rd screenshot img](https://github.com/sonali-guptaa/customer_retention_analysis/assets/151986702/df2131c3-62d1-4b60-b23f-6b5122bc554d)

Quantity Analysis Dashboard:
![4th screenshot img](https://github.com/sonali-guptaa/customer_retention_analysis/assets/151986702/1485b952-af91-4e68-a49c-7baa2df7c9d7)

Discount Analysis Dashboard:
![5th screenshot img](https://github.com/sonali-guptaa/customer_retention_analysis/assets/151986702/1cce2ffb-0001-4240-902d-e2ce6dbb2508)

Profit Margin Analysis Dashboard:
![6th screenshot img](https://github.com/sonali-guptaa/customer_retention_analysis/assets/151986702/ed7b4f91-63a7-4a61-af77-9ea3c6f2153d)

## Insights:
- Shipping mode is the most preferred mode out of all other modes.
- Consumer segment is the largest contributor to all KPIs, suggesting a strong B2C market.
- Even though, the technology is the top selling category but the profit margin is high for office supplies category.
- The West region is leading in sales, profit, quantity and profit margin but the discount is high for central region.
- The sales, profit, quantity and profit margin are high in California state but the discount is high in Texas state.
- New York City leads in all KPIs except for high discounts in Philadelphia.
- Phones is the top selling and high profit sub-category.
- Discount and quantity is high for binders sub-category.

## Recommendation:
Some recommendations based on the analysis are:
- Ensure reliability of Standard Class; create incentives for Second Class, First Class, and Same Day shipping.
- Increase B2C marketing efforts; implement loyalty programs and personalized marketing.
- Expand technology offerings; promote the profitability of Office Supplies.
- Apply successful West region strategies to other regions; develop customized marketing to boost sales.
- Review and optimize discount policies for profitability.
- Adjust discount strategies in Texas for better profitability; continue supporting California’s success.
- Assess and adjust high discounts in Philadelphia; maintain successful strategies in New York City.
- Reduce discounts slightly for binders to improve margins.
- Monitor sales data for trends; gather and act on customer feedback to enhance offerings.
- Ensure discounts drive sales while maintaining healthy profit margins.
---




