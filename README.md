# 🚗 ABC Motors Limited — Car Sales Dashboard (2022–2023)

> An end-to-end sales analytics project built in Tableau, analysing 23,906 vehicle transactions across 7 dealer regions to uncover demand trends, brand performance, and actionable insights for FY2024 planning.

---

## 📊 Dashboard Preview

![ABC Motors Sales Dashboard](https://img.shields.io/badge/Tableau-Dashboard-blue?style=for-the-badge&logo=tableau&logoColor=white)
![Data Period](https://img.shields.io/badge/Data%20Period-2022–2023-darkblue?style=for-the-badge)
![Records](https://img.shields.io/badge/Records-23%2C906-green?style=for-the-badge)

> Open `042_Kanishk_Tableau.twbx` in Tableau Desktop (2022.1 or later) to explore the full interactive dashboard.

---

## 📁 Repository Structure

```
📦 abc-motors-sales-dashboard
 ┣ 📊 042_Kanishk_Tableau.twbx       # Packaged Tableau workbook (data + dashboard)
 ┣ 📄 README.md                       # This file
```

---

## 🏢 Business Context

**ABC Motors Limited** is a leading automobile retail chain operating across the United States. The management team commissioned this analysis to:

- Understand sales performance across FY2022 and FY2023
- Identify demand patterns by brand, body style, region, and customer segment
- Generate actionable insights to support inventory planning and growth strategy for the upcoming financial year

---

## 📈 Key Findings

| Metric | Value |
|---|---|
| Total Units Sold | 23,906 |
| Total Revenue | $671.5 Million |
| Average Sale Price | $28,090 |
| 2022 Units | 10,645 |
| 2023 Units | 13,261 |
| **YoY Unit Growth** | **+24.6%** |
| **YoY Revenue Growth** | **+23.6%** |
| Top Performing Region | Austin ($117.2M) |
| Best-Selling Brand | Chevrolet (1,819 units) |
| Most Popular Body Style | SUV (26.7%) |
| Peak Sales Month | November 2023 (1,465 units) |

---

## 📉 Dashboard Sections

The Tableau workbook contains **8 interactive worksheets** assembled into a single dashboard:

| # | Worksheet | Chart Type | Key Insight |
|---|---|---|---|
| 1 | Monthly Sales Trend | Area Chart | Consistent YoY growth; Q4 is peak season |
| 2 | Top 10 Brands | Horizontal Bar | Chevrolet, Dodge & Ford lead volume |
| 3 | Body Style Distribution | Donut Chart | SUVs dominate at 26.7% share |
| 4 | Revenue by Region | Bar Chart | Austin contributes 17.5% of total revenue |
| 5 | YoY Comparison | Dual Line | 2023 outperformed 2022 in 10 of 12 months |
| 6 | Colour Preference | Bar Chart | Pale White is preferred by 47.1% of buyers |
| 7 | Avg Price by Brand | Bar Chart | Lexus & Porsche lead on per-unit value |
| 8 | Transmission & Engine | Grouped Bar | Auto (52.6%) vs Manual (47.4%) near-parity |

---

## 🗂️ Dataset Overview

The dataset covers all vehicle sales transactions recorded by ABC Motors Limited from January 2022 to December 2023.

| Column | Type | Description |
|---|---|---|
| `Car_id` | String | Unique transaction identifier |
| `Date` | Date | Sale date (MM/DD/YYYY) |
| `Customer Name` | String | Buyer's first name |
| `Gender` | String | Customer gender |
| `Annual Income` | Integer | Customer's annual income ($) |
| `Dealer_Name` | String | Name of the selling dealership |
| `Company` | String | Vehicle brand/manufacturer |
| `Model` | String | Vehicle model name |
| `Engine` | String | Engine type (OHC / DOHC) |
| `Transmission` | String | Auto or Manual |
| `Color` | String | Vehicle colour |
| `Price ($)` | Integer | Sale price in USD |
| `Body Style` | String | SUV / Sedan / Hatchback / Passenger / Hardtop |
| `Dealer_Region` | String | Geographic region of the dealership |

**Data quality note:** One null value in `Customer Name`; `Engine` field cleaned via calculated field in Tableau (`DOHC` / `OHC`).

---

## 💡 Strategic Recommendations

Based on the analysis, the following actions are recommended for FY2024:

1. **Expand Austin & Janesville** — these two regions account for 33% of total revenue; invest in increased inventory allocation and staffing
2. **Grow female customer segment** — currently only 21.4% of buyers; targeted campaigns can unlock significant upside
3. **Prepare for Q4 surge** — stock up 6–8 weeks before October each year to avoid lost sales at peak demand
4. **Elevate premium brands** — Lexus, Porsche, and Jaguar generate higher revenue per unit; expand their availability in high-income regions
5. **Shift to 60% automatic inventory** — global consumer trend is moving away from manual transmission
6. **February promotions** — consistently the weakest month; targeted financing offers can drive volume in this period

---

## 🛠️ Tools & Technologies

![Tableau](https://img.shields.io/badge/Tableau-Desktop%202022.1+-blue?style=flat-square&logo=tableau)
![Excel](https://img.shields.io/badge/Data%20Source-XLSM%20%2F%20CSV-green?style=flat-square&logo=microsoft-excel)
![Python](https://img.shields.io/badge/EDA-Python%20%2F%20Pandas-yellow?style=flat-square&logo=python)

- **Tableau Desktop** — Dashboard design, calculated fields, interactive filters and actions
- **Python / Pandas** — Exploratory data analysis and data validation prior to Tableau import
- **Microsoft Excel / CSV** — Source data format

---

## 🚀 How to Open

1. Download or clone this repository
2. Open **Tableau Desktop** (version 2022.1 or later)
3. Double-click `042_Kanishk_Tableau.twbx` — the packaged workbook includes the data, so no separate CSV is needed
4. Navigate between the 8 worksheet tabs and the main dashboard tab
5. Use the **Year filter** (All / 2022 / 2023) and **Region filter** to interactively explore the data

> **Don't have Tableau Desktop?** Download a free 14-day trial at [tableau.com/trial](https://www.tableau.com/products/trial)

---

## 👤 Author

**Kanishk**
PGDM — Finance & Research/Business Analytics
MILE Education, Batch 2025–27

---

## 📄 License

This project is intended for academic and portfolio purposes.
Data source: ABC Motors Limited (academic case dataset).
