# Restaurant Orders: SQL Relational Database Analysis


### Project Overview

This project involves the creation and analysis of a relational database for a restaurant. By linking menu data with order transactions, I performed an Exploratory Data Analysis to identify sales trends, popular cuisines, and high-value orders.


### The Data Schema

The database consists of two primary tables:

- menu_items: contains the name, category (American, Asian, Italian, Mexican), and price of every item.

- order_details: a transactional table recording every item sold, including date, time, and order ID.


### Key Skills Demonstrated

- Database Schema Design: creating tables with primary and foreign keys.

- Data Aggregation: using GROUP BY and SUM/AVG to calculate revenue.

- Table Joins: connecting orders to menu items to associate prices with sales.

- Trend Analysis: identifying peak ordering times and dates.


### Sample Insights

- Cuisine Diversity: the menu spans multiple categories, allowing for a comparison of Asian vs Italian vs American sales performance.

- Top Performers: the queries identify the most frequently ordered items (e.g., Hamburger vs. Edamame).

- Transaction Value: analysis of which order_ids generated the highest revenue by joining item prices to order quantities.


### How to Run the Analysis

Execute create_restaurant_db.sql to build the schema and populate the data.

Run the queries in Restaurant Project SQL.sql to generate the business insights.
