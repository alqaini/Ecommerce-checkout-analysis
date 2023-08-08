
## Overview
The E-commerce Checkout Dataset contains transaction data of an e-commerce store between April 24th and November 21st, 2020. The dataset includes information on customer orders, product details, category codes, brands, prices, and user IDs.
## Tools and Libraries Used

The analysis of the E-commerce Checkout Dataset was conducted using a combination of Python programming and popular data analysis libraries. The following tools and libraries were utilized:

- **Python:** The primary programming language used for data analysis and manipulation.

- **Pandas:** A powerful data analysis library in Python used for data manipulation, transformation, and analysis.

- **SQLite:** A lightweight, serverless database engine used for managing and querying structured data.

- **Matplotlib:** A versatile data visualization library in Python used for creating static, interactive, and publication-quality visualizations.

- **Seaborn:** A statistical data visualization library based on Matplotlib, used for creating aesthetically pleasing and informative visualizations.

Additionally, Jupyter Notebook or JupyterLab might have been used for interactive data analysis and code documentation.

The combination of these tools and libraries allowed for efficient data processing, exploration, visualization, and insights generation from the E-commerce Checkout Dataset.

## Business Metrics
##### GMV (Gross Merchandise Value)
The GMV represents the total value of all orders made during the given period. It is calculated as the sum of all prices for all products purchased.

##### GMV Orders and GMV Units
GMV Orders represent the count of unique order IDs, while GMV Units represent the total count of products sold.

##### Average Selling Price (ASP)
ASP is the average price per item sold, calculated as the total GMV divided by the total number of units sold.

##### Average Order Value (AOV)
AOV is the average value of each order, calculated as the total GMV divided by the total number of orders.

## Site Metrics
Site Metrics
Session Count
Session count represents the number of recorded events in the dataset, assuming each event time corresponds to a session.

Total Order per Session
The total number of orders per session is calculated as the count of unique order IDs divided by the total session count.

Session Conversion
Session conversion represents the percentage of sessions that resulted in an order. It is calculated as the count of sessions with orders divided by the total session count.

Visitor Count and Customer Count
Visitor count represents the total number of unique visitors to the e-commerce store. Customer count is the total number of unique customers who made purchases.

Average Visits per Customer
Average visits per customer is calculated as the total session count divided by the total number of unique customers.


## Category Metrics
Category Metrics
Category GMV
Category GMV represents the total value of orders for each category. It is calculated as the sum of prices for all products in each category.

Brand GMV
Brand GMV shows the total value of orders for each brand. It is calculated as the sum of prices for all products of each brand.

Moving Average
A moving average for 7 days, 14 days, and 28 days can be calculated for GMV to analyze trends over time.