# Module 5, Video 7: Stop Loss Placement, Position Sizing, and Position Management (Take Profit)

## Step 4: Stop Loss Placement (Intraday Context)

For intraday trading, the stop loss should be placed below the pre-market low (for a long) or above the pre-market high (for a short), and we also look at recent consolidation levels. If these levels converge with a moving average (20, 50, 100, 200), the level becomes even more relevant/pertinent.

**Avoid obvious stop placement.** Never place your stop at the exact "textbook" level where everyone expects major resistance or support (e.g., "$0.02 below" or "$0.05 below"). Don't place your stop where most other day traders hold theirs — you'll get "stuffed." Algorithms and certain market makers specialize in "fishing for stops": they know where stops cluster, trigger them, take the other side of the trade, and the market immediately reverses back in its original direction. If you think everyone else will place their stop $0.05–$0.10 below a level, place yours $0.15 below instead — that extra distance is what keeps you out of the algo noise and keeps you in the trade.

**Key recommendation (learned from years of mistakes):** always favor a smaller position size with a slightly wider stop, rather than a tighter stop with a larger position size. Beginner and even intermediate traders instinctively want to minimize their loss in dollar terms (a very human impulse — humans hate losing), so they place tight stops and then try to compensate by increasing size. This is backwards. Keep your size aligned to your fixed-fractional risk management and equity allocation, and accept a slightly wider stop — it is far better than a tight stop with a bigger size that gets you stopped out constantly.

**If the pre-market/consolidation-based stop is too wide** relative to what your risk allows, look for support/resistance on a lower timeframe (e.g., the 15-minute or 5-minute chart) to tighten the stop. Ideally, the stop should be close to **2× ATR** (Average True Range) on whatever timeframe you're basing the stop on — 15-minute, hourly, etc. for intraday trading; daily ATR for swing trading.

Finally (and covered more in the position management system), the main idea is to secure the trade at breakeven as soon as possible, once the trade is in the money.

## Step 5: Position Sizing

Using a spreadsheet example: initial capital of $50,000, risk per trade of 0.1% (as recommended), with a cap of 5% total nominal exposure to any single stock.

- Maximum dollar risk per trade at 0.1% = $50.
- Maximum nominal exposure at 5% of $50,000 = $2,500.
- This translates to a maximum long position size of 538 shares (based on the 5% nominal cap) — but the actual position taken, based on the risk-per-trade / stop-loss calculation, might only be 250 shares (2.33% of capital spent).

This is a **two-dimensional sizing system**:
1. Initial risk per trade (fixed fractional basis, tied to your stop loss).
2. Maximum total nominal exposure to any single equity.

### Why two dimensions matter — the gap risk illustration

If you ignore the 5% nominal exposure cap and instead just increase the risk per trade (e.g., to 0.5%), the position size could grow to 1,250 shares — spending ~12% of the account on one stock. If that stock then gaps 50% overnight or on unexpected news (entirely possible, as shown with prior examples of gap risk), the account would drop ~6% from that single position.

Push it further: if risk per trade is set to 1% and the stop is 2× ATR, the system might suggest 2,500 shares — about $12,000, or 23% of the account, in one stock with an unknown outcome. A 50% gap against that position would mean a **12% drawdown on the account from one single trade** — and remember: the deeper the drawdown, the more disproportionately difficult the recovery (11% loss needs ~20% gain to recover; 20% loss needs ~30% gain, etc.).

**The lesson:** you only need one bad trade — not two, just one — to blow out an account if position sizing ignores nominal exposure limits. Markets can and do gap 50%, 60%, even 100%+ against you, and large market declines of 60–90% have happened repeatedly throughout history. Since we cannot predict when this will happen, the only way to protect ourselves is to act as if it could happen at any time — hence the two-dimensional (risk-per-trade + max nominal exposure) system. These caps are guidelines, not laws set in stone — but they exist for a good reason, and beginners in particular should stay conservative while learning their own psychology and trading style.

**Note:** forex and commodities markets generally don't gap as aggressively as stocks and don't suffer the same illiquidity during "trading holes," so this exact caution is somewhat less critical there — but the same principles still apply.

### TC2000 practical tool

On a TC2000 daily chart, a custom column/indicator can calculate share quantity in real time based on your maximum dollar risk per trade (e.g., $100) divided by 2× the ATR (using a 20-day average of the 1-day ATR, though 2× ATR-14 would give similar results). This displays both the volatility-based stop-loss price (for long or short) and the allowed share quantity instantly when you pull up a symbol — saving time and reducing stress during fast-moving markets.

## Position Management (Take Profit) — Intraday Context

Recap of the full system so far: (1) daily check of overall account leverage/exposure — the first "firewall"; (2) risk management rules (daily/weekly/monthly max loss limits, and drawdown-based size reduction); (3) stop-loss placement (volatility-based via ATR, or technical/support-resistance based); (4) protection against gap risk via nominal exposure caps — essentially "buying insurance" the same way we insure a car or house: most years the premium goes unused, but the protection matters for when something bad does happen, and if you skip that protection, any resulting loss was your own conscious decision, not the market's fault.

