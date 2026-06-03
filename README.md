# Sales Analysis & Budget Management Dashboard

## Project Overview

The Sales Analysis & Budget Management Dashboard is a Business Intelligence and Data Analytics project developed using SQL Server and Power BI. The project focuses on transforming raw sales data into meaningful business insights through data preparation, modeling, visualization, and KPI reporting.

Organizations generate large volumes of sales data every day, but raw data alone does not help decision-makers. This project demonstrates how data can be extracted, transformed, modeled, and visualized to help stakeholders monitor sales performance, compare actual sales against budget targets, identify top-performing customers and products, and analyze business trends over time.

The final solution consists of interactive Power BI dashboards that provide a comprehensive view of sales performance and support data-driven decision-making.

---

## Dashboard Screenshots

### Sales Overview Dashboard

![Sales Overview](sales-overview.png)

The Sales Overview dashboard provides a high-level summary of business performance. It enables stakeholders to monitor sales trends, evaluate budget performance, identify top customers and products, and analyze sales distribution across different regions.

---

### Customer Details Dashboard

![Customer Details](customer-details.png)

The Customer Details dashboard focuses on customer-level analysis. It helps identify high-value customers, understand purchasing behavior, and evaluate customer contribution to overall revenue.

---

### Product Details Dashboard

![Product Details](product-details.png)

The Product Details dashboard provides detailed product performance analysis. It helps identify best-selling products, monitor product trends, and evaluate product contribution to sales revenue.

---

## Business Problem

Many organizations rely on static reports and spreadsheets for monitoring sales performance. While these reports provide historical information, they often lack flexibility and make it difficult to perform deeper analysis.

Common challenges include:

- Difficulty identifying top-performing products and customers.
- Limited visibility into sales trends and performance over time.
- Lack of comparison between actual sales and budget targets.
- Time-consuming manual reporting processes.
- Inability to perform interactive analysis using filters and drill-downs.

To address these challenges, an interactive reporting solution was required to provide stakeholders with actionable insights and improve decision-making.

---

## Project Objectives

The primary objectives of this project were:

- Analyze sales performance across different time periods.
- Compare actual sales against budget targets.
- Identify top-performing products and customers.
- Monitor business performance using KPIs.
- Analyze sales distribution across geographical regions.
- Enable interactive and self-service reporting.
- Support data-driven business decisions through visualization and analytics.

---

## Dataset Overview

The project utilizes sales, customer, product, calendar, and budget datasets.

### FACT_InternetSales

The Internet Sales fact table contains transactional sales data and serves as the primary source for revenue analysis.

Key fields include:

- Product Key
- Customer Key
- Order Date
- Sales Order Number
- Sales Amount

This table is used to calculate sales performance metrics and revenue-related KPIs.

---

### FACT_Budget

The Budget fact table contains planned sales targets used for comparison against actual sales performance.

This table enables variance analysis and helps measure business performance against predefined goals.

---

### DIM_Customers

The Customer dimension table contains customer-related information used for customer analysis.

Key attributes include:

- Customer Name
- Gender
- Customer City
- Date of First Purchase

This table supports customer segmentation and revenue contribution analysis.

---

### DIM_Products

The Product dimension table contains product-related information used for product performance analysis.

Key attributes include:

- Product Name
- Product Category
- Product Subcategory
- Product Color
- Product Status

This table helps identify high-performing products and product categories.

---

### DIM_Calendar

The Calendar dimension table contains date-related information used for trend analysis and time intelligence reporting.

Key attributes include:

- Date
- Month
- Quarter
- Year

This table enables monthly, quarterly, and yearly sales analysis.

---

## Data Preparation

Data preparation was performed using SQL Server before loading the data into Power BI.

The preparation process included:

### Data Extraction

Relevant tables were extracted from the source database to support reporting requirements.

### Data Cleansing

Unnecessary fields were removed and only business-relevant attributes were retained.

### Data Transformation

Columns were renamed and transformed into a business-friendly format to improve readability and usability.

### Data Validation

Data quality checks were performed to ensure consistency and accuracy before dashboard development.

The transformed dataset was then imported into Power BI for modeling and visualization.

---

## Data Modeling

A Star Schema data model was implemented to improve reporting performance and simplify analysis.

