# ☕ Coffee Shop Sales Dashboard

An end-to-end data analysis project exploring sales performance for a coffee shop, built entirely in **Excel**

---

## 📌 Project Overview

This project analyzes transactional sales data from a coffee shop to uncover patterns in customer behavior, product performance, and revenue drivers. The goal was to move beyond simple order counts and understand **where the actual revenue comes from** — by time, by product, by day, and by payment method — then present the findings in a clean, professional, one-page dashboard.

---

## 🗂️ Repository Contents

| File | Description |
|---|---|
| `index.csv` | Original, unmodified raw dataset |
| `Orders Coffe Shop.xlsx` | Full Excel workbook: Power Pivot data model, DAX measures, pivot table analysis, and the final dashboard |

---

## 🛠️ Tools & Techniques

- **Excel Power Pivot** — data modeling and DAX measures
- **DAX** — custom measures (Total Orders, Total Sales, Average Order Value, Money by Coffee Type, Money by Month)
- **PivotTables** — multi-dimensional breakdowns (by month, day, shift, coffee type, payment method)
- **Excel Charts** (Line, Bar, Doughnut) — visual analysis
- **Shapes linked to live cells** — KPI cards that update automatically with the data model

---

## 📊 Key Metrics

| Metric | Value |
|---|---|
| Total Orders | 1,313 |
| Total Sales | $42,627.58 |
| Average Order Value | $32.47 |
| Coffee Types Sold | 8 |

---

## 🔍 Key Insights

- **Revenue leader ≠ order-count leader.** *Americano With Milk* has the highest order count (319), but *Latte* generates more total revenue ($10,289.12 vs. $10,025.86) despite fewer orders — indicating a higher price point per cup.
- **May was the strongest month**, both in orders (267) and revenue ($9,063.42), while **August was the weakest** (180 orders, $5,118.70).
- **Mornings drive the most traffic**, accounting for the largest share of orders across all shifts (~39%).
- **Card is the dominant payment method** at 93.2% of all transactions, with cash used in only 6.8% of orders.
- **Tuesday is the busiest day of the week** (206 orders), while Sunday is the quietest (172 orders).

---

## 📈 Dashboard Preview

The dashboard consolidates all key metrics into a single view: 4 KPI cards at the top (Total Orders, Total Sales, Average Order Value, Coffee Items Sold), followed by monthly trends (orders and revenue), product performance by both order volume and revenue, orders by day of week, and breakdowns by shift and payment method.

*(Add a screenshot of the dashboard here, e.g. `![alt text](image-1.png)`)*

---

## 🚀 How to Use

1. Download `Orders Coffe Shop.xlsx`
2. Open in Excel (Power Pivot add-in required to view/edit the data model)
3. Explore the **PivotTable Fields** panel to see how each measure was built
4. View the **Dashboard** sheet for the final visual summary

---
