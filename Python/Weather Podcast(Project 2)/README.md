# 🌦️ Weather Forecast Data Analysis | Python & EDA

## 📌 Project Overview

This project focuses on **Exploratory Data Analysis (EDA)** of weather forecast data using Python. The objective is to explore weather variables, understand temperature distributions, analyze humidity levels under different rainfall conditions, and identify correlations between numerical weather variables.

Using Pandas, NumPy, Matplotlib, and Seaborn, this project transforms raw weather data into meaningful visualizations and analytical insights.

## 🎯 Project Objectives

- Load and explore the weather forecast dataset.
- Understand dataset structure, columns, and data types.
- Identify missing values and generate descriptive statistics.
- Compare average weather conditions across rainy and non-rainy days.
- Analyze the distribution of temperature.
- Examine correlations between numerical weather variables.
- Investigate the relationship between humidity and rainfall.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming and data analysis |
| NumPy | Numerical computing |
| Pandas | Data loading, manipulation, and analysis |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Jupyter Notebook | Interactive analysis |

## 📂 Project Structure

```text
Weather-Forecast-Data-Analysis/
│
├── Weather_Forecast_Data_Kaggle.ipynb
├── weather_forecast_data.csv
└── README.md
```

*Note: The CSV filename must match the filename used in the notebook. The dataset file should be uploaded to the repository if you have permission to share it.*

## 📊 Analysis Performed

### 1. Data Loading and Exploration
- Imported the dataset using Pandas.
- Inspected dataset information and column data types using `df.info()`.
- Examined missing values using `df.isnull().sum()`.
- Generated descriptive statistics using `df.describe()`.

### 2. Rainfall-Based Analysis
- Grouped observations according to the `Rain` column.
- Calculated average weather conditions for each rainfall category.
- Compared weather characteristics between rainy and non-rainy observations.

### 3. Correlation Analysis
Created a correlation heatmap using Seaborn to examine relationships between numerical weather variables.

**Visualization:** Correlation Matrix of Weather Variables

### 4. Temperature Distribution
Created a histogram with a Kernel Density Estimation (KDE) curve to understand the distribution and frequency of temperature observations.

**Visualization:** Temperature Distribution

### 5. Humidity vs. Rainfall
Used a box plot to compare humidity levels across rainy and non-rainy days.

**Visualization:** Humidity Levels on Rainy vs. Non-Rainy Days

## 🔍 Key Findings

- **Humidity and Rainfall:** The notebook's documented analysis reports higher humidity levels on rainy days compared with non-rainy days.
- **Temperature Distribution:** The histogram and KDE curve help identify common temperature ranges and the overall distribution.
-
