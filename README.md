**Project Overview**

This project explores the relationship between trader performance and market sentiment. The main objective was to uncover patterns in how different sentiment states (Extreme Greed, Greed, Fear, Neutral) influence trading outcomes such as profitability, win rates, trade sizes, and risk-adjusted returns.

**Data Preparation**

Two datasets were provided, one containing trading performance metrics and the other containing market sentiment scores.
Both datasets were merged on the Date column to align trades with the corresponding daily sentiment classification.
Data cleaning steps included handling missing values, standardizing column formats, and engineering new features such as fee rate and win/loss indicators.

**Tools & Libraries Used**

Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost)

**Conclusion**

By merging trading data with sentiment data, this project successfully revealed how market psychology impacts trading outcomes. The analysis not only quantified profitability differences across sentiments but also highlighted which trade behaviors and conditions drive performance. These insights can help design more informed and adaptive trading strategies.
