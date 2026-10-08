# copy trading OKX: how to choose traders, control risk, compare spot and futures copy trading

Copy trading on OKX is designed for people who want to follow another trader’s positions without manually placing every order. Once you copy a lead trader, the platform can replicate that trader’s entries and exits in your own account, subject to your settings, available balance, market conditions, and OKX’s copy-trading rules.

That sounds simple, but “simple to activate” does not mean “automatic profit.” The important decisions happen before you press **Copy**: whether to use spot or futures copy trading, how much capital to allocate, which trader metrics to inspect, and where to set your stop-loss limits.

This guide explains how OKX copy trading works, what it costs, which controls are available, and where the main risks sit. It also includes the current OKX copy-trading options and the referral link provided for this article.

> **Important availability note:** OKX’s official copy-trading FAQ currently lists the United States, Canada, the United Kingdom, and several other regions as unsupported for copy trading. Product availability can depend on your country, account entity, verification status, and local rules. Check what appears after logging in before depositing funds.

## What is copy trading on OKX?

OKX copy trading lets you select a lead trader and automatically mirror eligible trades in your own trading account. In futures copy trading, this generally means opening and closing corresponding positions. In spot copy trading, your account can replicate the lead trader’s spot purchases and sales.

You do not hand over control of your entire account to the lead trader. Instead, you set the parameters for your copy-trading allocation. Depending on the product, these can include:

- Amount per order
- Proportional multiplier
- Maximum total amount
- Supported coins or contracts
- Stop-loss per order
- Take-profit per order
- Stop-loss for the selected trader
- Whether remaining positions should be closed when a limit is reached

The platform also displays trader information such as profit and loss, PnL percentage, AUM, lead-trader investment, and win rate. OKX says these profile statistics refresh hourly for spot copy trading.

That data is useful, but it is not a prediction engine. A trader with strong recent returns can still experience a losing streak, change strategy, use more leverage, or take positions that do not match your risk tolerance.

## OKX copy trading options compared

OKX does not present copy trading as a collection of monthly subscription packages. There is no “Basic Copy Trading,” “Pro Copy Trading,” or fixed monthly plan in the official materials reviewed for this guide. Instead, the main choice is the type of strategy you want to follow.

