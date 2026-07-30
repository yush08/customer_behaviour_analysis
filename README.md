# Customer Shopping Behavior Analysis

## Overview

Customer Shopping Behavior Analysis is an end-to-end data analytics project that examines customer purchasing patterns using transactional retail data. The project combines **Python**, **PostgreSQL**, and **Power BI** to clean, analyze, and visualize customer shopping behavior, enabling data-driven business decisions.

The analysis focuses on customer demographics, spending habits, product performance, subscription behavior, discount usage, and purchasing trends.

---

## Project Objectives

- Clean and preprocess raw customer transaction data.
- Perform exploratory data analysis (EDA).
- Store cleaned data in PostgreSQL.
- Answer business questions using SQL.
- Build an interactive Power BI dashboard.
- Generate business insights and recommendations.

---

## Technology Stack

| Technology | Purpose |
|------------|---------|
| Python | Data Cleaning & Feature Engineering |
| Pandas | Data Manipulation |
| NumPy | Numerical Computation |
| PostgreSQL | Database Management |
| SQL | Business Analysis |
| Power BI | Dashboard & Visualization |
| Jupyter Notebook | Development Environment |

---

## Dataset Information

| Attribute | Value |
|-----------|-------|
| Total Records | 3,900 |
| Total Features | 18 |
| Dataset Type | Customer Shopping Transactions |
| Missing Values | 37 (Review Rating) |

### Dataset Features

- Customer ID
- Age
- Gender
- Location
- Subscription Status
- Item Purchased
- Category
- Purchase Amount
- Season
- Size
- Color
- Review Rating
- Shipping Type
- Discount Applied
- Previous Purchases
- Frequency of Purchases

---

## Project Workflow

```
Raw Dataset
      │
      ▼
Data Cleaning (Python)
      │
      ▼
Feature Engineering
      │
      ▼
PostgreSQL Database
      │
      ▼
SQL Business Analysis
      │
      ▼
Power BI Dashboard
      │
      ▼
Business Insights
```

---

## Data Preprocessing

### Data Exploration

- Loaded the dataset using Pandas.
- Inspected data types and structure.
- Generated descriptive statistics.
- Identified missing values and inconsistencies.

### Missing Value Treatment

The **Review Rating** column contained 37 missing values. Missing values were imputed using the **median review rating within each product category**, preserving category-specific trends.

### Data Cleaning

- Standardized column names using snake_case.
- Removed redundant attributes.
- Verified data consistency.
- Checked for duplicate records.

### Feature Engineering

Created additional features including:

- Age Group
- Purchase Frequency (Days)
- Customer Segment

---

## Database Integration

The cleaned dataset was imported into PostgreSQL to perform structured business analysis using SQL.

---

## SQL Business Analysis

The following business problems were addressed using SQL.

### Revenue Analysis

- Revenue by Gender
- Revenue by Age Group
- Subscriber vs Non-Subscriber Revenue

### Customer Analysis

- Customer Segmentation
- Repeat Buyers Analysis
- High-Spending Discount Customers

### Product Analysis

- Top Rated Products
- Top Products by Category
- Discount-Dependent Products

### Shopping Behavior Analysis

- Shipping Type Comparison
- Purchase Frequency Analysis
- Subscription Behavior

---

## SQL Concepts Used

- SELECT
- WHERE
- GROUP BY
- ORDER BY
- HAVING
- CASE Statements
- Aggregate Functions
- Common Table Expressions (CTEs)
- Window Functions
- Ranking Functions
- Joins
- Subqueries

---

## Power BI Dashboard

The dashboard provides an interactive overview of customer shopping behavior.

### Key Performance Indicators

- Total Revenue
- Total Customers
- Total Transactions
- Average Purchase Amount
- Subscriber Count

### Dashboard Visualizations

- Revenue by Gender
- Revenue by Age Group
- Revenue by Subscription Status
- Customer Segmentation
- Product Category Performance
- Top Rated Products
- Discount Analysis
- Shipping Type Analysis
- Purchase Frequency Distribution

### Interactive Filters

- Category
- Gender
- Age Group
- Subscription Status
- Shipping Type
- Season

---

## Key Insights

- Subscribers generated higher average purchase values than non-subsscribers.
- Loyal customers contributed a significant portion of total revenue.
- Express shipping customers tended to spend more per transaction.
- Certain products showed high dependence on discounts for sales.
- Middle-aged customers generated the highest overall revenue.
- Products with better customer ratings generally performed better in sales.

---

## Business Recommendations

### Increase Subscription Adoption

Introduce exclusive offers and loyalty benefits to encourage customer subscriptions.

### Improve Customer Retention

Implement loyalty programs to convert returning customers into loyal customers.

### Optimize Discount Strategy

Reduce unnecessary discounts while maintaining sales performance.

### Promote High-Performing Products

Prioritize highly rated and top-selling products in marketing campaigns.

### Personalized Marketing

Target high-value customer segments based on age group, purchase history, and subscription status.


---

## Future Enhancements

- Customer Lifetime Value (CLV) Prediction
- Sales Forecasting
- Customer Churn Prediction
- Product Recommendation System
- Customer Segmentation using Machine Learning
- Deployment using Power BI Service

---

## How to Run

### Clone the Repository

```bash
git clone https://github.com/your-username/Customer-Shopping-Behavior-Analysis.git
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Execute Data Cleaning

```bash
python src/preprocess.py
```

### Import Data into PostgreSQL

Execute the SQL scripts located in the `sql/` directory.

### Open Power BI Dashboard

Open the following file in Power BI Desktop:

```
dashboard/Customer_Shopping_Dashboard.pbix
```

---

## Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- SQL Query Optimization
- PostgreSQL
- Data Visualization
- Dashboard Development
- Business Intelligence
- ETL Pipeline Development
- Business Analytics

---

## Author

**Kumar Ayush**

**Technologies:** Python, SQL, PostgreSQL, Power BI

---
