### Toys Sales Analysis Using Power BI
Developing an interactive dashboard for a toy company, "Maven Toys". Managers can use this dashboard to get comprehensive report about the sales of toys. The aim of this data analysis project is to create an interactive dashboard using Power BI for analyzing sales of a toy company called "Maven Toys". The project involves taking raw sales and inventory data, cleaning and transforming it into a suitable format, and then visualizing the insights through an interactive and user-friendly dashboard.

## Overview
We have been given data about the sales, products, inventory and stores in CSV format. The data describes the 820,000+ transactions for all Maven Toys stores. The data spans from January 1st 2017 to September 30th 2018.

The main questions that are require to be answered are:

Which product categories drive the biggest profits? Is this the same across store locations?
Can you find any seasonal trends or patterns in the sales data?
Are sales being lost with out-of-stock products at certain locations?
How much money is tied up in inventory at the toy stores? How long will it last?

### Data Collection and Description:
The data is collected from Maven Data Playground.

We are given four files in CSV format described below:

Products:
- Product_ID - ID of the Product
- Product_Name - Name of the Product
- Product_Category - Category of Product
- Product_Cost - Product Cost (USD)
- Product_Price - Retail Price (USD)

Sales:
- Sale_ID - Sale ID for each transaction
- Date - Date when the transaction occured
- Store_ID - Unique ID given to toy store
- Product_ID - ID of the Product
- Units - Units of product sold

Stores:
- Store_ID - Unique ID given to toy store
- Store_Name - Store Name given of each toy store
- Store_City - City where the store is located
- Store_Location - Area where the store is located (Downtown,Commercial, Residential, Airport) Store_Open_Date - Store Opening Date
Inventory:
- Store_ID - Unique ID given to toy store
- Product_ID - ID of the Product
- Stock_On_Hand - Units of products currently in the inventory

### Data Modeling 
![image](https://github.com/user-attachments/assets/0a163322-9bb2-4dc6-aa4e-9263930c3ebd)

### Page 1: Monthly Sales and Performance Dashboard

Purpose:
This dashboard focuses on the monthly performance metrics, including profit, revenue, cost, and order count. It is crucial for tracking monthly progress towards goals.

Key Components:
1. Total Profit Current Month (180.45K): Displays the total profit for the current month, with a comparison to the set goal.
2. Total Revenue Current Month (658.19K): Shows the revenue earned this month, compared to the target.
3. Total Cost Current Month (477.75K): Represents the total cost incurred during the current month.
4. Total Orders Current Month (41,830): The total number of orders placed in the current month, with a goal comparison.
5. Total Sales (14.44M), Total Profit (4.01M), and Count Order (829K): Summarizes the overall sales, profit, and order count.
6. Count Orders by Product Category: A treemap chart showing the distribution of orders across different product categories.
7. Count Orders by Month: A line graph tracking the number of orders received each month, providing a view of seasonal trends.

Usage:
This dashboard is vital for monthly performance reviews, helping the management team to monitor key performance indicators (KPIs) against targets and make informed adjustments.

![sal](https://github.com/user-attachments/assets/e54422df-73b0-46bb-90ec-f459b653c508)

### Page 2: Product Performance Dashboard

Purpose:
This dashboard provides detailed insights into product performance, including sales, average pricing, and profits, segmented by product categories.

Key Components:
1. Total Products (35): The total number of products analyzed on this dashboard.
2. Average Price ($13.772): The average price of all products.
3. Total Quantity (1.091M): The total quantity of products sold.
4. Top 5 Products Over YTD Sales: A bar chart highlighting the top 5 products by year-to-date (YTD) sales, such as Lego Bricks and Colorbuds.
5. Top 5 Products Over Profit: Similar to the YTD sales chart, but ranked by profit contribution.
6. Product Category Breakdown: A table showing the total products, orders, quantities, profit, and sales for each product category.
7. Revenue and Costs by Product Category: A bar chart comparing the total sales and total costs across different product categories, illustrating profitability.

Usage:
This dashboard is ideal for product managers and sales teams to track product performance, identify best-sellers, and understand the profitability of different categories.
![pro](https://github.com/user-attachments/assets/526927d4-c8d6-4652-82f8-f0020c3dc365)

## Drill Through:
![drill](https://github.com/user-attachments/assets/18f7f4ca-1e10-4e62-bcb8-078af0dde594)


## Page 3: Store

Purpose:
The Overview Dashboard provides a high-level summary of the company's store locations, expansion history, and profitability across different store locations and product categories.

Key Components:
1. First Store Opened (1992): This metric shows the year the first store was opened, providing historical context.
2. Covered Cities (29): Indicates the number of cities where the stores are currently operational.
3. Number of Branches (50): The total number of branches across all locations.
4. Total Profit by Store Location and Product Category: A bar chart displaying profit contributions by different product categories (Art & Crafts, Electronics, Games, etc.) in various store locations (Downtown, Commercial, Residential, Airport).
5. Branches by Location: A donut chart representing the distribution of branches across different locations.
6. Number of Branches Opened Over the Years: A line graph showing the timeline of branch openings, indicating periods of rapid expansion.
7. 
These documentations provide a comprehensive guide to understanding and utilizing each dashboard effectively. Let me know if you need further details!

Usage:
This dashboard is useful for understanding the geographic and temporal spread of the company’s operations, as well as identifying which locations and product categories are most profitable.
![store (1)](https://github.com/user-attachments/assets/db21c5dc-c1cd-4cb1-8c89-a41d13351f8d)



### Page 4: Inventory and Stock Management Dashboard

Purpose:
The focus of this dashboard is on inventory and stock management, helping to ensure that stock levels are optimal and aligned with sales patterns.

Key Components:
1. Stock on Hand vs. Sold Units by Product Category: A chart comparing the current stock levels to the total sales for each product category, highlighting inventory turnover.
2. Stock on Hand by Store Location: A treemap displaying stock distribution across different store locations.
3. Total Stocks on Hand (30K): The total number of items currently in stock across all locations.
4. Stock on Hand vs. Sold Units by Product: A bar chart showing stock on hand versus units sold for top products like Deck of Cards, Dinosaur Figures, etc.

Usage:
This dashboard is essential for inventory managers and operations teams to track stock levels, prevent overstock or stockouts, and optimize inventory management.



![invent](https://github.com/user-attachments/assets/06cbecaa-56a5-4569-a345-2a378fd931f3)

## Drill Through:
![dr](https://github.com/user-attachments/assets/4b757517-7acd-4dcd-82ce-af866e255f1f)


