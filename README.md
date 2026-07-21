# COVID-19 Data Analysis

Analysis of global COVID-19 case, death, and vaccination trends using Python.

## Objective
Studied case trends across countries over time, identified top-affected 
countries, and visualized infection and recovery patterns using time-series 
and heatmap analysis.

## Dataset
Our World in Data COVID-19 dataset (archived snapshot):
https://github.com/owid/covid-19-data

## Tools
Python, Pandas, Matplotlib, Seaborn

## Process
- Cleaned raw data: handled nulls, formatted date columns, removed continent-level aggregates
- Performed EDA to identify top 10 countries by total cases
- Created time-series line plots of case trends and 7-day rolling averages
- Built heatmaps for monthly case volume and correlations between metrics
- Analyzed death rate patterns across the most-affected countries

## Visuals

### Total Cases Over Time — Top 10 Countries
![Cases Over Time](images/cases_over_time.png)

### 7-Day Average of New Cases — Top 10 Countries
![New Cases 7-Day Average](images/new_cases_7day_avg.png)

### Monthly New Cases Heatmap by Country
![Monthly Cases Heatmap](images/monthly_cases_heatmap.png)

### Correlation Between COVID-19 Metrics
![Correlation Heatmap](images/correlation_heatmap.png)

### Death Rate by Country — Top 10
![Death Rate Top 10](images/death_rate_top10.png)

