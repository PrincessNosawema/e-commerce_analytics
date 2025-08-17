# Customer Segmentation, Sales Analysis & Lookalike Modeling  
*Data-driven insights to boost sales, optimize inventory, and personalize customer engagement.*

## Overview
This project analyzes an eCommerce dataset to uncover actionable insights, segment customers, and recommend similar buyers for targeted marketing. It integrates **customer segmentation**, **sales trend analysis**, and **lookalike modeling** to guide strategies for revenue growth and customer retention.

Using three datasets—`customers.csv`, `products.csv`, and `transactions.csv`—the following were done:
- Clusteing customers (K-Means, k=4) by spend, quantity, preferences, and demographics.
- Identiying top-selling products, seasonal trends, and regional performance.
- Appying cosine similarity to build a Lookalike Model for high-precision targeting.

## Key Insights
- High-value clusters show distinct category preferences and geographic patterns.
- A small subset of products drives the majority of revenue (Pareto principle).
- Seasonal peaks occur in January, May, July, and September.
- Lookalike modeling enables extending successful campaigns to similar customers.

## Requirements
```
numpy
pandas
scikit-learn
seaborn
matplotlib
```

## Outcome
Enables data-driven marketing, inventory optimization, and personalized engagement strategies based on customer behavior.