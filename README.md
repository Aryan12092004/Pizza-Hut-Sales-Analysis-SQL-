🍕 Pizza Hut Sales Analysis using SQL
In this project, I performed a comprehensive sales analysis for a Pizza Hut store using SQL. By querying over 48,000+ clean sales records, I explored customer behavior, revenue trends, and product performance through business-driven queries.

I worked with multiple relational datasets and leveraged SQL Joins, CTEs, and Subqueries to generate structured insights and enable data-backed decisions for pricing, promotions, and operations.

🧾 Datasets Used
The project uses 4 interlinked .csv files:

orders.csv – contains order IDs, dates, and timestamps
order_details.csv – maps orders to pizzas and quantities
pizzas.csv – contains pizza size and price information
pizza_types.csv – describes each pizza type, category, and ingredients

🔧 Tools & Techniques
SQL (SQLite) – for data querying and analysis
Joins, Subqueries, CTEs – for data transformation
GROUP BY, Aggregations, Window Functions – for business metrics

📊 Business Questions Answered
🔹 Basic Level
✅ Total number of orders placed
✅ Total revenue generated from pizza sales
✅ Highest-priced pizza identified
✅ Most common pizza size ordered
✅ Top 5 most ordered pizza types by quantity

🔸 Intermediate Level
✅ Category-wise total quantity ordered (using joins)
✅ Distribution of orders by hour of the day
✅ Category-wise distribution of all pizza types
✅ Daily pizza sales and average pizzas per day
✅ Top 3 pizza types based on revenue

🔺 Advanced Level
✅ Percentage revenue contribution of each pizza type
✅ Cumulative revenue over time
✅ Top 3 pizza types by revenue within each pizza category