| Copy-trading option | How it works | Leverage or liquidation | Main controls | Cost structure | Access |
| --- | --- | --- | --- | --- | --- |
| Futures copy trading | Mirrors eligible futures positions opened and closed by a lead trader | Leverage may apply; liquidation risk exists | Fixed or proportional order amount, maximum total amount, leverage, take-profit, stop-loss, trader stop-loss | Regular trading fees plus applicable funding or other futures costs; profit share may apply | [ Open OKX with the supplied referral link](https://okx.com/join/CASH20) |
| Spot copy trading | Replicates eligible spot purchases and sales | No leverage or margin in spot copy trading | Fixed amount, proportional amount, maximum total amount, supported coins, order and trader stop-loss settings | Same trading fees as regular spot trading plus applicable profit sharing | [ Check OKX spot copy trading access](https://okx.com/join/CASH20) |
| OKX Wallet Trader Mode copy trading | Replicates transactions from a selected on-chain wallet using configured rules | Depends on the on-chain strategy and execution settings | Buy and sell conditions, token filters, liquidity and market-cap filters, take-profit and stop-loss | Network and execution costs may apply; exact costs depend on the wallet and transaction | [ Explore OKX Wallet access](https://okx.com/join/CASH20) |

The first two rows are the conventional exchange copy-trading products. The Wallet Trader Mode feature is different: it follows activity from an on-chain wallet and lets users configure filters such as market capitalization, liquidity, and token creation time. It is not the same as copying an OKX futures lead trader.

For most beginners comparing “copy trading OKX” options, the practical decision is between **spot copy trading** and **futures copy trading**.

## Spot copy trading: the lower-complexity option

Spot copy trading mirrors purchases and sales of crypto without leverage or margin. When the lead trader buys, your account attempts to place the corresponding purchase. When the lead trader sells, your position can be sold automatically, although your execution price may differ slightly.

OKX currently documents the following spot copy-trading mechanics:

- You can choose a fixed amount for each copied order.
- You can use a proportional amount based on the lead trader’s order size.
- You can set a maximum total amount for all open copy trades under one trader.
- You can choose the crypto assets to copy.
- You can set a stop-loss for the trader.
- You can set take-profit and stop-loss controls for individual orders.
- Spot copy trading does not support leverage or margin.
- The platform states that 114 spot cryptocurrencies are supported in the documented spot-copying rules, although supported assets can change.

Spot copy trading removes liquidation from the product design, but it does not remove market risk. If the copied asset falls and the lead trader does not sell, your position can continue losing value. Crypto prices can also move sharply between the lead trader’s execution and your own order.

There is also a practical issue that is easy to miss: assets purchased through spot copy trading may be frozen for other uses until they are sold. OKX says these funds are released after the copied asset is sold.

### How spot copy-trading amounts work

You can use either a fixed amount or a proportional amount.

With a fixed amount, every copied order uses the same amount you specify. For example, if you set 25 USDT per order, each eligible copied purchase attempts to use 25 USDT, subject to minimum order limits and available funds.

With a proportional amount, your order size follows the lead trader’s order value according to a multiplier. If the lead trader opens a 1,000 USDT order and your multiplier is 0.1x, your corresponding order value would be 100 USDT before considering execution conditions and platform rules.

For someone starting with a small account, fixed amounts are easier to understand and cap the size of each new position. Proportional copying can track the lead trader’s sizing more closely, but it can also produce larger orders than expected when the lead trader increases position size.

## Futures copy trading: more flexibility, more ways to lose money

Futures copy trading can mirror leveraged positions. That makes it fundamentally different from spot copying.

The lead trader may open long or short positions, use leverage, and close positions based on a strategy that may be difficult to reproduce manually. Your results can differ because of execution price, spread, funding, account size, leverage settings, available margin, and timing.

OKX’s copy-trading documentation lists several controls for proportional futures copying:

- A multiplier between 0.01x and 10x
- A maximum total copy amount between 20 USDT and 30,000 USDT in the referenced product documentation
- Leverage linked to the relevant manual contract-trading settings
- Take-profit per order, with a documented maximum of 150%
- Stop-loss per order, with a documented maximum of 75%
- A total stop-loss for all positions copied from one lead trader
- The choice to close remaining positions immediately, wait for the lead trader to close, or close manually
- The ability to choose which supported contracts to copy

The proportional multiplier deserves careful attention. A 1x setting does not mean the trade is safe or that your account will behave exactly like the lead trader’s account. It means your order value is calculated in relation to the lead trader’s order value. Leverage, margin balance, contract settings, and execution can still create very different outcomes.

OKX specifically warns that setting the multiplier too high can expose the copy trader to early liquidation. Its documentation also provides a recommended multiplier calculation based on your equity, maximum total copy amount, and the lead trader’s equity.

A cautious starting configuration generally means:

1. Use a small maximum total amount.
2. Keep the multiplier below the platform’s recommended range until you understand the trader’s position sizing.
3. Set a total stop-loss before copying.
4. Avoid copying several highly correlated futures traders.
5. Review leverage and margin mode instead of assuming the lead trader’s settings match yours.

The last point matters because one trader may use small, frequent positions while another may hold a concentrated leveraged trade. Their headline return could look similar while the risk profile is completely different.

## How much does OKX copy trading cost?

There is no fixed copy-trading subscription price listed in the official materials reviewed. The cost normally comes from several separate components.

### Regular trading fees

OKX states that copy-trading trading fees follow the regular trading-fee rules for your account tier. Fees can differ by product, market, trading pair, maker or taker execution, and VIP level. The rate shown in your logged-in account is the relevant one for your trades.

The current OKX fee page lists a regular-user example of 0.2000% maker and 0.3500% taker for the displayed standard table, while higher VIP tiers show lower rates. These rates are not universal for every region, instrument, or account, so use the fee rate displayed inside your own account rather than treating the public table as a guaranteed rate.

### Profit sharing

OKX’s copy-trading FAQ states that copy traders may share 8% to 13% of profits with lead traders according to the applicable profit-sharing level. Other current OKX documentation shows that trader-level rules can vary by product and status, with spot and futures lead-trader profit sharing described separately.

For spot copy trading, OKX describes a weekly settlement cycle. The system can withhold a provisional amount from profitable trades, then calculate the actual net profit for the settlement period after profitable and losing trades are considered. If the withheld amount is higher than the final amount owed, the difference is returned to the copy trader.

This means you should not judge the cost from one profitable transaction alone. The relevant figure is the applicable profit-sharing calculation after the settlement period, together with trading fees and any other product-specific costs.

### Futures funding and liquidation-related costs

Futures trading can involve funding fees. OKX’s fee documentation also explains that futures may involve liquidation-related charges and expiry settlement fees depending on the instrument.

A futures copy-trading strategy can therefore lose money even when the copied trader’s entry and exit direction appears correct. Funding, slippage, leverage, and the difference between accounts can all affect the final result.

## What should you check before choosing a lead trader?

The most visible number is usually recent PnL. It is also one of the easiest numbers to misuse.

A trader with a high 30-day return may have achieved it through concentrated positions, high leverage, or one unusually successful market move. That does not tell you how the trader behaves during a drawdown.

Before copying, inspect:

### Trading history length

A short profitable period provides limited information. Prefer a profile with enough trading history to show how the trader handled different market conditions. A trader who has only operated during a strong bullish move may look better than they actually are.

### Drawdown and losing periods

Look for the size and duration of losses, not only winning days. A strategy with frequent small gains and occasional deep losses requires different controls from a strategy with smaller but more consistent fluctuations.

### Leverage and position size

For futures traders, check average position size, leverage, and whether trades are concentrated in one asset. A lead trader using aggressive leverage may be unsuitable even if the recent PnL is attractive.

### AUM and copier count

AUM can show how much capital copy traders have allocated, but it is not a quality guarantee. A popular trader can still take excessive risk. Treat AUM as context, not as proof of reliability.

### Win rate

A high win rate is not enough by itself. A strategy can win many small trades and lose heavily on one large trade. Compare win rate with average loss, drawdown, and position sizing.

### Exit behavior

Check whether the trader closes positions quickly, holds through large swings, or regularly adds to losing positions. Your chosen stop-loss settings should reflect this behavior.

OKX describes lead-trader profiles using metrics such as PnL, PnL percentage, AUM, lead-trader investment, and win rate. Those metrics help with comparison, but they do not remove the need to examine the underlying strategy.

## How to start copy trading on OKX

The exact menu labels can change between the website and app, but the current official instructions follow this general process.

### On the web

1. Open the trading section.
2. Go to **Bots & Copy** and then **Copy trading**.
3. Choose between futures copy trading and spot copy trading.
4. Browse the market board and open a lead-trader profile.
5. Review the trader’s statistics, assets, activity, and risk settings.
6. Select **Copy** or **Copy now**.
7. Choose fixed or proportional order sizing.
8. Set the maximum total amount.
9. Configure take-profit and stop-loss controls.
10. Confirm the settings and monitor the copied positions.

OKX’s spot-copying instructions place the feature under **Trade > Bots & Copy > Copy trading** on the web. The app route is listed as **Trade > Bots & Copy > Recommended**, followed by the copy-trading section.

### For proportional futures copying

The documented flow is to go to **Discover > Copy trading**, select a trader, choose **Copy now**, select **Proportional amount**, configure the multiplier and risk controls, and confirm the copy trade.

Do not skip the maximum total amount. Without a hard allocation limit, a trader who opens many positions can use more of your available capital than you expected.

## Why a copied trade may not execute

Copy trading is not a guarantee that every lead-trader order will appear in your account.

OKX lists several reasons a copied trade may fail:

- The lead trader stopped leading trades.
- The lead trader lost lead-trader status.
- The lead trader reached the daily lead-trade limit.
- The trade triggered risk controls.
- Your account did not have enough funds.
- Your maximum copy amount was reached.
- The position exceeded a relevant contract or account limit.
- The price difference exceeded the spread-protection threshold.

For opening positions, OKX documents a 0.5% spread-protection rule. If the copy trader’s opening price is more than 0.5% away from the lead trader’s opening price, the trade may not be copied.

This is especially relevant during volatile markets. A lead trader may enter a position successfully while your account misses the copy because the market moved too quickly.

## Is OKX copy trading suitable for beginners?

Spot copy trading is easier to understand than leveraged futures copy trading because it does not use margin or liquidation. That makes it the more straightforward starting point for someone who is still learning how exchange orders, position sizing, and stop-losses work.

Futures copy trading may suit experienced traders who understand:

- Leverage
- Maintenance margin
- Liquidation
- Funding fees
- Position modes
- Contract sizing
- Slippage
- Correlation between positions

Copy trading can reduce the need to place every order manually, but it does not eliminate the need to manage risk. You still choose the lead trader, fund the account, select the allocation, and decide when to stop copying.

A sensible approach is to start with an amount you can afford to lose, use strict allocation limits, and treat the first period as an observation phase. The goal is to learn how the selected trader behaves in real conditions before increasing exposure.

## Referral link and access

The supplied referral link uses the code **CASH20**. You can use it to check whether OKX registration and copy-trading features are available for your jurisdiction:

[👉 Register or check OKX copy trading access](https://okx.com/join/CASH20)

The stated referral arrangement is a **20% commission** associated with the invitation code. That should not be confused with a guaranteed trading discount, guaranteed return, or guaranteed copy-trading result. Availability, fees, promotions, and product access are determined by OKX’s current regional terms and your account status.

## Final verdict

OKX copy trading is most useful when you treat it as a configurable trading tool rather than a passive income switch.

Spot copy trading is the clearer option for users who want automated trade replication without leverage. Futures copy trading offers more strategy flexibility, but the combination of leverage, funding, spread, and liquidation risk makes position sizing much more important.

Before copying a lead trader, check the trading history, drawdown, leverage, average position size, and exit behavior. Set a maximum total amount and stop-loss before the first trade. Then verify the actual fees and product availability inside your own OKX account, especially if you are in a region listed as unsupported by the official copy-trading FAQ.
