# BinanceAlgo
Algorithmic trading cryptocurrency template

This  is a template Based on BinancePython Library with the help of WebSockets.
For Algorithmic Tradding, I use EMA's for 9 and 21 Past closes (in 5 minutes klines). 
When the Longer(21) period crosses above the short(9) period it is set to sell/short.
When the opposite happens the Algorithm places a long/buy market order.

The Backtrader library can also be imported and initialized to test strategies on historical data before Running  the bot real time.
