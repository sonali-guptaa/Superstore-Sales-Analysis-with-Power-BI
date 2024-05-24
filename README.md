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
- Data Cleaning and Preprocessing: Checking for missing values, inconsistencies, and data quality issues.
- Descriptive Statistics: Summarizing key metrics like sales, profit, discounts, and quantities to gain an initial understanding of the data.
- Data Visualization: Creating visuals like bar charts, line graphs, scatter plots, and heatmaps to identify patterns, trends, and relationships within the data.
  
## Create Profit Margin column:
profit_margin = (profit/sales)*100

## Data Visualization (Dashboard):
Dashboards created in Microsoft Power BI Desktop:
Overview:




