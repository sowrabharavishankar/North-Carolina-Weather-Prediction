# TMAX 30-Day Forecast Using RandomForest

## Overview

This repository contains a Python project for forecasting **daily maximum temperatures (TMAX)** for 30 days using a **RandomForest regression model**. 
The model is trained on historical temperature data with lag features to capture short-term temporal patterns.

The project includes:

* Data preprocessing with lag feature creation
* RandomForest model training and saving
* 30-day temperature forecast after the last observed date
* Visualization of historical and forecasted temperatures

## Features

* Uses lag features (`lag1`, `lag2`, `lag7`) to predict next-day TMAX
* Generates a 30-day forecast beyond the historical dataset
* Plots historical data and forecast with shaded forecast period
* Publication-ready report template included

The script will output:

   * A **30-day forecast table** with predicted TMAX
   * A **plot** showing the last observed temperature and 30-day forecast

## Dependencies

* Python 3.8+
* pandas
* numpy
* scikit-learn
* matplotlib
* joblib

## References

* scikit-learn RandomForest documentation: [https://scikit-learn.org/stable/modules/ensemble.html#forest](https://scikit-learn.org/stable/modules/ensemble.html#forest)
* pandas documentation: [https://pandas.pydata.org/](https://pandas.pydata.org/)
* matplotlib documentation: [https://matplotlib.org/](https://matplotlib.org/)
