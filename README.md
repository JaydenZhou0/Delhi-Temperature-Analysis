# Delhi-Temperature-Analysis
Statistical analysis of temperature variation in Delhi using regression, GLS, and seasonal modeling

## Overview

This project analyzes temperature variation in Delhi using meteorological data.

The analysis investigates the relationships between mean temperature and humidity, wind speed, and atmospheric pressure, while accounting for seasonal patterns and temporal dependence.

## Methods

- Data cleaning and outlier detection
- Exploratory data analysis
- Multicollinearity diagnostics
- Multiple linear regression
- Generalized least squares (GLS)
- AR(1) correlation structure
- Seasonal dummy variables
- Interaction effects
- Model comparison using RMSE

## Key Findings

The analysis found evidence of temporal autocorrelation in the initial linear regression model, motivating the use of a GLS model with an AR(1) correlation structure.

<img width="422" height="260" alt="image" src="https://github.com/user-attachments/assets/efada91a-b5dd-40f2-8267-3da43808f4a5" />

After incorporating seasonal effects and interaction terms, the selected ANCOVA model provided better predictive performance than the GLS model in the comparison conducted in this project.

The model performed less well for extreme temperature values, suggesting that future work could explore time-series models or additional seasonal variables.
