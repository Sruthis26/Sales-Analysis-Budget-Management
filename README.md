# Sales Analysis & Budget Management Dashboard

## Project Overview

This project demonstrates an end-to-end Business Analysis and Business Intelligence solution developed using SQL Server and Power BI.

The objective was to transform sales data into interactive dashboards that provide visibility into customer performance, product performance, sales trends, and budget tracking. The solution enables stakeholders to make informed decisions through dynamic reporting and self-service analytics.

---

## Dashboard Preview

![Dashboard Preview](images/Sales_analysis_preview.gif)

---

## Business Problem

Traditional sales reports often make it difficult to:

- Analyze sales performance across products and customers
- Track sales trends over time
- Compare actual sales against budget targets
- Identify top-performing products and customers
- Access actionable insights quickly

An interactive reporting solution was required to improve business visibility and support data-driven decision-making.

---

## Business Analysis Activities

### Requirement Analysis
- Identified reporting objectives
- Defined analytical requirements
- Mapped business needs to dashboard features

### Documentation
- Created Business Requirement Documentation (BRD)
- Defined user stories and acceptance criteria
- Documented reporting requirements

### Solution Design
- Defined KPIs and reporting metrics
- Designed dashboard structure and navigation
- Planned analytical views for business users

---

## Project Objectives

- Analyze sales performance over time
- Compare sales performance against budget
- Identify top-performing customers
- Identify best-selling products
- Enable interactive filtering and reporting
- Improve visibility into business performance

---

## Data Preparation

Data was extracted, cleansed, and transformed using SQL before loading into Power BI.

### Fact Tables
- FACT_InternetSales
- FACT_Budget

### Dimension Tables
- DIM_Customers
- DIM_Products
- DIM_Calendar

---

## Data Modeling

A Star Schema data model was implemented to support efficient reporting and analysis.

### Relationships
- Customer → Sales
- Product → Sales
- Calendar → Sales

The model enables analysis across customers, products, and time periods.

---

## Dashboard Pages

### 1. Sales Overview

Provides a high-level summary of sales performance.

**Features**
- Sales vs Budget KPI
- Product Category Analysis
- Top 10 Customers
- Top 10 Products
- Sales Trend Analysis
- Geographic Sales Distribution
- Year and Month Filters

---

### 2. Customer Details

Provides customer-level sales analysis.

**Features**
- Top Customers Analysis
- Customer Purchase Trends
- Monthly Sales Analysis
- Budget Comparison
- Interactive Filtering

---

### 3. Product Details

Provides product-level sales analysis.

**Features**
- Top Products Analysis
- Product Sales Trends
- Monthly Product Analysis
- Budget Comparison
- Interactive Filtering

---

## Key Performance Indicators (KPIs)

- Sales
- Budget
- Profit
- Top 10 Customers
- Top 10 Products
- Product Category Performance
- Sales Trend Analysis
- Geographic Sales Distribution

---

## Business Value Delivered

The dashboard enables stakeholders to:

- Monitor sales performance efficiently
- Compare actual sales against budget targets
- Identify high-value customers
- Identify best-selling products
- Analyze sales trends over time
- Perform self-service analysis through filters
- Make faster and more informed business decisions

---

## Skills Demonstrated

### Business Analysis
- Requirement Analysis
- Business Requirement Documentation (BRD)
- User Story Definition
- Acceptance Criteria Mapping

### Data Analysis
- SQL
- Data Cleansing
- Data Transformation
- KPI Development

### Business Intelligence
- Power BI
- DAX
- Star Schema Modeling
- Dashboard Development
- Data Visualization

---

## Tools & Technologies

- Power BI
- SQL Server
- SQL
- DAX
- Microsoft Excel
- Star Schema Modeling

---

## Project Outcome

Successfully transformed sales data into an interactive Business Intelligence solution.

The dashboard provides visibility into:

- Customer Performance
- Product Performance
- Sales Trends
- Budget Tracking
- Geographic Sales Distribution

The solution supports data-driven decision-making through interactive reporting and analytical insights.

---

## Repository Contents

```text
Sales-Analysis-Budget-Management/
│
├── README.md
├── Sales Report_Finished.pbix
├── Business Analysis Report.pdf
├── User Stories.pdf
│
└── images/
    └── Sales_analysis_preview.gif
```

---

## Author

**Sruthi S**

B.Tech Computer Science and Design

Aspiring Business Analyst
