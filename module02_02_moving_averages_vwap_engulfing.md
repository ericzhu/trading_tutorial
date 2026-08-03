# Module 2, Video 2: Moving Averages, VWAP, and the Engulfing Pattern

Welcome to video two of Module 2. We're still dealing with technical analysis, and in this chapter we'll look at live, real examples. We'll talk about moving averages of all sorts — exponential moving averages compared to simple moving averages — and we'll also look at VWAP and weighted moving averages, discussing the benefits and disadvantages of each. Moving averages are very much part of the philosophy and methodology of Trading Academy. We'll also take a quick look at one of my favorite patterns, the engulfing pattern, with many live examples.

## Simple vs. Exponential Moving Averages

Pulling up the charting software (TC2000) on the SPY (the ETF representing the S&P 500 index), let's start talking about moving averages.

A moving average takes the average closing price of a stock over a certain number of days. For example, over three days, we'd take the daily close over those three days and divide by three — that gives the simple moving average (SMA).

The exponential moving average (EMA) does the same thing, but puts more weight on the most recent price data. In our three-day example, more weight would go to the last day or two in the calculation. This means the EMA reacts faster to current price developments and hugs the price chart more closely. I personally like it better, though some traders are more old-school and prefer the simple moving average — at the end of the day, both give a similar visual read on the trend.

## The Moving Averages on the SPY Weekly Chart

Looking at the weekly chart of the SPY, these are the moving averages I use most: the 10, the 20, the 50, and the 200. I usually keep the same color code so I can read the chart at a glance as soon as I look at it: light blue for the 10, dark blue for the 20, red for the 50, and purple for the 200.

Keep in mind the moving average applies to whatever unit of time you're viewing. On this weekly chart, the moving averages take weekly bars into account, so the 200 moving average uses 200 weeks of data, and the same logic applies to the 50 moving average, and so on. These same periods — 10, 20, 50, and 200 — are applied across all timeframes.

## Daily Chart, Trend Confirmation, and Support/Resistance

Switching to the daily chart of the SPY, the moving averages give a real visual idea and confirmation of the trend. The 200 moving average is usually considered a very important one on the daily chart.

Going back to the Dow theory we studied earlier, you can clearly see the higher highs and higher lows that make up the trend, and also how price sticks to the moving averages. This is part of why we use moving averages so much — they act not only as a visual aid for trend determination, but also as resistance and support, as we'll see in other examples.

## The Nasdaq Example (QQQ)

Pulling up the Nasdaq index, we see very much the same picture. The market has been in a long, long bull trend since 2009 — going back to the weekly chart to 2009, it's an amazing bull market.

Going back to the daily chart of the Nasdaq — the QQQ is the ETF that trades as the underlying instrument representing the Nasdaq 100 index — we're again visually compelled to immediately think the market is going up. The price data shows the higher highs and higher lows we establish each time, according to Dow theory, and the moving averages help us understand that visually right away.

The important thing is to understand the trend, and whether we're on the right side of it. If the market is above the moving average most of the time, and definitely above the 200 moving average, that means we're on the right side of the trend — remember, the trend is our friend. The moving average really is the helper that tells us whether we're on the right side of the trend or not, like the market wizard Marty Schwartz used to say. It was part of the arsenal of tools — the checks, the filters — that he used in his trading. He said if he wasn't on the right side of the moving average, he simply wouldn't trade it: if the market was below the moving average, that indicated the market had to be traded on the downside; if it was trading above the moving average, that indicated the long side was the right side of the trade.

You can see in several places on this chart where the market got stopped at the 200-day moving average, really acting as a strong support to the move. Many times you'll also see the 50-day moving average being used as a big support level.

## Introducing VWAP

Let me introduce another concept related to moving averages. As you understand, I personally prefer the exponential moving average because I think it's closer to recent market action compared to the simple moving average — but if you're more comfortable with simple, that's fine too.

The other concept I want to show you is the VWAP — Volume Weighted Average Price. A lot of traders use it, especially institutional traders: hedge funds, pension funds, and all sorts of institutional players use VWAP to give orders to their brokers. In order to not disrupt the market too much, they agree on a price that has to be transacted around the VWAP. So if I'm a large institutional buyer of stock XYZ and I give the order to my broker to buy 50,000 or 100,000 shares, the broker will work on execution depending on the liquidity provided to the market, and will most of the time target execution around the VWAP.

This average works like the exponential moving average, but it takes volume into account as well. EMAs are very useful to give us a visual idea of a trend and to act as resistance/support levels, and they work very well for foreign exchange. But when trading stocks, we have an additional piece of information available to us for free: the volume of the stock. Forex is an OTC market, so unless you're working on an ECN, you don't get a precise idea of the volume flowing through it — I wouldn't pay too much attention to it there. But for stocks, we use EMAs as well as the VWAP and the volume-weighted moving average — on TC2000, this is called the "moving VWAP."

## How VWAP Is Calculated

The VWAP calculation takes volume into account — you'll find the calculation method on the PDF related to Module 2. For a given unit of time — say, a five-minute bar chart — every five-minute candlestick has a high, low, and close. Most software calculates the average of the high, low, and close, then multiplies that by the volume transacted during that particular five-minute bar. It doesn't matter whether you use five-minute, ten-minute, or fifteen-minute bars — the logic adapts to whatever unit of time you're using.

