# Customer Behavior Analysis using Python, PostgreSQL, SQL and Power BI

## Project Overview

This project presents an end-to-end Customer Behavior Analysis workflow using Python, PostgreSQL, SQL, and Power BI. The objective is to analyze customer shopping patterns, purchasing behavior, demographic trends, and product performance to generate actionable business insights.

The project covers the complete analytics lifecycle, including data cleaning, exploratory data analysis (EDA), SQL-based business analysis, and interactive dashboard development.

---

## Problem Statement

Businesses collect large amounts of customer transaction data but often struggle to extract meaningful insights from it.

This project aims to answer key business questions such as:

* Which customer segments contribute the most revenue?
* Which product categories perform best?
* How do age, gender, and subscription status influence purchasing behavior?
* What impact do discounts and promotions have on spending?
* Which products are most popular within each category?

---

## Dataset Information

### Dataset Summary

| Metric         | Value                               |
| -------------- | ----------------------------------- |
| Records        | 3,900                               |
| Features       | 18                                  |
| Missing Values | 37 (Review Rating)                  |
| Domain         | Retail / Customer Shopping Behavior |

### Key Attributes

#### Customer Information

* Customer ID
* Age
* Gender
* Location
* Subscription Status

#### Purchase Information

* Item Purchased
* Category
* Purchase Amount
* Season
* Size
* Color

#### Behavioral Information

* Review Rating
* Previous Purchases
* Frequency of Purchases
* Shipping Type
* Discount Applied

---

## Tech Stack

### Programming & Analysis

* Python
* Pandas
* NumPy
* Matplotlib

### Database

* PostgreSQL
* SQL

### Visualization

* Power BI

### Development Tools

* Jupyter Notebook
* VS Code
* pgAdmin

---

## Project Workflow

```text
Data Collection
      ↓
Data Cleaning
      ↓
Exploratory Data Analysis
      ↓
Feature Engineering
      ↓
PostgreSQL Integration
      ↓
SQL Business Analysis
      ↓
Power BI Dashboard
      ↓
Business Insights & Recommendations
```

---

## Data Cleaning & Feature Engineering

### Data Cleaning

* Imported dataset using Pandas.
* Performed exploratory analysis using `info()` and `describe()`.
* Identified missing values in the Review Rating column.
* Imputed missing values using category-wise median ratings.
* Standardized column names using snake_case naming convention.
* Checked for duplicate records and data consistency.

### Feature Engineering

* Created `age_group` for customer segmentation.
* Created `purchase_frequency_days` from purchase frequency categories.
* Prepared the dataset for SQL analysis and reporting.

---

## Exploratory Data Analysis (EDA)

### Key Metrics

* Total Revenue Generated: **$233,081**
* Average Purchase Amount: **$59.76**
* Total Customers Analyzed: **3,900**

### Key Findings

* Clothing generated the highest revenue among all product categories.
* Young Adult customers contributed the highest revenue.
* Female customers showed slightly higher average spending.
* Subscription status had minimal impact on spending behavior.
* Accessories and Clothing consistently outperformed other categories.

---

## SQL Business Analysis

The following business questions were answered using PostgreSQL:

### Customer Analysis

* Revenue by Gender
* Revenue by Age Group
* Subscribers vs Non-Subscribers
* Customer Segmentation

### Product Analysis

* Top Products by Rating
* Top 3 Products per Category
* Category-wise Revenue Analysis

### Business Performance Analysis

* Discount Impact Analysis
* Shipping Type Analysis
* Repeat Purchase Analysis

### Advanced SQL Concepts Used

* Common Table Expressions (CTEs)
* Window Functions
* ROW_NUMBER()
* Aggregate Functions
* Subqueries
* CASE Statements

---

## Power BI Dashboard

The interactive dashboard provides insights into:

* Customer Distribution
* Revenue by Category
* Revenue by Age Group
* Sales by Category
* Subscription Status Analysis
* Customer Behavior Metrics

### KPI Cards

* Total Customers
* Average Purchase Amount
* Average Review Rating

## Dashboard Preview

![Customer Behavior Dashboard](dashboard/dashboard_powerbi.png)

---

## Key Insights

* Clothing emerged as the highest revenue-generating category.
* Young Adult customers contributed the highest revenue.
* Non-subscribers accounted for the majority of customers.
* Subscription status showed limited impact on average spending.
* Accessories and Clothing categories consistently generated strong revenue.
* Customer spending remained relatively stable across demographic groups.

---

## Business Recommendations

### Increase Subscription Adoption

Offer personalized discounts and exclusive loyalty rewards to encourage subscriptions.

### Focus on High-Revenue Categories

Allocate more marketing resources to Clothing and Accessories.

### Improve Customer Retention

Implement loyalty programs for repeat customers.

### Target High-Value Customer Segments

Develop marketing campaigns for high-revenue age groups.

### Promote Top-Performing Products

Highlight best-selling products in advertising and recommendation systems.

---

## Project Structure

```text
customer-behavior-analysis
│
├── data
│   └── customer_shopping_trends.csv
│
├── notebooks
│   └── customer_behavior_analysis.ipynb
│
├── sql
│   └── business_queries.sql
│
├── dashboard
│   ├── Customer_Behavior_Dashboard.pbix
│   └── dashboard.png
│
├── report
│   └── Customer_Behavior_Report.pdf
│
└── README.md
```

---

## Future Improvements

* Customer Churn Prediction
* Customer Lifetime Value Analysis
* Recommendation Systems
* Sales Forecasting
* Advanced Customer Segmentation

---

## Author

**Manisha Saloi**

Data Analytics | SQL | Power BI | Python
