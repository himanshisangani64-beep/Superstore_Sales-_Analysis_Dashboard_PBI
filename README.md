 <div align="center">

# 📊 Superstore Sales Analysis Dashboard

### *Data Cleaning, Transformation & Interactive Business Intelligence Dashboard*

**Power Query | Microsoft Power BI | Data Analytics**

</div>

---

## 📋 Table of Contents

- [📌 Project Overview](#-project-overview)
- [🎯 Problem Statement](#-problem-statement)
- [✨ Key Features](#-key-features)
- [🔄 Project Workflow](#-project-workflow)
- [🅰️ Part A — Data Cleaning & Transformation](#-part-a--data-cleaning--transformation)
- [🅱️ Part B — Sales Analysis Dashboard](#-part-b--sales-analysis-dashboard)
- [🎥 Dashboard Walkthrough & Demonstration](#-dashboard-walkthrough--demonstration)
- [📈 Key Performance Indicators (KPIs)](#-key-performance-indicators-kpis)
- [🔍 Business Insights](#-business-insights)
- [🛠️ Tech Stack](#️-tech-stack)
- [🏆 Advantages](#-advantages)
- [🙏 Acknowledgements](#-acknowledgements)
- [👩‍💻 About the Author](#-about-the-author)

---

## 📌 Project Overview

The **Superstore Sales Analysis Dashboard** is a data analytics project developed to understand sales performance, profitability, regional revenue, and product-category performance using a Superstore sales dataset.

This project is divided into two major parts:

- **Part A — Data Transformation:** Cleaning, filtering, and preparing the dataset using Power Query Editor.
- **Part B — Dashboard Development:** Creating an interactive dashboard in Microsoft Power BI to analyze sales, profit, quantity, discount, and regional performance.

The main objective of this project is to transform raw sales data into meaningful visual insights that help users understand business performance and support data-driven decision-making.

---

## 🎯 Problem Statement

Businesses generate large amounts of sales data, but raw data is not always ready for analysis. Errors, blank rows, inconsistent column names, and unorganized data can make reporting difficult.

**Objective:** To clean and transform the Superstore dataset and develop an interactive Power BI dashboard that presents important sales and profit metrics in a clear and understandable format.

The project focuses on the following business questions:

- What are the overall sales, profit, quantity, and average discount?
- Which region generates the highest revenue?
- Which region has the highest profit?
- Which product category generates the highest revenue?
- Which sub-categories have the highest sales?
- How does performance change when a category or region is selected?

---

## ✨ Key Features

| Feature | Description |
|---|---|
| Data Cleaning | Removes unsuitable blank rows and errors from the data |
| Data Transformation | Changes data types, renames columns, and reorders fields |
| KPI Cards | Displays Total Sales, Total Profit, Total Quantity, and Average Discount |
| Regional Analysis | Compares revenue and profit across four regions |
| Category Analysis | Compares revenue and profit across product categories |
| Sub-Category Analysis | Displays the top five sub-categories by sales |
| Interactive Slicers | Filters dashboard visuals by category and region |
| Visual Reporting | Presents business metrics using charts and KPI cards |

---

## 🔄 Project Workflow

```text
        Superstore Dataset
                |
                v
        Power Query Editor
                |
                v
          Data Cleaning
                |
                v
        Data Transformation
                |
                v
         Prepared Dataset
                |
                v
        Microsoft Power BI
                |
                v
        KPI Cards & Charts
                |
                v
        Interactive Slicers
                |
                v
      Business Insights
```

---

## 🅰️ Part A — Data Cleaning & Transformation

### 1. Overview

The first part of the project focuses on preparing the Superstore dataset for analysis using **Power Query Editor**.

Data cleaning and transformation help organize the dataset and make it more suitable for creating accurate reports and visualizations.

### 2. Data Transformation Steps

The following applied steps are visible in the Power Query screenshot:

| Step | Purpose |
|---|---|
| Source | Connects to the source dataset |
| Promoted Headers | Uses the first row as column headers |
| Changed Type | Assigns appropriate data types to columns |
| Renamed Columns | Improves column names for readability |
| Removed Errors | Removes rows containing errors in the affected data |
| Removed Null Rows | Removes unsuitable rows containing null values |
| Removed Blank Rows | Removes empty rows |
| Filtered Rows | Applies filters to the dataset |
| Split Column by Delimiter | Splits a column using a specified delimiter |
| Reordered Columns | Arranges columns in a useful order |

These steps are based on the visible Applied Steps panel. The exact transformations depend on the original Power Query configuration.

### 3. Dataset Columns

The following columns are visible in the Power Query:

- Order Region Code
- Order ID
- Order Date
- Shipping Date
- Shipping Mode
- Customer ID
- Customer Name
- Segment
- City
- State
- Region
- Product ID
- Category
- Sub-Category
- Product Name
- Sales
- Quantity
- Discount
- Profit


### 4. Part A Screenshot

![Power Query Data Transformation](images/Powe_Query.png)


### 5. Outcome of Part A

After the transformation process, the dataset is prepared for use in Power BI. Cleaning and organizing the data helps make the analysis workflow more structured and easier to maintain.

---

## 🅱️ Part B — Sales Analysis Dashboard

### 1. Overview

The second part of the project focuses on creating an interactive **Superstore Sales Analysis Dashboard** using Microsoft Power BI.

The dashboard combines KPI cards, a donut chart, bar charts, and slicers to present important sales and profit metrics in one place.

### 2. Dashboard Components

| Visualization | Business Purpose |
|---|---|
| Profit by Product Category | Compares profit across Technology, Office Supplies, and Furniture |
| Total Revenue by Region | Compares revenue across Central, East, West, and South |
| Total Revenue by Product Category | Compares revenue across the three product categories |
| Profit by Region | Compares profit across four regions |
| Sales by Sub-Category | Displays the top five sub-categories by sales |
| Category Slicer | Filters the dashboard by product category |
| Region Slicer | Filters the dashboard by region |

### 3. Part B Screenshot

![Superstore Sales Analysis Dashboard](images/dashboard_image.png)

---

## 🎥 Dashboard Walkthrough & Demonstration

Explore the Superstore Sales Analysis Dashboard through a comprehensive video walkthrough showcasing the data visualization, interactive reporting features, and key business insights developed using Microsoft Power BI.

[**View the Full Project Walkthrough**](https://drive.google.com/file/d/1S8WAdbbr8RNKkelws3cgu-OuDv4kG9F4/view?usp=drive_link)

*The video covers key performance indicators (KPIs), regional sales and profitability, product category analysis, interactive slicers, and actionable business insights.*

---


## 📈 Key Performance Indicators (KPIs)

The following KPI values are displayed in the supplied dashboard screenshot.

| KPI | Displayed Value |
|---|---:|
| Total Sales | 368.13K |
| Total Profit | 45.80K |
| Total Quantity | 6K |
| Average Discount | 0.16 |

*Note: These values are transcribed from the screenshot. They may change when slicers are applied or when the underlying dataset is updated.*

---

## 🔍 Business Insights

Based on the values displayed in the dashboard:

### 1. Regional Revenue Analysis

- Central has the highest displayed regional revenue at approximately **108K**.
- East follows with approximately **97K**.
- West shows approximately **94K**.
- South shows approximately **69K**.

### 2. Regional Profit Analysis

- East displays approximately **15.3K** in profit.
- West displays approximately **14.6K**.
- South displays approximately **10.0K**.
- Central displays approximately **5.9K**.

East has the highest displayed profit, while West has the second-highest.

### 3. Product Category Revenue

The dashboard displays the following approximate revenue values:

- Technology: **140K**
- Furniture: **123K**
- Office Supplies: **105K**

Technology is the highest-revenue category in the displayed chart.

### 4. Top Five Sub-Categories by Sales

| Rank | Sub-Category | Approximate Sales |
|---:|---|---:|
| 1 | Chairs | 51K |
| 2 | Phones | 41K |
| 3 | Machines | 40K |
| 4 | Tables | 35K |
| 5 | Copiers | 30K |

Chairs is the leading sub-category among the five displayed in the dashboard.

*These findings describe the values visible in the supplied screenshot. Verify the figures against the underlying Power BI report before using them for business decisions.*

### 5. Interactive Dashboard Analysis

The dashboard includes two slicers:

- **Category:** Select a product category to filter the visuals.
- **Region:** Select a region to focus on its performance.

These slicers allow users to explore the data without manually creating separate reports for each category or region.

---

## 🛠️ Tech Stack

| Tool / Technology | Purpose |
|---|---|
| Microsoft Power Query | Data cleaning and transformation |
| Microsoft Power BI | Dashboard development and visualization |
| Superstore Dataset | Source data for sales analysis |

---

## 🏆 Advantages

| Advantage | Description |
|---|---|
| Organized Data | Power Query helps prepare data before analysis |
| Easy Reporting | KPI cards provide a quick overview of key metrics |
| Visual Comparison | Charts make regional and category comparisons easier |
| Interactive Analysis | Slicers allow users to filter the dashboard |
| Business Understanding | Helps identify high-performing regions and sub-categories |
| Portfolio Development | Demonstrates practical data analytics skills |

---

## 🙏 Acknowledgements

I would like to express my gratitude to the people and resources that supported my learning and project development.

- **Teachers and Mentors:** For their guidance, feedback, and support throughout my learning journey.
- **Microsoft Power BI:** For providing tools to create interactive dashboards and visualizations.
- **Microsoft Power Query:** For providing data cleaning and transformation capabilities.
- **Superstore Dataset:** For providing the sales data used in this project.

---

## 👩‍💻 About the Author

**Himanshi Sangani**

🎓 **Education:** Bachelor of Computer Applications (BCA) Graduate

📊 **Project Focus:** Data Analytics and Business Intelligence

🛠️ **Skills:** Power Query, Microsoft Power BI, Data Cleaning, Data Transformation, Data Visualization, KPI Analysis, and Dashboard Development.


---

<div align="center">

### Thank You for Visiting!

*Learning • Analyzing • Visualizing • Growing*

</div>
