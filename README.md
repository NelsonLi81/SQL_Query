# SQL_Query
Create a fodlre for the project

## DVD Rental Database SQL Queries
## Introduction
This repository contains a set of SQL queries designed to extract valuable insights from the DVD Rental Database. 
The database includes various tables related to a DVD rental business, such as customers, films, rentals, payments, 
categories, and more. These SQL queries aim to answer specific business questions and help make data-driven decisions 
to improve the DVD rental business's performance and customer satisfaction.

## Getting Started
Before running the SQL queries, ensure you have set up a PostgreSQL database and imported the DVD Rental sample database. 
You can use tools like pgAdmin or command-line tools to run these queries against the database.

## Queries
1. Customer Rental Behavior
- SQL: customer_rental_behavior.sql
- Description: This query provides insights into customer rental behavior, including the average rental frequency, total spending, and average rental duration. It helps in understanding customer preferences and rental patterns.

2. Customer Spending and Status by District
- SQL: customer_spending_by_district.sql
- Description: This query explores how customer transactions, spending, and customer status vary across different districts in the DVD rental business. It helps in understanding customer demographics and tailoring services accordingly.

3. Store Transaction Trends
- SQL: store_transaction_trends.sql
- Description: This query analyzes the number of transactions and total payment amount for each store over the months, helping to monitor store performance and identify seasonal trends.

4. Most Popular Film Genres
- SQL: most_popular_genres.sql
- Description: This query lists the most popular film genres among customers based on the number of times DVDs from each genre are rented. It helps in understanding customer preferences for film genres and guides DVD selection decisions.

5. Top Categories by Active Customer Spending
- SQL: top_categories_active_customers.sql
- Description: This query identifies the categories of DVDs most commonly rented by active customers who have an average spending greater than 4. It assists in tailoring inventory and marketing efforts to high-spending customers.

6. Most Rented DVDs in Each Category
- SQL: most_rented_in_each_category.sql
- Description: This query lists the most rented DVDs in each film category, helping to align inventory with customer preferences.

7. DVDs with High Rental Frequency and Low Return Rates
- SQL: high_rental_low_return.sql
- Description: This query identifies film categories with DVDs that are most frequently rented but have the lowest return rates. It provides insights into customer satisfaction with specific DVDs.

8. Popular Time Slots for DVD Rentals
- SQL: popular_time_slots.sql
- Description: This query identifies the most popular time slots for DVD rentals throughout the year, aiding in staffing and inventory management.

9. DVD Inventory Turnover
- SQL: dvd_inventory_turnover.sql
- Description: This query calculates the inventory turnover rate for each film category, identifying categories with the highest turnover rates. It helps in optimizing inventory management and restocking strategies.

10. Top Actors/Actresses in Popular DVDs
- SQL: top_actors_in_popular_dvds.sql
- Description: This query lists actors/actresses with the most appearances in the top-rented DVDs, helping with content acquisition and promotion decisions.

## Conclusion

The data analysis plays a crucial role in driving informed decisions and optimizing various aspects of the DVD rental business. By utilizing SQL queries to analyze rental data, we gained valuable insights into customer behavior, preferences, and store performance. Here's a summary of the key findings:

1. Understanding Customer Behavior: Analyzing rental frequency, spending, and rental duration helps us understand customer preferences and demands. This information guides personalized marketing strategies and improves customer satisfaction and loyalty.

2. Customer Segmentation: Analyzing customer transactions and spending across different districts enables targeted marketing and tailored services. Segmentation helps maximize customer retention and acquisition.

3. Store Performance Analysis: Tracking store transactions and payment amounts helps monitor performance and optimize operations. Data-driven insights allow the allocation of resources to improve customer experiences across all locations.

4. Popular Film Genres: Identifying popular film genres among customers informs inventory curation. Aligning DVD selection with customer preferences enhances satisfaction and increases rental rates.

5. Catering to High-Spending Customers: Identifying top spending categories for active customers allows prioritizing inventory and promotions. Meeting high-spending customers' preferences enhances customer lifetime value.

6. Matching DVDs with Customer Preferences: Analyzing the most rented DVDs in each category ensures the inventory aligns with customer preferences, leading to higher rental rates and satisfaction.

7. Customer Satisfaction: Identifying DVDs with high rental frequency and low return rates indicates customer satisfaction. Promoting these DVDs increases engagement and encourages repeat rentals.

8. Optimizing Inventory Management: Analyzing DVD inventory turnover helps optimize stock levels and minimize holding costs. Focusing on high-turnover DVDs improves inventory management efficiency.

9. Promoting Top Actors/Actresses: Identifying frequently featured actors/actresses in top-rented DVDs guides marketing and content acquisition. Promoting films with popular actors/actresses attracts more customers and increases rentals.

10. Timing DVD Rentals: Analyzing popular time slots for DVD rentals optimizes staff scheduling and inventory management. Providing better customer service during peak rental times improves rental revenues.



## Dataset
- [Link](https://www.postgresqltutorial.com/postgresql-getting-started/postgresql-sample-database/) or [Download Here](https://github.com/gordonkwokkwok/DVD-Rental-PostgreSQL-Project/tree/main/dataset)




