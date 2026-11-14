# Air Quality Across Six Indian Monitoring Sites (2019–2025)

## Project overview

This project analyzes daily air-quality observations from six selected CPCB monitoring sites in India. It explores data coverage, particulate pollution patterns, seasonal and yearly variation, relationships between pollutants and weather, selected event periods, and next-day PM2.5 forecasting.

The results describe the selected monitoring sites. One station per city does not represent the entire city or India as a whole.

## Research question

How has air quality changed across the selected Indian monitoring sites since 2019, where and when are pollution levels highest, which variables are associated with pollution, and how well can next-day PM2.5 be predicted?

## Selected monitoring sites

- **Delhi:** Anand Vihar
- **Jaipur:** Police Commissionerate
- **Mumbai:** Worli
- **Kolkata:** Rabindra Bharati University
- **Bengaluru:** BTM Layout
- **Chennai:** Manali

These sites were selected to compare monitoring locations across different Indian regions and urban settings. They are case studies, not a nationally representative sample.

## Data

- **Source:** Central Pollution Control Board (CPCB), National Air Quality Data Management System (CAAQMS)
- **Source website:** https://airquality.cpcb.gov.in
- **Data frequency:** Daily 24-hour averages
- **Study period:** January 1, 2019–December 31, 2025
- **Downloaded files:** 42 files covering the selected sites and years
- **Approximate size:** 15,300 station-days

The variables analyzed include PM2.5, PM10, NO₂, NO, NOx, NH₃, SO₂, CO, ozone, benzene, toluene, xylene, temperature, relative humidity, and wind speed. Data availability varies by site, year, and variable.

## Analysis

The project examines:

- Data coverage and missing observations
- PM2.5 and PM10 distributions across stations
- Annual and monthly median patterns
- Daily variation and high-reading days
- Lockdown-period comparisons
- Pollutant and weather-variable associations
- Diwali-period comparisons
- Next-day PM2.5 forecast performance at Anand Vihar, Delhi

Charts show observed patterns and associations. They do not, by themselves, prove what caused a change.

## Main findings

- Anand Vihar, Delhi, has the highest annual median PM2.5 and PM10 among the selected sites in the reported comparisons.
- PM2.5 and PM10 tend to move together, while relationships with weather variables differ across stations.
- Particulate readings generally show seasonal variation, but the pattern and its strength differ by site and year.
- The annual trends do not show one shared direction of change across all six sites.

## Limitations

- The project uses one monitoring site per city. Results describe those sites, not entire cities.
- The six sites are case studies and are not a representative sample of India.
- Data coverage varies by site, year, and pollutant. Low-coverage periods limit some comparisons.
- Daily averages do not show within-day changes or brief pollution episodes.
- Event-period comparisons cannot prove that an event caused an observed change.
- Correlations show associations, not causation.
- The forecast evaluates a selected station and test period, so results may not generalize to other stations or future years.

- `requirements.txt` — Python packages, if included

## Data and reuse

Air-quality data are from CPCB. Check the source’s terms before redistributing downloaded data. If the raw data are not included, use the source information above to locate them.

## Acknowledgements

Central Pollution Control Board (CPCB) for the air-quality data.
