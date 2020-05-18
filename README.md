# UCSD DSC 190 Data Mining Challenge ([Kaggle](https://www.kaggle.com/c/ucsd-spring20-dsc190-intro-to-data-mining/leaderboard))

Dataset: New York Airbnb Dataset <br />
Task: Price Prediction

## Note:
- `train.ipynb` contains my work without any cleanup, which means that there are some code that is unused for the final model. But I want to keep it simply because it reflects the true process of finding the best features for model training and ddeveloping the best training method.
- `Below-80-Minimal-Features.ipynb` Production-ready Pipeline. It uses minimal number of features and minimal feature engineering. This effectively reduces memory usage and time duration during model training. (Before onehot: 51; After onehot: 95). This approach achieve RMSE score of 80, which is in Top 15 on the leaderboard
