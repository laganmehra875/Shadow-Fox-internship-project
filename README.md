# Shadow-Fox-internship-project

### 📌 Project Objective

The main objective of this project is to analyze air pollution levels in Delhi using AQI-related data and identify patterns, trends, and relationships between different pollutants.

Specifically, the project aims to:

* Understand overall pollution severity using key pollutants like PM2.5, PM10, NO₂, SO₂, CO, and O₃
* Analyze seasonal variations in air quality
* Identify which pollutants contribute most to poor air quality
* Explore relationships (correlation) between different pollutants
* Provide insights that can help in environmental monitoring and decision-making

---

### 📊Project Overview

This project performs exploratory data analysis (EDA) on Delhi’s air quality dataset using Python.

***🔹 Key Steps Covered:***

1. **Data Loading**
* Imported dataset (delhiaqi.csv) using pandas
  
2. **Data Preprocessing**
* Converted date column into proper datetime format
* Checked for missing values (dataset is clean)

  
3. **Pollution Analysis**
* Calculated statistical summary of pollutants
* Compared average pollution levels across pollutants

4. **Seasonal Analysis**
* Created seasonal categories (Winter, Summer, Monsoon, Post-Monsoon)
* Analyzed how pollution changes with seasons

5. **Data Visualization**
* Bar charts → Average pollution levels
* Box plots → Seasonal PM2.5 variation
* Heatmap → Correlation between pollutants

6. **Insights Extraction**
* Identified highest pollution levels
* Found relationships between pollutants

---

### 📊 Business Insights from AQI Analysis

1. **High Dependency on PM2.5 & PM10**
* These pollutants are the **main drivers of poor AQI**
* Indicates major sources like:
* Vehicle emissions 🚗
* Construction dust 🏗️
* Industrial pollution 🏭

  
**👉 Insight:** Controlling PM2.5 alone can significantly improve overall air quality.

2. **Strong Seasonal Impact (Winter Spike ❄️)**

* Pollution levels increase sharply during winter
* Causes:
* Temperature inversion
* Crop burning
* Low wind speed
**👉 Insight:** AQI is **predictable seasonally**, which helps in planning preventive actions.
  
3. **Pollutants Are Correlated**
* Some pollutants move together (e.g., PM2.5 & PM10)
**👉 Insight:**
* They likely come from **common sources**
* Tackling one source can reduce multiple pollutants at once
4. **Consistently Poor Air Quality**
* AQI remains in unhealthy ranges for long durations
**👉 Insight:**
Air pollution is not a short-term issue → it's a **chronic urban problem**





