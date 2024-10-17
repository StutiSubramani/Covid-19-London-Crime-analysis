# London Crime Analysis: Impact of COVID-19

## Project Overview

This project investigates the impact of the COVID-19 pandemic on crime patterns in London, focusing on how different types of crimes fluctuated during lockdowns and restrictive measures. By analyzing crime data across various periods (pre-pandemic, pandemic, post-pandemic), this study sheds light on the broader social effects of the pandemic and provides insights for future policy considerations.

## Objectives

Examine how crime rates evolved during the pandemic.
Identify crime categories most affected by lockdowns and restrictions.
Analyze the geographic and demographic variations in crime trends.
Provide data-driven insights to inform future policy and social interventions.

## Methods

#### Time Series Analysis:
Segmentation of crime data into pre-, during-, and post-pandemic phases.
Seasonal decomposition and trend identification using moving averages.
#### Lockdown Impact:
Interrupted Time Series Analysis (ITSA) to assess immediate effects of lockdowns on crime.
Comparison of full lockdowns vs. partial restrictions on crime categories.
#### Statistical Modeling:
Autocorrelation analysis (ACF/PACF) and ARIMA models for crime trend forecasting.
#### Geospatial Analysis:
Crime rate mapping to highlight geographic variations.
Spatial correlation using Moran’s I and LISA to identify crime clusters.
#### Correlation Analysis:
Examined the relationship between crime rates, COVID-19 cases, and socioeconomic factors such as population density and deprivation.

## Key Results

Property Crimes: Significant declines in burglary and theft, especially during strict lockdown periods.
Domestic Violence: Notable increase in domestic violence incidents, particularly during the early stages of the pandemic.
Geographic Variability: Crime trends varied across boroughs, influenced by local socioeconomic conditions.

## Data Source

London Crime Data: Monthly crime statistics across London boroughs (Source).
COVID-19 Data: Information on case numbers, lockdown periods, and government responses.
Demographic Data: Population data to normalize crime rates by borough.

## Tools & Technologies

Python for data analysis and visualization.
Pandas and NumPy for data manipulation.
Matplotlib and Seaborn for visualizing trends and patterns.
GeoPandas for geospatial analysis and mapping.
Statsmodels for time series analysis and statistical modeling.
