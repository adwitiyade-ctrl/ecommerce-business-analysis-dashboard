# E-Commerce Business Analysis Dashboard

An end-to-end e-commerce business analysis project using **Python, SQL, Excel, and Power BI** to analyze orders, revenue, payments, product categories, delivery performance, and seller performance.

## Project Overview

This project uses a synthetic e-commerce dataset to simulate a marketplace business environment and answer practical business questions through data analysis and visualization.

The analysis covers:

* Order and revenue performance
* Category and subcategory performance
* Monthly order-value trends
* Payment-method usage
* Delivery and non-delivery patterns
* Seller-rating performance
* Product-level performance
* Estimated gross profit by category

## Tools & Technologies

* **Python** — Synthetic data generation and analysis
* **SQL** — Business queries and aggregations
* **Excel** — Exploratory analysis and reporting
* **Power BI** — Interactive dashboard and visualization

## Dataset

The project contains two main datasets:

* `orders (1).csv` — Order-level information including order value, quantity, payment method, delivery time, seller rating, and order status.
* `products.csv` — Product information including category, subcategory, selling price, cost price, and product rating.

The dataset is **synthetically generated for portfolio and learning purposes** and does not contain real Meesho data.

## Business Questions

The analysis explores questions such as:

1. Which product categories generate the highest order value?
2. How does order value change month to month?
3. Which payment methods are most commonly used?
4. Is longer delivery time associated with higher non-delivery rates?
5. Is seller rating associated with order failure rates?
6. Which subcategories generate the highest order value?
7. Which categories generate the highest estimated gross profit?

## Power BI Dashboard

The dashboard includes:

* Total Order Value
* Total Orders
* Average Order Value
* Non-Delivered Rate
* Order Value by Category
* Monthly Order Value Trend
* Orders by Payment Method
* Delivery Time vs Failure Rate
* Seller Rating vs Failure Rate
* Top 10 Subcategories by Order Value
* Category, Order Status, and Payment Method filters

### Dashboard Preview

![E-Commerce Business Analysis Dashboard](market%20analysis%20dashboard%20preview.png)

## Key Insights

* **Women Fashion** generated the highest order count among the product categories.
* **October** recorded the highest monthly order value in the synthetic dataset.
* **UPI** was the most frequently used payment method.
* Longer delivery buckets showed higher non-delivery rates in the dataset.
* Lower seller-rating groups showed higher non-delivery rates than higher-rated groups.
* **Ethnic Wear** was the highest-value subcategory by total order value.

These relationships are **observational associations within the synthetic dataset and should not be interpreted as causal relationships**.

## Project Structure

```text
E-Commerce Business Analysis Dashboard/
│
├── BUSINESS ANALYSIS.ipynb
├── Market Analysis proj.pbix
├── README.md
├── market analysis dashboard preview.png
├── orders (1).csv
└── products.csv
```

## Disclaimer

This is an independent portfolio project created using **synthetic data** to demonstrate business analysis, SQL, Python, Excel, and Power BI skills. It is not affiliated with or based on confidential data from Meesho.
