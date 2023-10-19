# SQL_film_analysis
Contains SQL-driven data analysis for Rockbuster movie rental. Our goal is to identify key factors that influence profitability and provide recommendations for optimizing revenue.


# Rockbuster Movie Rental Data Analysis

This repository contains SQL queries and data analysis for Rockbuster movie rental. The analysis is conducted on various aspects of the movie rental business to gain valuable insights and optimize operations.

## Table of Contents

- [Inventory Analysis](#inventory-analysis)
- [Revenue Analysis](#revenue-analysis)
- [Payment Analysis](#payment-analysis)
- [Customer Analysis](#customer-analysis)
- [Top Countries by Customer Count](#top-countries-by-customer-count)
- [Category Metrics](#category-metrics)
- [MLfilm1 - XGBoost ML Model](#mlfilm1-xgboost-ml-model)

### Inventory Analysis
- **Columns**: `film_id`, `title`, `name`, `rating`, `rental_rate`, `rental_count`, `total_revenue`, `inventory_count`, `inventory_cost`
- **Description**: This section focuses on analyzing inventory data, including film details, rental rates, and revenue.

### Revenue Analysis
- **Columns**: `film_id`, `title`, `rating`, `category`, `rental_rate`, `replacement_cost`, `total_revenue`, `rental_count`, `inventory_count`, `inventory_cost`, `gross_profit`
- **Description**: In this part, we dive into revenue analysis, encompassing rental, replacement costs, and gross profit.

### Payment Analysis
- **Columns**: `rental_date`, `return_date`, `payment_date`
- **Description**: The payment analysis section examines rental, return, and payment dates.

### Customer Analysis
- **Columns**: `postal_code`, `city`, `country`, `customer_id`, `customer`, `total_spend`
- **Description**: We analyze customer data, including spending habits and location information.

### Top Countries by Customer Count
- **Columns**: `country`, `customer_count`, `top_customer`, `amount`
- **Description**: This section ranks countries by customer count and identifies the top customers.

### Category Metrics
- **Columns**: `category`, `count`, `category_cost`, `total_revenue`, `Profit Factor`
- **Description**: Category metrics are explored to understand the cost, revenue, and profit factors by category.

### MLfilm1 - XGBoost ML Model
- **Columns**: `film_id`, `title`, `rating`, `category`, `rental_rate`, `replacement_cost`, `total_revenue`, `rental_count`, `inventory_count`, `inventory_cost`, `gross_profit`
- **Description**: MLfilm1 is a CSV dataset used for an XGBoost machine learning model. It contains film-related features and financial data.

Feel free to do your own analysis of Rockbuster movie rental data.
