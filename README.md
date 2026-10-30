# ⚡ Energy House: Customer Segmentation & Retention Analysis

> **Portfolio Case Study | BoyCode Africa Excel Project (August 2026)**

## 📌 Business Problem
Management at a fictional Nigerian e-commerce company needed clarity on customer buying patterns: **Who is buying, how frequently do they purchase, and which customer groups generate the highest long-term commercial value?** As the Customer Analytics Analyst for Energy House, the objective was to move beyond basic transaction tracking and deliver actionable customer segmentation and retention insights.

---

## 🗄️ Dataset Overview
* **Source:** `BoyCodeAfrica Ecommerce_Dataset.csv` (1,812 raw records)
* **Core Fields:** Orders, customers, regions, categories, revenue, profit, marketing channels, payment methods, delivery types, and customer ratings.
* **Note:** The dataset is synthetic and created for educational/portfolio purposes.

---

## 🧹 Data Preparation & Quality Control
Before conducting analysis, the raw dataset underwent rigorous data quality checks:
1. **Duplicate Removal:** Identified and removed **12 exact duplicate rows**, reducing the dataset to **1,800 clean transaction rows**.
2. **Missing Value Handling:** Handled missing region values ("Unspecified") and unrated transactions (excluded from rating averages using conditional functions).
3. **Data Type Standardization:** Configured date fields, currency values (`₦`), and numeric quantities properly for aggregation.

---

## 🛠️ Methodology & Excel Techniques Used
The analysis was executed entirely within **Microsoft Excel** using advanced modeling techniques:
* **Power Query:** Automated data extraction, transformation, and cleaning steps.
* **Aggregations & Financial Formulas:** Utilized `SUMIFS`, `COUNTIFS`, `AVERAGEIFS`, and `IFERROR` to build a customer-level summary sheet (569 unique customers).
* **Logical Rules:** Implemented `IFS` logic to classify customers into behavioral tiers:
  * *New:* 1 order.
  * *Returning:* 2 to 3 orders.
  * *Loyal:* 4+ orders.
* **PivotTables & Charts:** Generated multi-dimensional summaries analyzing regional repeat rates, acquisition channel profitability, and customer lifetime value.
* **Executive Dashboard:** Built interactive KPI cards and visual charts for executive stakeholders.

---

## 📊 Key Findings
1. **Loyal Customers Drive the Business:** Loyal customers make up 36.4% of the customer base (207 users) but generate **₦52.46M in revenue (55.2% share)** and **₦16.62M in gross profit**.
2. **Strong Repeat Behavior:** The business enjoys an **85.76% repeat purchase rate**, with returning and loyal buyers forming the backbone of steady cash flow.
3. **Channel Efficiency:** **WhatsApp** and **Google** acquisition channels yield the highest customer lifetime value, delivering average customer revenues exceeding **₦71,000+ per user** alongside high repeat frequencies (1.32 orders/customer).
4. **Regional Hotspots:** **Enugu** leads in repeat purchase order frequency (1.18 orders/customer), while **Edo** records the highest average order value per customer (₦71,579.65).

---

## 💡 Strategic Recommendations
1. **Fast-Track "Returning" Buyers:** Implement automated email/messaging incentive triggers after a customer's 2nd purchase to transition them into high-value "Loyal" tier status.
2. **Upsell Frequent Low-Spenders:** Create minimum order thresholds (e.g., free shipping above ₦30,000) to increase Average Order Value (AOV) for high-frequency, low-basket customers.
3. **Optimize Acquisition Spend:** Reallocate marketing budget toward WhatsApp and Google campaigns, which consistently attract higher-value, more loyal shoppers.

---

## ⚠️ Limitations & Analytical Caution
This analysis is strictly **descriptive and correlational**. Higher repeat purchase frequencies associated with channels like WhatsApp or Google reflect historical customer purchasing habits, but **do not mathematically prove direct causation** that marketing channels alone forced customers to reorder.

---

## 📂 Repository Contents
* `BoyCode_Africa_Energy_House_Analysis.xlsx`: The final completed Excel workbook containing Raw Data, Data Cleaning logs, Customer Summaries, PivotTables, and the Executive Dashboard.
