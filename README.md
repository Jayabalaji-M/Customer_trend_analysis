# Customer_trend_analysis
End-to-end Customer Trende Analysis project using SQL, MySQL, Python (Pandas, NumPy), and Power BI. Includes data cleaning, transformation, exploratory analysis, and interactive dashboard development to uncover purchasing patterns, customer segmentation, revenue trends, and actionable business insights.

Customer Trend Analysis

End-to-End Data Analytics Project using Python (Pandas), MySQL & Power BI

Overview

This project analyzes customer shopping trends using 3,900 transactional records across multiple product categories.

The objective was to identify purchasing patterns, customer segments, product performance, and revenue trends to support data-driven business decisions.

The project demonstrates a complete analytics workflow — from data cleaning to dashboard reporting.

Dataset

Rows: 3,900

Columns: 18

Features Include:

Customer demographics (Age, Gender, Location, Subscription Status)

Purchase details (Item, Category, Purchase Amount, Season)

Behavioral metrics (Discount Applied, Previous Purchases, Frequency, Review Rating, Shipping Type)

Missing Data: 37 missing values in review_rating column (handled during preprocessing).

Tools & Technologies

Python (Pandas) – Data loading, cleaning, preprocessing

MySQL – Business queries and analytical reporting

Power BI – Interactive dashboard development

Jupyter Notebook – Analysis environment

Excel – Supporting validation

Data Preparation using Python (Pandas)

Loaded dataset into Pandas DataFrame

Checked structure using .info() and .describe()

Handled missing values in review ratings

Renamed columns for consistency (snake_case)

Created new features:

age_group

purchase_frequency_days

Removed redundant columns after validation

Data Analysis using MySQL

Performed SQL analysis to answer business questions such as:

Revenue by Gender

Top 5 Products by Average Rating

Subscriber vs Non-Subscriber Spending

Shipping Type Comparison

Revenue by Age Group

Customer Segmentation (New, Returning, Loyal)

Discount impact on purchasing behavior

Power BI Dashboard

Developed an interactive dashboard featuring:

Total Revenue KPI

Average Rating KPI

Product Performance Analysis

Customer Segmentation

Revenue by Age Group

Discount & Shipping Insights

Includes slicers and filters for dynamic data exploration.

Key Insights

Certain age groups contribute higher revenue

Subscription status influences spending behavior

Discount usage impacts purchase frequency

Loyal customers drive repeat sales

High-rated products do not always generate the highest revenue

How to Run

Clone this repository

Open the Jupyter Notebook to review data cleaning steps

Import the dataset into MySQL and run SQL queries

Open the Power BI .pbix file to explore the dashboard

Skills Demonstrated

Data Cleaning & Transformation (Pandas)
SQL Aggregation & Business Analysis
Dashboard Development
Business Insight Generation
End-to-End Analytics Workflow
