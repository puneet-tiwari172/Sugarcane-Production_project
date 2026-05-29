# Sugarcane-Production_project
# 🌍 Global Sugarcane Production Analysis

# 📌 Project Overview

This project performs an in-depth Exploratory Data Analysis (EDA) on global sugarcane production data. The analysis focuses on production volume, land usage, agricultural efficiency and continent-wise production trends.

Using Python data analysis libraries, the project uncovers relationships between production, acreage and yield while identifying the top sugarcane-producing countries and regions.

# 🎯 Objectives

* Analyze worldwide sugarcane production trends
* Identify top sugarcane-producing countries
* Compare continent-wise production
* Understand the relationship between acreage and production
* Detect outliers and agricultural efficiency patterns
* Visualize global sugarcane distribution using charts and plots 
# 🛠️ Tech Stack

| Technology       | Usage                     |
| ---------------- | ------------------------- |
| Python           | Programming Language      |
| Pandas           | Data Cleaning & Analysis  |
| NumPy            | Numerical Operations      |
| Matplotlib       | Data Visualization        |
| Seaborn          | Statistical Visualization |
| Jupyter Notebook | Development Environment   |

# 📂 Dataset Features

| Feature                   | Description                |
| ------------------------- | -------------------------- |
| Country                   | Country Name               |
| Continent                 | Continent Name             |
| Production(Tons)          | Total Sugarcane Production |
| Production_per_person(Kg) | Production Per Person      |
| Acreage(Hectare)          | Total Cultivation Area     |
| Yield(Kg/Hectare)         | Production Efficiency      |

# 🧹 Data Cleaning Process

The dataset was cleaned and preprocessed before analysis.

### ✔ Cleaning Steps

* Removed unnecessary symbols from numerical columns
* Standardized decimal formatting
* Removed unwanted columns
* Renamed columns for consistency
* Handled missing values
* Converted columns into numerical data types

# 📊 Exploratory Data Analysis

## 🌎 Countries Producing Sugarcane by Continent

| Continent     | Number of Countries |
| ------------- | ------------------- |
| Africa        | 38                  |
| Asia          | 25                  |
| North America | 22                  |
| South America | 11                  |
| Oceania       | 4                   |
| Europe        | 2                   |

### Insight

Africa has the highest number of sugarcane-producing countries, while South America dominates total production.

# 📈 Key Analysis Performed

## Univariate Analysis

Analyzed distribution of:

* Production(Tons)
* Production_per_person(Kg)
* Acreage(Hectare)
* Yield(Kg/Hectare)

### Findings

* Production is highly skewed toward Brazil and India
* Yield efficiency varies significantly across countries
* Acreage strongly impacts total production

## 📦 Outlier Detection

Boxplots and violin plots revealed major production outliers such as:

* Brazil
* India
* China

These countries contribute disproportionately to global sugarcane production.

## 🔍 Correlation Analysis

| Variables             | Correlation |
| --------------------- | ----------- |
| Production vs Acreage | 0.997       |
| Production vs Yield   | 0.132       |

### Insights

* Larger cultivation land strongly increases production
* Higher yield alone does not guarantee high total production

# 🌍 Country-Level Insights

| Metric                        | Top Country |
| ----------------------------- | ----------- |
| Highest Production            | Brazil      |
| Highest Acreage               | Brazil      |
| Highest Yield                 | Guatemala   |
| Highest Production Per Person | Paraguay    |

# 🌐 Continental Analysis

## Top Sugarcane Producing Continents

1. South America
2. Asia
3. Africa

### Insight

South America leads global sugarcane production mainly due to Brazil’s massive agricultural output.

# 📉 Visualizations Used

* Bar Charts
* Histograms
* Distribution Plots
* Scatter Plots
* Boxplots
* Violin Plots
* Heatmaps
 
# 📌 Key Findings
✔ Brazil is the world’s largest sugarcane producer
✔ Acreage has the strongest impact on production
✔ South America dominates global sugarcane output
✔ Yield efficiency varies between countries
✔ Large land area generally results in higher production

# 🚀 Future Improvements
* Build Machine Learning prediction models
* Add Power BI/Tableau dashboards
* Perform climate impact analysis
* Add time-series forecasting
* Create interactive visual dashboards


