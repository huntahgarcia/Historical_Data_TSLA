# Historical_Data_TSLA

Below is an overview of my project to retrieve & show stock data in Python

Goal: Obtain & show Open, Close, High, Low, Volume, Vol Weighted Avg Price, Time, & # of Transactions in Python

Status: Complete

Example: Tesla Stock

Scope: Aggregate data (categories listed below) based on start & end dates

    #v = volume, vw = volume weighted average price, o = open, c = close, h = high,  l = low
    #t = Msec timestamp for start of aggregate window, n= number of transactions in aggregate window 
    {'v': 104686035.0, 'vw': 390.2519, 'o': 382.5833, 'c': 399.9267, 'h': 400.3567, 'l': 378.68, 't': 1641186000000, 'n': 1162844}
    {'v': 99798258.0, 'vw': 387.3708, 'o': 396.5167, 'c': 383.1967, 'h': 402.6667, 'l': 374.35, 't': 1641272400000, 'n': 1051467}

Additional:  Visualize data in a candlestick chart + convert time (t: UTC/GMT from Polygon) 
