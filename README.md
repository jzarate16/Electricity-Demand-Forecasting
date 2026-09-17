# Electricity-Demand-Forecasting
Electricity demand forecasting and self-consumption analysis using ARIMA time-series models.
# Spanish Electricity Demand and Self-Consumption

## ARIMA Modelling and Solar Radiation Analysis

Bachelor's Thesis project focused on modelling hourly electricity demand in the Spanish peninsular system and analysing the impact of photovoltaic self-consumption through solar radiation.

## Project Objective

The project develops statistical time-series models to:

- Model hourly electricity demand in mainland Spain.
- Analyse the main variables affecting electricity consumption.
- Quantify the impact of photovoltaic self-consumption.
- Study how solar radiation affects observed electricity demand.

## Data

The analysis uses hourly electricity-demand data from 2011 to 2025, together with explanatory variables including:

- Temperature
- Solar radiation
- National and regional holidays
- Calendar effects
- COVID-19 related effects

## Methodology

The project develops separate models for each of the 24 hours of the day using:

- Time-series analysis
- ARIMA models
- Reg-ARIMA models
- Seasonal analysis
- Residual diagnostics
- Explanatory regressors for holidays, temperature and solar radiation

## Key Results

The analysis shows that incorporating solar radiation improves model performance during central hours of the day.

The estimated photovoltaic self-consumption:

- Reached approximately 10% of electricity demand in May 2025.
- Increased from approximately 5,300 GWh in 2021 to 13,000 GWh in 2024.

## Technologies

- R
- Time-series modelling
- ARIMA / Reg-ARIMA
- Statistical analysis
- Data visualisation

## Repository Structure

- `code/` — R scripts used for data preparation, modelling and analysis
- `figures/` — Selected visualisations and results
- `thesis/` — Full thesis document
