# Trading and Inventory Risk

**Method note / background.**

**Question:** How does a fair value become a quote that an account can afford?

I was a Top 15 finalist in the Akuna Capital 2026 Virtual Quant Trading Challenge, as recorded in my professional background. The [independent market-making lab](https://github.com/Mingju-Zhang-CBS/market-making-lab) is a new public simulation, not the contest submission or official scoring system. Contest questions, interfaces, opponent implementations and hidden evaluations are not distributed.

## Connect value to risk

Dynamic programming can turn a finite-state transition model into a conditional terminal payout. Quoting then introduces other decisions: spread, inventory preference, cash, collateral and the information advantage of customers. An accurate conditional expectation does not make every trade attractive.

In a small illustrative account, buying one unit at 0.40 with a 0.001 fee changes cash 10 to 9.599. If marked at 0.42, NAV becomes 10.019. A later zero payout can still produce a loss. Similarly, selling at 0.60 with only 0.10 cash leaves inadequate capital for a possible unit payout; premium receipt is not the same as free collateral.

## Experimental discipline

Compare fixed quote policies on the same underlying paths and exogenous order-flow draws. Report all predeclared environments. Look at terminal loss tails, inventory occupation, markouts and funding, not only mean P&L. A larger local rank or score under a constructed opponent world is not evidence of a hidden contest result.

The public lab gives informed takers next-state information while maker quotes remain isolated. The legacy baseline gives noise customers price-inelastic demand, mechanically rewarding wider quotes. The current extension adds reservation-price acceptance with three fixed widths, common draws and independent seeds. Wider quotes lose customers and can receive worse informed-flow markouts; the full experiment retains policy-ranking reversals instead of selecting a favorable scenario. Neither assumed mechanism identifies an optimal real-market spread.

## Skills and next questions

This area demonstrates conditional probability, dynamic programming, simulation, numerical accounting, inventory risk and adversarial-flow reasoning. [Pricing and hedging](https://github.com/Mingju-Zhang-CBS/derivatives-pricing-lab) provides a complementary option-risk example. Real execution research would additionally require lawful order-level data, calibrated queue/fill behavior, fees, latency and capacity evidence.

## Evidence boundary

The competition achievement is a separate background fact. The original nine cases and the current 108-case extension are independently generated simulation evidence. Neither implies employer endorsement, live trading, contest code redistribution or real-market profitability.

[Research directory](../README.md)