Sticking with the five-minute example: it takes the high-low-close average, multiplies it by the volume during that bar, and accumulates that number, dividing by the number of shares at every instant. What we get is the average price transacted in the market, weighted by the volume where it was transacted.

To me this is important information because, compared to the EMA, the VWAP (or moving VWAP) gives me an idea of what buyers and sellers have actually been transacting. The EMA gives a good idea of the average price transacted over the unit of time we're looking at, but the VWAP gives additional information about where the volume has been going — meaning where the most buyers have been buying and where the most sellers have been selling. That's relevant information to me when trading stocks, or any financial instrument with official volume data, like futures contracts.

## Moving VWAP on the Chart

On the chart, the moving VWAP is calculated over 50 days here — the 50-day exponential moving average is the red line, as mentioned before, and the blue line represents the 50-day moving average as well, but taking volume into account.

Below the price chart is the volume traded on this ETF (the QQQ, the Nasdaq index) — the bars represent the volume each day. There's also a white line, a simple moving average of volume this time, over 20 days, taking the average of the last 20 days of volume.

On days where volume is above the recent average, you'll see the moving VWAP move correspondingly closer to the 50 average. Why? Because the calculation of the moving VWAP takes into account that we've had days with a lot more volume than average recently, so the average shifts closer to the 50 average.

## Daily VWAP

On some platforms, unlike TC2000's moving VWAP, the VWAP is calculated on a daily basis. Here's what that looks like: the moving VWAP is an average of the last 20 candlesticks, where each candlestick now represents 15 minutes — so we're looking at a 15-minute unit of time. The moving VWAP calculates the last 20 bars (the last 20 times 15 minutes) and takes volume into account, putting more weight on the bars with higher volume and less weight on the bars with lower volume compared to the recent average.

The VWAP itself, shown separately here, is calculated on a daily basis and resets every day. This gives a better idea of where the volume has actually been going — where price has traded with the most volume, and therefore where the most holders or short sellers of that particular stock have been transacting.

## More Examples: 200-Day Moving Average as Resistance

Looking at XLB, we can see the stock has been in a long-standing bear market, with the moving averages trending down. This is another instance where the 200-day moving average acts as strong resistance, this time on the way up, rather than as support like before — the stock traded back up to the 200-day moving average, then retraced down, continuing the original downtrend.

Same thing on another example: the market bounced back strongly on one day, from $6 all the way to almost $12–$13, then sold off again, with the 200-day EMA acting very strongly as resistance.

Looking at another example, the moving averages — the 10, 20, and 50 — really show strongly that the market is on a downtrend; there's no ambiguity looking at the chart, and looking at the moving averages, everything is visually obvious.

## The Engulfing Pattern

Now let's turn to the Japanese candlestick pattern I mentioned earlier — the engulfing pattern. Let's look at a few examples of this pattern in action. I like to look at this pattern on indices as well as stocks — the pattern works the same way on both, but right now we'll look at a series of ETFs representing specific sectors (we'll touch on sector rotation in a later chapter).

**XES** (Oil & Gas Equipment & Services ETF): here we see a candle that engulfs the previous candle — meaning its high and low completely take over the previous candle, and even the previous three candles. A candlestick formation like that is extremely bearish, and the market corrected quite strongly after that. Keep in mind this sort of pattern is even more pertinent when we're close to key support or resistance levels, especially with a spike in volume. In this case, the volume spike was modest — close to average — but we were at an important resistance level, almost forming a double top.

**XME** (SPDR Metals & Mining ETF): again we see the engulfing pattern, where a big candle takes over the first one and almost the last two previous candles, indicating the market is willing to move down. This bearish engulfing pattern is a very clear signal, or at least a clear warning, that we might have reached the end of the bull trend, and we need to be careful about an upcoming correction.

**FDI** (an ETF representing the MSCI Consumer Discretionary Index): here we get a big candle that happens to land right on the 200-day moving average, which is acting as a very strong support. Then we get a day with quite strong volume compared to the average, which engulfs the previous candle — and even the last two, almost three, candles — signaling a turn in the recent market trend.

**XLI** (SPDR Select Sector Consumer Discretionary ETF): the same type of pattern, occurring very close to the 200-day moving average.

**S&P Internet ETF**: here again we see an important resistance level, where we almost come into an area forming a double top. A big engulfing pattern swallows all the previous — at least three — candles, with increasing volume above the average, and we get a quite big correction in the market afterward.

**XLF weekly chart**: here's a typical engulfing pattern on weekly candles — this candle gobbles up the previous candle, closing down below the low of the prior candle, indicating the market has changed course, at least temporarily, until we find support again around the 50 moving average (keep in mind that's 50 weeks, or about 250 days — nearly a year of trading).

**Pharmaceuticals sector ETF** (weekly chart): one of the last examples of the engulfing pattern — a big engulfing candle gobbles up the last two previous weekly candles, indicating the market is changing trend again, at least temporarily. We need to be very careful here. As noted before, it started turning when we were reaching almost a double top from the previous highs back in 2016.

On the same pharmaceuticals chart, we also get another engulfing pattern — this time on the way up, bullish — happening close to the lows we saw back in 2016–2017.

That covers the engulfing pattern. In the next video, we'll look at other characteristics of the technical analysis tools we're using.
