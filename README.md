# walmart-sales-executive-report
Google Spreadsheet - Walmart Sales Data Analysis &amp; Executive Dashboard

## 📌 Project Overview & Documentation

### 1. Project Context
This project evaluates the sales performance and spatial efficiency of Walmart's retail departments throughout the fiscal year 2012. In retail data analytics, gross revenue alone doesn't reveal the complete operational picture. By cross-referencing total sales with the physical square meters ($m^2$) allocated to each department, this study identifies which categories maximize profitability and yield relative to their store footprint.

### 2. Methodology & Analysis
The analytical workflow followed an end-to-end Data Analytics lifecycle within Excel:
* **Data Integration (ETL):** Consolidated transactional records from raw sales (`raw_ventas`), store dimensions (`raw_tiendas`), and master department catalogs (`raw_departamento`) into a unified analytics table (`clean_ventas`).
* **Quality Assurance (QA) & Validation:** Designed rigorous data sanity checks using conditional formulas (`COUNTIF`/`CONTAR.SI`) to audit records, identifying unassigned department IDs, tracking down anomalous null or negative entries, and verifying zero-value store areas.
* **Aggregations & Business Intelligence:** Generated advanced Pivot Tables to compute corporate strategic KPIs:
  * *Sales per $m^2$:* Measures the financial yield and operational efficiency of the floor space.
  * <img width="883" height="298" alt="image" src="https://github.com/user-attachments/assets/97e5f068-1cd8-4152-b46e-e9965edc47eb" />


  * *Market Share per Department (%):* Measures the percentage contribution of each category against total organizational revenue.
  * <img width="710" height="302" alt="image" src="https://github.com/user-attachments/assets/522b6fc6-8c42-4ec5-a521-29c68958a222" />


### 3. Key Findings & Executive Insights
* **The Category Leader:** The analysis officially identifies the **"Despensas y Básicos"** (Groceries & Staples) department as the absolute top performer of 2012. It ranks #1 in spatial efficiency, generating an outstanding **$652.81 per $m^2$**.
* **Revenue Driver:** Concurrently, **"Despensas y Básicos"** represents Walmart's single largest revenue engine for the period, capturing **15.23%** of the company's total market share.
* **Data-Driven Strategy & Implications:** 
  * *Shelf-Space Optimization:* Based on these efficiency returns, Walmart should increase aisle exposure and shelf allocation for high-yield categories like "Despensas y Básicos" across retail locations.
  * *Inventory Prioritization:* Procurement pipelines must prioritize stocking these dominant departments to avoid out-of-stock scenarios that directly jeopardize core revenue.


 
## 📊 Executive Dashboard Preview & Analysis

* <img width="991" height="456" alt="image" src="https://github.com/user-attachments/assets/6fdc3ae0-0d9b-44c5-94ce-9b648c8aaa9f" />


The interactive dashboard built in Excel allows stakeholders to dynamically filter performance metrics by department. The screenshot below illustrates an active analysis snapshot when filtering specifically for the **"Despensa y Básicos"** (Groceries & Staples) category:

*(Aquí puedes arrastrar y soltar tu archivo image_61cc37.png)*

### Key Dashboard Insights & Technical Highlights:
* **Interactive Filtering:** Utilizing dynamic filtering at the top left seamlessly syncs all visual components, allowing for an isolated performance drill-down of individual departments.
* **Outstanding Spatial Yield:** As visualized in the *Ventas por metro cuadrado de cada Departamento* horizontal bar chart, **"Despensa y Básicos"** completely outperforms all other organizational sectors, comfortably leading efficiency metrics at **$652.81 per $m^2$**. It is followed by "Comida Fresca" and "Artículos del Hogar y Papel".
* **Highest Sales Contribution:** The stacked column chart (*Participación de Ventas por Departamento*) highlights that **"Despensa y Básicos"** secures the baseline position as the single largest revenue stream, contributing to **15.23%** of overall weekly sales.

