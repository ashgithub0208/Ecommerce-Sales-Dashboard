# ðŸ“Š Ecommerce Sales Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Data%20Analysis%20Expressions-blue?style=for-the-badge)
![Power Query](https://img.shields.io/badge/Power%20Query-ETL-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=for-the-badge)

An interactive **Power BI** dashboard that turns raw ecommerce order data into decision-ready insights â€” covering sales, profitability, product performance, and regional trends across India.

<p align="center">
  <img src="salesdashboard.png" alt="Ecommerce Sales Dashboard Preview" width="850">
</p>

---

## ðŸ“‘ Table of Contents

- [Overview](#-overview)
- [Dashboard Preview](#-dashboard-preview)
- [Dataset](#-dataset)
- [Data Model](#-data-model)
- [Features](#-features)
- [Tools & Techniques](#-tools--techniques)
- [Repository Structure](#-repository-structure)
- [How to Use](#-how-to-use)
- [Key Insights Enabled](#-key-insights-enabled)
- [Future Improvements](#-future-improvements)
- [Author](#-author)

---

## ðŸ“Œ Overview

Ecommerce businesses generate large volumes of order-level data that's difficult to act on in raw spreadsheet form. This project consolidates order and product-level transaction data into a single Power BI data model and presents it through an interactive report â€” letting stakeholders explore **sales, profit, and quantity trends** by category, sub-category, state, and time period without touching the underlying data.

The dashboard answers questions such as:
- Which product categories and states drive the most revenue and profit?
- Where is volume high but margin low (risk areas)?
- How do sales trend over time, and where are the growth opportunities?

## ðŸ–¼ Dashboard Preview

<p align="center">
  <img src="salesdashboard.png" alt="Dashboard Screenshot" width="850">
</p>

## ðŸ—‚ Dataset

The dashboard is built on two linked datasets:

| File          | Grain              | Key Fields                                                                 |
| ------------- | ------------------- | --------------------------------------------------------------------------- |
| `Orders.csv`  | One row per order   | Order ID, Order Date, Customer, State/City                                  |
| `Details.csv` | One row per line item | Order ID, Category, Sub-Category, Quantity, Amount, Profit, Payment Mode  |

## ðŸ”— Data Model

`Orders.csv` and `Details.csv` are joined on **Order ID** inside Power BI's data model, enabling analysis at both the order level (location, customer, timing) and the product-line level (category, quantity, profit). A calendar/date table supports time-intelligence measures (YTD, trends, period comparisons).

## ðŸ”¹ Features

- **Sales Analysis** â€” Total revenue trends and overall performance overview
- **Profit Analysis** â€” Profitability breakdown to flag high- and low-margin segments
- **Quantity Analysis** â€” Units sold across products and time
- **State-wise Sales** â€” Geographic performance comparison across Indian states
- **Category-wise Sales** â€” Performance by product category and sub-category
- **Interactive Filters** â€” Slicers for dynamic, self-service data exploration

## ðŸ›  Tools & Techniques

- **Power BI Desktop** â€” Report design and dashboard visualization
- **Power Query** â€” Data cleaning, transformation, and merging of `Orders.csv` and `Details.csv`
- **DAX** â€” Calculated measures for sales, profit, and quantity KPIs
- **Data Modeling** â€” Relationship building between fact and dimension tables

## ðŸ“ Repository Structure

```
Ecommerce-Sales-Dashboard/
â”œâ”€â”€ ECOMMERCE SALES DASHBOARD.pbix   # Power BI report file
â”œâ”€â”€ Orders.csv                       # Order-level dataset
â”œâ”€â”€ Details.csv                      # Line-item level dataset
â”œâ”€â”€ salesdashboard.png               # Dashboard preview image
â””â”€â”€ README.md
```

## ðŸš€ How to Use

1. Clone or download this repository.
2. Open **`ECOMMERCE SALES DASHBOARD.pbix`** in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free to install).
3. If prompted, update the data source file paths to point to `Orders.csv` and `Details.csv` on your local machine, then click **Refresh**.
4. Use the slicers and filters on the report to explore sales, profit, and quantity by category, state, and time period.

## ðŸ“ˆ Key Insights Enabled

- Identify top- and bottom-performing product categories by revenue and profit
- Spot high-growth vs. underperforming states for targeted regional strategy
- Track quantity sold alongside profit margin to flag high-volume, low-margin risk areas
- Filter dashboards dynamically for ad-hoc, self-service business analysis

## ðŸ”® Future Improvements

- Add year-over-year and month-over-month comparison visuals
- Incorporate customer segmentation (RFM analysis)
- Publish to Power BI Service for web-based interactive access
- Automate data refresh via a scheduled gateway

## ðŸ‘¨â€ðŸ’» Author

**Ashmit Srivastava**
[LinkedIn](https://linkedin.com/in/ashmit-srivastava0208) Â· [GitHub](https://github.com/ashgithub0208) Â· [Email](mailto:ashmitsrivastava0208@gmail.com)
