# 🛒 Retail Inventory Optimization & Customer Segmentation

An end-to-end data analysis project using a real-world UK online retail dataset (541,909 transactions).
Applies RFM analysis and K-Means clustering to segment customers, and identifies 
inventory patterns to reduce overstock and stockouts.

## 📊 Key Findings
- Identified 4 distinct customer segments (Champions, At-Risk, Lost, New Customers)
- Top 20% of customers drive ~65% of revenue (Pareto analysis)
- Flagged 12% of SKUs as dead stock candidates

## 🛠️ Tech Stack
Python · Pandas · Scikit-learn · Matplotlib · Seaborn · Jupyter Notebook

## 📁 Dataset
[UCI Online Retail Dataset](https://archive.ics.uci.edu/ml/datasets/Online+Retail) — 
real transactions from a UK-based e-commerce store (2010–2011)

## 🚀 How to Run
```bash
git clone https://github.com/arshaimran/Inventory-Optimisation-and-Customer-Segmentation
jupyter notebook DMproject.ipynb
```

## 📌 Methods Used
- Data cleaning & outlier removal
- RFM (Recency, Frequency, Monetary) scoring
- K-Means clustering with elbow method
- Product-level sales trend analysis
