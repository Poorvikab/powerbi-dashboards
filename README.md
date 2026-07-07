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
## 4. U.S. Airline Performance & Delay Analysis
<img width="1132" height="637" alt="Image" src="https://github.com/user-attachments/assets/63789d4c-a056-43ad-9032-5f7891b70bda" />

**File:** `US_Airline_Performance_Delay_Analysis.pbix`  
**Dataset:** U.S. domestic flight records — 6M rows (2015)

### Overview
An interactive dashboard analysing on-time performance, delays, cancellations, and diversions across U.S. domestic flights, with airport-level and airline-level breakdowns of delay causes.

### Key Metrics
| Metric | Value |
|--------|-------|
| Total Flights | 6M |
| OTP Rate | 82.41% |
| Avg Arrival Delay | 4.41 min |
| Cancellation Rate | 1.54% |
| Diversion Rate | 0.26% |

### Visuals
- **Avg Arrival Delay by Month** — Line chart tracking average arrival delay trends across months
- **Worst Airports by Average Delay** — Horizontal bar chart ranking airports (Wilmington, Gustavus, Pago Pago, St. Cloud, Jack Brooks, Aspen-Pitkin, Southwest) by average delay
- **Airport Performance Map** — Geographic map plotting flight volume and delay concentration across North America
- **Top 10 Airlines by OTP** — Horizontal bar chart comparing on-time performance rates (Hawaiian, Alaska, Delta, American, US Airways, Skywest, Southwest)
- **Delay Cause Breakdown** — Donut chart splitting delay minutes by cause: Airline Delay (32.2%), Late Aircraft Delay (39.84%), Air System Delay (22.88%), Weather Delay (4.95%), Security Delay (0.13%)

### Filters
- Airline Name dropdown
- Cancellation Reason dropdown
- Month dropdown
- Origin Airport Name dropdown

### Data Schema
| Column | Type |
|--------|------|
| Airline Name | Text |
| Origin Airport Name | Text |
| Month | Number |
| Avg Arrival Delay Numeric | Number |
| OTP Rate | Decimal |
| Cancellation Reason | Text |
| Airline Delay | Number |
| Air System Delay | Number |
| Weather Delay | Number |
| Late Aircraft Delay | Number |
| Security Delay | Number |

---
