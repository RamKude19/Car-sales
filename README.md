# 🚗 Car Sales Performance Dashboard | Power BI

An end-to-end business intelligence solution built in Power BI to monitor and analyze car dealership sales data. The dashboard provides real-time visibility into key sales KPIs with year-over-year comparisons, weekly trends, and granular breakdowns by dealer, car model, region, and more.

---

## 📊 Dashboard Pages

### 1. Overview
A high-level summary of dealership performance with:
- **KPI Cards** — YTD Total Sales, YTD Avg Price, YTD Cars Sold (each with Sales Difference, YoY Growth %, and MTD KPI)
- **YTD Sales Weekly Trend** — Area chart showing weekly revenue with max-point highlighting
- **Sales by Body Style** — Donut chart breakdown
- **Sales by Color** — Donut chart breakdown
- **Geographic Map** — Cars sold by dealer region
- **Company-Wise Sales Table** — Avg price, units sold, and total revenue per brand
- **Slicers** — Filter by Body Style, Dealer Name, Transmission, and Engine type

### 2. Details
A drill-through transaction-level view including:
- All KPI cards from the Overview page
- Detailed table with Car ID, Customer Name, Dealer Name, Company, and Color
- Same slicers for consistent filtering across pages

---

## 📐 Key Metrics & DAX Measures

| Metric | Description |
|---|---|
| YTD Total Sales | Year-to-date cumulative revenue |
| YTD Avg Price | Average selling price year-to-date |
| YTD Car Sold | Total units sold year-to-date |
| Sales Difference | Variance vs. previous year |
| YOY Growth % | Year-over-year percentage growth |
| MTD KPI | Month-to-date performance indicator |

---

## 🔍 Filters & Slicers
- Body Style
- Dealer Name
- Transmission Type
- Engine Type

---

## 🛠️ Tools & Technologies
- **Power BI Desktop** — Report development
- **DAX** — Custom KPIs, time intelligence (YTD, MTD, YoY)
- **Power Query** — Data transformation & Calendar Table
- **Map Visual** — Regional sales distribution

---

## 📁 File
| File | Description |
|---|---|
| `CAR_Sales.pbix` | Main Power BI report file |

---

## 🚀 How to Use
1. Download and open `CAR_Sales.pbix` in [Power BI Desktop](https://powerbi.microsoft.com/desktop/)
2. Connect to your data source or use the embedded sample data
3. Use the slicers on each page to filter by dealer, car type, or engine
4. Navigate between the **Overview** and **Details** pages using the page navigator

---


