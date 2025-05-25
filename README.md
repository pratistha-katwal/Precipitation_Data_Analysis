# 🌧️ Spatial and Temporal Analysis of Precipitation and Its Extremities in Nepal (1995–2024)

This project analyzes Nepal’s precipitation trends and extremes from 1995 to 2024 using CHIRPS rainfall data at a spatial resolution of 5 km. It explores seasonal and annual patterns, visualizes spatial distributions, and applies statistical methods to detect significant trends in precipitation.

---

## 🎯 Objective

To assess the **spatial and temporal patterns** of precipitation and its **extremities** over Nepal from 1995 to 2024 using satellite-derived CHIRPS rainfall data.

---

## 🛰️ Data Source

- **Dataset**: CHIRPS (Climate Hazards Group InfraRed Precipitation with Station Data)  
- **Spatial Resolution**: ~0.05° (~5 km)  
- **Temporal Range**: 1995–2024  
- **Format**: NetCDF  
- **Source**: [CHIRPS Official Website](https://data.chc.ucsb.edu/products/CHIRPS-2.0)

---

## ⚙️ Methods

### 1. Preprocessing
- Clipped precipitation data to Nepal's boundary  
- Handled missing values  
- Reprojected to a common coordinate reference system (CRS)

### 2. Data Analysis

#### 2.1 Climatic Normals
- Analyzed **seasonal and annual precipitation** using long-term averages  
- Applied the **Mann-Kendall test** to identify monotonic trends over time  

#### 2.2 Climatic Extremes
- Analyzed temporal and spatial trends in precipitation thresholds:
  - **PRCP ≥ 1 mm** (wet days)  
  - **PRCP ≥ 10 mm** (moderate rain)  
  - **PRCP ≥ 20 mm** (heavy rain)  
- Calculated **R95p** and **R99p** indices:
  - Annual total precipitation on days exceeding the 95th and 99th percentiles  
  - Reference period: **1995–2015**

---

## 📊 Results Summary

- **National-level Trends**:  
  - No statistically significant trends observed in seasonal, annual, or extreme precipitation indices  
- **Spatial Patterns**:  
  - Significant **localized changes** in extremes were detected, indicating **regional variability** in precipitation behavior  

---

## Author
Pratistha Katwal

