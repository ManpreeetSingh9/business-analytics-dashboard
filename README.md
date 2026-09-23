
# Business Intelligence & Advanced Analytics Dashboard \| SQL • Power BI • DAX

## 📌 Project Overview

-   **Business-focused analytical dashboard** built to transform raw
    customer and product data into actionable business insights.
-   The project follows a complete **data preparation → transformation →
    modelling → analytics → visualization** workflow.
-   Raw data is **first transformed and prepared using SQL queries**,
    including business-oriented aggregations and analytical
    calculations.
-   The transformed data is then imported into **Power BI** for data
    modelling, advanced DAX measures, interactive analysis, and
    visualization.
-   Designed with a **management and decision-making perspective**,
    focusing on the questions businesses typically ask about customers,
    sales, products, demand, and performance.
-   The dashboard is divided into two analytical views:
    -   **Customer Intelligence Dashboard**
    -   **Product Performance Dashboard**

------------------------------------------------------------------------

## 🎯 Business Objective

-   Convert transactional-level data into **high-level business
    intelligence** that can support data-driven decisions.
-   Identify the **customers, products, categories, and periods
    contributing most to revenue**.
-   Understand customer behaviour through **segmentation, recency,
    purchasing value, and spending patterns**.
-   Evaluate product performance using **sales, quantity sold, product
    segments, categories, and subcategories**.
-   Identify high-performing products and areas of demand that can
    support **sales planning, inventory decisions, customer strategy,
    and revenue optimization**.
-   Provide an interactive analytical layer where users can drill into
    business performance using filters and customer/product selections.

------------------------------------------------------------------------

# 👥 Customer Intelligence Dashboard

## 📊 Key Business KPIs

The customer dashboard provides an executive-level snapshot of customer
performance:

-   **18.5K Total Customers**
-   **\$29.4M Total Sales**
-   **60.4K Units Sold**
-   **5 Average Customer Lifespan**
-   **\$911.7 Average Order Value**
-   **\$452.8 Average Monthly Spend**

These KPIs provide a quick view of the overall customer base, revenue
contribution, purchasing volume, and customer value.

## 🔎 Customer Analytics Covered

-   **Sales by Age Group**
    -   Analyzes revenue contribution across different customer age
        groups.
    -   Helps identify customer demographics associated with higher
        sales.
-   **Sales by Customer Segment**
    -   Compares revenue contribution from:
        -   New Customers
        -   Regular Customers
        -   VIP Customers
    -   Provides visibility into the revenue mix of different customer
        segments.
-   **Recency Distribution**
    -   Examines the distribution of customers based on recency.
    -   Helps identify customer activity patterns and potential
        opportunities for customer re-engagement.
-   **Top 5 Value Customers**
    -   Highlights the highest-value customers using **sales and
        quantity-based analysis**.
    -   Helps identify customers with significant commercial
        contribution.
-   **Monthly Sales Distribution**
    -   Shows how sales are distributed throughout the year.
    -   Helps identify periods of stronger and weaker revenue
        performance.
-   **Sales Over Time**
    -   Uses a **running-total analysis** to understand cumulative
        revenue progression across years.
    -   Supports trend analysis and long-term performance evaluation.
-   **Interactive Customer Analysis**
    -   Enables filtering by:
        -   Customer Segment
        -   Age Group
        -   Recency
        -   Lifespan
        -   Customer Search

------------------------------------------------------------------------

# 📦 Product Performance Dashboard

## 📊 Key Business KPIs

The product dashboard provides a high-level view of product and sales
performance:

-   **\$29.4M Total Sales**
-   **60.4K Total Quantity Sold**
-   **27.7K Total Orders**
-   **18K Total Customers**
-   **\$1.09K Average Selling Price**
-   **\$14.8K Average Monthly Revenue**

## 🔎 Product Analytics Covered

-   **Sales by Subcategory**
    -   Identifies which product subcategories contribute most to total
        revenue.
    -   Enables comparison of major revenue-generating product groups.
-   **Sales by Category**
    -   Provides a category-level view of revenue performance.
    -   Helps understand the overall contribution of major product
        categories such as Bikes, Accessories, and Clothing.
-   **Top 15 Products by Sales**
    -   Identifies the highest-revenue products.
    -   Helps highlight products with strong commercial performance.
-   **Product Sales by Year**
    -   Tracks product revenue across years.
    -   Helps analyze changes in product sales performance over time.
-   **Sales by Product Segment**
    -   Compares products across:
        -   High-Performer
        -   Mid-Range
        -   Low-Performer
    -   Provides a portfolio-level view of product performance.
-   **Top Products in Demand**
    -   Uses **quantity sold** to identify products with strong customer
        demand.
    -   Provides a different perspective from revenue-based product
        rankings.
-   **Interactive Product Analysis**
    -   Enables filtering by:
        -   Category
        -   Subcategory
        -   Product Segment
        -   Product Name

------------------------------------------------------------------------

# 🧠 Advanced Analytics & Technical Implementation

## SQL Data Transformation

-   Raw business data is **first transformed using SQL queries** before
    being consumed by Power BI.
-   SQL is used as the initial analytical layer to prepare
    business-ready data.
-   Transformation focuses on creating meaningful analytical attributes
    and aggregated business metrics.
-   This approach separates **data preparation from visualization**,
    creating a more structured BI workflow.

## Power BI Data Modelling

-   Transformed data is brought into **Power BI** for analytical
    modelling.
-   A structured data model is used to support relationships, filtering,
    aggregation, and interactive analysis.
-   The model is designed to allow customer and product dimensions to be
    analyzed from multiple business perspectives.
