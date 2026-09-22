# 📊 Retail Sales Analytics & Profitability Dashboard Suite (Tableau)

## 📌 Project Overview

This project presents an end-to-end Tableau Business Intelligence solution designed to analyze multi-channel retail performance. Divided into a 3-dashboard Tableau Story, this project translates raw transactional data into actionable commercial strategies—evaluating top-line sales growth, customer purchasing behavior, regional performance, and discount-driven profitability risks.

---

## 🏗️ Dashboard Architecture & Storyline

### 1️⃣ Marketing Performance Overview

* **Focus:** High-level commercial health and high-value revenue drivers.
* **KPIs Tracked:** Total Sales ($\sum \text{Sales}$), Total Profit ($\sum \text{Profit}$), and Profit Margin ($\frac{\sum \text{Profit}}{\sum \text{Sales}}$).


* **Core Visualizations:**
* **Monthly Sales & Profit Trend:** Dual-axis line chart tracking demand and margin alignment over time.
* **Sales by Customer Segment:** Horizontal bar chart evaluating Consumer, Corporate, and Home Office demand.
* **Sales by Category:** Bar chart comparing Furniture, Office Supplies, and Technology revenue.





### 2️⃣ Customer & Product Insights

* **Focus:** Value concentration, top-performing product groups, and basket size distribution.
* **KPIs Tracked:** Total Customers, Total Orders, and Average Order Value (AOV).
  
* **Core Visualizations:**
* **Customer Pareto Chart:** Dual-axis bar/line chart identifying the top customer percentile contributing to 80% of revenue.
* **Top Sub-Categories:** Ranked horizontal bar chart identifying high-volume product categories.
* **Order-Value Distribution:** Histogram binning transaction frequencies to evaluate basket sizes.





### 3️⃣ Regional & Discount Opportunities

* **Focus:** Spatial revenue mapping and promotional discount risk analysis.


* **Core Visualizations:**
* **Regional Sales Map:** Geographical symbol map visualizing state-level sales and profit.
* **Discount vs. Profit Scatter Plot:** Scatter plot analyzing individual orders to pinpoint loss-making high-discount sales.
* **Sales & Profit by Region:** Grouped bar chart identifying regional efficiency gaps.

---

## 🛠️ Technical Implementation & Features

* **Tooling:** Tableau Desktop / Tableau Public.
* **Calculated Fields:** Aggregated ratios (Profit Margin, AOV) and Pareto running totals.
* **Interactivity:** Global top-row filters, cross-dashboard filter actions, custom tooltips, and dynamic **Top-N parameters**.

---

## 💡 Key Strategic Recommendations

1. **Discount Governance:** Restructure promotional rules to eliminate loss-making orders identified in high discount brackets.
2. **Customer Retention:** Target the top Pareto customer tier with tailored loyalty programs to secure core revenue.
3. **Basket Optimization:** Utilize order-value binning insights to establish minimum-spend thresholds for free shipping.
