# 🚴 Urban Mobility Analysis: NYC Citi Bike Usage Patterns

## Project Overview

This project analyzes bike-sharing usage patterns in New York City using Citi Bike trip data from February 2024. The analysis demonstrates statistical modeling, geospatial analysis, and data visualization techniques applied to urban transportation systems.

**Key Objectives:**
- Identify temporal and spatial patterns in bike-sharing usage
- Analyze factors influencing trip duration and demand
- Map station-level activity and accessibility
- Provide insights for urban mobility planning

## 📊 Datasets

- **Source:** Citi Bike System Data (February-April 2024)
- **Coverage:** NYC bike-sharing trips with ~400k+ records
- **Variables:** Trip duration, start/end times, station locations, user types

## 🛠️ Technologies & Tools

- **Python:** Pandas, NumPy, Scikit-learn
- **Geospatial:** GeoPandas, Shapely, Folium
- **Visualization:** Matplotlib, Seaborn, Plotly
- **Statistical Analysis:** SciPy, Statsmodels
- **GIS:** QGIS (for preprocessing)

## 📈 Key Analyses

### 1. Statistical Analysis
- **Descriptive Statistics:** Trip duration, frequency distributions, peak hours
- **Regression Analysis:** Modeling trip duration based on distance, time, user type
- **Hypothesis Testing:** Comparing member vs. casual rider behavior
- **Time Series:** Daily and hourly usage patterns

### 2. Geospatial Analysis
- **Station Mapping:** Interactive maps of bike station locations and activity
- **Spatial Clustering:** Identifying high-demand zones
- **Route Analysis:** Popular origin-destination pairs
- **Accessibility Metrics:** Station coverage and service areas

### 3. Data Visualization
- **Heatmaps:** Temporal usage patterns (day/hour)
- **Choropleth Maps:** Station-level trip volumes
- **Network Graphs:** Station connectivity
- **Time Series Plots:** Usage trends over the analysis period

## 🔍 Key Findings

1. **Peak Usage Hours:** Commute times (8-9 AM, 5-7 PM) show highest activity
2. **User Behavior Differences:** Members take shorter, more frequent trips vs. casual riders
3. **Spatial Patterns:** Manhattan stations show highest throughput, outer boroughs vary
4. **Trip Duration Model:** Distance, time of day, and user type significantly predict duration (R² = 0.68)

## 📁 Project Structure

```
citibike-mobility-analysis/
│
├── data/                          # Raw data files (not uploaded to Git)
│   ├── 202402-citibike-tripdata.csv
│   ├── 202403-citibike-tripdata.csv
│   └── 202404-citibike-tripdata.csv
│
├── notebooks/                     # Jupyter notebooks for analysis
│   ├── 01_data_exploration.ipynb
│   ├── 02_statistical_analysis.ipynb
│   └── 03_geospatial_mapping.ipynb
│
├── src/                           # Python scripts
│   ├── data_processing.py
│   ├── statistical_analysis.py
│   └── geospatial_analysis.py
│
├── figures/                       # Output visualizations
│   ├── usage_heatmap.png
│   ├── station_map.html
│   └── regression_results.png
│
├── outputs/                       # Analysis results
│   └── summary_statistics.csv
│
├── requirements.txt               # Python dependencies
└── README.md                      # This file
```

## 🚀 Getting Started

### Prerequisites
```bash
Python 3.8+
pip install -r requirements.txt
```

### Installation
```bash
# Clone repository
git clone https://github.com/yourusername/citibike-mobility-analysis.git
cd citibike-mobility-analysis

# Install dependencies
pip install -r requirements.txt
```

### Usage
```bash
# Run data processing
python src/data_processing.py

# Run statistical analysis
python src/statistical_analysis.py

# Run geospatial analysis
python src/geospatial_analysis.py

# Or explore notebooks
jupyter notebook notebooks/
```

## 💡 Urban Planning Insights

1. **Infrastructure Planning:** High-demand stations need capacity expansion
2. **Rebalancing Strategy:** Off-peak redistribution based on flow patterns
3. **New Station Placement:** Service gaps identified in outer boroughs
4. **Policy Recommendations:** Pricing strategies for demand management

## 📝 Methods & Techniques

- **Statistical Tests:** t-tests, ANOVA, chi-square tests
- **Regression Models:** Linear regression, polynomial features
- **Spatial Analysis:** Point pattern analysis, kernel density estimation
- **Data Cleaning:** Outlier detection, missing value imputation

## 🔗 Related Work

- [NYC Bike Share Data](https://citibikenyc.com/system-data)
- [Urban Mobility Research](https://example.com)

## 📧 Contact

For questions or collaboration:
- **Email:** your.email@example.com
- **LinkedIn:** [Your Profile](https://linkedin.com/in/yourprofile)
- **Portfolio:** [Your Website](https://yourwebsite.com)

## 📜 License

This project is for portfolio and educational purposes. Data provided by Citi Bike under their [data license](https://www.citibikenyc.com/data-sharing-policy).

---

**Built with:** Python • GeoPandas • Scikit-learn • Folium

*Part of Urban Data Science Portfolio demonstrating statistical analysis, geospatial techniques, and data visualization for urban mobility research.*
