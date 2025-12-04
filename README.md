# Python-Assignment-4
Dataset Description

The project uses a CSV file stored in data/weather.csv.

Each row represents daily (or hourly) weather information with the columns:


Date – date of observation

Temperature – temperature in °C

Rainfall – rainfall in mm

Humidity – relative humidity in %

The dataset can be a real-world file downloaded from open sources (e.g., Kaggle / IMD) or a custom sample with the same columns.

Tools Used

Python 3

Pandas – data loading, cleaning, grouping

NumPy – numerical statistics (mean, min, max, std)

Matplotlib – line, bar, and scatter visualizations

Results

The script src/weather_analysis.py generates:

output/cleaned_weather_data.csv – cleaned and processed dataset

output/temp_trend.png – line chart of daily temperature trend

output/monthly_rainfall.png – bar chart of monthly rainfall totals

output/humidity_vs_temperature.png – scatter plot of humidity vs temperature

output/combined_plots.png – figure combining temperature and rainfall plots

output/summary_report.txt – text report summarizing key trends and anomalies

