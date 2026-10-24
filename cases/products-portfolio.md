# Financial Products and Portfolio Decisions

**Method note / background.**

**Question:** Which assumptions change the investment decision?

The background includes option payoff analysis, portfolio concentration, risk attribution and liquidity allocation. The original internship materials, client scenarios and workbooks remain private. This page provides original teaching explanations and routes to public implementations.

## Payoff is not current value

A piecewise terminal payoff can be understood as a combination of calls, puts and cash or underlying exposure. Its value before expiry also depends on remaining time, volatility, rates and option prices. Fees and entry price change the investor's return even when the terminal contract payoff is unchanged. A stated buffer over an outcome period is not automatically an investor's protection at an arbitrary purchase date.

The implemented [Defined-Outcome Research](../projects/defined-outcome-research.md) uses fresh public issuer terms and independently written scenarios. It separates terminal target, model marks and a typed market-observation channel. No quotes are bundled and no ETF NAV reconciliation is claimed; private internship figures are not reused.

## Portfolio risk and liquidity

For covariance matrix Sigma and weights w, volatility is sqrt(w' Sigma w). Euler volatility contributions are `w_i*(Sigma*w)_i / portfolio_volatility` and sum to portfolio volatility under the model. Different covariance estimators and lookbacks can change those contributions. Concentration by portfolio weight is distinct from contribution to risk.

For a hypothetical 100-unit account with 20 units immediately liquid and an unexpected 25-unit withdrawal, the account has a five-unit immediate liquidity shortfall unless another asset can be monetized in time. Total NAV alone does not establish payment capacity. Simulated sale delays, loss assumptions and redemption timing must be recorded separately.

## Skills and public route

This area demonstrates mathematical finance, constrained allocation, risk decomposition, scenario design and explaining trade-offs. [Derivatives Pricing Lab](https://github.com/Mingju-Zhang-CBS/derivatives-pricing-lab) supplies analytical and simulated hedge evidence; [Systematic Strategy Lab](https://github.com/Mingju-Zhang-CBS/systematic-strategy-lab) shows paid cash, receivables and holdings in an auditable account.

## Limits

The arithmetic and formulas here are teaching material, not current product recommendations or client analysis. Model agreement does not prove a fair market quote, execution capability or future return. The public study records data dates, rights, fee conventions and the scope of each comparison.

[Research directory](../README.md)
