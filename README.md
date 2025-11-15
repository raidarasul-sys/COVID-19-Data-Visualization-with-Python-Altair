# COVID-19 Visualization & Geospatial Analysis Using Python & Altair 

## 🚀 Executive Summary
This project explores COVID-19 trends across the United States using Python, Altair, and Jupyter Notebook.

The goal is to demonstrate declarative visualization with Altair and illustrate how interactive and geospatial views can reveal patterns in public health data.

---

### 🎯 Business Problem / Objective
Public health decision-makers need clear visuals to understand where COVID-19 cases and fatalities are concentrated and how they vary by geography.

**This notebook answers:**
- Which U.S. states report the highest confirmed case counts?  
- How do confirmed cases and deaths compare across the worst-hit states?  
- How are fatality rates distributed at the county level across the U.S.?

## **Skills**
- **Language:** Python 3  
- **Environment:** Jupyter Notebook
- **Libraries:**  
  - `pandas` – data manipulation  
  - `altair` – declarative visualization  
  - `vega_datasets` – built-in TopoJSON (U.S. counties)  
- **Data Types:** Tabular CSV, TopoJSON (geometries)

## **Methodology**

1. Environment Setup**
2. Data Loading & Cleaning
3. Data Visualization

## **Visualizations**

<img src="visuals/barchart.png" width="600">
<img src="visuals/scatterplot.png" width="600">
<img src="visuals/choropleth.png" width="600">

## Dataset Overview
**Source:** COVID-19 dataset provided for coursework (JHU-style county data)

Contents:

- `ST_Name` – State name  
- `Confirmed` – Confirmed COVID-19 case count  
- `Deaths` – Number of deaths  
- `FatalityRa` – Fatality rate  
- `FIPS` – County FIPS code (used to join to geospatial data)
