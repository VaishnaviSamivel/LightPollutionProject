# LightPollutionProject
Analyze nightlight data to monitor light pollution trends in Asia using Python.
This project analyzes VIIRS Nighttime Lights data (2013–2024) to study light pollution trends across Asian countries. Using Python and pandas/matplotlib, the project filters the dataset for Asia, aggregates nightlight intensity by year, month, and country, and generates informative plots to visualize trends.

The repository includes:
Original and filtered datasets
Jupyter Notebook with full analysis and plots
Saved visualizations (yearly, monthly, and country-wise)
A ready-to-run Python environment with dependencies listed in requirements.txt

## Data Preprocessing & EDA & forecasting

In this phase, we:
- Cleaned and preprocessed the dataset (handled missing values, created a combined `date` column).
- Filtered and focused on Asia-specific data (`asia_nightlight_sample.csv` used for GitHub).
- Aggregated data at country and regional levels for analysis.
- Performed basic exploratory data analysis (EDA) including:
  - Nightlight trends over time
  - Country-level comparison
  - Initial visualizations of changes in nightlight intensity
- Exploratory Data Analysis (EDA)
- Setting up forecasting with **Facebook Prophet**

 ✅ Processed Data
- `asia_nightlights_processed.csv` → Cleaned dataset  
- `monthly.csv` → Monthly aggregated statistics  
- `yearly.csv` → Yearly aggregated statistics  
- `asia_year.csv` → Asia-wide yearly averages  
- `district_rank.csv` → Ranking of districts by light density  

### ✅ Forecasting
- Implemented **Prophet** model to predict light pollution trends for the next 10 years.  
- Forecast results are stored in `prophet_forecast.csv`.  


