boxplay-trading-system
======================

My submission for 2007 Automated Trading Olympiad held by Interactive Brokers.

Written in Excel VBA

How the system works:

1. It takes the highest and lowest price points for the GBP currency pair (GBP/USD, GBP/JPY).
2. Sets limit orders at those points.
3. Only factors in the London currency exchange opening and closing time. (Rationale: highest volatility with highest potential for breakout prices)
4. Profit???

You will need to consult the IB Excel API documentation which at the time of writing, was missing documentation. I relied on Yahoo discussion groups and trial and error.

