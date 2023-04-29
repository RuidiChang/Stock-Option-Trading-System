# Stock-Option-Trading-System
Established a stock option trading system to predict price trend and simulated a model-managed portfolio. 

• Created a Financial News Predictor object by Tweet scraping, built databases storing critical keywords and labelled articles.

• Cleaned the raw news and price data from API, extracted features and pre-processed the data, aggregated the features and
implemented the sentiment analysis using FinBERT model, TextBlob and SVD.

• Predict prices using XGBoost, the final RMSE and MAPE for test set are 1.162 and 0.58% respectively.

Preprocessing: Remove emoticons, Add sentiment polarity, Replace negations by tag "NOT", Convert Acronym

Feature generator: TextBlob sentiment

Feature aggregator: SVD

Exploratory Data Analysis: Match news_vectors and price data, select feature sklearn.feature_selection

XGBoost: The model has a greater tendency to label news with 'do_nothing'.

<img width="473" alt="Performance_Test" src="https://user-images.githubusercontent.com/92975748/235268279-1326fd47-4cd7-40d1-8629-f38ee280884d.png">


Citation: https://github.com/Sapphirine/202005-Event-Linkage-and-Impact-Prediction



