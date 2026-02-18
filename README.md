# Portfolio-Optimisation-in-Australian-Mining-and-Metals-Project

- Collected daily financial data from Yahoo Finance for the period 2021–2025. The portfolio consisted of 11 assets including BHP.AX, FMG.AX, RIO.AX, EVN.AX, NST.AX, IGO.AX, PLS.AX, LTR.AX, SFR.AX, SVL.AX, and GOLD.AX (GC=F).

- Preprocessed the dataset by removing outliers using Z-score filtering, handling missing values, and computing log returns to capture continuously compounded asset returns.

- Performed exploratory data analysis (EDA), including price trend visualisation, trading volume analysis, return distributions, volatility patterns, and correlation matrices to evaluate diversification potential.

- Implemented the Mean-Variance Model (Markowitz Portfolio Optimisation) to construct the Efficient Frontier, identify minimum-variance portfolios, and determine the Tangency Portfolio with the maximum sharpe ratio.

- Developed the Black–Litterman Model by integrating market equilibrium returns with subjective investor views, generating more stable and diversified allocations compared to traditional mean-variance optimisation.

- Applied the Risk Parity Portfolio approach to equalise asset risk contributions preventing over-concentration in highly volatile mining equities and improving diversification balance.

- Formulated a Conditional Value-at-Risk (CVaR) Optimisation Model to minimise downside risk by controlling extreme losses beyond the Value-at-Risk threshold, suitable for risk-averse investors

- Compared the performance of all four models (Markowitz, Black–Litterman, Risk Parity, CVaR) across key metrics such as expected returns, volatility, risk contribution, and tail-risk exposure.

- Visualised results using the Efficient Frontier, portfolio allocation weight charts, and CVaR tail-loss distributions to clearly illustrate model differences.

- Provided investment strategy insights for investors who are interested in mining and commodity-focused financial assests.
