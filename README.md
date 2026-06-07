# 📦 Supply Chain Performance & Inventory Intelligence Dashboard

## 📖 Project Overview

This project is an end-to-end **Supply Chain Performance & Inventory Intelligence Dashboard** developed using **Power BI**. The dashboard provides actionable insights into inventory management, warehouse operations, and logistics performance, helping businesses make data-driven decisions to optimize their supply chain.

The solution transforms raw supply chain data into meaningful business insights through interactive dashboards, custom DAX measures, and advanced visualizations.

---

## 🎯 Business Objectives

- Monitor inventory performance across warehouses
- Analyze warehouse utilization and capacity management
- Track transportation and logistics costs
- Identify operational bottlenecks
- Improve inventory turnover and stock management
- Support strategic decision-making through analytics
- Enhance supply chain visibility

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|--------|---------|
| Power BI | Dashboard Development |
| Power Query | Data Cleaning & Transformation |
| DAX | KPI & Measure Creation |
| Data Modeling | Relationship Management |
| Excel/CSV Dataset | Data Source |

---

## 📂 Dashboard Pages

### 1️⃣ Executive Summary

Provides a high-level overview of supply chain performance through key business metrics and trends.

#### Key KPIs
- Days Sales of Inventory (DSI)
- Warehouse Utilization %
- Inventory Turnover Ratio

#### Visuals
- Warehouse Utilization Gauge
- Transportation Cost by Region & Category
- Units Sold Trend Analysis
- Average Lead Time by Category
- Order Status & Backorder Analysis

#### Business Value
- Quickly identifies operational performance
- Highlights inventory movement trends
- Provides management-level supply chain overview

---

### 2️⃣ Warehouse Analytics

Focused on warehouse performance, inventory allocation, and capacity utilization.

#### Key KPIs
- Total Inventory
- Total Capacity
- Capacity Remaining
- Warehouse Utilization %

#### Visuals
- Warehouse Utilization Comparison
- Capacity vs Inventory Analysis
- Warehouse Efficiency Analysis
- Warehouse Risk Indicator
- Inventory Heatmap

#### Business Value
- Identifies underutilized warehouses
- Supports capacity planning
- Highlights inventory concentration patterns
- Improves warehouse efficiency monitoring

---

### 3️⃣ Logistics Analytics

Analyzes logistics performance, transportation costs, and regional efficiency.

#### Key KPIs
- Total Transportation Cost
- Logistics Cost %
- Cost Per Unit
- Total COGS

#### Visuals
- Transportation Cost Trend
- Cost Per Unit by Category
- Regional Cost Comparison
- Regional Logistics Efficiency

#### Business Value
- Monitors transportation spending
- Identifies expensive product categories
- Compares regional logistics performance
- Supports logistics optimization

---

## 📊 DAX Measures Implemented

### Inventory Metrics

```DAX
Total Inventory =
SUM('Inventory_SupplyChain_Dataset'[Inventory Level])
```

```DAX
Warehouse Utilization % =
DIVIDE(
    [Total Inventory],
    [Total Capacity],
    0
)
```

```DAX
Inventory Turnover Ratio =
DIVIDE(
    SUM('Inventory_SupplyChain_Dataset'[Units Sold]),
    SUM('Inventory_SupplyChain_Dataset'[Inventory Level]),
    0
)
```

### Logistics Metrics

```DAX
Total Transportation Cost =
SUM('Inventory_SupplyChain_Dataset'[Transportation Cost])
```

```DAX
Cost Per Unit =
DIVIDE(
    [Total Transportation Cost],
    [Total Units Sold],
    0
)
```

```DAX
Logistics Cost % =
DIVIDE(
    [Total Transportation Cost],
    [Total COGS],
    0
)
```

---

## 📈 Key Insights

- Warehouse utilization is operating below maximum capacity, indicating potential optimization opportunities.
- Inventory turnover demonstrates efficient stock movement across warehouses.
- Transportation costs vary significantly across regions and categories.
- Furniture category has the highest transportation cost per unit.
- Logistics efficiency differs across regions, highlighting areas for improvement.
- Inventory heatmap reveals product concentration within warehouses.
- Warehouse efficiency analysis helps identify top-performing facilities.

---

## 📋 Project Workflow

### Data Collection
- Imported supply chain dataset into Power BI.

### Data Cleaning
- Corrected data types
- Removed inconsistencies
- Validated business fields

### Data Transformation
- Applied Power Query transformations
- Created calculated columns
- Prepared data model

### Data Modeling
- Established relationships
- Optimized model performance

### KPI Development
- Created custom DAX measures
- Developed business-focused metrics

### Dashboard Design
- Built interactive visualizations
- Added slicers and filters
- Designed user-friendly layouts

---

## 🚀 Future Enhancements

- Supplier Analytics Dashboard
- Demand Forecasting
- Inventory Forecasting
- Stock-Out Risk Prediction
- Inventory Aging Analysis
- ABC Inventory Classification
- Supplier Performance Scorecard
- Drill-Through Reports
- Tooltip Pages
- Real-Time Data Refresh
- Power BI Service Deployment
- Automated Data Refresh

---

## 💡 Skills Demonstrated

### Technical Skills
- Power BI
- Power Query
- DAX
- Data Modeling
- Data Visualization
- Dashboard Design

### Business Skills
- Supply Chain Analytics
- Inventory Management
- Warehouse Analytics
- Logistics Analytics
- KPI Development
- Business Intelligence

---

## 📸 Dashboard Screenshots

### Executive Summary
![Executive Summary](images/executive-summary.png)

### Warehouse Analytics
![Warehouse Analytics](images/warehouse-analytics.png)

### Logistics Analytics
![Logistics Analytics](images/logistics-analytics.png)

---

## 👨‍💻 Author

**Vishal Awasthi**

Aspiring Data Analyst | Power BI Developer | SAP FICO Enthusiast

### Connect With Me

- LinkedIn: [www.linkedin.com/in/vishalawasthi0804]

---

⭐ If you found this project useful, consider giving it a star!
