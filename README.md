# Kevin Jeswani - Data Science Projects

# [Project 1: Big Twitter Topic Modelling (Clustering) & Sentiment (Classification)](https://github.com/kevinjeswani/BigTwitter_Clustering-Classification)
-	Streamed tweets into AWS S3 with Kinesis Firehose and combined it with a larger 55 mil.-tweet dataset *(Not covered in this repo)*
-	Utilized PySpark in DataBricks to build custom PySpark transformers, label sentiment with SparkNLP/VADER, explore SparkML RandomForest and Logistic Regression classifiers, and to perform Latent Drichlet Allocation topic modelling
-	Visualized results in AWS QuickSight through an Athena pipeline


# [Project 2: Foreign Exchange Rate Forecasting](https://github.com/kevinjeswani/forex_stock_forecasting)
Foreign Exchange Rate Forecasting
-	Locally-warehoused 11gb of financial API stock/ ForEx data in SQLite
-	Developed additional normalized financial technical indicators to create exogenous variable time-series
-	Studied classical forecasting techniques (ARIMA, VARMAX) to determine ForEx trend and seasonality dependence
-	Performed a grid-search cross-validation hyperparamter tuning of XGBoost, RandomForest, CatBoost, & LGBoost time-series regressors (SkForecast) and built a LSTM-RNN (PyTorch-Keras) regressor, incorporating exogenous variables
	IN PROGRESS: 
- Upgrading forecasting framework with GluonTS
- Application to Tech and Semiconductor stocks

# Project 3: Historical Sales Analysis of Activewear Startup (Real Client)
-	Examined $1.5 mil. of sales data of a recently-acquired activewear firm to provide the new owner with insight on current/historical product lines with highest sales and regions with greatest concentration of sales, to streamline future product offerings/development and for region-/demographics-specific marketing
-	Forecasted future demand of product categories given discount rates using GluonTS (Neural Nets), Prophet, & AutoTS
-	Developing a CI/CD pipeline and dashboard web-app with Plotly-Dash/Atoti & Heroku for forecasting & profitability


# [Project 4: Regression Analysis of Deaths due to Environmental Factors](https://github.com/kevinjeswani/Environmental_Factor_Deaths)
-	Utilized Auto-ML (PyCaret) for regressor model selection and preliminary hyperparameter selection
-	Hyperparamter tuning, auto-encoding, cross-validation, & ensembling of RandomForest, Extra Tree, and XGBoost
