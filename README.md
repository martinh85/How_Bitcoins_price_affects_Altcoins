# How Bitcoin's price affects Altcoins

### Holy grail of crypto trading

Trading cryptocurrencies most profitably means switching effectively between holding altcoins, Bitcoin and FIAT(regular currency). This analysis aims to better understand altcoins behaviour based on Bitcoin's price action, since the correlation with Bitcoin is most relevant fact to lean on.

Historically, altcoin markets tend to rise together. In crypto community, such period is often called "altseason". During that time, most of the altcoins experience parabolic growth followed by equally rapid decline. After altseason prices eventually tend to visit previous bottoms again, accumulation zone.

#### Analysis in steps:
- observe time periods based on market cycles, 
- plot Bitcoin daily chart with historical events,
- **mark days when altcoin markets experienced highest volatility.**

#### As the indicator for altcoins volatility we:
- calculate **daily returns** (percent price change compared to previous day's close) calculated for selected coins,
- identify **median value**, rather than mean value. This approach will exclude price action of outlier coins with abnormal volatility. More sofisticated methods could be definitely used, but for purpose of selecting high volatily days, median meets our expectations.

Altcoins tend to pump during whole altseason unexpectedly.  So the days when whole markets dumps due to correlation with Bitcoin, should be more frequent.

#### Data preparation
Bitcoin's data is loaded from Bitstamp exchange on daily timeframe. Altcoins data is loaded from Bittrex exchange due to availabity of historical data. We load 25+ coins equally spread by size of current market cap with minimum 2 years history, resample data to 1D timeframe and calculate daily returns.

Analysis will cover interval from March 2017 to February 2019.

Our altcoins sample group: ARDR, DASH, DGB, DOGE, ETC, ETH, FCT, GAME, GRS, KMD, LSK, LTC, MONA, NAV, PIVX, STEEM, STRAT, UBQ, VIA, WAVES, XCP, XEM, XLM, XMR, XRP, XVG, ZCL, ZEC
