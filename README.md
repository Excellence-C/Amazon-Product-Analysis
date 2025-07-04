# Amazon-Product-Analysis
A full Excel dashboard built from raw e-commerce product reviews data
This project explores product review data from an online store (Amazon) and transforms it into a powerful Excel dashboard with insightful visualizations. It covers everything from data cleaning to business-driven metrics.

---

## Data Source
- Microsoft Excel (2019) [download here](https://www.microsoft.com/en-ng)

## Objective

Analyze e-commerce product reviews to discover patterns in:
- Discounts and pricing
- Customer ratings
- Product performance by category
- Revenue potential
  
---

## Tools Used
- Ms Excel
    - for data cleaning
    - Data manipulation
- Pivot Tables
     - For data Summarization ( totals, averages, counts).
- Conditional Formatting
    - Using Excel Functions (`IF`, `RIGHT`, `MID`, `TEXTSPLIT`, `COUNTA`, etc.)
- Slicers for interactivity

---

## Project Structure

```
Amazon-product-analysis/
├── README.md
├── Excel_Dashboard.xlsx
├── data/
│   └── cleaned_product_reviews.xlsx
├── visuals/
│   ├── avg_discount_by_category.png
│   ├── top_reviewed_products.png
│   ├── rating_vs_discount_scatter.png
│   └── ...
└── documentation/
    └── data_cleaning_notes.md
```

## Data Cleaning 
In the initial phase of the data cleaning and preparations, i performed the following actions;
   - Removed empty spaces, typos, and irrelevant characters
   - Standardized category and product names Using the function `PROPER`, and then proceded in making all my first rows headers
   - Extracted key values using formula logic (e.g., last word after pipe delimiter) and `mid and find` functions
   - Removed duplicates
   - Ensured correct data types (numbers, text, general)
   - Created calculated columns: Discounted_Price, Revenue, Price_Bucket

## Key Visualizations
- Average Discount % by Category
- Total Reviews per Category
- Top Reviewed Products
- Average Rating per Category
- Ratings Distributions
- Rating Count vs Discount % (Scatter Plot)
- Products with ≥50% Discount
- Top 5 Products by Rating
- Total Revenue by Category
- Unique Products by Price Bucket
- Actual vs Discounted Price by Category
- Product with Highest Discount

## Dashboard Features
Fully interactive Excel dashboard

Insightful comparisons between pricing, reviews, and ratings

Structured for storytelling and business decision-making

## Outcome
This project showcases Excel's full potential for data storytelling. The dashboard offers actionable insights for Amazon's marketing team, pricing strategists, and product managers — all without a single line of code.

Author

Excellence C.

Data Analyst | Chemist | Photographer

LinkedIn: https://www.linkedin.com/in/excellence-c-14b784267?trk=contact-info
