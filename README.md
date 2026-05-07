# Supply Chain Analytics Dashboard — Excel

## Project Overview
This project analyzes supply chain data for a beauty products company 
using Microsoft Excel. The goal is to clean raw data, perform analysis, 
and build an interactive dashboard to support business decisions.

---

## Dataset
- **Source:** Kaggle — Supply Chain Analysis Dataset
- **Size:** 100 rows, 24 columns
- **Domain:** Beauty Products Supply Chain
- **Fields:** Product types, Revenue, Stock levels, Shipping costs, 
  Supplier info, Defect rates, Transportation modes

---

## Tools Used
- Microsoft Excel
  - Data Cleaning
  - Formulas & Calculated Columns
  - Pivot Tables
  - Dashboard with Charts

---

## Process

### Phase 1 — Data Cleaning
- Replaced 31 "Unknown" values in Customer Demographics with "Not Specified"
- Formatted currency columns (Price, Revenue, Shipping Costs, Manufacturing Costs)
- Formatted Defect Rates as percentage
- Checked and confirmed no duplicate SKUs
- Converted data to structured Excel Table (SupplyChainData)

### Phase 2 — Calculated Columns
- **Profit Margin %** → `=(Revenue - Cost) / Revenue`
- **Stock Status** → Low / Medium / High based on stock levels
- **Shipping Efficiency** → Fast / Normal / Slow based on shipping time

### Phase 3 — Pivot Tables
- Revenue by Product Type
- Average Defect Rate by Supplier
- Average Shipping Cost by Carrier
- Stock Status Count Distribution

### Phase 4 — Dashboard
- 4 interactive charts with consistent purple theme
- Pie Chart — Revenue by Product Type
- Bar Chart — Defect Rate by Supplier
- Horizontal Bar — Shipping Cost by Carrier
- Donut Chart — Stock Status Distribution

---

## Key Insights

1. **Skincare dominates revenue** — contributing 42% ($241,628) 
   of total revenue ($577,604)
2. **Supplier 5 has highest defect rate** — 2.67% average, 
   needs quality review
3. **Supplier 1 is most reliable** — lowest defect rate at 1.80%
4. **Carrier B is most cost-effective** — average shipping 
   cost of $5.51 vs Carrier C at $5.60
5. **27% products are Low Stock** — immediate restocking 
   required to avoid stockouts
6. **High profit margins across all products** — averaging 
   above 90%, indicating healthy pricing strategy

---

## Dashboard Preview
![Dashboard](dashboard_screenshot.png)

---

## Author
**Samia Sharif**
- LinkedIn: https://www.linkedin.com/in/samia-sharif-161304342/
- GitHub: https://github.com/SamiaSharif
