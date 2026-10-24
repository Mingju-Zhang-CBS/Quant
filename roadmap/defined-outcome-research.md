# Defined-Outcome Research: completed first study and next extensions

**Status: implemented, issuer-facts plus model-scenario study.** [Repository](https://github.com/Mingju-Zhang-CBS/defined-outcome-research) · [Report](https://github.com/Mingju-Zhang-CBS/defined-outcome-research/blob/main/reports/demo/REPORT.md).

The original brief proposed testing how entry time, option costs and fees change a buffer/cap structure. The first implementation uses newly retrieved public BJAN/FJAN terms, a fixed European-claim model, 36 entry states and explicit fee/cash conventions. It provides independent payoff/valuation tests, integer-budget constraints, five figures and a fully offline packaged demonstration.

The source-shaped gross strip is not automatically worth 100. A later buyer's denominator is recomputed, remaining fees are declared, and strikes stay fixed. The issuer's positive-strike deep call is identified; missing quantities and fund cash prevent a claimed ETF NAV replication. The quote channel is separately validated and empty, so no actual execution or historical return is claimed.

## Remaining extensions, not completed claims

1. Establish licensed, synchronized option and ETF quotes with complete fund quantities, cash, accrued expenses and unit conversion before attempting NAV reconciliation.
2. Replace flat volatility with a verified surface and quantify skew, term structure, dividend and liquidity assumptions.
3. Model a multi-period reset with explicit dates, distributions, taxes and new caps; the current single-period model cannot infer a long-run investor return.
4. Add broker-specific margin and package execution constraints under a documented account agreement.

The original internship's private basis-point results and client materials are not evidence for this implementation.
