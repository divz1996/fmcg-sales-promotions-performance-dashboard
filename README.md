
# FMCG Sales & Promotions Performance Dashboard (Power BI + SQL + Python)

> Status: Work in progress (data exploration and model design phase)

## 1. Project Overview

This project analyzes synthetic Fast Moving Consumer Goods (FMCG) daily sales data from 2022–2024 to build a leadership-ready Sales & Promotions Performance dashboard in Power BI, supported by SQL and Python for data preparation and quality checks.[web:1][web:4]

The scenario: you support a regional commercial team in an FMCG company selling multiple product categories across regions and channels. Leadership needs ongoing visibility into:

- Multi-year sales and growth versus last year.
- Promotion effectiveness by product, category, and region.
- Regional and channel performance and mix.
- Product/SKU winners and underperformers.

This repository is designed as a portfolio-grade, end-to-end analytics project that mirrors real FMCG / retail reporting work (data → model → measures → dashboard → documentation).[web:3][web:7]

## 2. Dataset

Source: FMCG Daily Sales Data (2022–2024) on Kaggle (synthetic daily-level FMCG sales across three consecutive years).[web:1][web:4]

To reproduce the analysis, download the dataset directly from Kaggle and place it under `data/raw/` (the raw file is not committed to this repo).

## 3. Planned Structure

```text
data/
  raw/                # Kaggle dataset (local only)
  processed/          # Model-ready CSVs

sql/
  # SQL scripts for creating tables, cleaning data, and building Fact/Dim tables

notebooks/
  # Jupyter / Colab notebooks for EDA and data quality checks

pbix/
  # Power BI .pbix file

docs/
  data_dictionary.md
  model_diagram.png
  report_screenshots/
```

## 4. Next Steps (WIP)

- Explore the Kaggle dataset and finalize the FactSales grain.
- Define dimension attributes and complete the data dictionary.
- Build the SQL / Power Query data layer and export processed tables.
- Create the Power BI model, DAX measures, and four report pages:
  - Executive Overview
  - Sales & Promotions
  - Regions & Channels
  - Products / SKUs
EOF
