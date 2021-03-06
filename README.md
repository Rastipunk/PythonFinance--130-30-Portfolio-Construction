# PythonFinance--130-30-Portfolio-Construction

130-30 Portfolios are long-short portfolios that have notionally ensured market protection and investment exposure at the same time. Construction of optimal 130-30 portfolios calls for an integrated combination of long positions and short positions and is therefore a  one-portfolio strategy. Metaheuristic strategies are ideal for such integrated optimization of non-linear constrained portfolios.  

In this work, the construction of optimal 130-30 portfolios is undertaken using a metaheuristic strategy viz., Differential Evolution with Hall of Fame. 130-30 portfolios that report maximal Sharpe Ratio and whose volatility moves with that of the market subject to the budget constraints of 130% on long positions and 30% on short positions, are constructed.  The model is demonstrated over S&P BSE 200 Index ( April 2009-July 2020, Bombay Stock Exchange, INDIA) portfolios.

The Jupyter Notebook "MainContent.ipynb" can be downloaded and executed over the input file "S&PBSE200_kPortfolio.csv" which describes parameters of the k-portfolio for k = 20. Another input file "S&PBSE200_K30Portfolio.csv" which describes parameters of a k-portfolio for k = 30 has also been made available  and the Python code can be executed over this input file after making appropriate changes in the Main Python Program.
