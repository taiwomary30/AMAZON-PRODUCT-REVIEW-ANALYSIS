# Project Topic: AMAZON PRODUCT REVIEW ANALYSIS

## Project Overview
This Data analysis project contains information scraped from Amazon product pages. It is an Excel-based analysis that focuses on product, category, pricing and customer review data to uncover insights around Customer feedback, discount trends, marketing strategies and revenue growth. Based on the project requirements, the goal is to analyze products performance and customer engagement using metrics like pricing, rating, discount, reviews and category insights, and end with to creating an interactive Excel dashboard for business decision making. 

### Data Source
The primary Data source used here is Amazon Data.xlsx and this is a real-life data source received as a project to work on from Incubator Hub. The dataset includes the following column: product_id, product_name, category, discounted_price, actual_price, discount_percentage, rating, rating_count, about_product, user_id, user_name, review_id, review_title, review_content, img_link and product_link.
### Tools used
- MS Excel (Data Cleaning & Preparation)
  -  For Data Collection
  -  For Data cleaning
  -  Calculated column
  -  Pivot tables
  -  Data visualization (Charts and Slicers)
### Data Cleaning and preparation
In the initial phase of the Data cleaning and preparation, we perform the following actions;
1. Data loading and Inspection
2. Handling missing variables by replacing with 0
3.	Removed duplicates and corrected data errors
4.	Standardized product_name by shortening the very long name into another column named Product name Extracted for the use of visualization. 
5.	Removed irrelevant columns such as about_product, user_id, user_name, review_id, review_title, review_content, img_link and product_link. 
6.	Split the category column into four different columns and a portion named main category was used for the visualization. 
7.	Addition of calculated column such as: Potential Revenue, Price Range Bucket, Combine Rating Score, 50% or More discount and Reviews Fewer than 1000.
   
### Key Metrics Analyzed
-	Average discount percentage by product category
-	Products listed under each category
-	Total number of reviews per category
-	Products with the highest average ratings
-	Average actual price vs the discounted price by category
-	Products that have discount of 50% or more
-	Distribution of product ratings
-	Total potential revenue by category
-	Number of unique products per price range bucket
-	Products with the highest number of reviews
-	Categories that have products with the highest discounts
-	Top 5 products in terms of rating and number of reviews combined.

### Dashboard features
- Interactive filter – Slice by Main category and Price range bucket
- Bar and column charts – To show their comparisons
- Click here to view Dashboard



