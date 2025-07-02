

![image](https://github.com/user-attachments/assets/bc847ee3-9b45-493d-ba7d-3edc08037634)


# 🌍 U.S. Carbon Emissions Analysis (EDA)

This repository showcases a data-driven **Exploratory Data Analysis (EDA)** project focused on understanding **carbon dioxide (CO₂) emissions trends across the United States**. The project draws from publicly available emissions data to extract strategic insights that support **climate action, ESG reporting, and policy development**.

---

## 📌 Project Overview

As the urgency to address climate change intensifies, analyzing CO₂ emissions across regions, sectors, and fuel types is critical. This project examines a rich dataset on U.S. emissions over time—identifying patterns by:

- **State**
- **Sector**
- **Fuel type**
- **Year**

The analysis includes both **total** and **average** emissions perspectives to uncover hidden patterns and inform climate-related strategies.

---

## 🎯 Objectives

- 📊 Explore **temporal trends** in CO₂ emissions from 2000–2021  
- 🧭 Identify **top-emitting states**, sectors, and fuel sources  
- 🔎 Investigate **sector–fuel relationships** using heatmaps  
- 🗺️ Visualize **geospatial emissions** using choropleth maps  
- 📌 Deep-dive case study: **Texas emissions breakdown**  
- 🧩 Discover correlations between categorical variables (fuel & sector)

---

## 🛠️ Features

- Cleaned dataset with a custom `wrangle_co2_emissions()` function  
- Dual perspectives: **average vs. total emissions**  
- Comparative side-by-side plots for rich storytelling  
- Sector and fuel-specific time-series trends  
- Interactive **Plotly choropleth** maps for geospatial insight  
- **Correlation heatmaps** of sector–fuel usage relationships  
- Export-ready visualizations for portfolio or reports

---

## 📁 Repository Structure

```bash
US_carbon_emissions_analysis/
├── US_carbon_emissions_analysis.ipynb     # Main Jupyter Notebook
├── data/                                  # Source data (optional)
├── figures/                               # Exported visuals for report/presentation
├── README.md                              # This file
└── LICENSE                                # (Optional) License info
