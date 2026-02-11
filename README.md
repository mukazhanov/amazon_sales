# 🛒 Amazon E-commerce Analytics (Portfolio)

## Overview
End-to-end analytics project on Amazon sales report data. The repo demonstrates:
- **Data cleaning & validation**
- **Business KPI analysis (Python)**
- **SQL analytics (SQLite)**
- **Insights & recommendations**

**Period in data:** 2022-03-31 → 2022-06-29  
**Rows:** 128,975 (line-level) | **Orders:** 120,378

---

## Key KPIs (computed)
- Orders: **120,378**
- Cancelled orders: **17,185** (**14.28%**)
- Revenue (gross): **78,592,678.30 INR**
- Revenue (net, excl. cancelled): **71,673,394.00 INR**
- Average order value (net): **694.56 INR**
- Top categories by revenue (net): **Set, kurta, Western Dress**

---

## Notebooks
1. **`ecommerce_data_cleaning.ipynb`** — how the raw CSV was cleaned and validated:
   - standardized columns, removed junk columns
   - converted types (dates / numeric)
   - created flags (`is_cancelled`, `has_promo`) and simple features (`month`, `weekday`)
   - quick data quality checks
   - exported cleaned dataset

2. **`ecommerce_analysis.ipynb`** — business analysis in Python:
   - KPI overview (orders, revenue, AOV, cancellation rate)
   - monthly trend
   - category performance
   - geography (top states)
   - promo / fulfilment impact
   - insights & recommendations

3. **`ecommerce_sql_analysis.ipynb`** — the same business questions solved in SQL (SQLite):
   - GROUP BY, CASE WHEN
   - CTE
   - window functions (RANK)

---

## Data
- Raw: `Amazon Sale Report.csv`
- Clean: `amazon_sales_clean.csv`

---

## Tools
- Python, pandas, matplotlib
- SQL (SQLite)
- Jupyter Notebook

---

## Author
**Adil Mukazhanov** — Junior Data Analyst (portfolio)