Now that a trade is on (stop placed, size determined), we need a **take-profit system** to manage the position. Some traders (trend followers at heart) never take partial profits. My personal preference is to bank money quickly and protect capital/trade as soon as possible — I "trade scared" because I prefer consistency over maximum aggression. It doesn't matter if you miss extra upside (opportunity cost) — what matters is being profitable and consistent. You will never buy the exact bottom or sell the exact top; the goal is tight risk control combined with the ability to enjoy profits consistently.

For **intraday/day trading**, position management is done on the **15-minute timeframe** (since momentum stocks favored for day trading move quickly, and this is the most efficient timeframe to manage risk intraday). If you have the screen time (even just 2–3 hours a day), day-trading-style management also improves entry techniques — but if not, you can still succeed by trading on a daily/weekly basis with orders placed for market open.

### Intraday take-profit (TP) breakdown

| Target | % of position closed | Basis | Stop management |
|---|---|---|---|
| **TP1** | 50% | Minimum risk-reward of 1, ideally 2, at a major resistance/support level | Move stop to breakeven immediately (or use partial profit to raise the original stop instead of full breakeven) |
| **TP2** | 30% | Predetermined Donchian channel level or chart resistance/support | Alternatively, trailing stop at EMA 20 (minus ~0.5× ATR buffer) |
| **TP3** | 20% (remainder) | Major resistance/support | Alternatively, exit at close below EMA 50 (with small buffer) |

The 5% max nominal exposure rule plus the 0.1% initial risk-per-trade rule together mean that, even in the event of a gap through breakeven, the account remains protected.

A TC2000 spreadsheet example: entry, stop loss (2× ATR), and TP1/TP2/TP3 price levels (e.g., $5.90, $6.50, $7.20 against an entry near $4.65) feeding a risk-reward calculation on TP1 (target ~2 or higher) and automatically splitting the position size (e.g., 250 shares → 125/75/50 across the three targets) — this automation reduces stress and calculation errors during fast-moving markets.

## Position Management (Take Profit) — Daily Swing Trading Context

For swing trading, we distinguish between three types of price moves, each requiring a different take-profit table:

1. **Gradual move** — price grinding higher steadily over many days/weeks/months, with EMAs running roughly parallel to each other.
2. **Parabolic move** — a faster, curving, accelerating move where EMAs spread apart quickly, candles get large, volume and ATR increase noticeably, typically playing out over 1–2 weeks.
3. **Supernova move** — an extreme, very sudden, very high-percentage move (100%–2,000%+) typically occurring over just 1–4 trading days, where EMAs on the daily chart become almost meaningless because price moves so far, so fast.

### General process for all move types
1. Establish take-profit targets based on price convergence/confluence areas (Donchian channels, chart support/resistance, Fibonacci levels, EMAs) — the more confluence, the stronger the target.
2. Establish a valid stop loss — for daily swing trades, just below the previous day's low, or 2× daily ATR (intraday equivalent: pre-market low/support-resistance or 2× ATR on the 15-minute timeframe).
3. Confirm risk-reward of at least 1 between TP1 and the stop before taking the trade (with the plan to secure the stop at breakeven ASAP).
4. You do not have to wait for the stop to be hit if price action clearly contradicts your thesis (e.g., a breakout that immediately re-enters the prior consolidation range signals stop-fishing, not genuine follow-through) — you can proactively close 50% of the position early and leave the rest running, reducing the eventual loss below the full initial stop-loss amount if you are stopped out later.

### Gradual move take-profit table

