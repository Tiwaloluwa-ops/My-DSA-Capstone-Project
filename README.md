# My-DSA-Capstone-Project
This is theRatings
project I submitted in my portfolio building journey, while taking my Data Analytics Class with Digital Skillup and The Incubator Hub

# Project Topic-Amazon Product Review Analysis

# Overview
As a Junior Data Analyst at RetailTech Insights, my objective is to nalyze Amazon product review data to generate actionable insights for e-commerce sellers regarding product performance, pricing strategies, and customer engagement

## Step-by-Step Analysis
### 1. Data Preparation
Before analysis, I would:
- Clean the data (remove duplicates, handle missing values)
- Ensure proper data types for each column
- Create necessary calculated columns:
  - Discount percentage, Discounted price, and Price range bucket
  - Transform the dataset into a table.
  ![TableCapture](https://github.com/user-attachments/assets/9aa24380-130b-4bfd-9360-09841760cd37)

 ### **1. Project Scope**  
- **Dataset:** 1,465 products with 16 fields (product details, pricing, discounts, ratings, and reviews).  
- **Tools Used:** Microsoft Excel (For clenaing, PivotTables, Formulas, Charts, Dashboard)  
- **Key Deliverables:**  
  - Data cleaning and preprocessing  
  - 14 analytical questions answered using PivotTables  
  - Interactive Excel dashboard summarizing insights
 
## Solution to Analysis Tasks
### 1. Average Discount Percentage by Product Category
 Represented as a pivot table
 ![adp](https://github.com/user-attachments/assets/aa4cb1d7-566c-4956-97c7-2c1dc4baa537)
- This will show which categories tend to have the highest/lower discounts

### 2. Number of Products per Category
- Pivot table
  ![number of products per category](https://github.com/user-attachments/assets/b23998d3-ece5-4e2a-b89d-10c42c92a961)

- Shows which categories have the most product offerings
### 3. Total Reviews per Category
Represented as a pibot table
- ![number of review per category](https://github.com/user-attachments/assets/1c003ef0-0b79-46f9-b372-990aa4511f13)
- This identifies which categories generate the most customer engagement

### 4. Products with Highest Average Ratings
Represented as a pivot table
![highest average rating](https://github.com/user-attachments/assets/6b1d3d37-baa9-4e46-a8f5-2a7e121e22c6)

### 5. Average Actual Price vs Discounted Price by Category
- Pivot table and Bar Chart
![avg price vs discountprice by category](https://github.com/user-attachments/assets/f073aecc-1bfa-41f3-b46c-dc64e17308cd)
- This shows price differentials across categories

### 6. Products with Highest Number of Reviews
- Sorting ofdataset by review count (descending)

![product highest number of reviews](https://github.com/user-attachments/assets/e9e7cad4-d872-4964-9c51-c50a562b2827)

This identifies the top products, likely popular or best-selling items, wit Electronics at the too of the list

### 7. Products with ≥50% Discount
- Create a filter on discount percentage column
- Count rows where discount ≥ 50%
- Can be shown by category using a pivot table

### 8. Distribution of Product Ratings
- Create bins for ratings (e.g., 1-1.9, 2-2.9, etc.)
- Pivot table with:
  - Rows: Rating bins
  - Values: Count of Products
- Shows rating distribution histogram
### 9. Total Potential Revenue by Category
- Create calculated column: Actual Price × Rating Count (as proxy for units sold)
- Pivot table with:
  - Rows: Category
  - Values: Sum of Potential Revenue
- Identifies most valuable categories
### 10. Unique Products per Price Range
- Create price buckets (<₹200, ₹200-₹500, >₹500)
- Pivot table with:
  - Rows: Price buckets
  - Values: Count of Products
- Shows product distribution across price points
### 11. Rating vs Discount Level
- Create scatter plot with:
  - X-axis: Discount Percentage
  - Y-axis: Average Rating
- Add trendline to show correlation
- Can also calculate correlation coefficient
### 12. Products with <1,000 Reviews
- Filter review count column for values <1000
- Count the number of products
- Can break down by category with pivot table
### 13. Categories with Highest Discounts
- Pivot table from Q1 sorted by average discount (descending)
- Shows which categories have most aggressive discounting
### 14. Top 5 Products by Rating & Reviews
- Create a composite score (e.g., Rating × log(Review Count))
- Rank products by this score
- Select top 5 products

## Dashboard Creation
**Dashboard Components:**
1. **Summary Metrics Card:**
   - Total products analyzed
   - Total reviews across all products
   - Average rating
 
2. **Category Performance Section:**
   - Bar chart: Number of products by category
   - Bar chart: Total reviews by category
   - Bar chart: Average discount by category
   - Tree map: Potential revenue by category
   - 
3. **Price Analysis Section:**
   - Pie chart: Product distribution by price bucket
   - Scatter plot: Price vs Rating (color by category)

4. **Top Products Section:**
   - Table: Top 5 products by composite score
   - Table: Products with highest discounts

5. **Rating Distribution:**
   - Histogram: Number of products by rating range

6. **Discount-Rating Relationship:**
   - Scatter plot with trendline: Discount % vs Rating

**Interactive Elements:**
- Category filter to drill down into specific categories
- Toggle between different metrics views
- Tooltips with detailed information

**Design Considerations:**
- Consistent color scheme by category
- Clear labeling and legends
- Mobile-responsive layout
- Dynamic titles that update with filters

This dashboard will provide RetailTech Insights' clients with actionable insights to optimize their Amazon product offerings, pricing strategies, and marketing approaches.


