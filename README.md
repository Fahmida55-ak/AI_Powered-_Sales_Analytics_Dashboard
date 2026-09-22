# 📊 AI-Powered Sales Revenue Dashboard (Power BI)

An interactive Power BI dashboard that uses AI visuals — **Key Influencers**, **Decomposition Tree**, and **Anomaly Detection** — to explain what drives total revenue across products, locations, and platforms, and to surface unusual spikes or dips in the revenue trend automatically.

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Data%20Modeling-blue)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

---

## 🔍 Overview

This dashboard analyzes sales performance across **Amazon, iHerb, and Walmart** in the **UK, Canada, and USA**, covering categories such as Vitamins, Minerals, Protein, Performance, and more. It combines standard KPI reporting with Power BI's built-in AI visuals to turn raw numbers into plain-language insights, so stakeholders can understand *why* revenue moves, not just *that* it moved.

## ✨ Key Features

- **Smart Narrative** — Auto-generated summary sentences (e.g., highest/lowest revenue day, percentage swings, revenue range across the period) that update dynamically as filters change.
- **Key Influencers visual** — Identifies which factors (e.g., Sum of Price, Sum of Units Sold) most increase or decrease total revenue, with plain-English explanations like *"When Sum of Price goes up by 152.41, total revenue increases by 20.76K on average."*
- **Decomposition Tree (Revenue Breakdown Explorer)** — Lets users drill down through Location → Category → Platform to see exactly where revenue is coming from.
- **Anomaly Detection** — Flags unexpected spikes or dips in the daily revenue trend line for fast root-cause investigation.
- **Interactive Filters** — Slice the entire report by Category, Location, and Platform.
- **KPI Cards** — At-a-glance totals for Total Revenue, Units Sold, and Discounts.

## 🧩 Dashboard Sections

| Section | Description |
|---|---|
| **Summary Narrative** | AI-generated text summary of top/bottom performing dates and revenue trends |
| **KPI Cards** | Total Revenue, Sum of Units Sold, Sum of Discount |
| **Key Revenue Drivers** | Key Influencers visual showing what pushes revenue up or down |
| **Revenue Breakdown Explorer** | Decomposition tree across Location, Category, and Platform |
| **Revenue Trend with Anomaly Detection** | Time series of daily revenue with anomaly markers |
| **Filters Panel** | Category, Location, and Platform slicers |

## 📈 Sample Insights (from the current dataset)

- Total revenue across the period: **5.17M**
- Highest single-day revenue: **$104,811.96** (12/14/2020)
- Lowest single-day revenue: **$34,449.80** (3/15/2021) — a **204.25%** difference from the peak
- The top revenue day accounted for **2.03%** of total revenue
- **Sum of Price** was the largest positive driver of revenue growth, followed by **Sum of Units Sold**

## 🛠️ Tools & Technologies

- **Power BI Desktop** — report design and data modeling
- **DAX** — calculated measures and KPIs
- **Power BI AI Visuals** — Key Influencers, Decomposition Tree, Smart Narrative, Anomaly Detection

## 📁 Repository Contents

```
├── sales-dashboard.pbix      # Power BI report file
├── screenshots/              # Dashboard preview images
└── README.md                 # Project documentation
```

## 🚀 How to Use

1. Clone this repository.
2. Open `sales-dashboard.pbix` in **Power BI Desktop**.
3. Connect/refresh the data source if prompted.
4. Use the slicers (Category, Location, Platform) to explore the data interactively.

## 📷 Preview

*(Add a screenshot of the dashboard here, e.g. `![Dashboard Preview](screenshots/dashboard.png)`)*

## 📄 License

This project is open for learning and portfolio purposes. Feel free to fork and adapt it.

---

### 💡 Suggested Repository Description (for GitHub's "About" field)

> Interactive Power BI sales dashboard with AI-powered Key Influencers, Decomposition Tree, and Anomaly Detection to explain revenue trends across products, locations, and platforms.
