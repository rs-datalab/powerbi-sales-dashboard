# Sales Performance Dashboard

## Overview

This project is an interactive Power BI dashboard that analyzes sales performance across products, customers, and regions. It provides a structured view of revenue trends, customer demographics, top-performing products, and key markets to support business decision-making.

The dashboard is designed to present business information clearly and make it easy to explore sales performance through filters and visual breakdowns.

## Objective

The goal of this project is to:

- track overall sales performance over time
- identify top-performing products and categories
- understand customer distribution across demographics
- analyze geographic revenue trends
- present insights in a clear, business-friendly dashboard

## Dataset

**Source:** AdventureWorks sample dataset

The dataset includes:

- sales transactions
- product details such as category and pricing
- customer demographic data such as age and gender
- geographic information such as country and region

## Tools

- Power BI
- DAX
- data modeling

## What This Project Does

This dashboard brings together several business-facing views of sales performance:

- displays total sales as a headline KPI
- visualizes sales trends over time
- highlights top-performing products by revenue
- shows sales concentration across product categories
- breaks down revenue and customer activity by age group
- compares revenue by gender
- compares revenue across top-performing countries
- supports interactive exploration through filters for year, month, and product category

## Highlights

The dashboard supports several high-level observations:

- revenue shows an overall upward trend with periodic fluctuations
- a small number of products contribute a significant share of total sales
- sales are heavily concentrated in one product category
- certain age groups contribute more strongly to revenue than others
- a small number of countries drive a large share of total sales

## Outputs

This project includes:

- `AdventureWorks Dashboard.pbix` — interactive Power BI dashboard
- `AdventureWorks Dashboard.pdf` — exported dashboard preview

The dashboard includes views for:

- total sales KPI
- sales trends over time
- top products by revenue
- product category breakdown
- customer demographics
- country-level revenue analysis

## Project Structure

```text
powerbi-sales-dashboard/
├── dashboard/
│   └── AdventureWorks Dashboard.pbix
├── screenshots/
│   └── AdventureWorks Dashboard.pdf
└── README.md
```

## How to Run

1. Open `AdventureWorks Dashboard.pbix` in Power BI Desktop.
2. Use the filters for:
   - Year
   - Month
   - Product Category
3. Interact with the visuals to explore different segments of the data.
4. Use the PDF preview if you want a quick static overview of the dashboard layout.

## Notes

- The dashboard is designed with a clear structure: **Overview → Trends → Breakdown → Details**
- Visuals were formatted to improve readability and consistency.
- DAX measures were used to support aggregation and filtering.
- This project focuses on dashboard design and business-facing reporting rather than advanced forecasting.

## Future Improvements

Potential next steps include:

- adding profit-based analysis if cost data is available
- including more advanced KPIs such as profit margin or customer lifetime value
- adding drill-through pages for product, region, or customer detail
- expanding the model to support more granular time analysis