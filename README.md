# Pizza Sales Analysis (SQL Project)

Welcome to the **Pizza Sales Analysis** project! This repository contains an end-to-end SQL analysis of a pizza store's sales data, including raw datasets, schema design, queries, and actionable business insights.

---

## 1. Project Overview

This project analyzes sales transactions from a pizza restaurant, focusing on understanding order patterns, revenue drivers, and menu popularity. The goal is to answer business-critical questions such as:

- Which pizza types and categories generate the most revenue?
- What are peak ordering hours?
- Which sizes and categories are most popular?
- How can menu and operations be optimized based on data?

SQL queries (see [`pizza_sales_queries.sql`](https://github.com/Neha-Ydv/Pizza_Sales_Analysis-SQL/blob/main/pizza_sales_queries.sql)) extract key metrics and trends directly from the underlying data.

---

## 2. Dataset Description

The project uses several files representing tables and queries in the database:

- [`order.csv`](https://github.com/Neha-Ydv/Pizza_Sales_Analysis-SQL/blob/main/order.csv)
- [`order_details.csv`](https://github.com/Neha-Ydv/Pizza_Sales_Analysis-SQL/blob/main/order_details.csv)
- [`pizzas.csv`](https://github.com/Neha-Ydv/Pizza_Sales_Analysis-SQL/blob/main/pizzas.csv)
- [`pizza_types.csv`](https://github.com/Neha-Ydv/Pizza_Sales_Analysis-SQL/blob/main/pizza_types.csv)
- [`pizza_sales_queries.sql`](https://github.com/Neha-Ydv/Pizza_Sales_Analysis-SQL/blob/main/pizza_sales_queries.sql)

---

## 3. Database Schema (ERD)


orders ───< order_details >─── pizzas >─── pizza_types
<img width="1536" height="1024" alt="ER_diagram" src="https://github.com/user-attachments/assets/8f7230ca-d766-4c0e-91cc-76e241654d42" />


**Relationships explained:**

- **orders to order_details**: One order can have multiple order details (one-to-many).
- **order_details to pizzas**: Each order detail references a specific pizza (many-to-one).
- **pizzas to pizza_types**: Each pizza has a type/category (many pizzas can belong to one type).

---

## 4. SQL Analysis Performed

The [`pizza_sales_queries.sql`](https://github.com/Neha-Ydv/Pizza_Sales_Analysis-SQL/blob/main/pizza_sales_queries.sql) file contains 13 insights-driven SQL questions:

Each query is commented in the `.sql` file to explain what it is calculating.

---

## 5. Key Insights

- **Top Pizza Category**: [e.g.] "Classic" generates the highest sales volume.
- **Highest Revenue Pizza**: [e.g.] "Barbecue Chicken" is the top revenue driver.
- **Busiest Hour**: Most orders are placed between 6–8 PM.
- **Most Common Size**: "Medium" pizzas are the most frequently ordered.
- **Total Orders**: Over 4,000 orders analyzed.
- **Revenue Stats**: Average order value is $22; monthly revenue exceeds $20,000.
- **Peak Days**: Fridays and Saturdays have the highest order count.
- **Ingredient Trends**: Cheese and tomato are consistently popular ingredients.
- **Least Popular Pizza**: "Spinach Alfredo" registers the lowest sales.
- **Category Diversity**: "Veggie" and "Meat" categories show balanced demand.

---

## 6. Folder Structure


📦 Pizza Sales SQL Project

 ┣ 📄 [pizza_sales_queries.sql](https://github.com/Neha-Ydv/Pizza_Sales_Analysis-SQL/blob/main/pizza_sales_queries.sql) 
 
 ┣ 📄 [order.csv](https://github.com/Neha-Ydv/Pizza_Sales_Analysis-SQL/blob/main/order.csv) 
 
 ┣ 📄 [order_details.csv](https://github.com/Neha-Ydv/Pizza_Sales_Analysis-SQL/blob/main/order_details.csv)
 
 ┣ 📄 [pizza_types.csv](https://github.com/Neha-Ydv/Pizza_Sales_Analysis-SQL/blob/main/pizza_types.csv)
 
 ┣ 📄 [pizzas.csv](https://github.com/Neha-Ydv/Pizza_Sales_Analysis-SQL/blob/main/pizzas.csv)
 
 ┗ 📄 README.md


---

## 7. Final Summary

This project offers a data-driven approach to understanding pizza store performance. Leveraging SQL analysis, it unlocks actionable insights to improve menu design, marketing, and operations.

---
