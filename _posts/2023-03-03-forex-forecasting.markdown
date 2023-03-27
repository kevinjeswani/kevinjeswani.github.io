---
layout: post
title:  Forex/Stock Forecasting
description: Foreign Exchange Rate (& Stock Price) Forecasting
date:   2023-03-03 15:00:00 +0800
image:  '/images/1005.jpg'
tags:   [timeseries,neural-nets]
featured: false
---
- Locally-warehoused 11gb of financial API stock/ ForEx data in SQLite, using Dask for parallelizing API calls. Initially used H5Tables for smaller forex dataset.
- Developed additional normalized financial technical indicators to create exogenous variable time-series
- Studied classical forecasting techniques (ARIMA, VARMAX) to determine ForEx trend and seasonality dependence
- Performed a grid-search cross-validation hyperparamter tuning of XGBoost, RandomForest, CatBoost, & LGBoost time-series regressors (SkForecast)
- Deep-learning with an LSTM-RNN (Keras) regressor, incorporating exogenous variables

[Github](https://github.com/kevinjeswani/forex_stock_forecasting)