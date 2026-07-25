# Ecommerce Sales Dashboard — Power BI

An interactive Power BI dashboard built on ecommerce sales data, providing a consolidated view of revenue, profit, order volume, and customer/category-level trends to support data-driven business decisions.

## Overview

This dashboard consolidates transactional ecommerce data into a single-page interactive report, enabling stakeholders to monitor sales performance, identify top-performing categories and customers, and analyze payment behavior — all with real-time filtering by state and quarter.

## Key Features

- **KPI Summary Cards** — At-a-glance metrics for Sum of Amount, Sum of Profit, Sum of Quantity, and Sum of AOV (Average Order Value), custom-formatted for clean, minimal-decimal readability.
- **Interactive Slicers** — Quarter-based button slicer (Qtr 1–Qtr 4) and a searchable State dropdown slicer, allowing users to filter the entire dashboard by time period and geography.
- **Profit by Month** — A waterfall-style bar chart highlighting monthly profit/loss trends across the year, with positive and negative months visually distinguished.
- **Category & Sub-Category Breakdown** — Donut chart of quantity sold by product category (Clothing, Electronics, Furniture) and a horizontal bar chart ranking profit by sub-category (Printers, Bookcases, Saree, Accessories, Tables).
- **Payment Mode Analysis** — Donut chart visualizing order distribution across COD, UPI, Debit Card, Credit Card, and EMI to understand customer payment preferences.
- **Geographic & Customer Insights** — Bar charts showing sum of amount by state (Maharashtra, Madhya Pradesh, Uttar Pradesh, Delhi) and by top customers, surfacing regional and individual sales concentration.
- **Consistent Custom Theming** — Dark navy/purple color scheme applied uniformly across all visuals, including matched card backgrounds, borders, and rounded corners for a cohesive, presentation-ready look.

## Tools & Techniques

- **Power BI Desktop** — Data modeling, DAX measures, and report design
- **DAX** — Custom measures for AOV, profit aggregation, and formatted display units (K-notation with controlled decimal precision)
- **Data Formatting** — Cleaned and structured raw ecommerce transaction data into report-ready fields (Category, Sub-Category, PaymentMode, State, CustomerName, Order Date hierarchy)
- **UI/UX Design** — Manual visual formatting (background fills, borders, transparency, card callout formatting) to achieve a consistent custom theme beyond default Power BI styling

## Dashboard Preview

The report includes:
- 4 KPI cards (Amount, Profit, Quantity, AOV)
- 1 time-series profit chart
- 2 donut charts (Category, Payment Mode)
- 2 ranked bar charts (Sub-Category profit, Customer-wise amount)
- 1 state-wise bar chart
- 2 slicers (Quarter, State)

## Key Insights Surfaced

- Clothing accounts for 63% of quantity sold, making it the dominant category by volume
- COD remains the most preferred payment mode (44%), followed by UPI (21%)
- Profit shows clear seasonality, with November and April emerging as peak months and mid-year months (May–June) dipping into losses
- Maharashtra leads in sales amount among the states tracked

---

*This project demonstrates end-to-end BI dashboard development — from raw data structuring to interactive report design — applicable to business/data analyst and consulting-oriented roles.*
