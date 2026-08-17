# 📊 Power BI Analytics & Business Intelligence Portfolio[cite: 1]

A curated collection of end-to-end **Power BI** dashboards, automated reporting solutions, DAX calculation libraries, and dimensional data models designed to transform raw business data into actionable visual insights[cite: 1].

[![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![DAX](https://img.shields.io/badge/DAX-Data%20Analysis%20Expressions-0078D4?style=for-the-badge&logo=microsoftexcel&logoColor=white)](https://learn.microsoft.com/en-us/dax/)
[![Power Query](https://img.shields.io/badge/ETL-Power%20Query%20M-FF5722?style=for-the-badge&logo=databricks&logoColor=white)](https://powerquery.microsoft.com/)
[![Star Schema](https://img.shields.io/badge/Data%20Model-Star%20Schema-9C27B0?style=for-the-badge&logo=diagram&logoColor=white)](#-data-architecture--star-schema)
[![Status](https://img.shields.io/badge/Project%20Status-Complete%20%E2%9C%94%EF%B8%8F-00E676?style=for-the-badge&logo=checkmarx&logoColor=black)](#)

<br/>

---

## 📑 Table of Contents[cite: 1]

- [Overview](#-overview)[cite: 1]
- [Repository Structure](#-repository-structure)[cite: 1]
- [Featured Dashboards & Projects](#-featured-dashboards--projects)[cite: 1]
  - [1. Executive Sales & Revenue Analytics](#1-executive-sales--revenue-analytics)[cite: 1]
  - [2. Customer Retention & Churn Analysis](#2-customer-retention--churn-analysis)[cite: 1]
  - [3. Supply Chain & Inventory Optimization](#3-supply-chain--inventory-optimization)[cite: 1]
  - [4. Financial Performance & Variance Tracking](#4-financial-performance--variance-tracking)[cite: 1]
- [Data Architecture & Modeling](#-data-architecture--modeling)[cite: 1]
- [DAX Formula Library](#-dax-formula-library)[cite: 1]
- [Power Query (M) ETL Transformations](#-power-query-m-etl-transformations)[cite: 1]
- [How to Use This Repository](#-how-to-use-this-repository)[cite: 1]
- [Tools & Tech Stack](#-tools--tech-stack)[cite: 1]
- [Connect & Feedback](#-connect--feedback)[cite: 1]

---

## 🌟 Overview[cite: 1]

This repository demonstrates practical implementations of Business Intelligence best practices[cite: 1]:
- **Star Schema Dimensional Modeling** (Fact & Dimension design, bridge tables, surrogate keys)[cite: 1].
- **Advanced DAX Calculations** (Time Intelligence, dynamic ranking, matrix decomposition, What-If scenario modeling)[cite: 1].
- **Performance Optimization** (DAX Studio analysis, VertiPaq engine optimization, aggregation management)[cite: 1].
- **User-Centric UI/UX Design** (Custom tooltips, dynamic bookmarking, synchronized drill-throughs, accessible color palettes)[cite: 1].

---

## 📁 Repository Structure[cite: 1]

```plaintext
powerbi-portfolio/
│
├── dashboards/
│   ├── Sales_Executive_Report.pbix
│   ├── Customer_Retention_Cohort.pbix
│   ├── Supply_Chain_Operations.pbix
│   └── Finance_Variance_Matrix.pbix
│
├── dax-scripts/
│   ├── time_intelligence.dax
│   ├── sales_metrics.dax
│   ├── cohort_retention.dax
│   └── dynamic_ranking_abc.dax
│
├── power-query-m/
│   ├── dynamic_calendar_generator.m
│   ├── api_data_ingestion.m
│   └── data_cleaning_transforms.m
│
├── data/
│   ├── sample-sales-dataset.csv
│   └── dimensional_lookup_tables/
│
├── assets/
│   ├── architecture_diagram.png
│   └── previews/
│       ├── sales_preview.png
│       ├── churn_preview.png
│       └── supply_chain_preview.png
│
├── templates/
│   └── corporate_theme_template.pbit
│
└── README.md
```[cite: 1]

---

## 🚀 Featured Dashboards & Projects[cite: 1]

### 1. Executive Sales & Revenue Analytics[cite: 1]
* **Objective:** Track global sales pipeline, margin realization, and regional quarterly targets[cite: 1].
* **Key Features:**[cite: 1]
  - Dynamic MoM, YoY, and YTD performance KPIs[cite: 1].
  - Drill-down hierarchies (Region → Country → Territory → Product Category)[cite: 1].
  - Decomposition Tree for revenue driver analysis[cite: 1].
  - Custom tooltips highlighting top 5 performing SKUs per segment[cite: 1].
* **File:** [`dashboards/Sales_Executive_Report.pbix`](dashboards/)[cite: 1]

```plaintext
[ Preview Placeholder: assets/previews/sales_preview.png ]
```[cite: 1]

---

### 2. Customer Retention & Churn Analysis[cite: 1]
* **Objective:** Evaluate user lifetime value (LTV), cohort retention curves, and early-warning churn indicators[cite: 1].
* **Key Features:**[cite: 1]
  - Monthly active customer cohort matrices[cite: 1].
  - RFM (Recency, Frequency, Monetary) customer segmentation scoring[cite: 1].
  - Churn risk classification with interactive sensitivity threshold sliders[cite: 1].
* **File:** [`dashboards/Customer_Retention_Cohort.pbix`](dashboards/)[cite: 1]

```plaintext
[ Preview Placeholder: assets/previews/churn_preview.png ]
```[cite: 1]

---

### 3. Supply Chain & Inventory Optimization[cite: 1]
* **Objective:** Monitor warehouse lead times, fulfillment rates (OTIF), and safety stock buffers[cite: 1].
* **Key Features:**[cite: 1]
  - ABC/XYZ inventory segmentation matrix[cite: 1].
  - Stockout risk alerts based on lead time standard deviation[cite: 1].
  - Interactive map visual with custom geocoded supplier routing[cite: 1].
* **File:** [`dashboards/Supply_Chain_Operations.pbix`](dashboards/)[cite: 1]

---

### 4. Financial Performance & Variance Tracking[cite: 1]
* **Objective:** Compare Actual vs. Budget vs. Forecast P&L breakdowns across multi-currency operations[cite: 1].
* **Key Features:**[cite: 1]
  - Waterfalls for EBITDA reconciliation[cite: 1].
  - Dynamic currency conversion selector using disconnected exchange rate tables[cite: 1].
  - Smart Narrative summarizing material monthly budget variances[cite: 1].
* **File:** [`dashboards/Finance_Variance_Matrix.pbix`](dashboards/)[cite: 1]

---

## 🏗️ Data Architecture & Modeling[cite: 1]

All solutions adhere to scalable **Kimball Dimensional Modeling** principles[cite: 1]:
