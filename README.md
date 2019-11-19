# day-trade-bot
This project reviews development of an application that will automatically day trade. Orders will be triggered, based on a stock's performance.

## Step 1: Obtain stock data
I choose to use a combination of Yahoo's and Kibot's finance API to obtain stock history.

## Step 2: Analyze/calculate stock's performance
At market close, I analyze all Nasdaq and NYSE stocks and determine which to buy based on the following criteria:

1) Stocks with high average volume.

2) Stocks that pay dividends.

3) Stocks with a low positive P/E ratio.

4) Stocks that have 50 day moving average above the 200 day moving average.

Stocks meeting the above requirements are posted to a daily report.

## Step 3: Choose brokerage
Take your pick of a brokerage with an API.

## Step 4: Set buy/sell trigger
I check for the following intraday movement against the above daily report's stocks:

1) Price/volume differentials.

2) Moving average changes.

If the above criteria is meet, buys are triggered.

Please direct any questions or comments to jason@solvingnet.com
Disclaimer: This is not investment advice. Use at your own risk.
<br><br>
<center><a href="https://stocktwits.com/JasonsBuy"><img src="https://images.duckduckgo.com/iu/?u=https%3A%2F%2Flh5.ggpht.com%2Fph6pKSLuobuxO1z6O7gh-S91llO1PKDWFEQau6NUtJj5J-wGvGvkOsVXGbhCCOzy3os%3Dw300&f=1" height="100" width="100"/></a>
<a href="https://twitter.com/JasonsBuy"><img src="https://images.duckduckgo.com/iu/?u=https%3A%2F%2Ftse2.mm.bing.net%2Fth%3Fid%3DOIP.Mc271a56ac51adb93a36fda9725e6f0f9H0%26pid%3D15.1&f=1" height="100" width="100"/></a></center>
