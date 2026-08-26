# 🍫 Chocolate Sales & Performance Analysis (2023–2024)

## 📌 Project Overview
This project delivers an interactive Tableau business intelligence dashboard analyzing retail sales data for a chocolate distributor from 2023 through 2024. The objective of the dashboard is to provide executive stakeholders and retail store managers with clear, actionable insights into revenue growth, product profitability, store-level performance, and customer loyalty trends.

---

## 🎯 Key Business Insights
The dashboard answers critical business questions to aid operational and marketing decision-making:

1. **Which product categories drive the highest profit margins?**
   * *Insight:* Premium dark chocolate lines generated the highest individual profit margins, while milk chocolate bars led overall sales volume.
2. **How are store locations performing relative to one another?**
   * *Insight:* Top-tier metro store locations accounted for over 40% of total revenue, highlighting key targets for priority inventory stocking.
3. **Does customer loyalty membership correlate with higher sales?**
   * *Insight:* Loyalty program members recorded a higher average units-per-transaction metric compared to non-loyalty shoppers.
4. **What are the seasonal revenue trends over 2023–2024?**
   * *Insight:* Consistent revenue spikes occurred during Q4 holiday seasons and mid-Q1 (Valentine's Day period).

---

## 📊 Dashboard Key Metrics (KPIs)

* **Total Revenue:** Sum of total sales generated across all stores ($)
* **Total Profit:** Net earnings after factoring in product cost of goods sold ($)
* **Profit Margin (%):** Ratio of net profit to total revenue (`Profit / Revenue`)
* **Total Sales Transactions:** Count of total sales transactions per customer

---

## 🛠️ Data Architecture & Tech Stack

* **Tooling:** Tableau Public, CSV
* **Data Source:** [**Kaggle Chocolate Sales Dataset**](https://www.kaggle.com/datasets/ssssws/chocolate-sales-dataset-2023-2024)
* **Data Model:** Star Schema
  * `sales.csv` (Central Fact Table)
  * `stores.csv` (Dimension: Location, City, Store Name)
  * `products.csv` (Dimension: Product Name, Brand, Category, Cost, Price)
  * `customers.csv` (Dimension: Loyalty Status, Demographics)

---

## 🚀 Interactive Dashboard Features
* **Global Date & Year Filters:** Slice sales data across monthly, quarterly, or yearly horizons.
* **Loyalty Member Segmenting:** Instantly filter views by `Loyalty Member (Yes/No)` to compare shopper behavior.
* **Dynamic Cross-Filtering:** Click any store location or product category to update all visuals on the dashboard in real time.
