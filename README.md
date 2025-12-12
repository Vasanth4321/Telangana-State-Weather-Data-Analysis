# Telangana-State-Weather-Data-Analysis
Comprehensive analysis of Telangana State weather data. Dataset includes rainfall, temperature, humidity, and wind speed patterns across districts and mandals. Detailed EDA, visualization, and insights on weather trends.

## Dataset Description

This project analyzes weather data from Telangana State, India. The dataset contains detailed meteorological observations recorded across various districts and mandals (administrative subdivisions). Below is a comprehensive description of each column in the dataset:

### Data Columns

**District**
- Description: Identifies the district in which the weather data was recorded
- Purpose: Provides geographical context for regional weather analysis
- Type: Categorical

**Mandal**
- Description: A more localized identifier within the district
- Purpose: Provides detailed information about the specific area of data collection for granular analysis
- Type: Categorical

**Date**
- Description: Records the date of the weather observation
- Purpose: Enables time-series analysis to identify temporal patterns and trends
- Type: Date/Temporal

**Rain (mm)**
- Description: Amount of rainfall measured in millimeters
- Purpose: Helps in understanding precipitation patterns, drought conditions, and monsoon trends
- Type: Numerical (Float)
- Unit: Millimeters (mm)

**Min Temp (C)**
- Description: The minimum temperature recorded in degrees Celsius
- Purpose: Helps in analyzing the lowest temperature trends and identifying cold weather patterns
- Type: Numerical (Float)
- Unit: Degrees Celsius (°C)

**Max Temp (C)**
- Description: The maximum temperature recorded in degrees Celsius
- Purpose: Provides insights into the highest temperature trends and heat wave conditions
- Type: Numerical (Float)
- Unit: Degrees Celsius (°C)

**Min Humidity (%)**
- Description: Minimum humidity percentage recorded during the day
- Purpose: Gives insights into the driest conditions and moisture levels
- Type: Numerical (Float)
- Unit: Percentage (%)

**Max Humidity (%)**
- Description: Maximum humidity percentage recorded during the day
- Purpose: Provides information about the most humid conditions and moisture saturation
- Type: Numerical (Float)
- Unit: Percentage (%)

**Min Wind Speed (Kmph)**
- Description: The minimum wind speed recorded in kilometers per hour
- Purpose: Highlights the calmest wind conditions and low-wind periods
- Type: Numerical (Float)
- Unit: Kilometers per hour (Kmph)

**Max Wind Speed (Kmph)**
- Description: The maximum wind speed recorded in kilometers per hour
- Purpose: Shows the windiest conditions and identifies potential severe weather events
- Type: Numerical (Float)
- Unit: Kilometers per hour (Kmph)

## Analysis Focus Areas

- Seasonal weather patterns and variations
- Temperature extremes and their distributions
- Rainfall patterns across districts
- Humidity levels and their correlation with temperature
- Wind speed patterns and their temporal changes
- District-wise and mandal-wise weather comparisons
- Time-series trends and forecasting

## Technologies & Tools

- **Data Analysis**: Python (Pandas, NumPy)
- **Visualization**: Matplotlib, Seaborn, Power BI
- **Statistical Analysis**: SciPy, Scikit-learn
- **Database**: SQL for data querying and aggregation

## Project Structure

```
Telangana-State-Weather-Data-Analysis/
├── README.md (this file)
├── data/
│   └── telangana_weather_data.csv
├── notebooks/
│   ├── EDA.ipynb
│   └── analysis.ipynb
├── scripts/
│   ├── data_preprocessing.py
│   └── analysis.py
└── visualizations/
    └── weather_reports.md
```

## Key Insights

This analysis reveals:
- Temperature variations across seasons and regions
- Rainfall distribution patterns in the monsoon season
- Humidity-temperature relationships
- Wind speed patterns and their seasonal changes

## Author

**Vasanth.N.V.S**

## License

This project is available for educational and research purposes.

---

> ⭐ **If you find this project helpful, please consider starring this repository!** It helps others discover this project and motivates continued development.

---

*Last Updated: December 2025*