### Fact Tables

- FACT_InternetSales
- FACT_Budget

### Dimension Tables

- DIM_Customers
- DIM_Products
- DIM_Calendar

The fact tables store transactional data, while the dimension tables provide descriptive information used for filtering and categorization.

### Benefits of Star Schema

- Faster query performance
- Improved dashboard responsiveness
- Simplified report development
- Easier maintenance and scalability
- Better analytical capabilities

---

## DAX Measures

Several DAX measures were created to support KPI reporting and business analysis.

### Total Sales

Calculates the total revenue generated from sales transactions.

```DAX
Sales =
SUM ( FACT_InternetSales[SalesAmount] )
```

### Total Budget

Calculates the total budget allocated for the selected period.

```DAX
Budget =
SUM ( FACT_Budget[Budget] )
```

### Profit

Calculates the difference between actual sales and budget.

```DAX
Profit =
[Sales] - [Budget]
```

These measures form the foundation of the dashboard's KPI reporting.

---

## Dashboard Pages

### 1. Sales Overview Dashboard

The Sales Overview dashboard provides a consolidated view of business performance.

Key features include:

- Sales vs Budget KPI
- Product Category Analysis
- Top 10 Customers
- Top 10 Products
- Sales Trend Analysis
- Geographic Sales Distribution
- Year and Month Filters

Business users can quickly assess overall performance and identify important trends.

---

### 2. Customer Details Dashboard

The Customer Details dashboard focuses on customer-level insights.

Key features include:

- Top Customers by Revenue
- Customer Purchase Trends
- Monthly Sales Analysis
- Budget Comparison
- Interactive Filtering

This dashboard helps businesses identify valuable customers and understand customer purchasing patterns.

---

### 3. Product Details Dashboard

The Product Details dashboard focuses on product-level performance.

Key features include:

- Top Products by Sales
- Product Performance Trends
- Monthly Product Analysis
- Budget Comparison
- Interactive Filtering

This dashboard helps stakeholders evaluate product success and identify opportunities for growth.

---

## Key Performance Indicators (KPIs)

The project tracks several important business metrics.

### Total Sales

Measures the total revenue generated during the selected period.

### Budget

Represents planned sales targets used for performance evaluation.

### Profit

Measures the variance between actual sales and budget.

### Top Customers

Identifies customers contributing the highest revenue.

### Top Products

Identifies products generating the highest sales.

### Product Category Performance

Measures sales contribution across product categories.

### Sales Trends

Tracks sales growth and performance over time.

### Geographic Sales Distribution

Visualizes sales performance across different locations.

---

## Key Insights

The dashboard enables several business insights, including:

- Identification of top-performing products and categories.
- Recognition of high-value customers contributing significant revenue.
- Analysis of sales trends across different time periods.
- Evaluation of business performance against budget targets.
- Identification of geographical regions generating the highest sales.

These insights support strategic planning and operational decision-making.

---

## Tools & Technologies Used

### Data Analysis
- SQL Server
- SQL

### Business Intelligence
- Power BI
- DAX

### Data Modeling
- Star Schema Design

### Supporting Tools
- Microsoft Excel

---

## Skills Demonstrated

This project demonstrates the following skills:

### Data Analysis
- SQL Querying
- Data Extraction
- Data Cleaning
- Data Transformation
- Data Validation

### Data Modeling
- Star Schema Design
- Fact and Dimension Modeling
- Relationship Management

### Data Visualization
- Dashboard Design
- Interactive Reporting
- KPI Reporting
- Business Data Visualization

### Business Intelligence
- DAX Measures
- Performance Monitoring
- Trend Analysis
- Data-Driven Decision Support

---

## Project Outcome

The project successfully transformed raw sales data into an interactive Business Intelligence solution.

The dashboard provides stakeholders with visibility into:

- Sales Performance
- Customer Performance
- Product Performance
- Budget Tracking
- Geographic Sales Analysis

By combining SQL-based data preparation, star schema modeling, DAX calculations, and Power BI visualizations, the solution enables efficient reporting and supports data-driven business decision-making.

---

## Author

**Sruthi S**

B.Tech Computer Science and Design

Aspiring Data Analyst | Business Analyst
