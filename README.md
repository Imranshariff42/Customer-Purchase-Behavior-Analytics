🛍️ **Customer Purchase Behavior Analysis**

📌 **Project Overview**

This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories.
The goal is to uncover insights into spending patterns, customer segments, product preferences, and subscription behavior to support better business decisions. 

Customer Shopping Behavior Anal…

📊 **Dataset Summary**

Dataset Size

Rows: 3,900

Columns: 18

Key Features

Customer Demographics: Age, Gender, Location, Subscription Status

Purchase Details: Item Purchased, Category, Purchase Amount, Season, Size, Color

Shopping Behavior: Discount Applied, Promo Code Used, Previous Purchases, Purchase Frequency, Review Rating, Shipping Type

Missing Data

37 missing values in the Review Rating column. 

Customer Shopping Behavior Anal…

🛠️ **Tools & Technologies**

Python (Pandas) → Data cleaning and preprocessing

PostgreSQL → SQL analysis and querying

Power BI → Data visualization and dashboard creation

🧹 **Data Preparation (Python)**

Key steps performed during preprocessing:

Data Loading using pandas

Initial Exploration using df.info() and df.describe()

Missing Value Handling for the review_rating column

Column Standardization to snake_case

Feature Engineering

age_group

purchase_frequency_days

Removed Redundant Column

promo_code_used

Database Integration

Loaded cleaned dataset into PostgreSQL

🧠 **Data Analysis (SQL)**

Business questions answered using SQL:

Revenue by Gender

High-Spending Discount Users

Top 5 Products by Rating

Shipping Type Comparison (Standard vs Express)

Subscribers vs Non-Subscribers Spending

Discount-Dependent Products

Customer Segmentation (New, Returning, Loyal)

Top 3 Products per Category

Repeat Buyers & Subscription Behavior

Revenue by Age Group 

Customer Shopping Behavior Anal…

📈 **Power BI Dashboard**

An interactive Power BI dashboard was created to visualize insights such as:

Total Customers

Average Purchase Amount

Average Product Rating

Revenue by Category

Customer Distribution by Subscription Status

Revenue by Age Group

This helps stakeholders quickly understand customer trends and spending patterns. 

Customer Shopping Behavior Anal…

💡 **Key Insights**

Loyal customers make up a large share of repeat purchases.

Certain products rely heavily on discount-driven sales.

Express shipping customers tend to spend slightly more.

Young adult customers contribute significantly to total revenue.

🚀 **Business Recommendations**

Boost Subscriptions → Offer exclusive benefits to members.

Customer Loyalty Programs → Reward repeat buyers.

Optimize Discount Strategy → Balance revenue growth and profit margin.

Promote Top-Rated Products in marketing campaigns.

Target High-Revenue Age Groups for better marketing ROI.

**Live Dashboard Link**

https://app.powerbi.com/view?r=eyJrIjoiOGMwNzlhNDItMzk2Ni00OWE4LThmNDYtNmZkYzYzMzIyY2EwIiwidCI6ImQ0NjZlNTA5LWQ4YWMtNGZmZC1iMTAxLWViN2QzYmQ1MzlhYSJ9


