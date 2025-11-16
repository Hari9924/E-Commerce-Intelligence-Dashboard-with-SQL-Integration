# 🛒 E-commerce Sales Dashboard – Power BI

An interactive Power BI dashboard built to analyze e-commerce sales performance using KPIs, category/state insights, product trends, shipping analysis, and dynamic filtering. The project demonstrates end-to-end BI development, including SQL-based data loading, modeling, DAX calculations, and visualization design.

---

## Overview

This dashboard provides a comprehensive analytical view of an e-commerce business by showcasing:

- Year-to-date Sales, Profit, Quantity, and Profit Margin  
- Year-on-Year Growth with dynamic indicators  
- Sales by Category, State, Region, and Shipping Type  
- Top 5 & Bottom 5 products  
- Monthly sales trend comparison with previous year  
- Customer Segmentation through slicers  

The report is fully interactive and optimized for business decision-making.

---


## **Visuals Overview**
- Sales by Category  
- Sales by State (Map)  
- Top 5 / Bottom 5 Products  
- Sales by Region (Donut)  
- Sales by Shipping Type  
- Monthly Trend Line  

---

## Data & Setup

### **Data Sources**
- Customer data  
- Orders & line items  
- Product & category information  
- Shipping and regional data  

Data was first loaded into **MS SQL Server**, cleaned, and connected to Power BI.  
Alternative method: Direct flat-file import via Power BI.

---

## Tech Stack

- Power BI Desktop  
- Microsoft SQL Server  
- Power Query  
- DAX Measures  
- Star Schema Modeling  

---

## Dashboard Features

### **1. KPI Banner**
- Year-to-Date Sales  
- Year-to-Date Profit  
- Year-to-Date Quantity  
- Year-to-Date Profit Margin  
- YOY Growth with icons  

### **2. Trend Analysis**
- Monthly sales trend  
- Previous Year vs Current Year  

### **3. Sales Insights**
- Category-wise performance  
- State-wise sales (Map)  
- Region-wise distribution  
- Shipping Type analysis  

### **4. Product Insights**
- Top 5 Products  
- Bottom 5 Products  

### **5. Slicers and Interactivity**
- Customer segment  
- Region  
- Shipping Mode  
- Date filters  

---

## Key DAX Measures Used

- YTD Sales  
- Previous YTD Sales  
- YOY Growth %  
- YTD Profit & Margin  
- Monthly Sales Trend logic  

Time intelligence functions power most KPI logic.

---

## Development Workflow

### **1. Problem Understanding**
Business needed insights into product, region, category, and shipping performance.

### **2. Data Import**
- Loading to SQL Server
- Connecting SQL to Power BI
- Alternative flat-file import

### **3. Data Modelling**
- Creating relationships between fact and dimension tables  
- Star schema design  

### **4. Dashboard Design**
- Adding backgrounds and themes  
- KPI cards creation  
- Custom formatting  
- Visual layout

---

## Recommended Folder Structure

```
📦 ecommerce-sales-dashboard
 ┣ 📂 Data
 ┣ 📂 SQL
 ┣ 📂 PowerBI
 ┃ ┗ Ecommerce_Sales_Dashboard.pbix
 ┣ 📂 Screenshots
 ┗ 📄 README.md
```


