🛍️ **Customer Purchase Behavior Analysis**

📌 **Project Overview**

This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories.
The goal is to uncover insights into spending patterns, customer segments, product preferences, and subscription behavior to support better business decisions. 

📊 **Dataset Summary**

Dataset Size

Rows: 3,900

Columns: 18

**Key Features**

1- Customer Demographics: Age, Gender, Location, Subscription Status

2- Purchase Details: Item Purchased, Category, Purchase Amount, Season, Size, Color

3- Shopping Behavior: Discount Applied, Promo Code Used, Previous Purchases, Purchase Frequency, Review Rating, Shipping Type

4- Missing Data

5- 37 missing values in the Review Rating column. 

🛠️ **Tools & Technologies**

→ Python (Pandas) → Data cleaning and preprocessing

→ PostgreSQL → SQL analysis and querying

→ Power BI → Data visualization and dashboard creation

🧹 **Data Preparation (Python)**

Key steps performed during preprocessing:

• Data Loading using pandas

• Initial Exploration using df.info() and df.describe()

• Missing Value Handling for the review_rating column

• Column Standardization to snake_case

• Removed Redundant Column

• Loaded cleaned dataset into PostgreSQL

**Feature Engineering**

• age_group

• purchase_frequency_days

🧠 **Data Analysis (SQL)**

1- Business questions answered using SQL:

2- Revenue by Gender

3- High-Spending Discount Users

4- Top 5 Products by Rating

5- Shipping Type Comparison (Standard vs Express)

6- Subscribers vs Non-Subscribers Spending

7- Discount-Dependent Products

8- Customer Segmentation (New, Returning, Loyal)

9- Top 3 Products per Category

10- Repeat Buyers & Subscription Behavior

11- Revenue by Age Group 


📈 **Power BI Dashboard**

An interactive Power BI dashboard was created to visualize insights such as:

• Total Customers

• Average Purchase Amount

• Average Product Rating

• Revenue by Category

• Customer Distribution by Subscription Status

• Revenue by Age Group

This helps stakeholders quickly understand customer trends and spending patterns. 

💡 **Key Insights**

— Loyal customers make up a large share of repeat purchases.

— Certain products rely heavily on discount-driven sales.

— Express shipping customers tend to spend slightly more.

— Young adult customers contribute significantly to total revenue.

🚀 **Business Recommendations**

1- Boost Subscriptions → Offer exclusive benefits to members.

2- Customer Loyalty Programs → Reward repeat buyers.

3- Optimize Discount Strategy → Balance revenue growth and profit margin.

4- Promote Top-Rated Products in marketing campaigns.

5- Target High-Revenue Age Groups for better marketing ROI.

**Live Dashboard Link**

https://app.powerbi.com/view?r=eyJrIjoiOGMwNzlhNDItMzk2Ni00OWE4LThmNDYtNmZkYzYzMzIyY2EwIiwidCI6ImQ0NjZlNTA5LWQ4YWMtNGZmZC1iMTAxLWViN2QzYmQ1MzlhYSJ9


