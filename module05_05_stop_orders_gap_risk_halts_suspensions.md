# Module 5, Video 5: Stop Orders, Gap Risk, Trading Halts, and Suspensions

Now that we're able to calibrate our risk versus our reward to help decide whether a trade is worth taking, we need to know the optimal way of placing a stop order — and we also need to understand the limitations of the protection that stop losses actually provide.

## Types of Stop Orders

**1. ATR / volatility-based stops.** Volatility stops are based on the assumption that volatility represents the noise in the market. Consequently, if you set a stop at some multiple of the ATR (we used the example of two times the ATR previously), you probably have a good stop that's beyond the immediate noise of the market. In my experience, volatility stops are among the best stops you could select.

**2. Technical stops.** These are based on support and resistance levels on the price chart — some traders may be paranoid about such stops because they seem so obvious. To avoid getting caught up with the rest of the crowd, always place them slightly below or above the obvious levels. When you see a chart with a massive resistance/support level, everyone will place their stop just a few cents below or above it. What typically happens is that market makers, or algorithms that know exactly where the stops are clustered, will push price that little bit extra to trigger them before reversing — back when most futures trades happened on the exchange floor, this was the specialty of the "locals." We used to call it "stop fishing" — they fish for the stops, trigger them, and then go the other way, profiting at everyone else's expense. So if you're going to use technical stops, place them a bit further away from the obvious levels (not just 2-3-5 cents like most people do, which exposes you to stop fishing).

## Overnight Gap Risk

Imagine being short or long overnight in some of the top gainers/losers — it can be extremely painful on either side if you're exposed on the wrong side of the trade.

On June 6th, 2017, we had stocks that opened up 75%, up 36%. Imagine being short and holding that position overnight — the stock opens in your face up 75% or 36%, and there's absolutely nothing you can do. On the flip side, looking at pre-market top losers on that same day: stocks opening -18%, -14%, -35%, -24%. If you were carrying a long position overnight in any of these, they'd open against you by -25%, -30%, -40%. That's the sort of thing you need to deal with.

More examples: Vinco Ventures-type stocks opening up 75%, Dynegy opening up 27%, others up 20%, and Helios and Matheson (a famous one, on big volume) up 90%, up 48% — imagine having shorted these and held overnight. On the other side: stocks opening down -35%, -34%, -15%, -20% — imagine carrying a long position overnight into that.

Even major-cap, investor-favorite stocks can drop very sharply overnight:
- **Facebook**, July 26th, 2018: the company's market cap dropped $120 billion, stock down **19%**.
- **Intel**: down **22%**.
- **Microsoft**: down **15%**.
- **Bank of America** (a major US banking stock): down **26%**.
- **Lucent Technologies**: down **20%**.

Even major companies are exposed to overnight risk. How can we protect ourselves from such gap moves? The answer: there's no alternative but to manage our risk very actively, applying our risk and money management as we're supposed to. As much as we can't control what the market is about to do, we can more or less control our risk — and controlling it means being aware of these sudden, unpredictable overnight price moves.

This doesn't only affect penny stocks or small/mid caps — it can affect large caps too. Please don't feel secure or protected just because you own a Dow Jones 30 or S&P 500 stock. Remember Enron (covered back in module one or two) — once the most favorite stock of every US portfolio manager, which ended up going to zero, bankrupt.

## Trading Halts

Another type of gap risk many traders forget about: trading halts. As a full-time trader, it's inevitable you'll get caught in a trading halt from time to time, so it's important to understand why they happen, what causes them, and how to deal with them.

Any stock in the market can get halted at any time. The two most common reasons: **pending news** or a **volatility pause**. When a stock is halted, it cannot be traded by anyone. The risk with halts is that when the stock reopens, it can reopen at any price — there really isn't much you can do, much like overnight gap risk. If you get stuck in a halt, all you can do is wait until trading resumes. A halt for pending news can last hours or even longer, while a volatility pause is usually 5-10 minutes, but can keep getting rolled over if there's a lot of volatility in that stock that day.

**Two types of trading halts:**

1. **Regulatory halts** — typically imposed when a company is about to release significant, market-moving news: earnings reports, earnings warnings, mergers/acquisitions, government rulings, pending FDA decisions, board changes, etc. These can last from minutes to hours. A common code for a pending-news halt is **T1** — you can find the full list of halt codes with explanations on the official Nasdaq or FINRA websites.

2. **Non-regulatory halts** — essentially "speed bumps," also known as **circuit breakers**, triggered when a stock breaches a price percentage move threshold (up or down) within a rolling window, meant to pause the action and stabilize order/balance. Nasdaq, for instance, implements circuit breakers on stocks that spike or fall beyond a 10% or 20% range threshold within a rolling five-minute period for more than 15 seconds. Rules vary by exchange. These can last around 5-10 minutes. A common code for a volatility halt is **LUD**.

**Effect on the stock:** while halted, trading is prohibited across all exchanges. In situations where significantly negative news is about to come out (or has come out), a stock might reopen at a dramatically lower price. Exchanges post information on when the security will resume trading, but indicative pricing usually starts to display about five minutes before trading resumes.

## Trading Suspensions

Trading suspensions are executed by the exchange on behalf of the SEC (Securities and Exchange Commission). The reason can stem from concerns or an investigation into a publicly traded company's operations or financials — investigating stock manipulation, filings, or failure to meet regulatory requirements. These suspensions are meant to protect investors by pausing trading activity until serious questions about the company are addressed.

