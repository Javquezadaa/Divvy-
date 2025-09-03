# Divvy Bike Analysis Exercise

## Objective
Analyze Divvy bike-sharing data to understand trip patterns, daily usage, and environmental factors affecting bike usage.

## Data
- **Trips Data:** CSV files containing start/end stations, timestamps, ride type, and user info.
- **Weather Data:** NOAA API data (temperature, precipitation) for the corresponding dates.

## Tools & Libraries
- Python (pandas, numpy)
- Visualization: Matplotlib, Seaborn
- Optional: Jupyter Notebook for interactive exploration

## Methodology
1. **Data Cleaning**
   - Removed trips outside the target dates.
   - Merged trip data with weather information.
2. **Aggregation**
   - Calculated daily trip counts.
   - Aggregated average temperature and precipitation per day.
3. **Visualization**
   - Line charts of bike trip counts vs. temperature using dual axes.
   - Optional: Rolling averages to smooth trends.
4. **Insights**
   - Highlighted days of peak demand.
   - Observed relationships between weather and bike usage.

