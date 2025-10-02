# Time Series Forecasting for Household Energy Consumption

## Overview:

Accurate forecasting of energy consumption is critical for energy providers to manage grid
stability, for consumers to optimize their usage, and for developing strategies for
sustainability. Machine learning offers powerful tools for analyzing historical consumption
patterns and making accurate predictions about future demand. This project aims to build a
machine learning model to forecast household energy consumption based on historical timeseries data. To achieve this, you will work through the complete machine learning project
lifecycle: data collection, cleaning and preprocessing, exploratory analysis, model training,
and evaluation.

## Data Collection:

- Choosen a publicly available, gold-standard time-series dataset for household energy
  consumption. The recommended dataset is in the "Individual household electric power
  consumption Data Set" available from the UCI Machine Learning Repository, which can
  also be accessed on Kaggle: https://www.kaggle.com/datasets/uciml/electric-powerconsumption-data-set.
- Selecting and loading the dataset containing the time-series data.

## Data Preprocessing:

- Cleaned the data by handling missing values and any duplicates. This dataset is known
  to have missing values that require a robust strategy.
- Convert the data into a format suitable for time-series analysis. This involved parsing date-time columns and setting a time-based index.
- Resampled the data to a more appropriate frequency (e.g., from minute-level to hourly
  or daily averages) to make computation manageable and to smooth out noise.
- Performed feature engineering by creating new time-based features.

## Exploratory Data Analysis (EDA):

- Conducted an exploratory analysis of the resampled data.
- visualizations (e.g., line plots, box plots) to identify trends, seasonality, and other
  patterns in energy consumption over time.

## Model Selection and Design:

- Spliting the preprocessed time-series dataset into training and testing sets.
- Proposed and provided brief details for existing machine learning algorithms
  suitable for time-series forecasting. Consider a mix of classical statistical models and
  modern machine learning regression models.

## Model Evaluation:

- Evaluating models using appropriate regression metrics such as Mean Absolute
  Error (MAE), Root Mean Squared Error (RMSE), and R-squared (R2
  ).
- Visualizing the performance by plotting the predicted values against the actual values for
  the test set.
- Comparing the machine learning techniques, emphasizing the model that performed the best and outlining the factors that contributed to its success.
