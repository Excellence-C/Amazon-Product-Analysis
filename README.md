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

[CLEAN DATA](https://github.com/user-attachments/assets/ce16cfd2-f346-453b-93b9-71194e7b686b)


## Exploratory Data Analysis
- Average Discount % by Category
    This chart compares the average discount percentage across different product categories. some categories recied higher discounts while others rarely do. in my analysis i discovered that Homeimprovement category got the hightest discount (58%). which helps me to understand that the products in this category are most price sensitive.
[1  AVERAGE DISCOUNT PERCENTAGE BY PRODUCT CATEGORY](https://github.com/user-attachments/assets/9ee0906c-68f2-4dbf-9804-957333d822dc)

- Total Reviews per Category
  This chart shows how many review each category recieved. from my analysis i have come to realise that categories such as Electronics have much higher customer engagement than  others which indicates frequently purchased items and in turn potentially drives hiher sales.
  [2 products per category](https://github.com/user-attachments/assets/85dae2cb-deea-47f7-9c2f-f6d096f181f5)

  
- Top Reviewed Products,
- Product ratings Distributions,
- Products with ≥50% Discount,
-  Total Revenue by Category,
-  Unique Products by Price ange,
-  Relationship between rating count and discount level
[VISUALISATION_DASHBOARD](https://github.com/user-attachments/assets/ae9d4fb5-62de-4144-9658-ade9645c177e)

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
