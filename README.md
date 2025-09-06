# Vistula Retail BI Dashboard

📊 Business Intelligence dashboard simulated for the **Polish retail market**, developed in **Power BI**.  
The goal is to demonstrate expertise in data modeling, advanced DAX, and visual storytelling for executive reporting.

---

## 🔎 Data Model
- **fact_sales**: Sales (quantity, net/gross values, discounts, VAT).  
- **fact_returns**: Returns and quality (quantity and value).  
- **fact_payments**: Payments and methods (card, cash, PayPal, etc.).  
- **dim_customer**: Customer master data.  
- **dim_product**: Product catalog.  
- **dim_channel**: Sales channels (Marketplace, E-commerce, Store, etc.).  
- **dim_date**: Calendar (time intelligence).  
- **dim_store**: Physical stores.  
- **dim_geo**: Geographic regions / Polish Voivodeships.  
- **dim_payment_method**: Payment methods.

---

## 📈 Dashboard Pages

### 1. **Sales Performance**
- KPIs: Total Net Sales, Gross Sales, VAT, Discounts, Total Quantity.  
- Column chart: Net Sales by category.  
- Stacked columns: Net Sales by channel (colored by Gross Margin %).  
- Table: Top 20 products (Quantity, Net Sales, Margin %).  
- Line chart: Net Sales trend (Year-Month).  
- Donuts: Net Sales share by region and channel.  

---

### 2. **Returns & Quality**
- KPIs: Return Rate (Qty & Value), Total Returns Qty, Total Returns Value.  
- Line chart: Returns evolution (Year-Month).  
- Bar chart: Return Rate by channel.  
- Bar chart: Return Rate by region.  
- Detailed table: Returns by product.  

---

## 🎯 Technical Highlights
- DAX measures created for Sales, Returns, VAT, Discounts, and Return Rates.  
- Star Schema modeling connecting fact and dimension tables.  
- Professional dark theme layout for clear visualization.  

---

## 📂 Repository Structure
- `Vistula_Retail_Demo.pdf` → Exported PDF of the report.  
- `assets/preview_sales.png` → **Sales Performance** page preview.  
- `assets/preview_returns.png` → **Returns & Quality** page preview.  

---

## 🚀 Purpose
This dashboard is part of an **international BI portfolio** designed for opportunities in Central Europe, with a focus on **Poland**.
