# investor-sentiment-fear-greed

Master's thesis (Data Science & Business Analytics, IMF Business School, 2026).
The primary objective of this research is to analyze whether investor sentiment plays a fundamental role in financial markets, specifically within the cryptocurrency market, the S&P 500, and gold—three of the most liquid and capitalized markets globally. To achieve this, the project builds upon the established Fear & Greed Index from the crypto ecosystem, benchmarking its signaling performance against passive investment strategies such as Dollar-Cost Averaging (DCA) and lump-sum investing. Subsequently, using transfer learning techniques, an equivalent sentiment indicator was extrapolated and constructed for both the S&P 500 and gold, enabling a cross-asset evaluation of market psychology.

## Key results
#### 1. Cryptocurrency Market (BTC & ETH)

Backtest Period (2018–2026):
* Passive Benchmark (DCA): Yielded approximately +479% on Bitcoin (BTC) and +473% on Ethereum (ETH).
* Standard Fear & Greed Strategy: Increased overall returns to +693% on BTC and +708% on ETH.

Out-of-Sample Test Period (2024–2025):
* Sentiment-based models—specifically the custom Machine Learning models developed in this project—achieved the highest overall performance.

Key Finding: Visual performance analyses demonstrate that sentiment-driven signals effectively identify price troughs ("buying the dips") during market capitulation phases.

#### 2. S&P 500 Index

Backtest Period (2018–2026):
* Passive DCA: Delivered a total return of ~79%.
* Cross-Asset Crypto Fear & Greed: Improved returns up to 95%.
* Transfer Learning Custom Models: Significantly outperformed all baselines, surpassing +100% cumulative return, with the top-performing custom sentiment model reaching +147%.

#### 3. Gold

Backtest Period (2018–2026):
* Passive DCA: Returned 140%.
* Cross-Asset Crypto Fear & Greed: Added an incremental +20% return boost compared to DCA.
* Transfer Learning Custom Model: Achieved ~180% return, demonstrating that adapting sentiment metrics directly to the precious metals market creates a substantial edge.

## Data sources
Yahoo Finance, Alternative.me API, Google Trends, AAII Sentiment Survey, CNN Business

## Methodology
1. Data collection and cleaning
2. Exploratory data analysis
3. Feature engineering (RSI, Bollinger bands, drawdowns, VIX, volatility)
4. Modelling (Linear Regression, Random Forest, XGBoost)
5. Transfer learning to S&P 500 and gold
6. Backtesting the strategy vs DCA and Buy & Hold

## Limitations
Part of the backtesting period overlaps with the training data, no transaction
costs are included, and no risk-adjusted metrics (e.g. Sharpe ratio) were computed.

## Tools
Python, pandas, scikit-learn, MatplotLib, XGBoost, Plotly

## Author
Patrick Milla López | [LinkedIn](https://www.linkedin.com/in/patrick-milla-lopez-49302a2a1/) | patrickmilla7@gmail.com
