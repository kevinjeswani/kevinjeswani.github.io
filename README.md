# Kevin Jeswani - Data Science Projects

## [Big Twitter Topic Modelling (Clustering) & Sentiment (Classification)](https://github.com/kevinjeswani/BigTwitter_Clustering-Classification)
-	Streamed tweets into AWS S3 with Kinesis Firehose and combined it with a larger 55 mil.-tweet dataset *(Not covered in this repo)*
-	Utilized PySpark in DataBricks to build custom PySpark transformers, label sentiment with SparkNLP/VADER, explore SparkML RandomForest and Logistic Regression classifiers, and to perform Latent Drichlet Allocation topic modelling
-	Visualized results in AWS QuickSight through an Athena pipeline


## [Foreign Exchange Rate Forecasting](https://github.com/kevinjeswani/forex_stock_forecasting)
Foreign Exchange Rate Forecasting
-	Locally-warehoused 11gb of financial API stock/ ForEx data by parallelizing API calls in Dask and storage in SQLite
-	Developed additional normalized financial technical indicators to create exogenous variable time-series
-	Studied classical forecasting techniques (ARIMA, VARMAX) to determine ForEx trend and seasonality dependence
-	Performed a grid-search cross-validation hyperparamter tuning of XGBoost, RandomForest, CatBoost, & LGBoost time-series regressors (SkForecast) and built a LSTM-RNN (PyTorch-Keras) regressor, incorporating exogenous variables <br>
	**IN PROGRESS**: 
- Upgrading forecasting framework with GluonTS
- Application to tech and semiconductor stocks

## Historical Sales Analysis of Activewear Startup (Real Client) - Ongoing
-	Examined $1.5 mil. of sales data of a recently-acquired activewear firm to provide the new owner with insight on current/historical product lines with highest sales and regions with greatest concentration of sales, to streamline future product offerings/development and for region-/demographics-specific marketing
-	Forecasted future demand of product categories given discount rates using GluonTS (Neural Nets), Prophet, & AutoTS
IN PROGRESS:
-	Developing a CI/CD pipeline and dashboard web-app with Plotly-Dash/Atoti & Heroku for forecasting & profitability


## [Regression Analysis of Deaths due to Environmental Factors](https://github.com/kevinjeswani/Environmental_Factor_Deaths)
-	Utilized Auto-ML (PyCaret) for regressor model selection and preliminary hyperparameter selection
-	Hyperparamter tuning, auto-encoding, cross-validation, & ensembling of RandomForest, Extra Tree, and XGBoost

## [Online Retail Competitor Intelligence for 2 Real Clients](https://github.com/kevinjeswani/Lazada_Scraping)
-	Scraped 4000+ Lazada product pages of clients, their competitors, and similar recommended products (with Selenium)
-	Derived insight on comparative prices, discounts, & ratings across similar items. Assessed text similarity between the clients’ products and similar items using SpaCy, to find and report suspected “copy-cat” posts

