# Module 5, Video 1: Money Management and Risk Management — The Key to Survival

Welcome to module number five. In this module we will talk about a very important subject: money management and risk management. I entitled this module "The Key to Survival," and it really is the key to survival — throughout this module you will understand why.

We'll go through several concepts, and some of them might involve a bit of math, stats, and probabilities. Don't be scared — I'll give you as much as you really need, and if you want to dig in further, you're welcome to. I understand not everyone is a "math brain" and not everyone likes all this stats, but it's an important part of your education — trying to understand how we work, and what the methodology and trading system are based upon.

## The Tom Basso Experience

Let's turn to Mr. Tom Basso. Basso was a very active, quite big-sized commodity trading advisor. He ran a hedge fund that, at one stage, had more than $600-700 million under management — which back in the mid-90s was definitely a big-sized hedge fund. Nowadays that might seem small compared to the biggest funds managing hundreds of billions, but Basso was running one of the big hedge funds of his era and was very famous in the market.

I had the chance to meet him — he was one of the clients we dealt with at the bank, early in my career on Wall Street. Very nice guy, very down to earth. Now he spends his time managing his own money, investing in funds he trusts, still doing what he always loved — but from home, spending more time golfing and enjoying life. His motto: "enjoy the ride," no matter what happens.

This first section is entitled "The Tommaso Experience." The reason: in 1991, during a seminar, Basso explained that the most important part of his system was the exits and the position-sizing algorithms he used. A member of the audience asked, essentially, "From what you're saying, Mr. Basso, it sounds like you could make money consistently with a random entry, as long as you have good exits and size your positions intelligently." He replied, "I suppose so." A few days later, he had his team of programmers testing exactly this concept — a random entry, i.e., a coin-flip entry.

**The rules of the experiment were very simple:**
1. A hypothetical $1 million account, used to simulate diversification among different futures contracts while withstanding margin requirements and drawdown.
2. Markets selected had to have a tendency to trend, but also had to be liquid enough that trades could be entered and exited immediately with low slippage (a very small difference between the price you wanted to execute at and the price you actually got in the backtest). The markets used: gold futures, silver, US bonds, eurodollars, crude oil, soybeans, sugar, the Deutsche Mark (the old German currency vs. the dollar), the British pound vs. the dollar, and live cattle — a very diversified basket across asset classes and markets.
3. The exit, no matter what, was three times the daily Average True Range (ATR) — a concept we covered back in module two — subtracted from the close.
4. A trailing stop was used that could only move closer to the current market price, never further away.
5. Position size was automatically 1% of total account equity, and the system was always in the market — as soon as one trade closed, another opened.

This is a great illustration of how simplicity can work in system development. Whenever you run a random-entry system, you get different results, but this particular system made money on 80% of the runs when trading only one contract per futures market — and made money 100% of the time once a simple 1%-risk money management rule was added. That's quite impressive, because the system's reliability level was only 38%, about average for a trend-following system. In other words: flipping a coin to decide whether to buy or sell, but applying sound risk and money management rules, still made the system profitable.

Looking at the details, yes, the system had drawdowns — not everyone would have stomached them — but it shows that, to a large extent, the entry is not that important in the grand scheme of things. A lot of people spend a huge amount of time trying to find the "perfect entry," when really that time should be spent perfecting your exit and your money/risk management.

**A modern re-run:** The same rules from the Basso experiment were used to run a simulation in MT4 (a trading application some of you might know). A team tested the six major FX pairs plus gold from January 2014 to June 2016 (the New Zealand dollar was only run to the end of February 2016 due to some data errors), effectively testing random entries across both trending and range-bound environments. They ran 20 iterations and found no significant deviation from the core concept — Tom Basso's coin-flip system rules held up just as well as they did back in the 1980s/90s. This shows the power and importance of money management and risk management. Of course, this simple random-entry system would sometimes bring deep drawdowns that probably not every investor could handle, but the point is that even with coin-flip entries, the end result was positive. Now imagine we have a half-decent entry methodology with an actual edge and higher probabilities in our favor.

## Is It Possible to Be Wrong a Lot and Still Be Profitable?

Yes — and I want to show you what's possible when you put the power of statistics on your side. I'll explain the concept that helped me become a consistently profitable trader, trading with the right peace of mind.

As we discussed in module three, whether a particular trade is a winner or a loser is irrelevant in the grand scheme of things. What matters is the positive edge of our strategy — our system's **expectancy** over time. With the probabilities attached to it, we can tell with fair confidence whether a strategy is likely to be profitable in the long run.

Funny enough, a strategy can produce big winners occasionally and still result in a net loss over the long run. On the flip side, a system can lose more times than it wins — a win ratio under 50% — and still be profitable overall.

Trading metrics matter because they help us understand whether a system can approach the "risk of ruin" — the risk of running our trading account down to an unacceptable level of loss, if not a total blowout. What makes this business so fascinating is that while we don't know what will happen tomorrow or today, we can have a pretty decent idea of what will happen over the long run. Just like in the insurance business: an insurer has no clue about the odds of one specific 70-year-old being alive next year, but can have a very good estimate by taking a sample of 100,000 seventy-year-olds (the minimum sample size statistics allows). In a way, we are like trading actuaries. But the important thing is to constantly remind ourselves that we know that we don't know, and that we can all be wrong — so as long as we don't bet our lifestyle on it, we should be fine. The reality is: while we can't quantify how much we can make, we can quantify how much we can risk with a fair amount of certainty.

## Win Ratio, Payoff Ratio, and Expectancy

There are two key metrics that matter enormously in any trading system:

