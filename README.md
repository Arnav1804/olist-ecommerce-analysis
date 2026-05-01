# 🛒 Olist E-Commerce Performance Analysis

![Python](https://img.shields.io/badge/Python-Pandas%20%7C%20Matplotlib%20%7C%20Seaborn-blue)
![PowerBI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow)
![Dataset](https://img.shields.io/badge/Dataset-Olist%20Brazilian%20E--Commerce-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## 📌 Project Overview
End-to-end data analytics project analyzing **96,000+ real e-commerce orders**
from Olist, Brazil's largest online marketplace. The project covers the full 
analytics workflow — from raw data cleaning to an interactive Power BI dashboard
— simulating a real business analytics role.

---

## 🎯 Business Problem
Olist's operations team needs to understand:
- Which product categories drive the most revenue?
- How has monthly sales trended over 2016–2018?
- What percentage of orders are delivered late?
- Is there a relationship between delivery delays and customer satisfaction?

---

## 📂 Project Structure
olist-ecommerce-analysis/
│
├── olist_cleaning.ipynb     # Data cleaning pipeline (4 tables merged)
├── olist_eda.ipynb          # EDA — 5 business questions answered
├── olist_cleaned.csv        # Final cleaned dataset (output)
├── Olist_Dashboard.pbix     # Power BI dashboard file
├── charts/                  # EDA visualizations exported from Python
│   ├── chart1_category_revenue.png
│   ├── chart2_monthly_trend.png
│   ├── chart3_delivery_delay.png
│   └── chart4_review_vs_delay.png
└── README.md
---

## 🛠️ Tools & Technologies
| Tool | Purpose |
|---|---|
| Python (Pandas) | Data cleaning, merging, feature engineering |
| Matplotlib & Seaborn | EDA visualizations |
| Power BI Desktop | Interactive dashboard |
| Jupyter Notebook | Development environment |

---

## 📊 Dashboard Preview
> Power BI Dashboard — Olist E-Commerce Performance

![Dashboard Preview](charts/dashboard_preview.png)

---

## 🔍 Key Insights
1. **Health & Beauty** and **Bed & Bath** are the top 2
   revenue-generating categories
2. Monthly revenue grew **3× from 2016 to 2018**
   showing strong business growth
3. **8.1% of orders** were delivered late —
   concentrated in specific categories
4. Orders with delivery delays of **10+ days**
   consistently received **1–2 star reviews**
   confirming the delay–satisfaction relationship
5. Most orders arrived **early**, indicating
   conservative delivery estimates

---

## 📈 KPIs Tracked
- Total Revenue
- Total Orders
- Average Review Score
- Late Delivery Rate

---

## ⚙️ How to Run This Project

**Python notebooks:**
```bash
# Install dependencies
pip install pandas matplotlib seaborn

# Open notebooks in VS Code or Jupyter
# Run olist_cleaning.ipynb first
# Then run olist_eda.ipynb
```

**Power BI Dashboard:**
- Download `Olist_Dashboard.pbix`
- Open with Power BI Desktop (free)
- All visuals load automatically

---

## 📁 Dataset Source
- **Source:** [Kaggle — Brazilian E-Commerce by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
- **Size:** 100,000+ orders across 9 tables
- **Period:** 2016–2018
- **Tables used:** orders, order items, products, reviews

---

## 👤 Author
Arnav Yadu
- LinkedIn: https://linkedin.com/in/arnav-yadu-5aa1442937
- GitHub: https://github.com/Arnav1804/
- Email: yaduarnav0411@gmai.com

---

## 📜 License
This project is open source and available under the MIT License.
