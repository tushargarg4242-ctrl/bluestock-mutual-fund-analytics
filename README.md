# Bluestock Mutual Fund Analytics Capstone

## Project Overview

This project was developed as part of the Bluestock Data Analytics Internship Capstone.

The goal of this project was to analyze the Indian mutual fund industry using real-world datasets and build an end-to-end analytics solution. The project covers data cleaning, database creation, SQL analysis, exploratory data analysis (EDA), and interactive dashboard development using Power BI.

Through this project, I explored mutual fund performance, investor behavior, SIP trends, and industry growth patterns to generate meaningful business insights.

---

## Objectives

The main objectives of this project were:

* Analyze the growth of the mutual fund industry.
* Understand Assets Under Management (AUM) trends across fund houses.
* Identify high-performing mutual fund schemes.
* Compare fund returns with risk metrics.
* Analyze investor transaction behavior.
* Study SIP contribution trends over time.
* Explore category-wise inflows and market movements.
* Build an interactive Power BI dashboard for decision-making.

---

## Tools & Technologies Used

* Python
* Pandas
* NumPy
* SQLite
* SQL
* Power BI
* Git & GitHub
* Jupyter Notebook

---

## Dataset Information

The project uses 10 datasets covering different areas of the mutual fund ecosystem.

| Dataset               | Description                    |
| --------------------- | ------------------------------ |
| Fund Master           | Scheme and fund details        |
| NAV History           | Historical NAV records         |
| AUM by Fund House     | Assets managed by AMCs         |
| Monthly SIP Inflows   | SIP contribution trends        |
| Category Inflows      | Category-wise inflow data      |
| Industry Folio Count  | Investor participation metrics |
| Scheme Performance    | Fund return and risk metrics   |
| Investor Transactions | Investor transaction records   |
| Portfolio Holdings    | Fund portfolio holdings        |
| Benchmark Indices     | Market benchmark data          |

---

## Project Workflow

### 1. Data Ingestion

* Loaded all datasets into Python using Pandas.
* Verified data quality and structure.

### 2. Data Cleaning

* Removed duplicate records.
* Handled missing values.
* Standardized date formats.
* Fixed inconsistent column types.
* Saved cleaned datasets for analysis.

### 3. Database Creation

* Created a SQLite database.
* Loaded all cleaned datasets into relational tables.
* Executed SQL queries for business analysis.

### 4. Exploratory Data Analysis

Performed EDA to understand:

* Industry AUM growth
* SIP trends
* Fund performance
* Investor behavior
* Category inflows
* Market trends

### 5. Dashboard Development

Created a multi-page Power BI dashboard to visualize insights and enable interactive exploration.

---

## Dashboard Pages

### Page 1 – Industry Overview

This page provides a high-level view of the mutual fund industry.

Key Metrics:

* Total AUM
* SIP Inflows
* Folio Count
* Active Schemes

Visuals:

* Industry AUM Trend
* AUM by Fund House
* Risk Category Distribution

---

### Page 2 – Fund Performance

This page focuses on evaluating mutual fund schemes.

Visuals:

* Risk vs Return Scatter Plot
* Fund Performance Scorecard
* NAV vs Benchmark Analysis

Filters:

* Fund House
* Category
* Plan Type

---

### Page 3 – Investor Analytics

This page analyzes investor participation and transaction behavior.

Visuals:

* Transaction Amount by State
* SIP vs Lumpsum vs Redemption Split
* Average SIP Amount by Age Group
* Monthly Transaction Trend

Filters:

* State
* Age Group
* City Tier

---

### Page 4 – SIP & Market Trends

This page explores market trends and SIP activity.

Visuals:

* SIP Inflows vs Nifty 50 Trend
* Category Inflow Heatmap
* Top Categories by Net Inflow
* SIP Growth Analysis

---

## Key Insights

Some important observations from the analysis:

* Industry AUM showed steady growth over the analysis period.
* A few major fund houses account for a significant share of total AUM.
* Equity-oriented funds generally offered higher returns but with higher risk.
* Investors in the 26–35 age group contributed the largest share of SIP investments.
* SIP inflows continued to grow despite market fluctuations.
* Certain categories consistently attracted higher net inflows compared to others.

---

## Project Structure

bluestock_mf_capstone/

* data/

  * raw/
  * processed/
  * db/

* notebooks/

  * 01_data_ingestion.ipynb
  * 02_data_cleaning.ipynb
  * 03_eda_analysis.ipynb
  * 04_performance_analytics.ipynb
  * 05_advanced_analytics.ipynb

* scripts/

  * etl_pipeline.py
  * compute_metrics.py
  * live_nav_fetch.py
  * recommender.py
  * run_pipeline.py

* sql/

  * schema.sql
  * queries.sql

* dashboard/

  * bluestock_mf_dashboard.pbix

* reports/

  * Final_Report.pdf
  * Bluestock_MF_Presentation.pptx

* README.md

---

## How to Run the Project

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run ETL Pipeline

```bash
python scripts/run_pipeline.py
```

### Open Dashboard

Open the Power BI file:

```text
dashboard/bluestock_mf_dashboard.pbix
```

using Power BI Desktop.

---

## Future Improvements

Given more time, the following enhancements could be added:

* Live NAV data integration through APIs
* Automated ETL scheduling
* Mutual fund recommendation system
* Portfolio optimization analysis
* Predictive forecasting models

---

## Conclusion

This project demonstrates a complete data analytics workflow, starting from raw mutual fund datasets and ending with an interactive business intelligence dashboard.

It combines Python, SQL, SQLite, and Power BI to generate actionable insights about mutual fund performance, investor behavior, and market trends.

---

**Author:** Tushar
**Project:** Bluestock Mutual Fund Analytics Capstone
