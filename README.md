# Stock-Option-Trading-System
Established a stock option trading system to predict price trend and simulated a model-managed portfolio. 

•	Created a Financial News Predictor object by Tweet scraping and defined text classifier, built databases storing critical keywords and labelled articles according to price data. 

•	Cleaned the raw news and price data from API, extracted features and pre-processed the data, then aggregated the features and implemented the sentiment analysis using FinBERT model. 

•	Optimized the price classification and regression model through XGBoost to predict prices. 

Preprocessing: Remove emoticons, Add sentiment polarity, Replace negations by tag "NOT", Convert Acronym

Feature generator: TextBlob sentiment

Feature aggregator: SVD

Exploratory Data Analysis: Match news_vectors and price data, select feature sklearn.feature_selection

XGBoost: The model has a greater tendency to label news with 'do_nothing'.

<img width="499" alt="Performance" src="https://user-images.githubusercontent.com/92975748/235268103-97024ee5-8bfa-446f-92de-d1168416e00a.png">




