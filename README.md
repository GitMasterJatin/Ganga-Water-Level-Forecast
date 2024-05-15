# Ganga Water Level Prediction Project

## Overview

This project aims to predict the water level of the Ganga river for the next two years using data fetched from Altmetry and Broadway Radar Altimetry Toolbox. The prediction models utilized for this task include ARIMA (AutoRegressive Integrated Moving Average) and SARIMAX (Seasonal AutoRegressive Integrated Moving Average with eXogenous regressors).

## Data Fetching

Data for this project was sourced from Altmetry and Broadway Radar Altimetry Toolbox. These platforms provide reliable and up-to-date information regarding water levels in various rivers, including the Ganga.

## Prediction Models

1. ARIMA:
   - ARIMA is a time series forecasting model that captures the temporal dependencies in the data.
   - It consists of three main components: AutoRegressive (AR), Integrated (I), and Moving Average (MA).
   - ARIMA models are particularly useful for stationary time series data.

2. SARIMAX:
   - SARIMAX is an extension of ARIMA that incorporates seasonal components and exogenous variables.
   - It stands for Seasonal AutoRegressive Integrated Moving Average with eXogenous regressors.
   - SARIMAX models are suitable for time series data with seasonal patterns and external influences.

## Usage

1. Data Collection:
   - Use Altmetry and Broadway Radar Altimetry Toolbox to fetch water level data for the Ganga river.
   - Ensure that the data is clean and formatted correctly for analysis.

2. Data Preprocessing:
   - Perform any necessary data cleaning and preprocessing steps.
   - Convert the time series data into a format suitable for input into the prediction models.

3. Model Training:
   - Train the ARIMA and SARIMAX models using historical water level data.
   - Tune the model parameters to optimize performance.

4. Prediction:
   - Use the trained models to predict the water level of the Ganga river for the next two years.
   - Evaluate the accuracy of the predictions using appropriate metrics.

## Dependencies

- Python 3.x
- NumPy
- Pandas
- Statsmodels

## Acknowledgements

- Altmetry: (https://www.copernicus.eu/en)
- Broadway Radar Altimetry Toolbox: https://earth.esa.int/eogateway/tools/broadview-radar-altimetry-toolbox

## Contributors

- JATIN SHARMA




