# 📊 Enterprise BI Dashboards

> Production-grade Business Intelligence dashboards delivered across **Banking, Government, Education, and Telecom** sectors — built with Power BI, SQL, and scalable data modeling.

---

## 🎯 What's In This Repo

A curated portfolio of BI dashboards designed and delivered across enterprise environments. These samples showcase **data visualization, KPI design, and self-service reporting** — from executive scorecards to operational monitoring.

> ⚠️ **All data is anonymized or synthetic.** No confidential or proprietary information is included.

---

## 🖥️ Dashboard Gallery

### 1️⃣ Telecom Operations Dashboard

> 🏢 **Domain:** Telecom / Service Provider &nbsp;&nbsp;|&nbsp;&nbsp; 👔 **Audience:** Operations Management & C-Suite

![Telecom Operations Dashboard](screenshots/01_telecom_operations_dark.jpg)

**What it does:**

- 📈 **KPI Cards** — Total Ports, Port-In, Port-Out at a glance
- 🌍 **By Nationality** — Horizontal bars showing top customer segments
- 🏙️ **By City** — Geographic distribution of port activity
- 📅 **Time Series** — Monthly & Daily toggle with quarterly trend (log scale)
- 👤 **By Operator** — Competitive breakdown across telecom providers
- 🍩 **Donut Charts** — Billing Type · Plan Type · Channel Type for quick ratio analysis
- 🎨 **Dark theme** with vibrant accent colors for executive screen presentations

**Tech:** `Power BI` · `DAX` · `DirectQuery` · `SQL Server`

---

### 2️⃣ Sales Performance Dashboard — Light Theme

> 🏢 **Domain:** Retail / E-Commerce &nbsp;&nbsp;|&nbsp;&nbsp; 👔 **Audience:** Sales Leadership & Finance

![Sales Performance Dashboard - Light](screenshots/02_sales_performance_light.jpg)

**What it does:**

- 💰 **Revenue KPIs** — Sum of Sales ($29.99M) · Profit ($5.82M) · Product Count
- 📈 **Sales by Time** — Year-over-year growth trajectory
- 🌍 **Sales by Country** — 7-country breakdown (Sweden → Mexico)
- 📦 **Sales by Product** — Ranked horizontal bars with top performers highlighted
- 🍩 **Sector Split** — Government vs Private · Cash vs Card ratio
- 📊 **Volume by Product** — Absolute unit comparison for product-level decisions
- 🖨️ **Light theme** optimized for print, PDF export, and email distribution

**Tech:** `Power BI` · `DAX` · `Star Schema` · `Scheduled Refresh`

---

### 3️⃣ Government Statistical Dashboard (Arabic 🇸🇦)

> 🏢 **Domain:** Government / Regulatory Body &nbsp;&nbsp;|&nbsp;&nbsp; 👔 **Audience:** Ministerial & Executive Leadership

![Government Statistical Dashboard](screenshots/03_government_statistical_arabic.jpg)

**What it does:**

- 🗺️ **Interactive World Map** — Geographic distribution across continents with drill-through
- 🏛️ **Entity Tabs** — Filter by different organizational categories
- 📊 **Regional Breakdown** — Horizontal bars by administrative region
- 🍩 **Regional Progress Donuts** — Percentage completion per geographic zone
- 📈 **Before/After Comparison** — Impact analysis with side-by-side bar charts
- 🌐 **Full RTL Arabic Interface** — Native right-to-left layout for Arabic stakeholders
- 🔐 **Role-Based Access** — Deployed via Power BI Report Server with row-level security

**Tech:** `Power BI` · `Power BI Report Server` · `DAX` · `Oracle` · `Row-Level Security`

---

### 4️⃣ Sales Performance Dashboard — Dark Theme

> 🏢 **Domain:** Retail / E-Commerce &nbsp;&nbsp;|&nbsp;&nbsp; 👔 **Audience:** Executive Presentations & Live Screens

![Sales Performance Dashboard - Dark](screenshots/04_sales_performance_dark.jpg)

**What it does:**

Same analytical depth as the Light Theme version, redesigned for:

- 🖥️ **Executive boardroom presentations** — high contrast, eye-friendly on large screens
- 📺 **Always-on TV dashboards** — optimized for wall-mounted displays in offices
- 🌙 **Dark mode toggle** — users switch between Light ↔ Dark based on context

