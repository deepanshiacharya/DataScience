**1. Impact of Market Sentiment on Profitability**
The results show that sentiment plays a significant role in shaping overall profitability. On average, traders performed best under Fear conditions, generating the highest mean closed PnL (154.2) and the most favorable risk-adjusted returns (highest Sortino ratio). Extreme Greed markets also delivered positive returns (mean PnL = 46.6), but the higher volatility in losses reduced the efficiency of these gains. Neutral markets provided moderate and stable outcomes, while Greed markets consistently underperformed, with very low profitability and near-zero Sharpe and Sortino ratios.

This suggests that traders are more disciplined and effective under Fear, while Greed encourages overconfidence and poor decision-making. Extreme Greed, although profitable in nominal terms, exposes traders to large downside risks.

**2. Win Rate and Trade Sizing**
Win rates varied across sentiments, with the highest observed in Extreme Greed (71%) and the lowest in Greed (38%). However, trade sizing revealed an important nuance. In Fear markets, traders committed the largest average trade sizes ($15.5K) and still managed to remain profitable, highlighting a confident but disciplined approach. In Extreme Greed, traders typically used smaller trade sizes ($4.1K), which helped manage risk despite higher win rates. By contrast, Greed conditions were marked by large trade sizes but poor outcomes, reflecting inefficient capital allocation.

**3. PnL by Side and Direction**
Analysis by trade side and direction showed that Buy trades during Fear markets produced the strongest returns, particularly when closing short positions. In Neutral markets, Sell trades were also profitable. Conversely, Buy trades in Greed markets were consistently loss-making. Closing positions (both Long and Short) emerged as the most important contributors to profitability, while less common directions such as Auto-Deleveraging or Spot Conversions had minimal impact.

**4. Risk-Adjusted Performance Over Time**
Cumulative PnL analysis confirmed that Fear-driven trading compounded steadily over time, while Greed-driven trading stagnated. Sharpe and Sortino ratio analysis reinforced this pattern: Fear provided the best balance of returns and risk, Extreme Greed looked attractive on the Sharpe ratio but much weaker on the Sortino due to high downside volatility, and Greed produced negligible efficiency.

**5. Machine Learning Insights**
Machine learning models were applied to predict trade outcomes (Win vs. Loss). XGBoost delivered the strongest results (F1 = 98.7%), followed closely by Random Forest (F1 = 98.3%) and Logistic Regression (F1 = 94.9%). Feature importance analysis revealed that trade execution features (side, open/close long or short, execution price, and position size) were far more influential than the sentiment classifications themselves. While sentiment captures the broader environment, the mechanics of trade execution ultimately determine individual success.

**Strategic Implications**

Traders should allocate more capital and focus on opportunities during Fear markets, where performance is consistently strongest.
Extreme Greed markets can be profitable but require cautious position sizing to manage volatility.
Greed-driven trades should largely be avoided due to consistently poor performance.
Neutral conditions offer moderate opportunities but may not justify aggressive strategies.
Execution decisions are more critical than sentiment alone. Optimal strategies should combine sentiment indicators with execution signals such as trade side and closing behavior.

**Final Takeaway**

Market sentiment influences overall profitability trends, but individual trade outcomes depend more on execution strategy. Fearful market environments provide the best conditions for consistent and risk-adjusted gains, while Greed environments often lead to poor performance. Integrating sentiment signals with machine learning models focused on execution variables offers the most promising approach for developing smarter, more resilient trading strategies.
