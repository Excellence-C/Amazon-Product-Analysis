# Amazon-Product-Analysis
A full Excel dashboard built from raw e-commerce product reviews data
This project explores product review data from an online store (Amazon) and transforms it into a powerful Excel dashboard with insightful visualizations. It covers everything from data cleaning to business-driven metrics.

---

## Objective

Analyze e-commerce product reviews to discover patterns in:
- Discounts and pricing
- Customer ratings
- Product performance by category
- Revenue potential
  
---

## Tools Used

- Microsoft Excel (2019)
- Pivot Tables
- Conditional Formatting
- Excel Functions (`IF`, `RIGHT`, `MID`, `TEXTSPLIT`, `COUNTA`, etc.)
- Bar, Column, and Pie
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

## Data Cleaning Summary
• Removed spaces, typos, and irrelevant characters
• Standardized category and product names
• Extracted key values using formula logic (e.g., last word after pipe delimiter)
• Removed duplicates
• Ensured correct data types (numbers, text, general)
• Created helper columns: Discounted_Price, Revenue, Price_Bucket

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