> 💡 Both themes share the same data model and DAX measures — only the visual layer changes. This demonstrates **reusable, maintainable report design** where business logic lives in the model, not the visuals.

**Tech:** `Power BI` · `DAX` · `Custom Theme JSON` · `Bookmarks`

---

### 5️⃣ Operational Processing Dashboard (Arabic 🇸🇦)

> 🏢 **Domain:** Government / Operations &nbsp;&nbsp;|&nbsp;&nbsp; 👔 **Audience:** Operations Teams & Department Heads

![Operational Processing Dashboard](screenshots/05_operational_processing_arabic.jpg)

**What it does:**

- 🎯 **Processing Gauge** — 95% completion rate with status breakdown (Completed · In Progress · Delayed)
- 📈 **Growth Time Series** — Quarterly trend from 3,444 → 166,751 → 230,654 (6,600% growth)
- ⏱️ **Sparkline KPIs** — Average processing time · Monthly change rate · Beneficiary count
- 📊 **Regional Combo Chart** — Bar (volume) + Line (avg processing time) per region — multi-metric storytelling
- 🔄 **Period Toggle** — Monthly / Quarterly switch for different analysis granularity
- 🌐 **Full RTL Arabic Interface** — Native Arabic for government stakeholders

**Tech:** `Power BI` · `DAX` · `PostgreSQL` · `Scheduled Refresh` · `Report Server`

---

## 🛠️ Technical Stack

```
📊 Visualization       Power BI · Tableau · Looker · Looker Studio
🗄️ Databases           PostgreSQL · Oracle · SQL Server · MySQL · BigQuery · Snowflake
🔧 Data Modeling        Kimball Dimensional Modeling · Star Schema · Snowflake Schema
⚙️ Data Pipelines      dbt (Data Build Tool) · Apache Airflow · SSIS · Cloud Composer
💻 Programming          Python · SQL (Advanced) · DAX · Power Query (M)
☁️ Cloud                Google Cloud Platform · Microsoft Azure
🔄 CI/CD               GitLab CI/CD · GitHub · Docker · Kubernetes
📐 Methodologies        Agile · DataOps · Self-Service BI · Test-Driven Pipelines
```

---

## 📈 Impact Delivered

| Metric | Result |
|--------|--------|
| ⚡ Dashboard Refresh | Reduced from **2+ hours → under 5 minutes** |
| 📉 File Size Optimization | **500 MB → 100 MB** (79% reduction) |
| 🚀 ETL Pipeline Performance | Runtime cut by **80%** |
| 📊 KPIs in Production | **100+ executive-grade metrics** |
| 🏢 Domains Covered | Banking · Government · Education · Telecom · Retail |
| 🔒 Data Accuracy | **100% reconciliation** on regulatory datasets |
| 👥 Self-Service Adoption | **200+ business users** accessing data independently |

---

## 🏗️ Design Principles

```
1. 📋 Requirements First
   └── Stakeholder interviews → KPI definition → wireframe approval

2. 🗄️ Model Before You Visualize
   └── Source analysis → Kimball star schema → clean dimension & fact tables

3. ⚙️ Automate Everything
   └── Scheduled refresh → parameterized queries → zero manual intervention

4. 🎨 Theme Consistency
   └── Custom JSON themes → reusable across reports → brand alignment

5. 🔐 Security by Default
   └── Row-level security → report server deployment → role-based access

6. 📱 Design for the Audience
   └── C-Suite → KPI cards & trends · Operations → detail & drill-through
```

---

## 📂 Repository Contents

```
enterprise-dashboards/
├── 📄 README.md
├── 📑 Omar_Alfarouk_BI_Dashboards_Samples.pdf
└── 📸 screenshots/
    ├── 01_telecom_operations_dark.jpg
    ├── 02_sales_performance_light.jpg
    ├── 03_government_statistical_arabic.jpg
    ├── 04_sales_performance_dark.jpg
    └── 05_operational_processing_arabic.jpg
```

---

## 📜 License

This repository contains dashboard samples for portfolio purposes only. No proprietary data, client information, or confidential business logic is included. All data shown is anonymized or synthetic.

---

⭐ **If you found this useful, consider giving it a star!**
