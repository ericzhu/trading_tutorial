# Module 5, Video 3: The Percent Risk and Percent Volatility Position Sizing Models

When you enter a trade, it is essential — primordial — to know the point at which you will get out of the position, in order to preserve your capital. This is what you define as your risk, and it should represent your worst-case scenario or worst-case loss (except for slippage, a runaway market moving against you, or a gap that opens against you — but on average, over many, many trades, you'll get close to that defined risk, and sometimes even under it, depending on your exit policy).

A lot of people don't think this way. They think "I want to buy, I want to see how much I'm going to make" — always thinking in terms of profits, what they'll do with the money, what their next holiday destination will be. That's how a lot of people think. But professional traders and investors think the other way around: before putting a trade on, they think about how much money they stand to lose if it goes against them. That's how professionals handle their trading.

One of the most common position sizing systems involves controlling size as a function of the risk you're willing to take. Let's look at an example of how the **percentage risk sizing model** works.

## Example 1: The Percentage Risk Model (JPM)

Say you want to purchase JPM (JP Morgan) stock, and you have $50,000 in your account. JPM is trading around $140-141 per share. You decide you'd exit this position if the stock drops below $137 — a drop of $4 per share. That's your risk, defined from the start, even before buying the stock: you're willing to buy at $141, but no matter what, you will stop out at a loss if it drops $4 per share against you.

Your position sizing strategy tells you to limit your risk to 2.5% of your equity, or $1,250 — the maximum you're willing to lose on this trade. So you have two numbers: the total risk you're willing to take ($1,250), and your stop-loss distance ($4 per share). Dividing $1,250 by $4 gives you the number of shares you can buy: roughly 312-313 shares.

Buying 312 shares at $141 would cost just short of $44,000 of your capital — almost 80% of the value of your account. Obviously, you're limited by the marginable value of your account, but it's not impossible, and it really depends on your trading style. If you're a day trader who doesn't hold overnight positions, this isn't as much of an issue, since you don't intend to tie up capital for long (though other issues can pop up, like trading halts — covered later). If you're more of a swing trader, your capital would be tied up for many days, limiting your ability to take advantage of other opportunities, unless you inject more capital or start using margin. Another alternative for medium-term swing trading is using options for capital optimization — but we'll cover options specifically in module nine.

So now you have a better understanding of what a 2.5% risk really means. It's important to differentiate between the capital you're spending to buy the stock (in this case, $44,000 held in your account to hold the position) and the amount you're really willing to put at risk — the $1,250 stop-loss amount.

**What if you use a tighter stop?** Say a $1 stop instead of $4 — meaning you'd exit if the stock trades below $140. Using the same $1,250 total risk with a $1 stop, you could purchase about 1,250 shares under the same sizing model. The problem: 1,250 shares would cost you almost $176,000 — three times leverage on your account.

These days, retail brokers, depending on account size, typically provide 1:4 or 1:6 leverage for intraday trading (no problem there), and some brokers provide 1:2 or 1:4 for overnight holding — though this varies broker to broker and depends on account size; there are many variables, and these are just rough market averages. (This is specifically about regular stock trading brokers — some brokers also offer CFDs, stock trading contracts for difference, mostly used here in Europe; I don't believe CFD brokers are permitted in the US. CFD stock trading implies even more leverage, but that's a discussion for another day.)

In summary, I personally strongly advise against leverage above two times the account, especially when swing trading — I'll explain my position on that later, when we cover the specific risks involved in stock trading.

## Example 2: The Percent Volatility Model

Now let's look at the other sizing model — a derivative of the one we just saw — called the **percent volatility model**.

Volatility refers to the amount of daily price movement of an underlying instrument over a certain period — a direct measurement of the price change you're likely to be exposed to, for or against you, on any given position on any given day. If you equalize the volatility of each position you take, by making it a fixed percentage of your equity, you're essentially equalizing the risk and possible market fluctuation across every instrument in your portfolio.

Volatility-based position sizing has excellent features for controlling exposure, but the reality is very few traders use it — even though it's one of the most sophisticated models out there that I know of.

Not all investments are alike, and every instrument's respective level of volatility can differ from another — so we need to factor volatility into our position sizing to reflect these differences. This means, historically, less volatile instruments will command a larger position size than more volatile ones. For example, bonds are a lot less volatile than stocks — so you should be able to hold a larger size of a bond ETF in your portfolio than a stock ETF. The same applies to commodities: every commodity or commodity basket has its own level of volatility that should be adjusted relative to equities.

The volatility of every single instrument or stock is different — trading Facebook or JP Morgan is not the same as trading a biotech firm or a penny stock. These are very different animals with very different volatilities. Therefore, the position size for every single trade, on every different instrument, has to be relevant to the implicit volatility that instrument is showing you.

### Worked Example Using ATR

Let's assume a $50,000 account, using 1% as risk per trade — meaning on any single trade, we don't want to lose more than 1% of our equity (of course, things can happen and our maximum risk per trade can be blown out for reasons covered later, but the idea is that we try our best to limit our risk to that 1%).

Our dollar amount at risk = $50,000 × 1% = **$500**. That's what we're willing to lose on this trade.

Recall the concept of ATR (Average True Range) from module two — a measure of daily volatility. Traders usually use a 14-day ATR average, though you can use whichever period you prefer; it's not a huge issue. Roughly speaking, it tells us the range a stock price (or any financial instrument) can move in a day, on average. By using the ATR to set our stop-loss level, we implicitly incorporate the relevant volatility level for the stock under review.

In our example, the ATR for this particular stock is **$0.80** — meaning, on average, we'd expect a daily price range of about $0.80 for that stock.

When traders use ATR to set a stop loss, they typically use around **two times the ATR** from the entry level to set the stop — giving enough space and flexibility for the market to move around without getting stopped out from setting the stop too tight relative to the daily volatility range. If a stock moves $1 on average and you use a 50-cent stop, you run the risk of getting stopped out quite easily, since that's only 50% of the daily range of that stock (depending also on where in the range you enter).

To calculate the correct number of shares to buy or short, take the dollar risk amount and divide it by the dollar value of your stop distance. Here, the stop is set at two times the ATR per share: 2 × $0.80 = **$1.60 per share**.

$500 ÷ $1.60 ≈ **313 shares** to buy or short.

In this example, the short entry is set at $28.50. Since it's a short position, the stop is placed $1.60 above the entry — so the stop level would be at **$30.10**.

### Comparing the Two Models

In this example we used the percent volatility position sizing model. The simpler percent risk model we saw earlier achieves the exact same thing, except it doesn't use the ATR in calculating the stop level — instead, the stop level is based on other considerations, such as technical support or resistance levels on the chart. For instance, on a given chart, we might simply decide to go long at $88.83 and place our stop loss below the recent daily low established on the chart — below the moving averages, below the recent low we've established on the daily chart.
