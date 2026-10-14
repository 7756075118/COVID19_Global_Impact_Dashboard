# COVID-19 Global Impact Dashboard
# Day1
## Project Overview

The COVID-19 Global Impact Dashboard is a data visualization project developed using Microsoft Power BI. It aims to analyze COVID-19 trends across countries and over time using the Our World in Data (OWID) dataset.

The dashboard helps users explore case trends, compare countries, and understand changes in COVID-19 cases through interactive visualizations.

## Objectives

- Analyze COVID-19 case trends over time.
- Compare COVID-19 cases across countries.
- Visualize seven-day average new cases.
- Create an interactive dashboard using Power BI.
- Identify patterns in COVID-19 data.

## Tools and Technologies

- Microsoft Power BI
- Power Query
- CSV Dataset
- Python (optional, for data preprocessing)

## Dataset

**Dataset Name:** `owid-covid-data.csv`

**Data Source:** Our World in Data

The dataset contains country-wise and date-wise information about COVID-19, including cases, deaths, population, and other indicators.

Dataset source: https://ourworldindata.org/covid-cases


## Dashboard Development

### COVID-19 Cases Trend

A line chart is used to visualize the trend in seven-day average new COVID-19 cases over time.

- **X-axis:** Date
- **Y-axis:** Seven-day average new cases
- **Aggregation:** Sum, when appropriate for the selected country or countries

### Country Slicer

A country/location slicer allows users to select a country and explore its COVID-19 case trend.

## Expected Insights

- Changes in COVID-19 cases over time.
- Country-level trends and comparisons.
- Periods of increasing or decreasing cases.
- Differences in trends between selected countries.

Actual insights will be documented after completing and validating the dashboard.

## How to Use

1. Download or clone this repository.
2. Open the Power BI `.pbix` file using Microsoft Power BI Desktop.
3. If required, update the dataset path in Power BI.
4. Refresh the data.
5. Use the country slicer and charts to explore the data.

## Project Status

**Day 1:** Dataset setup, initial data preparation, and COVID-19 cases trend visualization.