| Target | % of initial position | Basis | Trailing stop alternative |
|---|---|---|---|
| **TP1** | — | Min risk-reward of 1 (ideally 2) vs. stop | Move stop to breakeven (or raise it using partial profit) |
| **TP2** | 25% | Technical chart level | EMA 50 close-below (exponential) |
| **TP3** | 25% | Technical chart level | EMA 100 close-below (only if EMA 50 trailing stop wasn't already triggered at TP2) |
| **TP4** | 15% (remainder, ~35% cumulative before TP4) | EMA 200 close-below and below the 63-bar (≈3 month) low Donchian channel | EMA 100 close-below (if not already triggered at TP3) |

All percentages are based on the **initial position size**, not the remaining size at each step.

### Parabolic move take-profit table (3 targets, since the move is faster)

| Target | % of initial position | Basis | Trailing stop alternative |
|---|---|---|---|
| **TP1** | 25% (smaller share than gradual's TP1) | Chart-based target | Move stop to breakeven (or raise using partial profit) |
| **TP2** | 50% | Chart level | Volume-weighted moving average (VWMA) 10 close-below |
| **TP3** | 25% (remainder) | Chart support level | EMA 20 close-below, or VWMA 10 close-below (if not already triggered at TP2) |

### Supernova move take-profit table (only 2 targets — must be highly reactive)

Given how sudden and extreme these moves are, only the **1-hour timeframe** is used (not daily) to stay reactive while still giving the market some room to move. Watch for exhaustion signals (doji candles, engulfing patterns with volume) near a price cluster/resistance area.

| Target | % of initial position | Basis | Trailing stop alternative |
|---|---|---|---|
| **TP1** | 50% | Price cluster/resistance, or exhaustion signal | Move stop to breakeven immediately |
| **TP2** | 50% (remainder) | Chart resistance/support | VWMA 7 (on the 1-hour chart) close-below |

The VWMA 7 on the 1-hour chart represents roughly one full US trading day (6.5 regular market hours); volume weighting matters for stocks because it better reflects where large players (institutions) have been entering and exiting.

### Chart examples discussed
- **Gradual movers:** Amazon, Netflix, and others — EMAs running parallel, frequent bounces off the 20/50/100 EMAs.
- **Parabolic movers:** Tilray and others — sudden acceleration after long flat periods, volume and ATR spike, EMAs spread apart quickly, typically achieving in 1–2 weeks what a gradual mover takes 3–4+ months to accomplish.
- **Supernova movers:** examples including Avalon (+800% over 4 days), a stock up 50% in 2 days with ATR jumping ~10x, Carver Bancorp (~+300% in 1 day), a stock up 540% over 2 days, IMT (~+1,900% in 2 days), and Arcadia (~+900% over 4 days) — many of these also crash back down just as fast as they rose, reinforcing the need to be highly reactive and opportunistic rather than waiting passively.

### Key lesson on flexibility
Many years of experience taught a hard lesson: being too rigid (fixed stop/fixed target, no proactive management) left enormous money on the table, including trades that were deeply profitable "on paper" but ultimately closed at breakeven or a loss because of inflexibility. It's far better to bank partial profits along the way — even small ones that add up — than to ride a full position back down to breakeven or worse. If stopped at breakeven, you can always re-enter later using the re-entry techniques covered in Module 6.

### Why intraday and swing tables use different percentages
Intraday management uses a larger initial TP1 (50%) because day trades are meant to be cashed in and managed quickly. Swing trades use a smaller initial TP1 (25% for gradual/parabolic) because more time is given for the position to develop into larger multiples — except for supernova moves, which are managed almost like intraday trades (50% TP1) because they only last 1–4 days regardless of trading style.

If an intraday trade is carried overnight into a swing position, there's no conflict in mixing tables — e.g., if 50% was already closed intraday, the position can simply continue being managed under the swing framework going forward (and can even be added back to on a good pullback, covered in Module 6).

## Diversification — What It Really Means

The fixed-fractional risk-per-trade rule prevents unnecessary concentration in a single asset; the nominal exposure/leverage rule prevents excessive relative position size. Someone who puts 80–90% of their account into a single stock/ETF/currency bet — especially with added leverage (e.g., 5x) — exposes themselves to catastrophic risk of ruin from a single unpredictable adverse event. This is not trading; it's reckless gambling.

**Beware of false diversification.** Buying/shorting a basket of highly correlated stocks from the same sector, or holding several correlated currency pairs (e.g., long GBP against JPY, AUD, NZD, and USD simultaneously), does not truly diversify risk — it multiplies exposure to the same underlying bet, since these positions are often 90–95% correlated. The same applies to major stock indices (S&P, Nasdaq, Russell), which are also highly correlated with each other.

That said, holding several correlated stocks in the same sector does dilute *single-company/credit-specific risk* somewhat (a stock-specific bad-news gap of -30% to -50% might only drag related stocks down -10% to -15% in sympathy) — but it does very little to protect against sector-wide risk.

**True diversification** requires combining genuinely uncorrelated asset classes (equities, fixed income/bonds, cash, commodities), or, if choosing to hold correlated instruments deliberately, sticking strictly to overall risk and money management limits with the understanding that these related positions functionally increase leverage on one underlying bet rather than truly diversifying risk.

## Psychology Bridge: Revenge Trading (Molly's Game)

A story from the movie *Molly's Game* (about Molly Bloom, who ran an exclusive high-stakes poker game): a seasoned professional player named Harold Allen is up big (over 2x his stake, ~$100K+) when he loses a hand to a complete novice who got lucky. Rather than accepting it, Allen becomes enraged at losing to an inferior player in front of the table, abandons his usual disciplined strategy, and starts chasing his loss out of ego. He borrows another $500K from Molly to "get back to even," and ultimately loses **over $1 million in a single night** — purely because his ego took over.

This is **revenge trading/gambling**: the moment you personalize a loss and feel you're owed something back by "Mr. Market," you've already lost. Revenge trading combined with fear of missing out (FOMO) will drive you straight into a wall, exactly as it did this poker player.

This is precisely why banks, hedge funds, and institutional players employ dedicated risk managers to enforce discipline as an external, unemotional third party. Our daily/weekly/monthly max-loss caps and drawdown-based size-reduction rules exist to serve the same function — protecting us from ourselves during emotionally clouded periods. If you know you cannot reliably stop yourself once a certain loss threshold hits, many brokers allow you to pre-set hard max-loss limits that will automatically halt your trading for the rest of the day or week.

Ultimately, risk and money management exist to manage these psychological pitfalls — to let us step back after a big loss, restart smaller, and rebuild lost confidence, rather than spiraling further out of control.
