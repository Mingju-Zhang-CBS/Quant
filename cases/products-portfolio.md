# Financial Products and Portfolio Decisions

**Method note / background.**

**Question:** Which assumptions change the investment decision?

The background includes option payoff analysis, portfolio concentration, risk attribution and liquidity allocation. The original internship materials, client scenarios and workbooks remain private. This page provides original teaching explanations and routes to public implementations and a future design brief.

## Payoff is not current value

A piecewise terminal payoff can be understood as a combination of calls, puts and cash or underlying exposure. Its value before expiry also depends on remaining time, volatility, rates and option prices. Fees and entry price change the investor's return even when the terminal contract payoff is unchanged. A stated buffer over an outcome period is not automatically an investor's protection at an arbitrary purchase date.

The [defined-outcome brief](../roadmap/defined-outcome-research.md) proposes an independently rebuilt scenario study based on fresh public issuer documents. It separates contractual payoff, model-implied mid-period value and actual executable quotes. It does not reuse historical internship reconciliation errors as new evidence.

## Portfolio risk and liquidity

For covariance matrix Sigma and weights w, volatility is sqrt(w' Sigma w). Euler volatility contributions are `w_i*(Sigma*w)_i / portfolio_volatility` and sum to portfolio volatility under the model. Different covariance estimators and lookbacks can change those contributions. Concentration by portfolio weight is distinct from contribution to risk.

For a hypothetical 100-unit account with 20 units immediately liquid and an unexpected 25-unit withdrawal, the account has a five-unit immediate liquidity shortfall unless another asset can be monetized in time. Total NAV alone does not establish payment capacity. Simulated sale delays, loss assumptions and redemption timing must be recorded separately.

## Skills and public route

This area demonstrates mathematical finance, constrained allocation, risk decomposition, scenario design and explaining trade-offs. [Derivatives Pricing Lab](https://github.com/Mingju-Zhang-CBS/derivatives-pricing-lab) supplies analytical and simulated hedge evidence; [Systematic Strategy Lab](https://github.com/Mingju-Zhang-CBS/systematic-strategy-lab) shows paid cash, receivables and holdings in an auditable account.

## Limits

The arithmetic and formulas here are teaching material, not current product recommendations or client analysis. Model agreement does not prove a fair market quote, execution capability or future return. New product work will record data dates, rights, fee definitions and the scope of every comparison.

[Research directory](../README.md)
