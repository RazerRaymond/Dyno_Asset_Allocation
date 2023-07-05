# Dyno_Asset_Allocation

An dynamic asset allocation study that bacjtesting multiple strategies' performances on real market data.

Present a comprehensive analysis of various asset allocation strategies applied to three benchmark Exchange-traded fund (ETFs) - iShares US Technology, Health-care, and Utilities - across different market conditions.
The methods tested include Inverse Volatility, Max Diversification, Risk Parity, Hierarchical Risk Parity, and Black-Litterman with different priors and clustering techniques. Employed a range of metrics, including Out-of-Sample Return, Out-of-Sample Sharpe Ra-tio, Sortino Ratio, Maximum Drawdown, Calmar Ratio, and Turnover ratio. Our findings suggest that when selecting an asset allocation strategy, it is important to consider whether the transaction cost matters or not. If transaction costs are high, then a strategy that prioritizes low turnover can be beneficial.

The closed-form r isk p arity method that we designed to minimize transaction costs consistently outperformed other strategies and surpassed the 1/N benchmark allocation across all assets and the market portfolio. However, if transaction costs are negligible, a strategy such as the Black-Litterman model will offer a Sharpe ratio even higher. We confirmed the robustness of our approach across various time periods, demonstrating resilience to market changes. Our asset allocation strategy, which takes turnover ratio into consideration, offers an effective, in tuitive, and adaptive solution for improved portfolio optimization across diverse assets.

Authors: Charles Xu, Gechen Shen, Yuyang Xu, Huarui Zhang, Jiaqi Xi
