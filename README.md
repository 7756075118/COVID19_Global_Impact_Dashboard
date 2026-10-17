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


## ## Dataset Setup

The original and cleaned CSV datasets are not included in this GitHub repository because of their large file sizes.

### Download the Dataset

1. Visit [Our World in Data — COVID-19 Data](https://ourworldindata.org/covid-cases).
2. Download the required COVID-19 dataset.
3. Save the CSV file in `Day1_Covid19_Global_Impact_Dashboard/Dataset/`.
4. Run the analysis notebook to perform data preparation and generate cleaned data.

The cleaned dataset is generated locally and is excluded from Git tracking.

### Day 2

# COVID-19 Global Impact Dashboard — Day 2

## 1. Project Objective

To analyze global COVID-19 data and identify trends in reported cases, deaths, and vaccination coverage across countries and dates.

## 2. Tools Used

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Jupyter Notebook
- Power BI

## 3. Day 2 Activities

- Loaded and inspected the Our World in Data COVID-19 dataset.
- Cleaned country and date fields and removed duplicate country-date records.
- Handled missing values without treating all missing reports as zero.
- Created seven-day rolling averages for new cases and deaths.
- Calculated case fatality ratio, vaccination coverage, and approximate case doubling time.
- Created visualizations for case trends, deaths, and country comparisons.
- Exported the cleaned dataset for dashboard development.

## 4. Deliverables

- Cleaned CSV dataset
- Jupyter Notebook containing analysis
- Charts and visualizations
- Initial insights for the executive summary

## 5. Next Steps

- Complete the interactive Power BI dashboard.
- Validate key metrics and document assumptions.
- Prepare three to five evidence-based insights.
- Create a one-page executive summary PDF.

## Day 3 — Advanced COVID-19 Analysis

### Objective
Perform advanced analysis of COVID-19 data to identify case trends, mortality patterns, vaccination coverage, and differences between selected countries.

### Tasks Completed
- Loaded and validated the COVID-19 dataset using Python and Pandas.
- Checked dataset dimensions, duplicate rows, missing values, and date ranges.
- Converted date and numeric columns into appropriate data types.
- Calculated 7-day rolling averages for new cases and new deaths.
- Analyzed reported cases and deaths per million people.
- Calculated the Case Fatality Rate (CFR).
- Calculated vaccination coverage and full vaccination coverage as percentages of population.
- Compared India, the United States, and Brazil using available data.
- Prepared country-level summary metrics for further analysis.

### Dataset Details
- **Source:** Our World in Data — COVID-19 dataset
- **Input file:** `owid-covid-data.csv`
- **Dataset dimensions:** 395,311 rows and 72 columns before additional Day 3 calculations
- **Date range:** January 1, 2020 – August 14, 2024

### Key Findings
1. **COVID-19 waves:** The 7-day rolling average helps identify increases and decreases in reported cases over time.
2. **Country comparison:** The United States had approximately 305,763.91 reported cumulative cases per million in the displayed comparison.
3. **Mortality:** The United States recorded approximately 3,527.05 reported deaths per million in the displayed comparison.
4. **Vaccination rollout:** India's displayed record showed approximately 72.50% with at least one vaccine dose and 67.18% fully vaccinated.
5. **Case Fatality Rate:** The displayed values were approximately 1.15% for the United States and 1.87% for Brazil.

*Note: These findings are based on available reported records. Missing values and differences in reporting can affect comparisons. Historical peaks and changes should be verified using the relevant trend charts.*

### Tools and Technologies
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Jupyter Notebook
- Git and GitHub

### Day 3 Deliverables
- Advanced analysis notebook
- Calculated COVID-19 metrics
- Country comparison summary
- Updated analysis CSV file
- Visualizations of COVID-19 trends, where generated

### Learning Outcomes
- Learned to calculate rolling averages and epidemiological indicators.
- Practiced handling missing values in real-world datasets.
- Improved skills in time-series analysis and country-level comparisons.
- Developed a foundation for improving the interactive Power BI dashboard.

## Day 4 — COVID-19 Global Impact Dashboard

### Objective
Develop an interactive Power BI dashboard to analyze reported COVID-19 cases, deaths, and vaccination coverage across countries and dates.

### Tasks
- Loaded the Day 3 analysis dataset into Power BI Desktop.
- Checked data types for date, country, cases, deaths, and vaccination columns.
- Planned the COVID-19 Overview page with KPI cards, cases trends, deaths trends, and country comparisons.
- Created the plan for a Vaccination Analysis page with vaccination trends and country comparisons.
- Added country and date slicers to support interactive analysis.
- Reviewed missing vaccination values and country-comparison limitations.
- Prepared the Day 4 project report.

### Dashboard Pages
1. **COVID-19 Overview:** KPI cards, cases and deaths trends, and country comparison.
2. **Vaccination Analysis:** Vaccination coverage trends, fully vaccinated trends, country comparison, and country/date filters.

### Tools Used
- Power BI Desktop
- Python and Pandas
- CSV dataset
- Git and GitHub

### Data Quality Notes
- Missing vaccination values should remain blank rather than being replaced with zero.
- Cumulative case and death totals should not be summed across daily records.
- Country comparisons should use a common reference date where possible.
- Reported trends do not establish cause and effect.

### Deliverables
- Power BI dashboard (`.pbix`)
- Dashboard screenshots
- Day 4 project report (PDF)
- Updated README documentation
