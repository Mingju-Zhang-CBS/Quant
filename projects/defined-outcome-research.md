# Defined-Outcome Research | From terms to investor outcomes

**Question:** How do buffer/cap terms, purchase time and fees change the payoff an investor actually buys?

The AI-assisted study translates public BJAN/FJAN issuer facts into a dated source ledger and a European-claim scenario engine. It evaluates 36 fixed entry-time/spot/volatility states, fee/friction and option-budget cases, and integer-funded settlement. Real issuer terms and synthetic pricing assumptions are explicitly distinguished; individual review is separate from automated execution.

![Entry time changes the payoff relative to purchase cost](../assets/defined-outcome-entry.png)

In the declared six-month/reference-120/20%-volatility scenario, maximum fee-adjusted terminal return is 4.62%; finishing at the original reference 100 produces -10.17%. These are model outcomes, not a historical ETF trade. All unfavorable scenarios and the uninvested cash in small budgets remain visible.

[Code](https://github.com/Mingju-Zhang-CBS/defined-outcome-research) · [Walkthrough](https://github.com/Mingju-Zhang-CBS/defined-outcome-research/blob/main/docs/WALKTHROUGH.md) · [Results](https://github.com/Mingju-Zhang-CBS/defined-outcome-research/blob/main/reports/demo/REPORT.md)

## What to inspect

- Interpretation: original outcome reference versus a later buyer's denominator; a buffer is not a rolling personal floor.
- Mathematics: piecewise payoff, signed European legs, dividends, independent risk-neutral integration and put-call parity.
- Implementation: computed entry debit, fee-unit convention, budget-balanced cap roots, integer packages and cash conservation.
- Market boundary: separately typed, timestamped NAV/bid-ask inputs; zero observations bundled, no fund NAV reconciliation or proven fills.
- Evidence: fixed protocol, source/data/output hashes, five result figures and 24 tests in a packaged offline study.

Original internship workbooks and prior reconciliation numbers remain private. The new study neither reproduces a private result nor labels a model mark as an executable quote. Development was AI-assisted. [Product method note](../cases/products-portfolio.md).
