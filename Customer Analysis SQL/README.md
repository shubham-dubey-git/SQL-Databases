# CUSTOMER CHURN ANALYSIS

This project explores customer shopping behavior and insights related to customer retention and spending patterns. It includes data cleaning, feature engineering, and business-focused SQL analysis based on a retail purchase dataset.

# PROJECT OVERVIEW

* The goal of this project is to:

* Clean and prepare the raw customer dataset.

* Create new meaningful features for segmentation and churn-related insights.

* Load the processed data into a MySQL database.

* Use SQL queries to generate actionable business insights around revenue, discounts, shipping, and subscription behavior.


# DATASET SUMMARY

3,900 rows representing individual customer transactions.

Contains demographic, purchase, subscription, and behavioral information.

Key columns:

Age, Gender, Item Purchased, Category, Purchase Amount, Review Rating, Subscription Status, Previous Purchases, Discount Applied, Shipping Type, Frequency of Purchases.


# DATASET PROCESSING

* Handled missing values in review ratings using category-wise median.

* Converted column names to snake_case for consistency.

* Created additional features:

* Age Groups (Young Adult, Adult, Middle-Age, Senior)

* Purchase Frequency Days – mapped frequency text (Weekly, Monthly, Fortnightly, etc.) to numeric day values.

* Removed redundant column where promo code and discount indicators were identical.


# SQL BUSINESS QUESTIONS

several analytical queries were performed to uncover insights such as:

* Revenue comparison by gender.

* Customers using discounts who still spent above average.

* Top 5 products by average review rating.

* Effects of shipping type on spend amount.

* Revenue and spending comparison between subscribers vs non-subscribers.

* Products with the highest percentage of discounted purchases.

* These queries help identify customer segments with higher value and behavior patterns that can support churn and retention strategies.

# OUTCOME 

Subscribers spend more and generate higher total revenue compared to non-subscribers.

Express shipping tends to correlate with higher average purchase amounts.

Some products are heavily discount-driven despite high engagement.

Demographic and behavioral segmentation helps identify customers likely to churn.
