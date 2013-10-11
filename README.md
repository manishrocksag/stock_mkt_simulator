stock_mkt_simulator
===================

This is the project that I built during the Coursera Computational Investment-1 course.

Tools/Libraries Used:

QSToolKit (QSTK) is a Python-based open source software framework designed to support portfolio construction and management.It is a software infrastructure to support a workflow of modeling, testing and trading.

Libraries of Python:Pandas,Numpy,Matplotlib,Scipy

Python 2.7


This a series of modules built in order to built a efficient market simulator.

Module 1:

Python function that can simulate and assess the performance of a  stock portfolio.

Inputs to the function include:
Start date
End date
Symbols for for equities (e.g., GOOG, AAPL, GLD, XOM)
Allocations to the equities at the beginning of the simulation (e.g., 0.2, 0.3, 0.4, 0.1)

The function should return:
Standard deviation of daily returns of the total portfolio
Average daily return of the total portfolio
Sharpe ratio (Always assume you have 252 trading days in an year. And risk free rate = 0) of the total portfolio
Cumulative return of the total portfolio

Some assumptions:
Allocate some amount of value to each equity on the first day. We then "hold" those investments for the entire year.
Use adjusted close data. In QSTK, this is 'close'

We than use this function to create a portfolio optimizer!
"Best" portfolio means: Highest Sharpe Ratio.

Module 2:

