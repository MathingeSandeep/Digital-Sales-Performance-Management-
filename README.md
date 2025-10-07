# Digital Sales Performance Management

## Project Overview
This project focuses on a deep-dive analysis of an e-commerce platform's sales and profitability over two years (2021-2022). The primary objective was to move beyond simple revenue tracking to identify specific drivers of profit growth, pinpointing high-risk customer segments and areas of sales concentration to guide strategic business decisions.


**🛠️ Tools and Technologies**

- **Database :** SQL Server (Used for advanced querying)

- **Data Analysis :** Advanced SQL (CTEs, Window Functions, YoY calculations)

- **Visualization & Reporting :** Power BI (To create the final interactive dashboard)

- **Data Source :** CSV files


**📈 Key Achievements & Business Impact**

This analysis on $11.53M in sales resulted in tangible, **quantifiable insights :**
  
- **Profitability Improvement :** Delivered insights that drove a 4.50% profit increase and 5.37% gain in overall profit margin, successfully mitigating a minor revenue decline (-0.83% YoY).

- **Strategic Segmentation :** Isolated the high-risk Home Office segment (down -1.93% YoY in sales) for immediate intervention and confirmed 60% sales concentration in two key regional markets (CA and NY) for resource allocation.

- **Operational Focus :** Quantified performance across all dimensions (products, regions, shipping types) to recommend strategic focus areas, such as optimizing the dominant Standard Class shipping channel (60.51% of sales).


**📊 Methodology**

The analysis followed a structured process, documented in the associated files:

**1. Data Source**

The primary dataset is stored in ecommerce_data.csv, which contains transactional details, customer demographics, and product information. A supplementary file, us_state_long_lat_codes.csv, was used for geographical mapping in the BI tool.

**2. Data Wrangling & ETL**

The raw data was loaded into a SQL environment (as detailed in the included SQL documentation). The main steps involved:

- Standardizing date formats and handling null values.

- Joining the main sales data with the geographical data for visualization context.

**3. Advanced SQL Querying**

All key performance indicators (KPIs) and analytical views were generated using complex SQL queries, which are available for review in the Digital Sales Performance Management SQL Queries.docx file. Specific query types include:

- **KPI Calculation (Query 1):** Calculating YTD Sales, Profit, and Profit Margin for 2022.

- **YoY Growth (Query 2 & 3):** Implementing Window Functions and Common Table Expressions (CTEs) to calculate Year-on-Year (YoY) growth rates for total sales and for each customer segment (Consumer, Corporate, Home Office).

- **Segmentation & Geography (Query 4 & 6):** Aggregating sales by customer state and region to determine the 60% concentration.

- **Product Performance (Query 5):** Identifying the top and bottom 5 selling products by total sales.

**4. Visualization & Reporting**

The final aggregated data was loaded into the Business Intelligence tool (Power BI) to create an interactive dashboard (visualized in the Digital Sales Performance Management.pdf report). The dashboard included:

- A KPI banner displaying YTD metrics and YoY trend arrows.

- Treemaps and bar charts showing sales breakdown by Category, Segment, and Product.

- A Geographical map view of sales concentration by state.

**📂 Repository Contents**
- ecommerce_data.csv: Main transactional sales dataset.

- us_state_long_lat_codes.csv: Supplementary data for state mapping.

- Digital Sales Performance Management SQL Queries.docx: All SQL scripts used for data extraction and aggregation.

- Digital Sales Performance Management.pdf: Final report containing the dashboard screenshots and key findings.
  
- **Screenshot :**
  
  ![Digital Sales Performance Management](https://github.com/user-attachments/assets/45cb45a2-e629-4906-8ae0-24b1475c7597)
