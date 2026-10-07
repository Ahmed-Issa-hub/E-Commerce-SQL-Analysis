# E-Commerce SQL Analysis Project

## Overview
This project analyzes an e-commerce relational database to understand customer purchasing behavior, product performance, profitability, repeat purchases, and return patterns.

The objective was to use SQL to answer business questions that could support decisions related to customer retention, product strategy, and profitability.

---

## Database Structure

The database consists of six related tables:

- Customers

- Products

- Orders

- Order Items

- Product Reviews

- Returns

An Entity Relationship Diagram (ERD) was created to define the relationships between the tables.

---

## Tools & Skills Used

- **SQL Skills Demonstrated**:  
  - INNER JOIN and LEFT JOIN
  - GROUP BY and HAVING
  - Common Table Expressions (CTEs)
  - Subqueries
  - Window Functions
  - Aggregate Functions
  - Conditional Logic
  - Business KPI Calculations

## Business Questions

The analysis answers questions including:

Which products generate the highest sales volume?

Which customers contribute the most revenue?

Which products generate the highest profit margins?

Which customers spend above the overall average?

Which products have the highest return activity?

What was each customer's first purchase?

Which products perform above their category's average rating?

What percentage of sold items are returned?

Which markets have the largest customer base?

Which customers demonstrate repeat purchasing behavior?


---

## Key Analytical Areas

### Customer Analysis
Identified high-value and repeat customers using order frequency and spending patterns.
### Product Performance
Analyzed product sales, revenue, cost, and profitability to identify strong and weak performers.
### Returns Analysis
Calculated return rates to identify products with unusually high return activity.
### Customer Purchase Behavior
Used window functions and aggregation techniques to analyze first purchases, repeat orders, and customer spending behavior.

---

## Entity Relationship Diagram (ERD)

![ERD](ERD.png)

---

## Repository Structure

01 schema.sql — database structure

02 mock_data.sql — sample data

/Queries — SQL analysis queries

ERD.png — database relationship diagram


