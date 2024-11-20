# R-shiny

# Australia Climate Dashboard

## Overview
The **Australia Climate Dashboard** provides a detailed analysis of the climate across various regions in Australia from 2007 to 2017. It includes modules focusing on **Temperature**, **Rainfall**, **Wind Speed**, and an **Exploration** panel that enables users to explore relationships between variables like temperature, humidity, wind speed, and rainfall. An **About** module summarizes the application's functionality and data sources.

---

## Modules Overview

### **1. Temperature Module**
- Displays temperature trends over a year for selected cities using a **ridge plot**.
- A **color gradient** (blue to red) is used to visualize temperature changes, making it easy to identify extreme years.
- **Interactive features**:
  - Switch cities to explore temperature trends in different regions.
  - Click on the "mountain" for specific years to view:
    - Maximum temperature.
    - Minimum temperature.
    - Comparison with historical averages.

---

### **2. Rainfall Module**
- An **interactive map** visualizes rainfall across Australian cities using:
  - **Color gradients** and **circular markers** to indicate rainfall intensity.
  - A **slider** allows users to adjust the year range.
- **Interactive features**:
  - Click on city markers to view detailed rainfall data.
  - Explore rainfall distribution for specific locations through a bar graph.
- The design helps users quickly identify areas with heavy rainfall and retrieve detailed data effortlessly.

---

### **3. Wind Module**
- A **polar histogram** illustrates the relationship between wind speed and direction.
  - Wind direction (ring classification data) is displayed as a circular chart.
  - Wind speed is represented through the length and color of histogram bars.
- **Interactive features**:
  - View maximum, average, and historical wind speed for selected regions.
  - Click on specific wind directions to explore historical wind speeds across years.

---

### **4. Exploration Module**
#### **Temperature VS Humidity**
- Sidebar houses navigation and filtering options.
- Main content dynamically displays **visualizations** and **data tables**.
- **Responsive design** ensures usability across different devices and screen sizes.

#### **Wind Speed VS Rainfall**
- **Scatter plot** visualizes the correlation between wind speed and rainfall (both continuous data).
- **Additional features**:
  - **Color classification** (e.g., humidity at 9 a.m. or 3 p.m.) reveals complex relationships between variables.
  - Provides a comprehensive view of the interplay between wind speed, rainfall, and humidity.

---

### **5. About Module**
- Introduces the dashboard’s functionalities and explains how to use the application.
- Provides information on the source dataset and allows users to search/query data directly.

---

## Data Sources
### Kaggle Datasets: [Australian Weather Dataset](https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package)
- **Provider**: Bureau of Meteorology, Commonwealth of Australia
- **Content**: 
  - ~10 years of daily weather observations across various Australian locations.
  - Includes variables such as temperature, rainfall, humidity, and wind speed.

### Bureau of Meteorology: [Official Climate Data](http://www.bom.gov.au/climate/data)
- **Usage**: 
  - Analyze weather trends.
  - Build rainfall prediction models.
  - Explore relationships between various weather variables.

---

## How to Use
1. Explore each module to gain insights into Australian weather patterns.
2. Use interactive features (clickable charts, filters, sliders) for detailed data exploration.
3. Refer to the **About Module** for additional context and dataset queries.

---

## Screenshots

#中文版



