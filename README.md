**Automated Sales Report Generation using Python libraries
**

**Overview**

This project **automates the creation of sales performance reports** from raw CSV data using Python. It **ingests sales data, computes key performance indicators (KPIs), generates visualizations**, and produces a **professional PDF report**, all with a single script. The solution is **fully repeatable and scalable, eliminating the need for manual report generation.
**

**Features**

- Load and clean sales data (CSV)
- KPI computation:
  - Total Revenue
  - Total Orders
  - Average Order Value
  - Revenue by Region
  - Monthly Revenue Trend
  - Top Products by Revenue
- Automated visualizations (Matplotlib):
  - Monthly revenue trend
  - Revenue by region
  - Top 5 products by revenue
- PDF report generation (ReportLab) with embedded charts and executive summary
- Configurable paths for input data and output reports
- Modular, reusable, and productionready design

**Dataset**

- **File:** sales_data_q1_2025.csv
- **Rows:** 1000
- **Columns:**
  - Order_ID – Unique identifier for each order
  - Date – Date of order
  - Region – Sales region (North, South, East, West)
  - Product – Product category (Laptop, Phone, Tablet, Monitor, Accessories)
  - Quantity – Number of items
  - Revenue – Order revenue in USD
  - Customer_Type – New or Returning customer