1. **Win ratio** — how many trades you win versus how many you lose. If you make 100 trades, win 60 and lose 40, your win ratio is 60%.
2. **Payoff ratio** — how many dollars you make for every dollar you lose. If on average you make $2,000 and lose $1,000, your payoff ratio is 2 to 1.

These metrics come from a series of real trades, or from testing your strategy on paper — but it takes time to gather them. That brings us to what we call the **expectancy** of a system.

**Example 1:** Suppose our system has a 60% win ratio (winning six times out of ten), an average gain per trade of $200, and an average loss of $100. Using the formula:

$$\text{Expectancy} = (\text{Win\%} \times \text{Avg Win}) - (\text{Loss\%} \times \text{Avg Loss})$$

$$0.6 \times \$200 - 0.4 \times \$100 = \$80$$

So we'd expect to make $80 on average per trade, over many trials.

**Example 2:** Now suppose our strategy has only a 40% win ratio (winning four times out of ten), an average gain of $500, and an average loss of $100 — a payoff ratio of 5 to 1 (we make five times as much as we lose). Using the same formula:

$$0.4 \times \$500 - 0.6 \times \$100 = \$140$$

So we'd expect to make $140 on average per trade, over many trades.

**The key lesson:** most people look for strategies with a very high probability of winning. Yet the first system had a 60% chance of winning but only $80 expectancy, while the second system had only a 40% chance of winning (wrong 60% of the time!) but its expectancy jumped to $140 — a whopping 75% increase. System two is almost twice as good as system one, assuming the same opportunity factor.

The key factor in a system is **not** the probability of winning — it's the **expectancy per dollar risked**. A word of caution: you can only realize your expectancy over the long term if you size your positions wisely relative to your equity. **Position sizing** — how much to risk per position — is a critical part of your overall system.

## Losing Streaks Are Normal — Prepare for Them

Going back to our examples, having a 60% (or 40%) win ratio certainly doesn't mean we win every time. In fact, over something like 1,000 trials, at some point we could easily hit 7 to 10 losses in a row. However, over that same 1,000 trades, we should still make on average $80 per trade (using the first system's numbers).

So although we can form a good estimate of our overall win ratio, it's impossible to pin down the exact distribution of trades and how they'll play out. You can't just tell yourself, "I have a 60% win ratio, so the max I can get is four consecutive losses in a row" — that's not how it works. The truth is we can get much longer strings of consecutive losses. The best thing we can do to prepare is think about the worst-case scenario — and even that is relative.

Keep in mind that from time to time we might go through a long string of consecutive losing trades that keeps us in a prolonged drawdown. Using a formula, we can approximate that over a relatively high number of trades, we should expect to hit at least one string of *n* consecutive losers. In our example, using a 99.9% confidence level and a 60% win rate, n comes out to about 7.5 — meaning that for every 1,000 trades, you could expect to eat at least one string of 7 or 8 losers in a row. And there's no way to know in advance when that string will happen.

## Position Sizing: Why It's the Real Key

To summarize: there's a triple dimension combining win ratio, profit factor (payoff ratio), and position sizing needed to reach the right expectancy for your system.

**A cautionary example:** Suppose you have a system with a 60% win ratio and a profit factor of 1:3 (you win 60% of the time, lose 40% of the time, and on average make three times as much as you lose). Now suppose you have a $1,000 account, and you decide — foolishly — to risk 50% of your stake on every single trade.

- You start with a $500 bet, and lose. Balance: $500.
- Next bet: 50% of what's left = $250. You lose again. Balance: $250.
- Next bet: 50% again = $125. You lose again. Balance: $125.

Three losses in a row — quite possible, as we just covered, even in a system that wins 60% of the time. Now you must make $875 just to break even — a 700% increase from your current balance. You're not likely to make that at all.

So despite a solid 60% win ratio, improper position sizing (risking 50% of the account per trade) destroyed your ability to realize your long-term expectancy. This illustrates that a system's win ratio is inversely proportional to the potential length of losing streaks: the higher the win ratio, the shorter the expected consecutive losing streaks tend to be, and vice versa. Therefore, you need a position-sizing algorithm that lets you withstand potentially substantial strings of consecutive losing trades, while still being able to exploit the big winning trades that will eventually come along.

**Remember:** your position size on any given trade must be low enough that you can realize the long-term expectancy of your system over many, many trades. This is the single most important thing to keep in mind from this entire discussion.

## Undercapitalization and Overleveraging

There are two other things you need to be aware of — two sides of the same coin:

- **Undercapitalization**: starting with too small an account, so that even a normal string of consecutive losing trades leaves you without enough capital to fund the next winning trades when they come.
- **Overleveraging**: betting far too much relative to your account size — you lose way too much on losing trades and, again, are left without enough in your account to fund the winning trades to come.

To recap: you could even have a trading system with a 90% win ratio — winning 90% of the time, losing only 10% of the time — and still lose money over time, simply because the expectancy is negative. How can expectancy be negative with such a high win ratio? Usually because of average losses that are far larger than average gains — a horrible, or even negative, payoff ratio.

## The Psychological Trap of "Being Right"

There is a strong psychological bias toward wanting to be right about our investment decisions. In most people, this bias greatly overrides the desire to make an overall profit, and it can inhibit us from reaching the true profit potential of our system. This isn't my line — it's from Van Tharp, very well known for his work in investments and trading systems — and it's exactly right. I call this true self-sabotage.

Remember: the idea is not to be right or correct about what the market is going to do. Our aim is to do the right thing, leave our ego aside, and keep repeating the process diligently. Our aim is to be profitable — not to be right or wrong about market direction — because nobody cares whether we're right or wrong. Nobody pays you for that, unless you're an analyst who's paid specifically for making calls.
