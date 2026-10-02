# Pizza-Sales-SQL-Analysis
Exploratory data analysis of pizza restaurant sales using SQL to uncover key business insights, calculate KPIs, and identify purchasing trends.

# Pizza Sales Data Analysis 🍕

## Project Overview
This project involves an in-depth exploratory data analysis of a pizza restaurant's sales records using SQL. The primary objective is to evaluate core Key Performance Indicators (KPIs) and uncover actionable business intelligence regarding customer purchasing patterns, temporal sales trends, and menu performance.

## Dataset
The analysis is based on a transaction-level dataset (`pizza_sales.csv`) containing 21,350 unique customer orders and 49,574 total pizzas sold. 

**Key Attributes:**
*   `order_id`: Unique identifier for each distinct customer order.
*   `order_date`: The date the transaction occurred.
*   `quantity`: The number of pizzas purchased in a specific order line item.
*   `total_price`: The total monetary value generated from the specific pizzas sold.
*   `pizza_category`: The menu classification (Classic, Supreme, Chicken, Veggie).
*   `pizza_size`: The size of the pizza ordered (S, M, L, XL, XXL).
*   `pizza_name`: The specific recipe of the pizza.

## Key Performance Indicators (KPIs)
*   **Total Revenue:** $817,860.05
*   **Average Order Value:** $38.31
*   **Total Pizzas Sold:** 49,574
*   **Total Orders:** 21,350
*   **Average Pizzas Per Order:** 2.32

## Key Insights & Findings
*   **Temporal Trends:** Order volume peaks late in the week, specifically on Fridays (3,538 orders) and Thursdays (3,239 orders). July is the strongest month for overall sales.
*   **Category Performance:** The "Classic" category is the most popular, generating 26.91% of total revenue, closely followed by the "Supreme" category at 25.46%.
*   **Size Preferences:** Large (L) pizzas overwhelmingly dominate customer preference, accounting for 45.89% of all revenue.
*   **Best & Worst Sellers:** "The Thai Chicken Pizza" is the highest revenue generator ($43,434.25), while "The Classic Deluxe Pizza" is the most ordered item by volume. "The Brie Carre Pizza" is consistently the lowest-performing item across all metrics.

## Tech Stack
*   **Language:** SQL
*   **Key Techniques:** Aggregation functions, type casting, date/time extraction, subqueries, and data grouping.

## Author
**Sanjay Singh**
GitHub: [@Sanjay2422](https://github.com/Sanjay2422)
