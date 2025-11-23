# 📊 Power BI Sales Analytics Dashboard

This repository contains a complete Power BI analytics solution designed to analyze sales performance, customer behavior, product insights, and shipping efficiency. The project uses a clean **star-schema** data model and includes multiple report pages with advanced DAX measures.

---

## 🚀 Features

### **🔹 4 Interactive Report Pages**
1. **Customer Overview**
   - Total Customers, Sales, Orders
   - Sales by Segment, Region, and Country
   - Top 10 Customers
   - Geographic insights with map visuals

2. **Product Performance**
   - Top-selling products and categories
   - Profit and quantity analytics
   - Product hierarchy (Category → Subcategory)
   - KPI cards for overall performance

3. **Sales & Time Analysis**
   - Sales trends over time
   - YoY, MTD, YTD comparisons
   - Forecasting using Power BI analytics
   - Seasonal and daily performance breakdowns
   - KPI cards for sales, profit, and orders

4. **Orders & Shipping**
   - Shipping time analysis
   - Order delivery KPIs
   - Shipping mode distribution
   - Calculated column: `Shipping Days`
   - Average shipping days visualization

---

## 🧱 Data Model (Star Schema)

The model uses the following structure:

- **Fact Table**
  - `Sales`  
    Contains order-level transactions including dates, quantities, prices, customer IDs, product IDs, and shipping information.

- **Dimension Tables**
  - `CustomerDim`  
  - `ProductDim`  
  - `DateDim`  
  - `DAX_Table` (for created measures, if used)

This structure improves performance and simplifies DAX calculations.

---

## 🧮 Key DAX Measures

Some of the core DAX measures used in this project include:

