# Systematic Strategy Lab

## Extension / commodity contracts before signals

[Methods](https://github.com/Mingju-Zhang-CBS/systematic-strategy-lab/blob/main/docs/COMMODITY_ACCOUNTING.md) · [Synthetic results and failures](https://github.com/Mingju-Zhang-CBS/systematic-strategy-lab/blob/main/reports/commodities/REPORT.md) · [Tests](https://github.com/Mingju-Zhang-CBS/systematic-strategy-lab/blob/main/tests/test_commodities.py)

The eight-product futures extension tests contract identity, delayed information,
delivery-safe rolls, same-quantity near/far positions, separate leg costs, a funded
cash ledger and explicit model collateral. Predetermined controls retain missing
references, low capacity, failed exits and insolvency. Public commodity results
are **synthetic accounting diagnostics**, separate from the real TSP study below.
Licensed WRDS/LSEG source work is private; full historical commodity tradability,
actual margin reconstruction and carry/basis-momentum performance are not claimed.
The [exploratory funded runner](https://github.com/Mingju-Zhang-CBS/systematic-strategy-lab/blob/main/docs/COMMODITY_RESEARCH.md)
connects carry, trend and basis-momentum with a declared scheduled-calendar
proxy, same-contract histories, integer risk requests, per-leg costs and paired
inference that retains non-evaluable paths. Its [compact public demonstration](https://github.com/Mingju-Zhang-CBS/systematic-strategy-lab/blob/main/reports/commodity-research-synthetic/REPORT.md)
is entirely synthetic; licensed real-reference findings remain private. The
repository has 78 tests: 23 original, 29 commodity accounting, 12 monthly signal
and 14 funded-research checks. AI-assisted implementation is distinct from
unaided human mastery; no complete historical PIT or actual margin claim is made.

[Code](https://github.com/Mingju-Zhang-CBS/systematic-strategy-lab) · [Walkthrough](https://github.com/Mingju-Zhang-CBS/systematic-strategy-lab/blob/main/docs/WALKTHROUGH.md) · [Full real-data report](https://github.com/Mingju-Zhang-CBS/systematic-strategy-lab/blob/main/reports/real/REPORT.md) · [Rights](https://github.com/Mingju-Zhang-CBS/systematic-strategy-lab/blob/main/DATA_RIGHTS.md)

**Question:** Does momentum improve a funded multi-asset allocation after a fair risk-budget control, publication lags and fees?

## Investment, data and market-implementation skills

The AI-assisted implementation provides a five-fund public NAV snapshot contract, fixed allocation rules, a shared-risk-budget static control, self-financing unit transfers, chronological evaluation, paired uncertainty and readable research artifacts. It connects opportunity-cost analysis with financial data judgment and valuation/funding questions. Contribution and individual review are distinct from automated execution.

The 5,639 official TSP valuation dates cover 2003–2025. Each strategy has 5,368 evaluation rows, giving 21,472 daily account rows across momentum, static, C buy-and-hold and G reserve controls. Investment income and expenses are embedded in NAV; no separate dividend, operating fee or cash yield is added. The data-rights record documents public numerical facts and the U.S.-government-work basis, without inventing a third-party Creative Commons grant.

![Real fund NAV allocation results](../assets/systematic-strategy-lab-real-result.png)

## Findings, including failure

In chronological confirmation (2020–2025), momentum returned 30.69% versus 33.97% for static. Its annualized mean paired log-return difference was −0.42 percentage points, with a 20-session block 95% interval [−3.23, +2.33] pp. The 63-session interval also contains zero; all nine predefined cost/delay comparisons were negative. The evidence does not establish an incremental momentum advantage.

The shared risk budget is not exact realized-risk equality, and a comparison with C buy-and-hold has a different exposure. Temporal windows retain continuous holdings, trailing covariance and fixed rules. Historical familiarity and unavailable publication/revision archives prevent a prospective independent OOS claim.

## A decision has four clocks

Use NAV observations through t, allow a full intervening session for publication, freeze percentage targets, and model a request at 11:00 New York time on t+2. The eventual posting NAV is unknown when weights are set. Whole-percent targets, reserve holdings and posting-month transfer counts reflect simplified plan mechanics. Fractional units and ordinary posting are assumptions; this is not an ETF fill model or full participant-account simulator.

## Follow the money

The engine solves after-fee value plus friction equals prior value, charging gross purchases and sales including the reserve leg. A $100,000 G-to-C transfer at a hypothetical 10 bp per leg leaves $99,800.20 invested after a $199.80 fee. Subsequent accumulation-NAV growth is counted once. Daily ledgers reconcile prior value, embedded-income price P&L and fees; target percentages and later realized weights remain distinct.

The executable packet contains 23 tests, five real-data figures, four strategies, all nine stress cases, 22 year slices, ledgers/decisions/orders and source/configuration/output hashes. A separately labeled [synthetic accounting study](https://github.com/Mingju-Zhang-CBS/systematic-strategy-lab/blob/main/reports/demo/REPORT.md) retains the raw split/ex-date/payment examples; its simulated ETF labels and performance are not real-data evidence.

## Source and scope

Source: official TSP public numerical fund-NAV facts, captured in October 2026 and truncated at 31 December 2025. Restricted fund eligibility, a special G reserve mandate, the 2024 I Fund benchmark transition, current-vintage revisions and hypothetical transaction friction constrain interpretation. No original course, employer, client or recruiting materials are included. Development and documentation were AI-assisted.
