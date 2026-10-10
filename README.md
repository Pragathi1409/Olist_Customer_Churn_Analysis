# Olist_Customer_Churn_Analysis
End-to-end e-commerce data analytics portfolio project featuring Python (Pandas/ETL), Power BI dashboard design, and customer churn &amp; retention modeling using the Olist dataset.
This project analyzes customer churn and retention patterns for **Olist** (Brazil's largest e-commerce marketplace). By integrating Python data engineering with an interactive Power BI dashboard, this project identifies critical driver metrics (such as delivery delays and review scores) behind customer drop-offs.
## 🎯 Key Metrics & Highlights
* **Total Customers Analyzed:** 96,000+ Unique Buyers
* **Customer Churn Rate:** ~97% (Single-purchase buyers)
* **Core Insight:** Customers experiencing delivery delays (>3 days past estimate) show a significantly higher churn likelihood and drop average review scores below 2.0.

---

## 🛠️ Data Pipeline & Architecture
1. **Python / Pandas (Gold ETL Pipeline):**
   * Processed raw transactional logs into customer-level aggregated features (`total_spent`, `recency_days`, `total_delayed_orders`).
   * Engineered binary retention target flags (`is_repeat_buyer`).
2. **Power BI Modeling & DAX:**
   * Built custom dynamic measures for Churn Rate, AOV, and Total Customer Volume.
   * Designed an executive card banner, geographic state breakdown, and interactive slicers.

---

## 📂 Repository Structure
* `notebooks/`: Jupyter Notebook containing data preprocessing & feature engineering.
* `dashboard/`: Power BI `.pbix` report file and visual screenshots.
* `data/`: Exported Gold-level feature dataset (`olist_customer_churn.xlsx`).

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/olist-customer-churn-analytics.git](https://github.com/YOUR_USERNAME/olist-customer-churn-analytics.git)
