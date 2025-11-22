### Project Summary and Scope
1. Objective: To conduct a comprehensive data analysis of pizza sales data to extract actionable business intelligence regarding financial performance, product popularity, and operational efficiency.
2. Data Scope: The analysis spans a full year of operational data, encompassing 21,350 unique orders and over individual pizza line items.
3. Core Achievement: The project successfully calculated the total annual revenue, identified critical sales trends, and determined key product drivers for revenue and volume.
4. Financial Metric: The total revenue generated from pizza sales during the analyzed period amounts to $817,860.05.

### Strategic Business Insights
## Operational & Demand Analysis
1. Peak Demand Hours: Order volume exhibits a bimodal distribution, with pronounced peaks during the lunch rush (12:00 PM to 1:00 PM) and the dinner period (5:00 to 7:00 PM). This insight is critical for optimized staff scheduling.
2. Average Daily Volume: The average number of pizzas sold daily is 60.10 units, providing a baseline for inventory and production targets.
3. Most Common Size: The Large (L) size is the dominant order, representing the majority of units sold and necessitating a corresponding focus on inventory management for `Large` size ingredients.

### Product and Revenue Performance
1. Highest Revenue Contributor (Overall): The Classic Deluxe Pizza is the top-performing item, generating the highest total revenue $20.5 thousand.
2. Top 5 Best-Sellers (Volume): The five most ordered pizza types, in descending order of quantity, are:
   The Classic Deluxe Pizza
   The Hawaiian Pizza
   The Thai Chicken Pizza
   The Sicilian Pizza
   The Barbecue Chicken Pizza
3. Revenue Contribution by Category: The Classic category drives the highest overall sales volume, followed by the Supreme and Veggie categories, indicating a strong market preference for traditional pizza types.
4. Highest Priced Item: The premium item in the catalogue is the Greek Pizza (Extra Large), priced at $35.95, demonstrating a successful high-tier pricing strategy.

### Advanced Financial & Technical Summary
1. Revenue Ranking by Category (Top 3): Product performance was segmented by category to identify specialized market leaders:
   Chicken: The Barbecue Chicken Pizza, The Thai Chicken Pizza, The Southwest Chicken Pizza.
   Classic: The Classic Deluxe Pizza, The Hawaiian Pizza, The Italian Supreme Pizza.
   Supreme: The Pepperoni, Mushroom, and Peppers Pizza, The Four Seasons Pizza, The Spicy Italian Pizza.
2. Percentage Contribution: The Classic Deluxe Pizza holds the largest single-product share of total revenue at 2.51 %.
3. Cumulative Revenue Analysis: The cumulative revenue metric confirms steady, monotonic financial growth throughout the year, serving as a reliable benchmark for year-over-year performance evaluation.
4. Technical Implementation: The analysis required multiple table joins (order\_details, pizzas, pizza\_types, orders) and the application of SQL-like aggregation, temporal functions, and Window Functions to compute daily averages and cumulative sums.
