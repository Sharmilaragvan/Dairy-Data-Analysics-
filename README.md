# Dairy-Data-Analysics-
Power BI dashboard connected to SQL for analyzing dairy farm operations, product sales, revenue trends, and brand performance across Indian states from 2019–2022.







# Dairy Data Analysis — SQL to Power BI

## Project Overview

This project performs end-to-end data analysis on a dairy business dataset, starting from data extraction and transformation in SQL to building an interactive dashboard in Power BI. The dashboard provides actionable insights on revenue, production volume, land usage, product-wise sales, brand performance, and storage conditions across multiple Indian states and farm sizes.

## Objectives

- Analyze total revenue, quantity produced, and land utilization across dairy farms
- Identify top-performing states, brands, and product categories
- Understand sales distribution across channels — Online, Retail, and Wholesale
- Examine shelf life patterns based on storage conditions
- Enable year-wise and farm-size-based filtering for granular insights

## Key Metrics

| Metric | Value |
|---|---|
| Total Revenue | 58.73 Million |
| Sum of Quantity Produced | 2.17 Million |
| Total Land | 2.18 Million acres |
| Years Covered | 2019 to 2022 |

## Dashboard Visuals

**Sum of Cattles and Total Milk Produced by Location**
A grouped bar chart comparing total land area, number of cattle, and quantity produced across states including Delhi, Chandigarh, Uttar Pradesh, Madhya Pradesh, and Gujarat.

**Total Revenue by Customer Location**
A treemap showing revenue distribution across Indian states. Major contributors include Delhi, Bihar, Kerala, West Bengal, Maharashtra, Telangana, Madhya Pradesh, Rajasthan, and Haryana.

**Sum of Quantity Sold by Product Name**
A line chart tracking quantity sold in liters or kilograms across products — Curd, Lassi, Milk, Butter, Paneer, Ice Cream, Yogurt, Cheese, Buttermilk, and Ghee.

**Sum of Quantity by Brand**
A horizontal bar chart ranking dairy brands by total quantity. Top brands include Amul at 525K, Mother Dairy at 510K, Raj at 347K, and Sudha at 317K. Other brands listed include Palle2patnam, Dodla Dairy, Warana, Dynamix Dairies, Parag Milk Foods, Passion Cheese, and Britannia Industries.

**Shelf Life by Storage Condition**
A donut chart breaking down storage methods — Polythene at 61.53%, Ambient at 16.45%, Tetra Pack, Frozen, Refrigerated, and others.

## Filters and Slicers

- Year: 2019, 2020, 2021, 2022
- Farm Size: Large, Medium, Small
- Sales Channel: Online, Retail, Wholesale

## Tools and Technologies

| Tool | Purpose |
| SQL (MySQL / SQL Server) | Data extraction, joins, aggregations, and cleaning |
| Power BI Desktop | Dashboard design and DAX measures |
| Power Query | Data transformation and loading |
| DAX | Custom KPIs and calculated columns |

## Project Structure


dairy-data-analysis/
    dairy_analysis.pbix         # Power BI dashboard file
    dairy_queries.sql           # SQL scripts for data preparation
    data/
        dairy_raw.csv           # Source dataset
    screenshots/
        dashboard.png           # Dashboard preview
    README.md


## Key Insights

- Amul leads all brands in quantity sold, followed closely by Mother Dairy, reflecting their dominance in the organized dairy sector.
- Delhi and Bihar contribute the highest revenue among customer locations.
- Polythene packaging accounts for the majority of storage at over 61%, indicating a need to evaluate shelf-life optimization.
- Milk, Curd, and Ghee show the highest product-level sales volumes.
- Wholesale and Retail channels collectively outperform Online, typical for perishable commodity distribution.

## How to Use

1. Clone this repository
2. Open the `.pbix` file in Power BI Desktop
3. Update the data source connection under Transform Data to point to your local SQL database or CSV file
4. Use the slicers on the left panel to filter by Year, Farm Size, or Sales Channel
5. Hover over any visual for detailed tooltips


