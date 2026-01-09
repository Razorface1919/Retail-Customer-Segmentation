# Retail-Customer-Segmentation
Analysis of UK Online Retail data using RFM Segmentation and Market Basket Analysis to improve retention.

# 🛒 E-Commerce Customer Segmentation & Market Basket Analysis

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Library](https://img.shields.io/badge/Library-Pandas%20|%20Sklearn-orange)
![Status](https://img.shields.io/badge/Status-Complete-green)

## 📌 Project Overview
Analyzed a dataset of **500,000+ transactions** from a UK-based online retailer. The goal was to transform raw sales data into actionable business intelligence using **RFM Analysis** and **Association Rule Mining**.

## 🔧 Techniques Used
* **Data Cleaning:** Handled missing values, removed duplicate entries, and filtered cancelled transactions.
* **Feature Engineering:** Created `TotalSales` and `RFM` metrics (Recency, Frequency, Monetary).
* **Customer Segmentation:** Segmented users into "Champions", "Loyal", and "At Risk" groups using Quantile Scoring.
* **Market Basket Analysis:** Used the **Apriori Algorithm** to find products frequently bought together.

## 📊 Key Results & Insights

### 1. Customer Segmentation (RFM)
The analysis revealed that the customer base follows the Pareto Principle (80/20 rule).
* **Champions (11%):** High spenders who buy recently.
* **At Risk (44%):** Large portion of customers who haven't purchased in >150 days.
* **Action:** Recommended a "Win-Back" email campaign targeting the "At Risk" group.

<img width="1278" height="683" alt="image" src="https://github.com/user-attachments/assets/0567f490-6630-485d-b339-1258f130bff4" />
<img width="1068" height="678" alt="image" src="https://github.com/user-attachments/assets/b75c819d-c6e1-44b4-a86c-7a59429f0f25" />
`![Customer Segments]`

### 2. Market Basket Analysis
We identified strong product associations (Lift > 10) to drive cross-selling strategies.
* **Key Discovery:** Customers purchasing specific color variants (e.g., Green Alarm Clock) are highly likely to purchase the alternative color (Red Alarm Clock).
* **Action:** Implement "Bundle & Save" offers on product pages.

<img width="1146" height="682" alt="image" src="https://github.com/user-attachments/assets/70630b56-6b3f-46fa-99cd-ea1f2ae0eb5d" />
`![Market Basket Analysis]`

## 🚀 How to Run the Code
1. Clone the repo:
   ```bash
   git clone [https://github.com/Razorface1919/Retail-Analytics.git](https://github.com/Razorface1919/Retail-Analytics.git)
