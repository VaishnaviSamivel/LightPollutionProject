# LightPollutionProject
Analyze nightlight data to monitor light pollution trends in Asia using Python.
This project analyzes VIIRS Nighttime Lights data (2013–2024) to study light pollution trends across Asian countries. Using Python and pandas/matplotlib, the project filters the dataset for Asia, aggregates nightlight intensity by year, month, and country, and generates informative plots to visualize trends.

The repository includes:

Original and filtered datasets

Jupyter Notebook with full analysis and plots

Saved visualizations (yearly, monthly, and country-wise)

A ready-to-run Python environment with dependencies listed in requirements.txt
## Phase 2: Data Preprocessing & EDA

In this phase, we:
- Cleaned and preprocessed the dataset (handled missing values, created a combined `date` column).
- Filtered and focused on Asia-specific data (`asia_nightlight_sample.csv` used for GitHub).
- Aggregated data at country and regional levels for analysis.
- Performed basic exploratory data analysis (EDA) including:
  - Nightlight trends over time
  - Country-level comparison
  - Initial visualizations of changes in nightlight intensity

### Files Updated
- `notebooks/preprocessing.ipynb` → contains preprocessing and EDA code
- `data/asia_nightlight_sample.csv` → small dataset sample (full dataset is large, stored locally)
- `README.md` → updated project description

