# project1
Penn Bootcamp Group project 1

ETF Trading

An ETF is an Exchange-Traded Fund which is traded on stock exchanges. An ETF is a collection of stocks which if managed right, can lead to very beneficial outcomes.

*Goal:* To find ETF would give us the best return

To answer this, we will be looking at three questions:

* What is the investment criteria we are looking at?
  * We want to pick and ETF that is going to benefit us most, we can choose which ETFs to invest in by finding which has the lowest risk and the highest reward.
* How did we pick the variable to analyze for the first question?
  * There are multiple different variables that we could analyze that could help us decide which ETF is the most promising for maximum profit, so how do you decide which one will best predict a good return?
* Is short-term trading better than long-term (ex. strategy returns and buy and holding)?

*Data Collection & Cleaning*

We collected all of our data from the ETF database which is publicly available for download. The ETFs we chose to analyze were picked at random. We decided to look at the ETFs SPY, QQQ, GLD, TIP, and VWO.

First we imported each of the ETF’s data from CSV files. Then all DataFrames for each ETF was merged by date which allows us to compare and contrast.

*Highest Return*

SPY had the highest cumulative return out of all of the ETFs, with a value of 301.254%. While it did not have the highest annual return value is managed to surpass the other ETFs over the entire time period. We are also choosing SPY despite it having a comparatively large max drawdown value because of the high cumulative return.
