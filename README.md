# Factor-Investing-MSFE
MSFE Factor Investing Capstone
Lehigh University

Contributors: Bryan Yekelchik, Jordan Weintraub, Randy Parker

Three step approach:
  1) Factor selection/optmization
  2) ML forecasting using best factors for equities incorporating a neural netowork
  3) Portfolio weight optimization using forecasted returns

We used three different securities in this process. They are Apple, Coke, and Google, and the monthly returns for the first ten months in 2019 are estimated for each security. The portfolio weights are then optimized to maximize the sharpe ratio.

This repo consists of three different folders that contain our data. This includes "NN", "Regression", and "optimization".
- The "Regression" folder contains the code used to duplicate Fama French and run a regression to project the returns. The output is the estimated returns for a selected security for designated time periods. It also includes an EDA to explore the stock price data.
- The "NN" folder contains notes and code about working with Neural Networks as that was used to predict the returns as well. The output is the estimated returns and it is saved to a csv file.
- The "optimization" folder contains a brief overview of the two different portfolio construction models used as well as the actual code. It determines the optimal weights based to maximize the sharpe ratio based on the returns that are provided.
