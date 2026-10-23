# Planned research: Defined-Outcome Products

**Status: design brief only, intended as a future extension of Derivatives Pricing Lab. No new ETF replication or investment recommendation is claimed.**

## Research question

How do entry time, option cost and fees change the protection and return cap an investor actually receives?

## Public sources and rights

Rebuild the study from newly retrieved, dated issuer prospectuses and published holdings, beginning with the [issuer's buffer-product explanation](https://www.innovatoretfs.com/buffer/). Record the exact outcome period, option strikes, multipliers, fee definitions and source timestamp. Original internship workbooks, customer scenarios, vendor quotes and previously reported cap-reconciliation errors are excluded.

The initial mathematical experiment uses fresh synthetic parameters. A real issuer comparison is a separate optional validation stage only when required holdings, definitions and data-use conditions are available. Public holdings are not a substitute for executable bid/ask quotes.

## Fixed first experiment

Compare underlying exposure, a protective put, a put-spread buffer plus capped upside, and cash as a funding reference. Use the existing analytical European price functions for model values. Set an illustrative spot 100, one-year horizon, annual continuous rate 3%, volatility 20% and zero dividends; label them as model assumptions, not current market inputs.

For the put-spread/call-overlay illustration, hold one underlying unit, buy a put at 100, sell a put at 90 and sell a call at 110. Compute the initial cost rather than assuming it is a zero-cost strategy. At expiry, evaluate the payoff piecewise on a dense terminal-price grid, including all strikes. The package leaves losses below the put-spread floor and gives up upside above the call strike.

Compare entry at the start and after 3/6/9 months, using spot levels 80/100/120 and volatility 10%/20%/40%. Fix these scenarios before looking at outcomes. Fees, bid/ask assumptions and remaining time enter separately. Return divides net terminal wealth by the actual modeled entry cost. A mid-period purchase does not inherit the initial investor's payoff percentages.

## Implementation logic

Represent signed option/underlying legs with quantity, strike, maturity and multiplier. Separate terminal payoff from pre-expiry model valuation. Add declared transaction-cost bands and optional integer contract sizing under a fixed synthetic budget. Report any uninvested cash, infeasible budget or failed protection constraint rather than returning a convenient allocation.

The model uses European assumptions; real FLEX holdings, exercise conventions, distributions and fund operations may require adjustments. Do not describe the analytical mark as a tradable option quote or equate mathematical replication with market liquidity.

## Deliverables and acceptance

Deliver a source/rights sheet, leg inventory, payoff identity tests, strike-boundary tests, fee and entry-time tables, cost reconciliation, scenario charts and a decision memo. Any issuer cap comparison must be recomputed from the new dated inputs, with gross/net definitions reconciled. The original internship's historical bps result is not an acceptance target.

The study demonstrates product reasoning, numerical finance and constrained decisions. It does not choose a product for a real investor, guarantee protection or claim market outperformance.
