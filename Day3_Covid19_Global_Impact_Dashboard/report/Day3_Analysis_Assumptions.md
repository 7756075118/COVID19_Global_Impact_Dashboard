# COVID-19 Global Impact Dashboard — Day 3

## Analysis and Cleaning Assumptions

**Data source:** Our World in Data COVID-19 dataset.

1. Date values were converted to a consistent datetime format.
2. Records without a valid country/location or date were excluded from the analysis.
3. Data was sorted by country and date before calculating rolling averages.
4. Seven-day rolling averages were calculated separately for each country. The first six observations per country remain blank for these averages.
5. Cases and deaths per million were calculated using population values to support fairer comparisons between countries.
6. Case fatality rate was calculated as reported cumulative deaths divided by reported cumulative cases, multiplied by 100.
7. Vaccination coverage was calculated using reported vaccination counts divided by population, multiplied by 100.
8. Missing values were not automatically replaced with zero. Missing observations were retained where appropriate.
9. Doubling time was estimated from cumulative reported cases seven observations apart. It was left blank where growth could not be calculated.
10. The analysis uses reported data. Differences in testing, reporting delays, population characteristics, and data revisions may affect comparisons.

## Day 3 Deliverables

- Analysis-ready CSV dataset
- Jupyter notebook containing calculations and visualizations
- Saved PNG charts
- Three to five evidence-based findings

## Limitation

Observed trends and associations do not by themselves establish causation. In particular, this analysis cannot prove that vaccination alone caused changes in death rates.