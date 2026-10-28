# Project 03 — Customer Churn / Sales Trend Analysis

## Context
This project analyzes a reproducible simulated e-commerce order dataset to identify monthly revenue trends, category performance, and the revenue contribution of high-spending customers.

**Data note:** The dataset is generated for practice. Results are not real business performance and must be described as simulated.

## Questions
1. Which months generate the most and least revenue?
2. How does revenue change month over month?
3. Which product categories contribute the most revenue and orders?
4. What share of revenue comes from the top 10% of customers?

## Methods
- Data validation: shape, types, missing values, duplicates, descriptive statistics
- Feature engineering: month, weekday, quarter
- Monthly revenue aggregation and month-over-month percentage change
- Category groupby summaries and a month-by-category pivot table
- Customer spend ranking and top-decile revenue contribution
- Visualizations and numerical recommendations

## How to run
1. Open `Project_03_Sales_Trend_Analysis.ipynb` in Google Colab or Jupyter.
2. Install dependencies if needed: `pip install pandas numpy matplotlib seaborn jupyter`.
3. Run all cells from top to bottom.
4. Review the generated findings and recommendations before submitting.

## Files to submit
- `Project_03_Sales_Trend_Analysis.ipynb`
- This README
- The notebook's generated findings and written business brief (included in the notebook)

## Important limitations
The data is simulated and does not support claims about a real business. In a real analysis, validate the findings using authorized sales data and consider profit margins, refunds, discounts, inventory, and customer acquisition costs.
