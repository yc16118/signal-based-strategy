# signal-based-strategy

In this project, I will design a signal-based trading strategy for SPY using multiple linear regression model. SPY tracks the SPDR S&P 500 ETF trust, an exchange-traded fund which trades on the NYSE Arca, and is the largest and oldest ETF in the world.

I will first use a multiple linear regression model to predict the daily price change in SPY. I will use multiple indices from the global markets as predictors. These indices include aud ordinaries from Australia, Nikkei from Japan, HSI from HK, DAX from Germany, CAC40 from France, S&P 500, Dji, and Nasdaq from US market. 

Then, I will use the predicted daily price change in SPY as a signal to propose a signal-based trading strategy for SPY. This strategy is compared with a passive buy and hold trading strategy, and is also evaluated in terms of consistency.

The data will be splitted into train and test sets to evaluate the performance of the mulitple linear regression model, as well as the propsed signal-based strategy.

This project is adapted from the Coursera course: Python and Statistics for Financial Analysis.

