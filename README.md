# 📊 Ecommerce Sales Dashboard

An interactive **Power BI** dashboard that analyzes ecommerce sales performance across orders, profitability, product categories, and geography — built to turn raw transactional data into decision-ready insights.

![Dashboard Preview](salesdashboard.png)

---

## 📌 Project Overview

Ecommerce businesses generate large volumes of order-level data that's hard to act on in raw spreadsheet form. This project consolidates order and product-level transaction data into a single Power BI model and presents it through an interactive dashboard, allowing stakeholders to explore sales, profit, and quantity trends by category, sub-category, state, and time period — without touching the underlying data.

The dashboard is built on two linked datasets:

| File | Description |
|---|---|
| `Orders.csv` | Order-level records — order ID, order date, customer, and location (state/city) details |
| `Details.csv` | Line-item level records — category, sub-category, quantity, amount, profit, and payment mode per order |

The two tables are joined on **Order ID** inside Power BI's data model, enabling analysis at both the order and product-line level.

---

## 🔹 Features

- **Sales Analysis** — Total revenue trends and performance overview
- **Profit Analysis** — Profitability breakdown to identify high/low-margin segments
- **Quantity Analysis** — Units sold across products and time
- **State-wise Sales** — Geographic performance comparison across Indian states
- **Category-wise Sales** — Performance by product category and sub-category
- **Interactive Filters** — Slicers for dynamic, self-service exploration of the data

---

## 🛠 Tools & Techniques

- **Power BI Desktop** — Report design and dashboard visualization
- **Power Query** — Data cleaning, transformation, and merging of `Orders.csv` and `Details.csv`
- **DAX (Data Analysis Expressions)** — Calculated measures for sales, profit, and quantity KPIs
- **Data Modeling** — Relationship building between fact and dimension tables

---

## 📁 Repository Structure

```
Ecommerce-Sales-Dashboard/
├── ECOMMERCE SALES DASHBOARD.pbix   # Power BI report file
├── Orders.csv                        # Order-level dataset
├── Details.csv                       # Line-item level dataset
├── salesdashboard.png                # Dashboard preview image
└── README.md
```

---

## 🚀 How to Use

1. Clone or download this repository.
2. Open **`ECOMMERCE SALES DASHBOARD.pbix`** in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free to install).
3. If prompted, update the data source file paths to point to `Orders.csv` and `Details.csv` on your local machine, then click **Refresh**.
4. Use the slicers and filters on the report to explore sales, profit, and quantity by category, state, and time period.

---

## 📈 Key Insights Enabled

- Identify top and bottom-performing product categories by revenue and profit
- Spot high-growth vs. underperforming states for targeted regional strategy
- Track quantity sold alongside profit margin to flag high-volume, low-margin risk areas
- Filter dashboards dynamically for ad-hoc, self-service business analysis

---

## 👨‍💻 Author

**Ashmit Srivastava**
[LinkedIn](https://linkedin.com/in/ashmit-srivastava0208) · [GitHub](https://github.com/ashgithub0208)
