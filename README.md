# QWIM Project: Stress testing and reverse stress testing in QWIM
## Name of the team: Numerisk
## Project description:
In this project, we followed the paper “Portfolio Selection Under Systemic Risk” and realized it with empirical data and simulated data from GARCH-Copula. We observed the portfolio weights from the CoSR strategy to be more diversified. 

In addition, the rolling window has a significant influence on the result. The strategy would have performed better if more financial crises are included in the window. It also seems to perform better when the threshold value C = -6.7%. From the empirical results, we can see that the strategy is learning from the market crash in 2008 and performing better subsequently. However, it fails to perform well during Covid-19 since any past crises is beyond the rolling window of 1500 days. Hence the simulation is significant in this strategy, as it offers more scenarios instead of only historical data.

For further improvement, we plan to discuss with the authors about possible changes, such as the ideas mentioned by Professor Acharya and Brian Reis.

## code files:
Systemic Risk: main codes without dashboard
Systemic Risk: codes for Dashboard
Garch_Copula: codes for Garch-Copula (it took one hour to run the model so we separated the codes.
