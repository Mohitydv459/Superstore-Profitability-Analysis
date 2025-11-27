# Superstore-Profitability-Analysis
End-to-end retail analysis using Excel. Built an interactive dashboard to identify profit loss drivers, discount inefficiencies, and underperforming product categories.

# Superstore Sales & Profitability Analysis 📊

## 📌 Project Overview
This project involves a comprehensive analysis of the "Superstore" sales dataset to identify the root causes of stagnant profitability despite increasing revenue. By analyzing over **10,000 transaction records**, I built an interactive Excel dashboard that reveals high-risk product categories and inefficient discounting strategies.

## 💼 Business Problem
The Superstore finance team noted that while total revenue (Sales) is hitting record highs, the Net Profit Margin has not kept pace. The objective of this analysis was to answer:
> **"Which products and sales strategies are causing financial bleed, and how can we stop it?"**

## 📂 The Dataset
* **Source:** Superstore Sales Dataset (Kaggle/Public Domain)
* **Volume:** ~10,000 rows
* **Key Columns:** `Order Date`, `Region`, `Segment`, `Category`, `Sub-Category`, `Sales`, `Quantity`, `Discount`, `Profit`.

## 🛠️ Tools & Skills Used
* **Microsoft Excel** (Primary Tool)
* **Data Cleaning:** Handling missing values, standardizing text, fixing date formats.
* **Feature Engineering:** Calculated `Profit Margin %` and `Delivery Days`.
* **Pivot Tables:** Aggregating data for "Wall of Shame" analysis.
* **Data Visualization:** Bar charts, Line charts, and Conditional Formatting (Data Bars).
* **Interactive Dashboard:** Slicers for Region and Segment filtering.

## 🔎 Key Insights Identified

### 1. The "Tables" Loss Leader
Despite generating over **$206,000 in revenue**, the "Tables" sub-category is responsible for a **net loss of -$17,725**. It is the only major category that consistently loses money for the company.

### 2. The Discount Trap
My analysis revealed a strict threshold for profitability regarding discounts:
* **0% - 20% Discount:** Profitable.
* **> 20% Discount:** Transactions turn net negative.
* **Discovery:** Discounts of 30% or more result in an average loss of **-$45 per transaction**.

### 3. Regional Inefficiency
The **Central Region** is the primary contributor to the negative profit margins in the Furniture category, suggesting potential issues with shipping costs or aggressive pricing in that specific area.

## 📊 Dashboard Visuals

*(<img width="1586" height="575" alt="Screenshot 2025-11-27 174917" src="https://github.com/user-attachments/assets/24a15c53-9867-466f-af0d-db5a6177f6ec" />)*

> *Above: The interactive dashboard highlighting the "Profit Cliff" and Category Performance.*

## 💡 Recommendations
Based on the data, I recommend the following actions to stakeholders:
1.  **Pricing Policy Update:** Implement a hard cap on discounts at **20%** for all Furniture items. Discounts above this threshold require Manager approval.
2.  **Product Strategy:** Re-evaluate the pricing model for "Tables" to account for shipping/manufacturing costs, or consider discontinuing the lowest-margin SKUs in the Central Region.
3.  **Sales Focus:** Shift sales team KPI targets from "Volume Sold" to "Gross Profit" to discourage unprofitable high-volume deals.
