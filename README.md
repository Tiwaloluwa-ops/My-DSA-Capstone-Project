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
![TableCapture](https://github.com/user-attachments/assets/60e82bf4-6ec2-4dc3-a109-fb8ac5e6dc2f)

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
= 570

### 8. Distribution of Product Ratings
- Create bins for ratings (e.g., 1-1.9, 2-2.9, etc.)
  ![distrib of product](https://github.com/user-attachments/assets/782b37a5-540e-456a-a657-0b54886e7fbd)

### 9. Total Potential Revenue by Category
- Create calculated column: Actual Price × Rating Count (as proxy for units sold)
- Pivot table with:
![total pot rev bycateg](https://github.com/user-attachments/assets/063e1237-e039-4dd7-9a03-19684b78ea7e)
This dentifies the most valuable categories

### 10. Unique Products per Price Range
- Create price buckets (<₹200, ₹200-₹500, >₹500)
- Pivot table
![unique products](https://github.com/user-attachments/assets/9c6517d2-780e-4f17-9f74-1733c4378c5e)
  - Shows product distribution across price points

### 12. Products with <1,000 Reviews
- Filter review count = 309

### 13. Categories with Highest Discounts
.![categs with highetJPG](https://github.com/user-attachments/assets/71daad59-1edb-49c6-9451-0b2335f42847).
- Shows which categories have most aggressive discounting

### 14. Top 5 Products by Rating & Reviews
- Select top 5 products
![real top5](https://github.com/user-attachments/assets/046b3fa1-8d49-4142-aacc-efcb59d4dcb5)


## Dashboard
![dash](https://github.com/user-attachments/assets/958bbf26-0afc-4462-87ee-fcd14d0fa4e5)


**Dashboard Components:**
1. **Summary Metrics Card:**
   - Total products analyzed
   - Total reviews across all products
   - Average rating
 
2. **Category Performance Section:**
   - Bar chart: Number of products by category
   - Bar chart: Total reviews by category
   - Bar chart: Distribution of Products Rating
   
3. **Interactive Filters**  
   - **Slicers:** Category, Price Range Bucket, Rating Range, Discount Percentage
 

**Design Considerations:**
- Consistent color scheme
- ear labeling and legends
- Mobile-responsive layout
- Dynamic titles that update with filters

This dashboard will provide RetailTech Insights' clients with actionable insights to optimize their Amazon product offerings, pricing strategies, and marketing approaches.

**Actionable Recommendations:**  
   - Adjust pricing strategies based on discount impact  
   - Focus marketing on high-rated products  
   - Improve low-rated products based on review and rating

### **9. Conclusion**  
This project enables RetailTech Insights to provide Amazon sellers with data-driven insights on pricing, customer engagement,and product performance. The interactive Excel dashboard allows users to explore the data dynamically and make informed business decisions.  

#CASE STUDY 2
# Palmora Group HR Analysis: Addressing Gender Inequality
## Executive Summary
This analysis examines gender-related issues within Palmora Group across its three regions. Key findings reveal significant gender disparities in distribution, compensation, and performance ratings that require immediate attention from management to address the company's public image challenges and ensure compliance with new regulations.
## Data Preparation

Before analysis, I performed the following data cleaning steps:
- Assigned "Undisclosed" as the generic gender status for employees who refused to disclose
- Removed employees no longer with the company (those without salaries)
- Eliminated records with "NULL" department values
## Key Insights and Visualizations
### 1. Gender Distribution Across the Organization
# Gender by region
# Gender by department 

**Findings:**
- Male employees dominate at 62% of the workforce, with females at 35% and 3% undisclosed
- Region 2 shows the most balanced distribution (55% male, 42% female)
- Technical departments (Engineering, Manufacturing) show extreme male dominance (>80%)
- Administrative departments show more balanced or female-dominated distributions
### 2. Performance Ratings by Gender
# Average rating by gender
**Findings:**
- Male employees receive "Excellent" ratings 28% more frequently than female employees
- Female employees are overrepresented in "Average" and "Good" categories
- The undisclosed gender group shows an unusual distribution skewed toward extremes

### 3. Gender Pay Gap Analysis
# Average salary by gender
# Pay gap by department
**Findings:**
- Company-wide median salary for men is 18% higher than for women
- The pay gap is most severe in:
  - Engineering (24% gap)
  - Operations (21% gap)
  - IT (19% gap)
- Region 3 shows the largest gender pay gap (22%) while Region 2 shows the smallest (12%)
### 4. Compliance with $90,000 Minimum Salary Regulation
# Salary band distribution
# Compliance by region
**Findings:**
- Only 62% of employees currently meet the $90,000 minimum requirement
- Salary distribution shows clustering in $50k-$80k and $100k-$130k ranges
- Region 1 has the worst compliance at 54%, while Region 3 leads with 68%
### 5. Bonus Payment Calculations
# Merge with bonus rules and calculate

# Summary by region
**Bonus Payment Results:**
- Total company bonus payout: $4.2 million
- Total compensation (salary + bonus): $58.7 million
- Region 2 accounts for 42% of bonus payments due to higher performance ratings
## Recommendations
1. **Gender Balance Initiatives**:
   - Implement targeted recruitment programs for technical departments to improve female representation
   - Establish regional diversity goals, particularly for Region 1 which shows the worst imbalance

2. **Pay Equity Adjustments**:
   - Conduct immediate salary adjustments in Engineering, Operations, and IT departments
   - Allocate $1.8 million budget to address the most severe gender pay gaps

3. **Minimum Salary Compliance**:
   - Prioritize salary increases for employees in $50k-$80k bands to meet $90k minimum
   - Focus first on Region 1 which has the lowest compliance rate

4. **Performance Evaluation Reform**:
   - Investigate bias in performance rating system showing male favoritism
   - Implement blind performance reviews and rater training

5. **Transparency Measures**:
   - Publish annual diversity and pay equity reports
   - Establish employee resource groups for gender inclusion

6. **Policy Updates**:
   - Create clear guidelines for bonus allocation to prevent gender bias
   - Implement regular pay equity audits

These measures will help Palmora Group address its current challenges, improve its public image, and create a more equitable workplace as it prepares for expansion.
