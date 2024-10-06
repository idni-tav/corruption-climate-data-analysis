# Corruption and Climate Data Analysis

## Overview

This project explores the relationship between corruption and climate by analyzing data on temperature, corruption perception, democracy index, and GDP for democratic nations in 2019. The analysis uses Python libraries such as Pandas for data processing, and Matplotlib and Seaborn for visualization. This simplified analysis aims to demonstrate and practice key skills in data analysis for potential recruiters, rather than providing an exhaustive examination.

## Dataset Information

### Temperature:
- **Indicator**: Mean annual temperature per country.
- **Source**: [Kaggle](https://www.kaggle.com/datasets/palinatx/mean-temperature-for-countries-by-year-2014-2022)
- **License**: MIT License (Copyright © 2013 Mark Otto and 2017 Andrew Fong)

### Corruption:
- **Indicator**: Corruption Perception Index (CPI), a ranking of 180 countries based on perceived public sector corruption, with scores from 0 (highly corrupt) to 100 (very clean).
- **Source**: [Transparency International](https://www.transparency.org/en/cpi/2019)
- **License**: Creative Commons Attribution 4.0 International (CC BY 4.0)

### GDP:
- **Indicator**: GDP per capita, PPP (current international $), a measure of economic output per person, adjusted for purchasing power parity.
- **Source**: [World Bank](https://data.worldbank.org/indicator/NY.GDP.MKTP.PP.KD)
- **License**: World Bank data are available under the CC BY 4.0 license.

### Democracy:
- **Indicator**: Democracy Index, a measure of political freedom and civil liberties, ranging from 0 (least democratic) to 10 (most democratic).
- **Source**: [Our World in Data](https://ourworldindata.org/grapher/democracy-index-eiu)
- **License**: Creative Commons Attribution 4.0 International (CC BY 4.0)

## Visualizations

The following visualizations were created:
- Histograms
- Correlation Matrix Heatmap
- Regression Plots
- OLS Regression Summary
- Bar PLot

## Key Findings

- The Corruption Index shows strong positive correlations with both the Democracy Index (0.81) and GDP (0.80).
- There is a weaker negative correlation between the Corruption Index and Temperature (-0.59).
- Regression analysis indicates that GDP and the Democracy Index are statistically significant predictors of corruption, while Temperature is not (p-value = 0.401).
- The OLS Regression results yield an R-squared value of 0.814, meaning 81.4% of the variation in corruption can be explained by GDP and the Democracy Index.
- The corruption index is higher in countries with greater income levels and, within the same income group, higher for fully democratic countries.

## Limitations

- This analysis is simplified and only uses corruption as the primary indicator of a country's organization. Other factors like Public Sector Efficiency, Infrastructure Quality, and Bureaucracy should also be considered.
- Climate is more complex than just temperature measurements. A regional analysis, rather than a country-based one, could offer more accurate results.
- Examining climate over a longer period (30 years) would provide with more robust insights compared to a single year of data.


## Licenses

All datasets used in this analysis are public and available under open licenses:
- Kaggle: MIT License
- Transparency International: CC BY 4.0
- World Bank: CC BY 4.0
- Our World in Data: CC BY 4.0