-   Data modelling enables consistent calculations across dashboard
    visuals and filters.

## DAX & Advanced Measures

-   The dashboard uses **DAX measures** rather than relying only on
    basic visual aggregations.
-   Measures support business-focused calculations such as:
    -   Total Sales
    -   Total Quantity Sold
    -   Total Orders
    -   Customer Counts
    -   Average Order Value
    -   Average Monthly Spend
    -   Average Selling Price
    -   Average Monthly Revenue
    -   Running Total Sales
-   Running-total analysis is used to evaluate **cumulative sales
    progression over time**.
-   Measures allow the dashboard to dynamically respond to filters and
    user selections.

------------------------------------------------------------------------

# 💡 Key Business Questions Answered

The dashboard is designed to answer questions such as:

### Customer Intelligence

-   Who are the highest-value customers?
-   Which customer segments contribute the most revenue?
-   How is revenue distributed across different age groups?
-   How recently are customers purchasing?
-   What is the average value generated by a customer?
-   How does customer spending vary over time?
-   Which periods generate the highest sales?

### Product Intelligence

-   Which products generate the highest revenue?
-   Which products have the highest demand based on quantity sold?
-   Which categories and subcategories contribute the most sales?
-   Which products belong to high-performing segments?
-   How does product revenue change across years?
-   Are the products generating the most revenue also the products with
    the highest demand?
-   Which areas of the product portfolio contribute most to overall
    revenue?

------------------------------------------------------------------------

# 📈 Business Value

-   **Revenue Intelligence:** Identifies the products, customers,
    categories, and periods driving revenue.
-   **Customer Intelligence:** Provides visibility into customer
    segments, recency, spending, and value.
-   **Product Intelligence:** Separates revenue performance from
    unit-demand performance for a more complete product evaluation.
-   **Performance Monitoring:** Enables year-over-year and cumulative
    sales analysis.
-   **Decision Support:** Converts large datasets into concise business
    metrics that can support management decisions.
-   **Interactive Exploration:** Allows stakeholders to move from
    high-level KPIs to specific customers, products, categories, and
    segments.
-   **Data-Driven Strategy:** Helps identify where revenue and demand
    are concentrated, providing a foundation for sales, customer, and
    product strategy.

------------------------------------------------------------------------

# 🛠️ Technology Stack

  -----------------------------------------------------------------------
  Technology                          Purpose
  ----------------------------------- -----------------------------------
  **SQL**                             Data transformation, preparation,
                                      aggregation, and analytical data
                                      creation

  **Power BI**                        Data modelling, dashboard
                                      development, interactive
                                      visualization

  **DAX**                             Advanced measures, KPIs, dynamic
                                      calculations, and running-total
                                      analysis

  **Power BI Filters/Slicers**        Interactive business analysis
  -----------------------------------------------------------------------

------------------------------------------------------------------------

# 🔄 End-to-End BI Workflow

``` text
Raw Business Data
       ↓
SQL Data Transformation
       ↓
Business-Ready Dataset
       ↓
Power BI Data Modelling
       ↓
DAX Measures & Calculations
       ↓
Interactive Visualizations
       ↓
Business Insights & Decision Support
```

------------------------------------------------------------------------

# 📂 Project Structure

``` text
Business-Analytics-Dashboard/
│
├── dataset/
│   └── Raw / source datasets
│
├── scripts/
│   └── SQL transformation queries
│
├── dashboard/
│   ├── Business_Analytics_Dashboard.pbix
│   └── Dashboard_Preview.pdf
│
└── docs/
    └── Project documentation
```

------------------------------------------------------------------------

# 🚀 Skills Demonstrated

-   SQL data transformation
-   Business-oriented data preparation
-   Power BI dashboard development
-   Data modelling
-   DAX measures
-   KPI development
-   Running-total analysis
-   Customer segmentation analysis
-   Customer value analysis
-   Product performance analysis
-   Revenue and demand analysis
-   Time-series analysis
-   Interactive filtering and drill-down analysis
-   Data storytelling
-   Business intelligence and decision support

------------------------------------------------------------------------

# 📌 Recruiter Snapshot

> **A complete SQL + Power BI Business Intelligence project
> demonstrating the ability to transform raw data into decision-ready
> insights. The project combines SQL-based data transformation, Power BI
> data modelling, DAX measures, KPI development, customer intelligence,
> product analytics, and interactive visualization to answer practical
> business questions around revenue, customer value, product
> performance, demand, and growth trends.**

### What this project demonstrates

-   **Not just visualization:** data is transformed and prepared using
    SQL before visualization.
-   **Not just basic Power BI:** the dashboard incorporates **data
    modelling and DAX measures** for advanced analytics.
-   **Business-first thinking:** metrics and visuals are designed around
    questions relevant to revenue, customers, products, and performance.
-   **Analytical depth:** combines revenue-based, quantity-based,
    customer-based, segmentation, and time-based analysis.
-   **Decision-oriented output:** converts raw data into concise
    insights that can help stakeholders understand business performance
    and identify areas requiring attention.

------------------------------------------------------------------------

## 📄 Dashboard Preview

The project includes both **Customer Intelligence** and **Product
Performance** dashboards, covering approximately **\$29.4M in sales**,
**60.4K units sold**, and thousands of customers/orders across the
analyzed dataset. fileciteturn0file0

------------------------------------------------------------------------

## ⭐ Project Focus

**SQL → Data Transformation → Data Modelling → DAX → Advanced Analytics
→ Power BI → Business Insights**

This project demonstrates an end-to-end approach to **Business
Intelligence and Data Analytics**, with emphasis on turning business
data into actionable information rather than simply creating visual
reports.
