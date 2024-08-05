# Divine Chocolate Sales Analysis
![Power BI dashboard](https://github.com/23MD/Chocolate_Sales_Analysis/blob/5826a80c87d6e0bb1b50e64a2fce3a81828d38e0/Dashboard_SS.PNG)

## Introduction
Welcome to the Devine Chocolates Data Analytics Portfolio Project. This project showcases my proficiency in data analytics by leveraging Power BI for data visualization and MySQL for data management. The primary aim is to provide actionable insights into the sales and operational performance of Devine Chocolates, a hypothetical company dealing in premium chocolates. This portfolio project involves extracting, transforming, and analyzing data using SQL queries executed in a Jupyter Notebook environment and visualizing the findings through a comprehensive Power BI dashboard.

## Objective
The objective of this portfolio project is to demonstrate my capability in handling real-world data analytics tasks by:
- Extracting and manipulating data from a MySQL database.
- Performing complex SQL queries to answer critical business questions.
- Creating insightful visualizations using Power BI to support decision-making processes.
- Providing a detailed analysis of sales performance, product profitability, team effectiveness, and market trends for Devine Chocolates.

## About Dataset
Database created in mysql and accessing database from jupyter notebook using mysql.connector library.
There are 3 tables in database namely Shipments table, Product table and Salesperson table.

`Shipments Table` - show the different categories of product shipped by salesperson to different region of the world. It also has date and number of boxes shipped along with the revenue made by each salesperson. Table has 6113 sales record and 6 attributes.

`Product Table` - It show 3 distinct categories for 22 unique kinds of chocolate and their prices per box.	

`Salesperson Table` - It contains the name of salesperson and their team name. There are 25 salesperson working in 4 Teams.

[Kaggle Dataset](https://www.kaggle.com/datasets/prajwal6362venom/choclate-sales-project)


## Business Requirement Table
| ID| Business Question| Objective| Key Metrics| Expected Outcome|
|-|-|-|-|-|
|1|	Total Sales per Category|	Determine the total sales for each product category.|	Total Sales, Product Category|	Identify top-performing product categories.|
|2|	Highest Salesperson per Geography	|Identify the top salesperson in each geography.|	Salesperson, Geography, Sales|	Recognize and reward top performers in different regions.|
|3|	Profit Calculation	|Compute the profit for each shipment and aggregate by salesperson.|	Sales, Cost, Profit	|Evaluate profitability and identify key contributors to profit.|
|4|	Sales Trend Analysis|	Show month-over-month sales trends for each product category.|	Monthly Sales, Product Category	|Understand sales seasonality and growth trends.|
|5|	Top Selling Products by Team|	Determine the top 3 best-selling products for each sales team.|	Sales Team, Product, Sales|	Optimize product offerings and sales strategies by team.|
|6|	Geography-based Sales Distribution|	Find the percentage contribution of each geography to total sales.|	Sales, Geography|	Identify key markets and allocate resources accordingly.|
|7|	Average Cost per Category	|Calculate the average cost of products for each category.|	Product Cost, Product Category	|Monitor cost efficiency across different product categories.|
|8|	Team-wise Sales Performance|	Compare total sales performance of different sales teams.|	Sales Team, Sales|	Assess team performance and provide targeted support or training.|
|9|	Shipment Details for High Value Products	|List all shipment details where the product cost is above a certain threshold.|	Product Cost, Shipment Details|	Focus on high-value products to ensure quality and manage risks.|
|10|	Salesperson Contribution to Team Sales|	Calculate the percentage contribution of each salesperson to their respective team’s total sales.|	Salesperson, Sales Team, Sales|	Evaluate individual contributions and align incentives accordingly.|
