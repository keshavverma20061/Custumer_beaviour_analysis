# Customer Behavior Analysis Dashboard

## Overview
End-to-end data analysis project on customer shopping behavior — from data cleaning to business insights, using Python, MySQL, and Power BI.

## Problem Statement
Retail businesses need to understand customer purchasing patterns across categories, age groups, and subscription status to improve marketing targeting and increase revenue.

## Dataset
Customer Shopping Behavior dataset (~3.9K customers) — includes purchase amount, category, age group, subscription status, review ratings, and shipping preferences.

## Tools & Tech Used
- MySQL (data cleaning, querying)
- Python (Pandas for EDA)
- Power BI (interactive dashboard & visualization)

## Key Steps
1. Cleaned and structured raw data using MySQL (handled duplicates, nulls, formatting)
2. Performed Exploratory Data Analysis using Python/Pandas
3. Built an interactive Power BI dashboard with filters for subscription status, gender, category, and shipping type

## Key Insights
- Clothing is the top-performing category in both revenue and sales, followed by Accessories, Footwear, and Outerwear
- Young Adults generate the highest revenue and sales volume across all age groups
- Only 27% of customers are subscribed, but subscribers show different purchase patterns — opportunity to grow this segment
- Average purchase amount is ~$60 with an average review rating of 3.75/5

## Dashboard Preview
![Dashboard Overview](screenshot1.png)
![Dashboard Filtered - Subscribers](screenshot2.png)
![Dashboard Filtered - Clothing/Male](screenshot3.png)

## How to Run
1. Clone this repo
2. Import `customer_shopping_behavior.csv` and run SQL scripts in `/sql` folder for cleaning
3. Open `.pbix` file in Power BI to view the interactive dashboard
