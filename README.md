# weather-forecasting-prophet

# weather-forecasting-prophet 🌦️📈

A **time series forecasting project** using Facebook Prophet to model and predict weather patterns over time.

This project focuses on **trend, seasonality, and forecast uncertainty**, demonstrating how probabilistic forecasting can be applied to real-world environmental data.

---

## Objective

The goal of this project is to:
- Build an interpretable weather forecasting model using historical data
- Capture seasonal and trend components in weather time series
- Evaluate forecast accuracy and uncertainty over future horizons

---

## What the Model Does

Given historical weather observations, the model:
- Learns long-term **trends**
- Captures **daily / weekly / yearly seasonality**
- Produces **future forecasts with confidence intervals**

Typical use cases:
- Short- and medium-term weather forecasting
- Understanding seasonal patterns (e.g. temperature cycles)
- Demonstrating applied time series modelling techniques

---

## Data

The dataset includes historical weather observations such as:
- Date / timestamp
- Temperature (or other weather metrics)
- Optional additional variables (humidity, precipitation, etc.)

> Data is cleaned and reformatted to match Prophet’s required structure  
> (`ds` for date, `y` for target variable).

---

## Approach

1. **Data Preparation**
   - Handle missing dates and values
   - Rename columns for Prophet compatibility
   - Train / validation split by time

2. **Modelling**
   - Baseline Prophet model
   - Trend + seasonality decomposition
   - Optional holiday or custom seasonal components

3. **Forecasting**
   - Generate future predictions
   - Extract prediction intervals
   - Visualise forecasts vs historical data

4. **Evaluation**
   - Compare forecasts against holdout data
   - Error metrics (MAE / RMSE)
   - Qualitative assessment of uncertainty bands

---

## Tech Stack

- Python
- Pandas
- Prophet
- NumPy
- Matplotlib

---

## Project Structure

