# FinancialInvestmentAndManagement
Calculate better spending rates as investors and Arbitrage possibilities with USD,EURO, GBP


Usage:
``To Find better spending rates:
There is a team of portfolio managers who maintain portfolios for clients. These portfolios are meant to generate regular income for clients, and clients usually dictate spending targets for the upcoming few years that they'd like to be able to withdraw from their portfolio.
Spending targets are typically based on future expenses the client plans to have. By making minor tweaks to their spending targets, the client can increase their income. As a programmer, you must help the portfolio management team run simulations based on client inputs that determine the top 3 spending rate combinations that will generate the most income for the client.

**Inputs required:**
The first line contains four space-separated values:

An integer, p , denoting the portfolio value invested.
A floating-point number denoting the interest rate as a percentage; divide this number by 100 to obtain r.
An integer, t , denoting the time.
An integer denoting the thresold in which spending rates can be adjusted.
The second line contains t space-separated integers denoting the client's spending rate (St) for each time t.

**Sample:**
5000 5.5 3 1
29 42 37

**Output:**
4083.843
4091.584 - 28 42 38
4091.494 - 28 43 37
4084.348 - 29 41 38

``Currency Arbitrage
An arbitrage is the simultaneous purchase and sale of an asset in order to profit from a difference in the price. This type of trade exploits price differences between similar or identical financial instruments, either on different markets or in different forms.

You are a currency trader looking for arbitrage opportunities in the currency market using these three quotes:

The cost of USD per EUR (USD/EUR) for converting USD -> EUR.
The cost of EUR per GBP (EUR/GBP) for converting EUR -> GBP.
The cost of GBP per USD (GBP/USD) for converting GBP -> USD.
You must use your USD to buy EUR, then use your EUR to buy GBP, and finally use your GBP to buy USD, resulting in some sort of profit or loss. Reverse trading is not allowed, so you are limited to 3 exchanges in the direction shown above.

Given 10000 USD for each trade, calculate the arbitrage profit truncated to whole dollars (USD); otherwise, print 0 if there is no arbitrage opportunity.