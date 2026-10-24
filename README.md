# investor-sentiment-fear-greed

Master's thesis (Data Science & Business Analytics, IMF Business School, 2026).
Builds a Fear & Greed indicator with machine learning and tests whether it
beats passive strategies like Dollar Cost Averaging (DCA).

## Key results
- Random Forest reconstructs the crypto Fear & Greed index (R² = 0.56 on a 2024-2025 hold-out set)
- Transfer learning adapts the model to the S&P 500 and gold
- Sentiment-based strategies beat DCA in backtests (e.g. S&P 500: +152% vs +79%, 2018-2025)

## Data sources
Yahoo Finance, Alternative.me API, Google Trends, AAII Sentiment Survey

## Methodology
1. Data collection and cleaning
2. Exploratory data analysis
3. Feature engineering (RSI, Bollinger bands, drawdowns, VIX, volatility)
4. Modelling (Linear Regression, Random Forest, XGBoost)
5. Transfer learning to S&P 500 and gold
6. Backtesting vs DCA and Buy & Hold

## Limitations
Part of the backtesting period overlaps with the training data, no transaction
costs are included, and no risk-adjusted metrics (e.g. Sharpe ratio) were computed.

## Tools
Python, pandas, scikit-learn, MatplotLib, XGBoost, Plotly

## Author
Patrick Milla López | [LinkedIn](your-linkedin-link) | patrickmilla7@gmail.com