Since the SEC cannot announce ahead of time which companies will face a trading suspension (they conduct investigations confidentially), the suspension can come at any time — that's our main problem. The SEC publicly lists companies under trading suspension on their website, along with an archive — this is genuinely worth bookmarking, as you can always check which stocks are under an active halt or being investigated.

**Effect on the stock:** trading suspensions can last up to ten days, during which the company must address the concerns raised. The SEC won't publicly comment on the status of the investigation until after the ten-day suspension period ends. For stocks trading over-the-counter (OTC) — including Bulletin Board and pink sheet stocks — trading only resumes after FINRA approves a **Form 211**; broker-dealers dealing in the stock act as gatekeepers deciding whether the company's financials are accurate and current. A common trading suspension code is **H10**.

This can be a bad one, resulting in a long investigation by the authorities and often massive drops of 80% or more, sometimes ending in delisting. Another bad one is circuit breaker code **T12**: when a stock runs up very fast without any particular reason backing it up, authorities can halt it pending additional information from the company. This kind of halt also tends to end badly, with the stock reopening much lower than before the halt and sometimes crashing further — and again, this can happen in a flash without warning, leaving you stuck.

## Why This Matters Even for Day Traders

The thing about these halts: even if you're a day trader — especially if you are one — you might think, "That's fine, I'm a day trader, I don't hold positions overnight, so I don't incur overnight gap risk." You're right, if you truly come home flat every day with no position whatsoever, your only exposure is during the day while you hold a position.

But I've seen many, many times people day trading, scalping, or doing even more active forms of day trading, feeling that because they don't carry positions overnight, they control their risk a lot better. To that I say: absolutely not. That's exactly why I wanted to cover trading halts — you might take a position that's much too large/leveraged for your account, believing you control your risk simply because you're in and out, in and out, all day. The fact is these stocks can get suspended without any notice — they just stop trading. As we've covered, this could be for volatility reasons, or for other types of suspensions pending further investigation — and you can't do anything about it. Whether it lasts one hour, two hours, two days, ten days, or more, your capital is tied up and there's nothing you can do — you can't sell the position until trading resumes, and when it does resume, in most cases it resumes very badly.

I want you to understand the risk you're running from trading halts and suspensions, which is exactly why we need to be very careful with the leverage we use in our accounts — not to mention that if you're short and get caught in a suspension, there are margin fees from your broker, and for certain stocks under a certain price (I believe around $3, though rulings can change over time), extra overnight fees also get added. So the longer you hold the position without knowing when it will reopen, the more fees accumulate — on top of not knowing where the stock will reopen. If you're short and the pending news turns out to be very positive, you could get absolutely hammered on your short position, on top of accumulated margin and exchange/broker fees.

## Delisting: The Final Nail in the Coffin

The final risk is delisting. All major US stock exchanges have minimum requirements companies must meet to remain listed. Companies that fail to maintain listing requirements can be kicked off the exchange. The worst case is when shares lose all their value and no longer trade on any market at all — companies that go bankrupt or shut down due to fraud. These shares become effectively worthless — a total write-off for the trader/investor.

You can see the official list of trading halts for FINRA OTC securities by visiting the FINRA website — you can view live trading halts or look back through their archives, with the exact halt codes as discussed above.

## Recap

We've almost reached the end of the road on this subject. We talked about key metrics and expectancy in our trading system, which led us to assess the risk of ruin and how to avoid it using simple but effective money management techniques like position sizing — and we covered the different types of position sizing we can use. We explored the close, important link binding money management and risk management, realizing they're basically twin brothers — you can't have one without the other. We manage and minimize our risk mostly through stop-loss orders.

However, as we've just discussed, no matter how disciplined and resolute we are in managing our risk, we still face unpredictable gap risk while trading stocks. To be clear: this gap risk exists in all financial instruments, but given the relative illiquidity of certain stocks — even compared to the most liquid major-cap US stocks (Facebook, Amazon, GE, etc.) — versus something like FX or the fixed-income bond market, stock liquidity is really nothing in comparison. That's why volatility of this type matters so much more when trading stocks: if a stock gets suspended or halted, or news comes out, the resulting gap can be a lot bigger than what you'd typically find in FX or bond markets, simply because those markets are so huge and liquid — you'll get gaps sometimes, especially around major economic news, but nothing compared to what can happen with stocks.

That's probably part of why FX brokers can offer such large leverage (even though this has been heavily regulated since the Swiss franc crisis, which shut down many FX brokers) — they know this kind of extreme gap situation, overnight or intraday, essentially doesn't happen the way it can with stocks. Some brokers might still offer ridiculous leverage like 100x, 200x, or even 500x, and some people take them up on it — which is how you run into serious trouble.

Now that we've discussed volatility and gap risks that exist particularly in stocks, we need to take that dimension very seriously in our overall risk management equation. Next, I'll present our complete guidelines — our full system for money and risk management. Keep in mind these aren't set in stone — they're guidelines you can follow as-is, or adapt to your own psychology and risk appetite. Nevertheless, if you're serious about your trading and investing, and especially if you want to trade without stress while protecting your capital, I'd strongly urge you to stick to these rules and use them as a benchmark for your own risk and money management process. Let's look at these guidelines now.
