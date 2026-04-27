# Power BI Dashboards Portfolio

A collection of three interactive Power BI dashboards built to explore and visualise data across e-commerce sales, online retail, and real estate domains.

---

## 1. E-Commerce Sales Dashboard
<img width="1280" height="720" alt="Image" src="https://github.com/user-attachments/assets/ba4a6f8b-fc06-4dee-921b-1b1347d45ea9" />

**File:** `ECOMMERECE SALES DASHBOARD.pbix`  
**Dataset:** `Details` table — 1,500 rows

### Overview
An interactive sales performance dashboard tracking revenue, profit, quantity, and average order value across Indian markets.

### Key Metrics
| Metric | Value |
|--------|-------|
| Sum of Amount | 438K |
| Sum of Profit | 37K |
| Sum of Quantity | 5,615 |
| Sum of AOV | 121K |

### Visuals
- **Sum of Profit by Month** — Bar chart showing monthly profit trends across the year, with both positive and negative profit months visible
- **Sum of Quantity by Category** — Donut chart: Clothing (63%), Electronics (21%), Furniture (17%)
- **Sum of Amount by State** — Horizontal bar chart comparing sales across Maharashtra, Madhya Pradesh, Uttar Pradesh, Delhi, and Rajasthan
- **Sum of Quantity by PaymentMode** — Donut chart: COD (44%), UPI (21%), Debit Card (13%), Credit Card (12%), EMI (10%)
- **Sum of Amount by CustomerName** — Bar chart for top customers: Harivansh, Madhav, Madan Mohan, Shiva, Vishakha
- **Sum of Profit by Sub-Category** — Horizontal bar chart: Printers, Bookcases, Saree, Accessories, Tables

### Filters
- Quarter selector (Qtr 1 – Qtr 4)
- All/individual quarter toggle

### Data Schema
| Column | Type |
|--------|------|
| Order ID | Text |
| Amount | Number |
| Profit | Number |
| Quantity | Number |
| Category | Text |
| Sub-Category | Text |
| PaymentMode | Text |
| AOV | Number |

---

## 2. Online Retail Dataset Analysis
<img width="1119" height="625" alt="Image" src="https://github.com/user-attachments/assets/c03a5f8b-2490-4a14-a20b-df0910e643da" />

**File:** `Online retail dataset Analysis.pbix`  
**Dataset:** `Sheet1` table — 4,00,947 rows

### Overview
A comprehensive retail analytics dashboard analysing revenue, customer behaviour, and product performance for a UK-based online retailer spanning December 2009 to December 2010.

### Key Metrics
| Metric | Value |
|--------|-------|
| Sum of Quantity | 1M |
| Sum of Revenue | 1.83M |
| Count of Customers | 85.76K |
| Average of Revenue | 21.29 |

### Visuals
- **Sum of Revenue and Sum of Quantity by Month** — Dual-axis line chart showing revenue and quantity trends (April–June 2010 visible)
- **Sum of Revenue by Country** — Donut chart: United Kingdom dominates at 86.97%, with EIRE, Netherlands, Germany, France, Sweden, and Switzerland making up the rest
- **Top 10 Products by Revenue** — Horizontal bar chart highlighting top performers (e.g., Regency Cakes, White Hanging items, Party Bunting)
- **Average Revenue per Customer by Month** — Line chart showing per-customer averages month over month
- **Monthly Sales Count** — Area/line chart tracking invoice count per month
- **Number of Unique Products Sold by Month** — Column chart showing product variety per month

### Filters
- Quarter selector (Qtr 1 – Qtr 4)
- Invoice date range picker (01-12-2009 to 09-12-2010)

### Data Schema
| Column | Type |
|--------|------|
| Invoice | Number |
| StockCode | Text |
| Description | Text |
| Quantity | Number |
| InvoiceDate | DateTime |
| Price | Decimal |
| Customer ID | Number |
| Country | Text |
| OrderMonth | Text |
| Revenue | Decimal |

---

## 3. Dubai Real Estate Intelligence Dashboard
<img width="1281" height="719" alt="Image" src="https://github.com/user-attachments/assets/63c1abec-2c0c-46ec-ad93-76e691a8ec68" />
**File:** `House_price_Dashboard.pbix`  
**Dataset:** `housing_price_dataset` table — 50,000 rows

### Overview
A real estate market intelligence dashboard for Dubai properties, segmenting the market by neighbourhood type, listing category, bedroom count, and decade of construction.

### Key Metrics
| Metric | Value |
|--------|-------|
| Total Listings | 50K |
| Avg Price | د.إ 225K |
| Max Price | د.إ 492K |
| Min Price | د.إ 155K |
| Avg Price per Sqft | د.إ 113 |

### Visuals
- **Average Property Price by Neighbourhood** — Column chart comparing Urban, Rural, and Suburb averages (~220K–228K range)
- **Bedroom Distribution Across Neighbourhoods** — Stacked bar chart showing 2–5 bedroom breakdown per neighbourhood (approximately 33% each)
- **Property Listings by Category** — Pie chart: Mid-Range (51.21%), Budget (24.42%), High-End (24.37%)
- **Avg Price Trend by Decade** — Multi-line chart from 1950s to 2020s for Budget, High-End, and Mid-Range categories
- **Listings by Category** — Treemap: Mid-Range (26K), Budget and High-End (~12K each)
- **Neighbourhood Market Share** — Donut chart: Rural (33.35%), Urban (33.44%), Suburb (33.21%)

### Filters
- Neighbourhood selector (Rural / Suburb / Urban / Select all)
- Listing Category dropdown (All / Budget / Mid-Range / High-End)
- Year Built dropdown
- Bedrooms dropdown

### Data Schema
| Column | Type |
|--------|------|
| SquareFeet | Number |
| Bedrooms | Number |
| Bathrooms | Number |
| Neighbourhood | Text |
| YearBuilt | Number |
| Price | Decimal |
| Price per Sqft | Decimal |
| Property Age | Number |
| Listing Category | Text |
| Property Age (bins) | Number |
| Decade | Text |

---

## Tools & Technologies

- **Platform:** Microsoft Power BI Desktop
- **Data Sources:** CSV / Excel imports
- **Visualisation Types:** Bar charts, line charts, donut/pie charts, treemaps, KPI cards, slicers
- **Features Used:** Cross-report drill-through, custom measures, date table integration, quarter-level filtering

---

## Author

**Poorvika**  
Created: April–April 2026
