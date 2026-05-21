# Supply Chain Operations Dashboard | Power BI, SQL, DAX

Power BI and SQL-based supply chain analytics project focused on designing KPI reporting workflows, dimensional data models, and operational performance monitoring for logistics and fulfillment operations.

![Star Schema](04_assets/star_schema_model.png)

---

# Project Overview

Designed a supply chain analytics framework using Power BI, SQL, DAX, and star schema modeling to support KPI reporting and operational performance analysis across warehouse, supplier, delivery, and fulfillment workflows.

The project focuses on building scalable analytical structures for monitoring delivery performance, inventory exposure, supplier reliability, shipping costs, and operational risk.

---

# Business Objectives

Large-scale logistics operations generate complex operational datasets across warehouses, suppliers, delivery partners, and customer fulfillment channels.

This project was designed to support centralized operational reporting and KPI monitoring for:

- Delivery performance analysis
- Supplier reliability monitoring
- Inventory exposure and stockout risk tracking
- Shipping cost analysis
- Return and damage-rate monitoring
- Operational bottleneck identification

---

# Data Model Architecture

The project follows a Star Schema architecture with a centralized fact table and supporting dimensions optimized for scalable reporting and analytical workflows.

![Star Schema Model](04_assets/star_schema_model.png)

---

# Dashboard Structure

![Dashboard Navigation](04_assets/dashboard_navigation.png)

## Executive Overview
- Revenue and profitability monitoring
- Shipping cost analysis
- Operational KPI reporting

## Delivery Performance Analytics
- SLA compliance analysis
- Delay root-cause tracking
- Carrier performance monitoring

## Inventory & Warehouse Risk
- Inventory exposure analysis
- Supplier reliability tracking
- Warehouse monitoring workflows

---

# Key KPIs

| KPI | Business Purpose |
|---|---|
| On-Time Delivery % | Measures delivery SLA performance |
| Net Profit | Tracks operational profitability |
| Net Profit Margin % | Evaluates margin efficiency |
| Product Damage Rate % | Identifies operational quality issues |
| Return Rate % | Measures fulfillment performance |
| Shipping Cost Analysis | Tracks logistics cost efficiency |

---

# Sample KPI Logic

## On-Time Delivery %

```text
(Total On-Time Orders / Total Orders) * 100Target Benchmark: 85%+
```
---

## Net Profit

```text
Revenue - (Item Cost + Shipping Cost)
```

---

## Net Profit Margin %

```text
(Total Net Profit / Total Revenue) * 100
```

---

# Key Analytical Features

- Star schema data modeling for scalable BI reporting
- SQL-based data transformation workflows
- KPI and business logic development
- DAX measure design for operational analysis
- Power BI analytical architecture design
- Supply chain operational monitoring framework

---

# Technology Stack

- Power BI
- SQL
- DAX
- Star Schema Modeling
- Excel / CSV Data Processing

---

# Repository Structure

```text
01_raw_data/              -> Raw datasets and source references
02_powerbi_dashboard/     -> Power BI dashboard files
03_documentation/         -> Business requirements and architecture documentation
04_assets/                -> Dashboard screenshots and project visuals
```

---

# Planned Enhancements

- Interactive executive KPI dashboards
- Advanced DAX calculations
- Drill-through operational reporting
- Inventory risk alerting
- Enhanced operational trend analysis

---

# Limitations

- Dataset is simulated for portfolio and analytical demonstration purposes
- Current implementation primarily focuses on analytical architecture and KPI framework design
- External variables such as macroeconomic demand and weather conditions are not yet incorporated
