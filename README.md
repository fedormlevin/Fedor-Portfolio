# Fedor Levin's Data Science Portfolio

## [Regime Change Prediction - US Recessions](https://github.com/fedormlevin/regime-change/blob/main/README.md)

- Extracted macroeconomic indicators from FRED
- Selected features and trained Logistic Regression model
- Achieved Area Under Curve: 0.94
- Forecasted 2020 recession one month ahead of the official data<br>

![image info](./regime_ch.png)

## [Constant Proportion Portfolio Insurance - Industry Portfolio](https://github.com/fedormlevin/cppi-industry-portfolio/blob/main/README.md)

- Created industry indexes based on S&P500 prises and market capitalization
- Applied CPPI model using STIP ETF as a "safe" asset
- Compared price returns of the combined portfolio to the "risky" (equity only) portfolio
- Achieved significant max drawdown reduction (38% for "Energy Minerals")

![image info](./riskysafe.png)

## [Sentiment Analysis - Markers - Amazon Reviews](https://github.com/fedormlevin/sentiment-amazon-markers-reviews/blob/main/README.md)

- Created Logistic Regression models predicting Positive/Negative labels for Amazon reviews of acrylic markers
- Engineered features using N-grams and Tfidf
- Optimized using GridsearchCV to reach the best model
- Achieved Area Under Curve: 0.90<br>

![image info](./truevspredicted.png)
