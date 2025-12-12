# Telangana State Weather Data Analysis

## 📊 Project Overview

This project analyzes comprehensive weather data from Telangana State, India, across multiple years (2021-2024). The analysis covers rainfall patterns, temperature dynamics, humidity variations, and wind speed metrics across different districts and mandals to identify weather trends and patterns.

## 📁 Project Structure

```
Telangana-State-Weather-Data-Analysis/
├── Weather Data/
│   ├── 2021/           # Weather data for 2021
│   ├── 2022/           # Weather data for 2022
│   ├── 2023/           # Weather data for 2023
│   ├── 2024/           # Weather data for 2024
│   └── Data Overview/  # Summary and overview data
│
├── reports/
│   └── dashboards/
│       ├── Humidity Trend Overview.png
│       ├── Rainfall Trends & Distribution.png
│       ├── Temperature Dynamics.png
│       ├── Wind Speed Metrics.png
│       └── Telangana Weather Dashboard.pbix
│
├── visualizations/     # Additional charts and visualizations
├── README.md          # Project documentation
└── requirements.txt   # Python dependencies
```

## 📊 Dataset Description

### Data Columns

The dataset includes the following weather metrics:

| Column | Description | Unit |
|--------|-------------|------|
| **District** | District name in Telangana State | Text |
| **Mandal** | Sub-district/administrative division | Text |
| **Date** | Date of observation | Date (YYYY-MM-DD) |
| **Rain (mm)** | Rainfall amount | Millimeters |
| **Min Temp (°C)** | Minimum temperature | Degrees Celsius |
| **Max Temp (°C)** | Maximum temperature | Degrees Celsius |
| **Min Humidity (%)** | Minimum humidity percentage | Percentage |
| **Max Humidity (%)** | Maximum humidity percentage | Percentage |
| **Min Wind Speed (Kmph)** | Minimum wind speed | Kilometers/hour |
| **Max Wind Speed (Kmph)** | Maximum wind speed | Kilometers/hour |

## 🛠️ Tools & Technologies Used

### **Data Processing**
- **R Package Installer** - Data cleaning and preprocessing using R packages
- File formats: CSV, XLSX

### **Data Visualization**
- **Power BI Desktop** - Creating interactive dashboards and visualizations
- Dashboard file: `Telangana Weather Dashboard.pbix`

### **Key Visualizations**
1. **Humidity Trend Overview** - Monthly and seasonal humidity patterns
2. **Rainfall Trends & Distribution** - Precipitation analysis across regions
3. **Temperature Dynamics** - Min/Max temperature variations
4. **Wind Speed Metrics** - Wind pattern analysis by district

## 📈 Key Analysis Areas

- **Seasonal Weather Patterns** - Identify weather trends across seasons
- **District-wise Comparisons** - Compare weather patterns across different districts
- **Temperature Analysis** - Extreme temperature events and trends
- **Rainfall Distribution** - Monsoon and precipitation patterns
- **Humidity & Wind Patterns** - Atmospheric conditions analysis
- **Year-over-Year Trends** - Changes from 2021 to 2024

## 🎯 Key Findings

This analysis reveals:
- Significant temperature variations across districts
- Monsoon-driven rainfall patterns in specific regions
- Humidity-temperature correlations during different seasons
- Wind speed variations and their seasonal changes
- District-specific weather characteristics

## 📊 Dashboards

Interactive Power BI dashboards are available in the `reports/dashboards/` folder:
- **Telangana Weather Dashboard.pbix** - Main comprehensive dashboard
- **PNG Exports** - Static visualization exports for quick reference

### To Open Dashboards:
1. Download Power BI Desktop: https://powerbi.microsoft.com/en-us/downloads/
2. Open the `.pbix` files in Power BI Desktop
3. Explore interactive visualizations and filters

## 💾 Data Files

- **CSV Files** - Raw and processed weather data
- **XLSX Files** - Formatted data with multiple sheets
- Data organized by year for easy filtering and analysis

## 🚀 How to Use This Project

1. **Explore the Data**
   - Navigate to `Weather Data/` folder
   - View data by year (2021-2024)
   - Review the Data Overview for summary statistics

2. **View Dashboards**
   - Open PNG files for quick visual reference
   - Open `.pbix` file in Power BI Desktop for interactive exploration

3. **Reproduce the Analysis**
   - Use R for data preprocessing and cleaning
   - Import processed data into Power BI for visualization
   - Follow the same analysis workflow

## 📋 Requirements

See `requirements.txt` for Python dependencies (if using Python for additional analysis)

### Software Requirements:
- **R** (with tidyverse packages) - for data processing
- **Power BI Desktop** - for creating/viewing dashboards

## 👤 Author

**Vasanth.N.V.S**

## 📄 License

This project is available for educational and research purposes.

## 🔗 Dataset Information

- **Time Period**: 2021-2024
- **Geographic Coverage**: Telangana State districts and mandals
- **Data Frequency**: Daily observations
- **Data Quality**: Cleaned and validated weather observations

---

> ⭐ **If you find this project helpful, please consider starring this repository!** It helps others discover this project and motivates continued development.

---

*Last Updated: December 2025*
