🛍️ Customer Shopping Behavior Analysis

📌Project overview 
This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories. The objective is to understand customer spending patterns, product preferences, customer segments, subscription behavior, and revenue contribution across different customer groups.
The project follows an end-to-end data analytics workflow:
Data Cleaning → Exploratory Data Analysis → SQL Analysis → Power BI Dashboard → Business Insights

🎯Business problem 
A retail business wants to better understand how customers shop and what factors influence purchasing behavior.
- The analysis focuses on identifying:
- Customer spending patterns
- Popular product categories and products
- Subscription behavior
- Customer loyalty and repeat purchasing
- Discount usage
- Revenue contribution by gender and age group
- Shipping preferences
- Product ratings

These insights can help the business improve customer retention, subscription adoption, marketing strategies, product positioning, and sales performance.

📊Key questions 
The project answers the following business questions:
- Which gender generates more revenue?
- Which customers use discounts but still have high spending?
- What are the top 5 products based on average review rating?
- How does average purchase amount differ between Standard and Express shipping?
- How do subscribers compare with non-subscribers in terms of spending and revenue?
- Which products have the highest percentage of discounted purchases?
- How can customers be segmented into New, Returning, and Loyal customers?
- What are the top 3 most purchased products in each category?
- Are customers with more than 5 purchases more likely to subscribe?
- Which age groups contribute the most revenue?

🛠️Tools used 
Python – Data cleaning, preprocessing, feature engineering, and exploratory data analysis
Pandas – Data manipulation and analysis
Jupyter Notebook - Data Cleaning
PostgreSQL – SQL-based business analysis
Power BI – Interactive dashboard and data visualization

🧹Data cleaning 
The dataset contains 3,900 rows and 18 columns, covering customer demographics, purchase details, and shopping behavior.
The following data preparation steps were performed using Python:
- Loaded the dataset using Pandas
- Inspected the dataset structure using info() and describe()
- Checked for missing and null values
- Handled 37 missing Review Rating values using the median rating of the corresponding product category
- Standardized column names 
- Created an age_group feature by categorizing customer ages
- Created a purchase_frequency_days feature
- Checked the relationship between discount_applied and promo_code_used
- Removed the redundant promo_code_used column
- Performed data consistency checks
- Loaded the cleaned dataset into PostgreSQL for SQL analysis

🔎Analysis 
Python was used to explore customer demographics, purchasing behavior, product categories, ratings, discounts, subscriptions, and other variables.
PostgreSQL SQL Analysis: 
SQL queries were used to perform business-focused analysis, including:
- Revenue analysis by gender
- High-spending discount users
- Top-rated products
- Shipping type comparison
- Subscriber vs. non-subscriber analysis
- Discount-dependent products
- Customer segmentation
- Top products by category
- Repeat buyers and subscription behavior
- Revenue analysis by age group

📉 Dashboard
An interactive Customer Behaviour Dashboard was created in Power BI to present the key findings in an easy-to-understand format.

Dashboard KPIs:
- Number of Customers:     3.9K
- Average Purchase Amount: $59.76
- Average Review Rating:   3.75
- 
Dashboard Visuals:
- Revenue by Category
- Sales by Category
- Customer Subscription Status
- Sales by Age Group
- Revenue by Age Group
- Subscription Status filter
- Gender filter
- Category filter

The dashboard allows users to interactively explore customer behavior across different genders, categories, subscription statuses, and age groups.

💡Key Insights
- The dataset contains approximately 3.9K customers/purchases, providing a useful view of retail customer behavior.
- Non-subscribers represent the majority of customers (73%), while subscribers account for 27%, indicating an opportunity to increase subscription adoption.
- Clothing generates the highest sales and revenue among the analyzed categories.
- Young Adults contribute strongly to both sales and revenue, making them an important customer segment.
- Customer purchasing behavior can be differentiated into New, Returning, and Loyal segments based on purchase history.
- Discount usage can encourage purchases, but discount-dependent products should be monitored to maintain healthy margins.
- Repeat customers with higher purchase frequency can be targeted with loyalty and subscription programs.
- Top-rated and best-selling products can be highlighted in marketing campaigns.

✅Conclusion
The analysis provides actionable insights into customer spending, product performance, subscription behavior, customer loyalty, discounts, and age-based revenue patterns. The findings can help a retail business improve customer retention, subscription adoption, targeted marketing, product promotion, and overall sales strategy.
