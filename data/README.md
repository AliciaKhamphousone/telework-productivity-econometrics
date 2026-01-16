# Telework and Productivity – Econometric Analysis

## Overview
This project investigates the impact of teleworking on worker productivity in France using
INSEE labor market data (2019–2021).

Productivity is proxied by hourly wages and analyzed through econometric methods.

## Dataset
- Source: INSEE – Enquête Emploi en Continu (EEC)
- Period: 2019–2021
- Observations: 100,000+ individuals
- Key variables: hourly wage, telework status, age, gender, working hours, sector

## Methodology
- Construction of hourly wage as a proxy for productivity
- Log-transformation of wages
- Ordinary Least Squares (OLS)
- Robustness checks (trimmed sample)
- Heckman two-step selection model
- Interaction effects by gender

## Key Results
- Telework is associated with a significant increase in hourly wages
- Results remain robust after correcting for selection bias
- The effect differs by gender

## Limitations
- Productivity measured indirectly through wages
- Potential remaining endogeneity
- Specific context of the COVID-19 period

## Tools
- Python
- pandas, numpy
- statsmodels

> This project is based on a first-year Master’s research project originally written in French.

