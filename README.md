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
- ### Average Discount % by Category
  
    This chart compares the average discount percentage across different product categories. some categories recied higher discounts while others rarely do. in my analysis i discovered that Homeimprovement category got the hightest discount (58%). which helps me to understand that the products in this category are most price sensitive.
  
[1  AVERAGE DISCOUNT PERCENTAGE BY PRODUCT CATEGORY](https://github.com/user-attachments/assets/9ee0906c-68f2-4dbf-9804-957333d822dc)

-  ### Total Reviews per Category

  This chart shows how many review each category recieved. from my analysis i have come to realise that categories such as Electronics have much higher customer engagement than  others which indicates frequently purchased items and in turn potentially drives hiher sales.
  
[2 products per category](https://github.com/user-attachments/assets/85dae2cb-deea-47f7-9c2f-f6d096f181f5)

- ### Top 10 Highest Average Rated Products

This chart identifies the top 10 products with the highest average customer ratings. These are standout performers in terms of quality or satisfaction, which could be prioritized for promotion or further product development.

- ### Average Actual Price vs Discounted Price by Category

This visual compares the average original prices of products to their discounted prices across categories. It highlights how much value is being offered to customers and which categories provide deeper price cuts.


- ### Top Reviewed Products

This table ranks products by the number of customer reviews received. The most-reviewed products likely represent best sellers or highly engaged items that resonate with customers.

-  ### Products with 50% Discount or More

This count reveals that **662** products received discounts of 50% or more. This may indicate clearance strategies or aggressive pricing used to boost sales.


- ### Product Rating Distribution

This bar chart breaks down how products are rated — showing how many products fall under each star rating (from 1 to 5). The  high count in the 4–5 range suggests good overall customer satisfaction.


- ### Total Potential Revenue by Category

Using available price data and review volume as a proxy for demand, this chart estimates potential revenue by category. *Electronics* and *Home & Kitchen* appear to generate the highest revenue opportunities.
  
[VISUALISATION_DASHBOARD](https://github.com/user-attachments/assets/ae9d4fb5-62de-4144-9658-ade9645c177e)

[PIVOT TABLES](https://github.com/user-attachments/assets/ca5a2aad-ad4d-4762-a3c8-c6255953f5d6)



## Dashboard Features
Fully interactive Excel dashboard

Insightful comparisons between pricing, reviews, and ratings

Structured for storytelling and business decision-making

## Outcome

This Excel dashboard offers actionable insights for Amazon's marketing team, pricing strategists, and product managers — all without a single line of code.  I was able to explore product listings, discount strategies, customer behavior, and category-level performance. 
Conclusively, I have gained experience in; Data wrangling (cleaning, formatting, transforming), Pivot Table analysis, Business-focused storytelling through visuals. This case study not only strengthens my data analysis skills but also demonstrates how spreadsheet tools can be used to drive decision-making in real-world business contexts — especially in e-commerce.

Here is my finished work file. 
[Amazon case study WORKED ON.xlsx](https://github.com/user-attachments/files/21068573/Amazon.case.study.WORKED.ON.xlsx)


Author

Excellence C.

Data Analyst | Chemist | Photographer

LinkedIn: https://www.linkedin.com/in/excellence-c-14b784267?trk=contact-info
