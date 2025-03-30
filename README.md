# 🚲 Citi Bike NYC 2024: Rider Behavior & Station Insights

This project analyzes a sample of 2024 Citi Bike trip data in New York City to uncover trends in rider behavior, station usage, and urban transportation patterns. It was completed as part of a data visualization assignment using Python and Tableau.

## 📁 Repository Contents

- `2024_citibike_sample.csv`  
  Sample dataset used for analysis and Tableau visualizations

- `Sample Citibike Tableau Data.ipynb`  
  Jupyter notebook used to clean and enrich the data

- `README.md`  
  Project overview and instructions

## 📊 Project Overview

As the lead analyst for the NYC Citi Bike program, I was tasked with producing interactive visualizations and dashboards to support city planning and transportation improvements. The analysis focuses on:

- Rider behavior patterns over time (member vs casual users)
- Peak usage hours and trip duration trends
- Station popularity across the city
- Geospatial distribution of rides using map visualizations

## 🧹 Data Preparation

The notebook performs:
- Datetime parsing and trip duration calculation
- Extraction of hour of day and day of week
- Removal of invalid or missing values
- Export of a cleaned CSV for use in Tableau

## 📍 Key Visualizations

All final visualizations were built in [Tableau Public](https://public.tableau.com/) and include:
- Average trip duration by rider type and bike type
- Hourly ride patterns (line chart)
- Weekly ride patterns (bar chart)
- Top 10 start and end stations
- Interactive map of start station popularity

### 🧭 View the Tableau Story:
**[Citi Bike NYC 2024 Tableau Story](https://public.tableau.com/app/profile/seven.george/viz/CitiBikeNYC2024/CitiBikeNYCUsageTrendsStationInsights2024Sample)**

## 📝 Summary of Findings

- **Members** ride more consistently on weekdays during commuting hours.
- **Casual riders** take longer trips, especially on weekends and afternoons.
- The most popular stations are located near transit, parks, and tourist zones.
- Mapping ride volume reveals clusters in Manhattan and parts of Brooklyn.

## 📌 Tools Used

- **Python / Pandas** (data cleaning)
- **Tableau Public** (visual analytics and dashboard creation)
- **Jupyter Notebook** (data prep workflow)
