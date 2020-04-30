# Portfolio Construction

  Employed Toolkit: portfoliovisualizer.com, tradingviews.com

**I. Market Screener**

Navigate to *Screener* Section on tradingviews webiste. Use key ratios (such as PE, EBITA, beta), techinical indicators and ratings to filter potential asset candidates. 

As an example, our screened result gives the following five tickers: APD, AQN, CBSH, SBU, INTC, KNX.

**II. Portfolio Optimization**

![PortfolioVisualizer](https://github.com/etccapital/Market_Insight/blob/master/assets/Optimzation%20Tool.PNG)

Use optimization tool available on portfolio visualizer website: set specific metrics such as sharpe. 
Note that in special cases, some chosen assets for optimization may not be utilized in the finalized portfolio. That is, the weight of such asset can be zero. 

**III. Backtest**

To evaluate the portfolio constructed, backtesting needs to be carried out. We employed the backtesting tool available on the portfoliovisualizer, setup according to the following metrics. SPY was chosen as benchmark.

![BacktestSetup](https://github.com/etccapital/Market_Insight/blob/master/assets/Backtest%20Setup.PNG)

After running the backtest, the following information is provided:

![AnalyticResults](https://github.com/etccapital/Market_Insight/blob/master/assets/Analytic.PNG)

Alternatively, Factor analysis can be used. 

"Main parameters could be seen on the visualizer.
Setting Benchmark Ticker before running simulations. Analyse the output for the main picture. Then use Factor Analysis to do the second-step verification. Mainly focus on whether the alpha still remains after including more factors."




**Programs/Websites/Apps recommended for individual trades**

Interactive Brokers https://www.interactivebrokers.ca/en/home.php

Questrade https://www.questrade.com/home

Wealthsimple https://www.wealthsimple.com/en-ca/

IC markets https://www.icmarkets.com/sc/en/

>对于A股的Portlio回测，可以使用以下教程，利用excel进行实操。量化系统可以考虑使用Tushare Library进行回测。https://www.youtube.com/watch?v=brv792lWQfg&t=520s
