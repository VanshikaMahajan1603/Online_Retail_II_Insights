# Online_Retail_II_Insights
This Tableau project analyzes the Online Retail II (UCI) dataset to uncover sales trends, customer behavior, and market performance. Through interactive visualizations, it highlights revenue drivers, customer retention, seasonal patterns, and actionable insights for business growth.
Here’s your updated **README file** with the author section added:

---

# Online Retail II Insights Dashboard

## 📌 Problem Statement

Understanding customer behavior and sales performance is critical for online retail businesses. This project leverages the **Online Retail II (UCI)** dataset to uncover trends, revenue drivers, customer retention, and seasonal sales patterns using data cleaning and visualization techniques.

## 📂 Dataset

* **Source:** [Online Retail II (UCI) – Kaggle](https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci?resource=download)
* Covers transactional data from a UK-based online retail store.
* Includes invoices, stock codes, descriptions, quantities, invoice dates, prices, customer IDs, and countries.

## 🛠️ Tools & Software

* **Jupyter Notebook (Python):** Data cleaning & preprocessing.
* **Tableau (Intermediate level):** Interactive data visualizations & dashboard.

## 📊 Dashboard Name

**“Online Retail II Insights”**

## 🔎 Business Questions & Visualizations

1. **Sales Trend Over Time** → Line Chart with Moving Average
2. **Top Countries by Sales** → Horizontal Bar (Top 10)
3. **Top Products by Revenue** → Treemap
4. **Order Value Distribution** → Histogram
5. **New vs Returning Customers per Month** → Stacked Bar
6. **Monthly Customer Retention Rate** → Line Chart (Cohort Analysis)
7. **Spending vs Purchase Quantity** → Bubble Chart
8. **Revenue Share: New vs Returning Customers** → Donut Chart
9. **Cancelled Orders (Negative Quantities)** → Bar Chart by Country
10. **Seasonal Sales Spikes** → Heatmap (Month vs Year, Revenue by Color Intensity)

## 📝 Data Cleaning Decisions

* **Dropping Missing Customer ID**

  * Customer ID is essential for customer-level analysis (retention, churn, cohorts).
  * Rows without IDs distort customer insights and retention metrics.
  * ✅ *Decision:* Dropped rows with missing Customer ID.

* **Filling Missing Product Description**

  * StockCode uniquely identifies products even without descriptions.
  * Only \~0.4% of rows had missing descriptions.
  * ✅ *Decision:* Filled missing descriptions with `"Unknown"` to avoid data loss.

## 🚀 Outcome

The Tableau dashboard provides actionable insights into **sales trends, customer acquisition, retention, cancellations, and seasonal behaviors**, helping businesses optimize decision-making in e-commerce.

## 👩‍💻 Author

**Vanshika Mahajan**
