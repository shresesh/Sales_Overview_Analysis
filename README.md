# Sales Overview Analysis Dashboard (Power BI)

## 📌 Project Overview
This project involves the development of a dynamic **Sales Overview Analysis Dashboard** using Power BI. The goal was to provide a comprehensive view of business performance across four key regions (Central, East, South, and West), allowing stakeholders to monitor Sales, Profit, and Quantity metrics through interactive visualizations and time-intelligence analysis.

## 🎯 Business Requirements
The dashboard was designed to meet the following key objectives:
* **Metric Tracking:** Display Sales, Profit, and Quantity based on a selected year filter.
* **Dynamic Interactivity:** Allow users to switch dynamically between the three core metrics (Sales, Profit, Quantity).
* **Historical Comparison:** Show Sales and other metrics for the previous year (PY) to facilitate performance benchmarking.
* **Geospatial Analysis:** Visualize sales distribution across states using a Bubble Map and a companion Bar Chart for detailed comparison.
* **Trend Analysis:** Include monthly sparklines with average lines to identify seasonal trends and performance against means.

## 🛠️ Key Features
* **Regional Deep Dive:** Dedicated sections for Central, East, South, and West regions featuring KPIs and monthly trend bars.
* **Executive Summary Grid:** A detailed table comparing Current Year (CY) vs. Previous Year (PY) and calculating Year-over-Year (YoY) growth for all metrics.
* **Interactive Slicers:** Year-based filtering to instantly update all regional and state-level data.

## 📊 Technical Stack
* **Tool:** Power BI Desktop
* **DAX (Data Analysis Expressions):** Used for creating complex measures such as:
    * `CY Sales`, `PY Sales`, and `YoY Sales %` 
    * `CY Profit`, `PY Profit`, and `YoY Profit %` 
    * `CY Qty`, `PY Qty`, and `YoY Qty %`
* **Data Modeling:** Establishing relationships between regional sales data and date tables for time-intelligence.

## 📈 Insights Captured
* Identification of high-volume states through bubble size correlation.
* Regional performance tracking against previous year benchmarks.
* Monthly volatility analysis using bar sparklines.

---
*This project serves as a showcase of end-to-end data analysis, from understanding business requirements to delivering an interactive BI solution.*
