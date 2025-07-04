# Spatial Statistics and Time Series Analysis - Training Exercises

A collection of educational R scripts for learning spatial statistics and time series analysis, developed during graduate-level coursework in geo-epidemiology and spatial statistics.

## Overview

This repository contains practical exercises covering:

- **Spatial Analysis**: Autocorrelation, clustering, GAM modeling
- **Time Series Analysis**: Decomposition, ARIMA modeling, forecasting
- **Applied Examples**: Real-world datasets from epidemiology and economics

## Scripts Overview

| Script | Topic | Dataset | Key Concepts |
|--------|-------|---------|--------------|
| `spatial_autocorrelation_malaria.R` | Spatial Autocorrelation | Malaria incidence data | Moran's I, spatial clustering |
| `time_series_decomposition_airpassengers.R` | Time Series Basics | AirPassengers | Decomposition, seasonality |
| `arima_modeling_temperature.R` | Stationarity & ARIMA | Temperature data | ADF tests, differencing |
| `forecasting_johnson_johnson.R` | Advanced Forecasting | Johnson & Johnson stock | Holt-Winters, model comparison |
| `spatial_gam_burkina_faso.R` | Spatial GAM | Burkina Faso health data | GAM, spatial effects |
| `spatial_clusters_satscan.R` | Spatial Clustering | Disease surveillance | SaTScan methodology |
| `time_series_correction_exercises.R` | Model Validation | Multiple datasets | Residual analysis, diagnostics |

## Prerequisites

### Required R Packages

```r
# Spatial analysis
install.packages(c("sf", "spdep", "tmap", "mgcv"))

# Time series analysis  
install.packages(c("forecast", "tseries", "tsibble", "fable", "feasts"))

# General packages
install.packages(c("readxl", "dplyr", "ggplot2", "corrplot"))
