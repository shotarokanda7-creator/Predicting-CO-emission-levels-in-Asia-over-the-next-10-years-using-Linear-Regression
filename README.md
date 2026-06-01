# CO₂ Emission Forecasting in Asia

## Overview

This project develops machine learning models to forecast CO₂ emissions across Asia using climate, demographic, and economic indicators.

The objective is to predict future regional CO₂ emission levels by analyzing historical relationships between emissions and key explanatory variables such as:

* GDP
* Population
* Urban Population
* Greenhouse Gas (GHG) Changes

## Dataset

Climate Change Dataset from World Bank Climate Data Repository.

## Methodology

### Data Preparation

* Filtered Asian countries
* Handled missing values using interpolation and mean imputation
* Aggregated regional statistics
* Constructed feature datasets for modelling

### Exploratory Data Analysis

* Correlation analysis
* Distribution analysis
* Time-series trend analysis

### Models

1. Linear Regression
2. ARIMA Time Series Forecasting
3. Gradient Boosting Regressor

## Results

| Model             | R² Score |
| ----------------- | -------- |
| Linear Regression | 0.922    |
| Gradient Boosting | 0.965    |

Gradient Boosting outperformed Linear Regression by capturing complex non-linear relationships among economic and environmental variables.

## Key Insights

* Urban population showed the strongest correlation with CO₂ emissions.
* GDP and population growth were significant emission drivers.
* Gradient Boosting provided the most accurate long-term forecasts.

## Technologies

* Python
* Pandas
* NumPy
* Scikit-Learn
* Statsmodels
* Matplotlib
* Seaborn

## Author

Shotaro Kanda
