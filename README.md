# Olist E-Commerce Analysis: What Drives Low Customer Reviews?

Understanding what factors lead to negative customer experiences in e-commerce using real-world transactional data.

---

## Overview

This project analyzes customer reviews from the Brazilian Olist e-commerce dataset to identify the key drivers of customer dissatisfaction. The goal is to uncover actionable insights that businesses can use to improve customer experience and retention.

---

## Key Questions

- Do late deliveries lead to lower customer reviews?
- Are certain product categories more prone to poor ratings?
- Do some sellers or regions contribute more to delays?
- Is price or shipping cost a major factor in dissatisfaction?

---

## Key Insights

- **Late deliveries significantly increase negative reviews**  
  Orders that arrived late had over **4x higher rates of bad reviews** compared to on-time deliveries.

- **Longer delays lead to worse outcomes**  
  Customers experiencing longer delays were much more likely to leave poor ratings.

- **Certain product categories consistently underperform**  
  Some categories showed significantly lower average review scores, suggesting potential product or fulfillment issues.

- **Seller performance varies across regions**  
  Late delivery rates differ by seller location, indicating logistical inefficiencies in certain areas.

- **Price and shipping costs are not the main issue**  
  Customers with low reviews did not pay significantly more, suggesting that **service quality matters more than cost**.

---

## Methods

- Data cleaning and preprocessing using **Pandas**
- Feature engineering (e.g., delay calculation, late delivery indicator)
- Exploratory Data Analysis (EDA)
- Group-by aggregations to identify trends
- Data visualization using **Matplotlib** and **Seaborn**

---
