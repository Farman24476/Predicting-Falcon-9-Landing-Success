# Project: **Predicting Falcon 9 Landing Success**

## Project Overview

**Crime Rates by Region: A Data-Driven Visual Analysis** is a data science project that investigates regional violent crime patterns across the 50 U.S. states using 1973 standardized crime statistics. By integrating data cleaning, geospatial visualization, statistical analysis, and unsupervised learning (clustering), the project aims to provide actionable insights to policymakers, researchers, and the public.

---

## Problem Statement

Despite the availability of crime data, much of it remains underutilized due to poor visualization and a lack of region-level comparative analysis. Traditional reporting methods often fail to highlight spatial patterns, correlations with urbanization, and differences across states. A comprehensive, data-driven visualization framework is needed to improve public safety decision-making and policy development.

---

## Objectives

- To analyze spatial and temporal patterns in violent crime data across U.S. states  
- To examine the relationship between crime categories (murder, assault, rape) and urban population  
- To identify and cluster states with similar crime profiles using unsupervised learning  
- To provide visual and statistical tools for informed public safety planning

---

## Methodology

The project was implemented in several stages:

1. **Data Collection and Cleaning**  
   - Source: U.S. violent crime data from 1973  
   - Tasks: Renaming columns, handling missing values, creating new features (e.g., total crime)

2. **Exploratory Data Analysis**  
   - Techniques: Descriptive statistics, bar charts, heatmaps, choropleth maps, radar charts, pair plots  
   - Libraries: Pandas, Seaborn, Matplotlib, Plotly, Folium

3. **Clustering and Pattern Recognition**  
   - Algorithm: K-Means clustering  
   - Input Features: Murder and assault rates  
   - Output: State-level crime clusters categorized by intensity and pattern

---

## Key Findings

- California, Texas, and Florida reported the highest overall violent crime levels  
- Urban population was positively correlated with violent crime rates  
- K-Means clustering categorized states into three distinct crime-pattern groups  
- Radar and choropleth maps revealed regional disparities in crime types  
- Some low-population states exhibited disproportionately high crime-to-population ratios

---

## Tools and Technologies

- Programming Language: Python  
- Libraries: Pandas, NumPy, Seaborn, Matplotlib, Plotly, Folium, Scikit-learn  
- Methods:  
  - Exploratory Data Analysis  
  - Feature Engineering  
  - Clustering and Unsupervised Learning  
  - Correlation and Pattern Analysis

---

## Impact and Future Work

This project offers a reusable, scalable framework for understanding crime dynamics through data visualization and analysis. It contributes to regional crime research and can support future policy initiatives.

Planned future enhancements include:

- Incorporating multi-year data for time-series forecasting  
- Adding socioeconomic indicators such as income, education, and employment  
- Deploying interactive dashboards using Streamlit or Tableau  
- Applying advanced models such as Prophet or ARIMA for predictive crime trend analysis

---

This repository includes all necessary datasets, Python scripts, Jupyter notebooks, and generated figures required to fully reproduce the analysis and results.

