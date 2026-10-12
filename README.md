# ShopEase Orders: End-to-End Exploratory Data Analysis

An end-to-end data analysis project in Python that cleans a messy e-commerce orders dataset and turns it into business insights and recommendations.

## Business Problem
ShopEase's raw orders data contains quality issues (duplicates, inconsistent labels, mixed formats and invalid values) that make direct analysis unreliable. This project cleans the data and answers eight business questions about revenue, products, order fulfilment, discounts, delivery, ratings and customers.

## Dataset
- **Source:** [ShopEase Raw Orders Dataset on Kaggle](https://www.kaggle.com/datasets/mernahabib/shopease-raw-orders-dataset) (synthetic data)
- **Raw size:** 10,020 rows × 16 columns
- **Cleaned size:** 10,000 unique orders × 23 columns (covering January to June 2026)

## Tools
Python, pandas, NumPy, Matplotlib, Seaborn, SciPy, Jupyter Notebook

## Workflow
1. Business understanding and dataset inspection
2. Data cleaning (text, formats, invalid values, missing values, duplicates, outliers, new features)
3. Exploratory data analysis and KPIs
4. Statistical analysis (descriptive statistics, hypothesis tests, correlation)
5. Visualization
6. Insights, recommendations and conclusion

## Key Findings
- **Realized revenue is 26.12 million** (delivered orders only), about 4.34 million a month, with no clear growth or decline.
- **78% of orders are delivered, 12% are pending and about 10% are cancelled**, with the same split across cities, categories and payment methods.
- **Revenue is highly concentrated:** Electronics earns 52% of revenue and the Laptop alone 42%, from only 4% of orders.
- **Discounts cost 1.86 million (6.6% of pre-discount value)** without increasing the quantity per order.
- **Delivery takes about 3.5 days everywhere**, and ratings (average 3.96) are unrelated to delivery time or discount.
- A typical order is worth about **1,600 (median)**, while the mean of 3,306 is inflated by a few expensive orders.
- Gender and age do not change what customers buy or spend.

## Recommendations (summary)
- Closely monitor high-value Electronics and Laptop orders.
- Investigate the general causes of cancelled and pending orders, and record a cancellation reason.
- Test the discount policy on a trial basis before changing it widely.
- Capture the payment method at order time and validate data at entry.

0
## Limitations
The data is synthetic, covers six months, and has no cost, profit or payment information. Customer IDs are inconsistent, so customer-level conclusions were not drawn. See the notebook for the full list.
