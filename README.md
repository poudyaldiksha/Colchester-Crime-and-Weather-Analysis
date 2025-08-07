# 🌦️ Colchester Crime and Weather Analysis

## 📌 Project Overview  
This project investigates crime trends in Colchester from April 2024 to March 2025 and examines how they are influenced by weather patterns. Using R for data cleaning, analysis, and interactive visualization, it explores seasonal, spatial, and meteorological correlations with daily crime rates.

## ❓ Problem Statement  
Authorities in Colchester aim to:

- Understand the relationship between temperature, precipitation, and daily crime rates.
- Identify peak crime seasons and geographic hotspots.
- Use weather-informed insights for proactive policing and community safety strategies.

This project integrates local crime data with historical weather data to support evidence-based urban safety planning.

## 📁 Datasets  
**Datasets Used:**
- `crime2024-25.csv`: Street-level crime records in Colchester (type, date, location).
- `temp2024-25.csv`: Weather metrics for the same period (temperature, rainfall).
- `temp2023-24.csv`: For comparative weather analysis.

**Data Sources:**
- [UK Police API](https://data.police.uk/data/)
- [OGIMET Weather Station](https://www.ogimet.com/)

## 🛠 Technologies Used  
- **Language**: R  
- **Libraries**:  
  `tidyverse`, `lubridate`, `ggplot2`, `plotly`, `leaflet`, `heatmaply`, `corrplot`, `DT`, `GGally`  
- **Tools**:  
  - RStudio  
  - Interactive HTML widgets  
  - Leaflet maps and Plotly charts  

## 🧹 Data Cleaning & Preprocessing  
- Filtered data for 2024–25 period.
- Fixed date formats and created derived time features (e.g., `month`, `season`).
- Joined weather and crime datasets on date.
- Removed missing geolocations.
- Aggregated daily crime counts and computed summaries.

## 📊 Exploratory Data Analysis (EDA)

### 🔎 Key Questions
- Does temperature affect crime rates?
- Which crimes are most common?
- Are there seasonal or monthly crime spikes?
- Where are crime hotspots in Colchester?

### 📈 Visualizations
- **Bar/Pie Charts**: Top 5 crime types
- **Histograms/Density Plots**: Distribution of daily crimes
- **Box & Violin Plots**: Variability in crime types
- **Time Series Plots**: Trends with LOESS smoothing
- **Scatter Plots**: Crime vs. temperature
- **Correlation Heatmaps**: Weather variables vs. crime
- **Interactive Leaflet Maps**: Crime incident locations and clusters
- **Interactive Tables & Plots**: Monthly trends by crime type

## ✅ Key Insights
- **Violent crime** is the most reported (2,314 cases), followed by anti-social behaviour and shoplifting.
- Crime spikes in **July and August**, and is lowest during winter.
- Strongest positive correlation: crime count vs. **maximum temperature** (**r = 0.67**).
- **Precipitation** shows a weak **negative correlation** with crime.
- Central areas of Colchester are the main crime hotspots.

## 🚀 Future Work
- Develop predictive models using weather variables.
- Include socio-demographic data for deeper insights.
- Run temporal-lag analysis (e.g., impact of next-day weather).
- Deploy real-time dashboards using Shiny or Dash.
- Collaborate with local authorities for smart policing.

## 📓 Report
📄 [Colchester_Crime_and_Weather_Analysis.pdf](./Colchester%20Crime%20and%20Weather%20Analysis.pdf)

## 🧠 Author
**Diksha Poudyal**  
📍 [GitHub Profile](https://github.com/poudyaldiksha)  

---

📝 *This analysis was developed as part of the MA304 Data Visualization module and uses real datasets to explore climate-influenced crime patterns in urban environments.*
