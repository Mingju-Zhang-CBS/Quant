# Derivatives Pricing Lab

**Question:** How much of a valuation difference comes from numerical implementation, model assumptions or the observed contract?

[Code](https://github.com/Mingju-Zhang-CBS/derivatives-pricing-lab) · [QuantLib comparison](https://github.com/Mingju-Zhang-CBS/derivatives-pricing-lab/blob/main/reports/quantlib/REPORT.md) · [Quote methods](https://github.com/Mingju-Zhang-CBS/derivatives-pricing-lab/blob/main/docs/QUOTE_RESEARCH.md) · [Tests](https://github.com/Mingju-Zhang-CBS/derivatives-pricing-lab/tree/main/tests)

## Numerical correctness first

European call/put prices and delta, gamma, vega, theta and rho are compared with independently authored QuantLib 1.44 over 1,296 predetermined parameter cases. Maximum absolute price difference is 4.3e-14 in grid price units. Greek errors use native sensitivity units. This establishes numerical agreement on the grid, not agreement with market quotes.

Original analytical, antithetic Monte Carlo and discrete delta-hedging examples remain available. Sampling error, convergence, costs and hedge frequency answer different questions from formula correctness.

## Contract-aware quote diagnostics

The new workflow checks strike and rate scales, contract size, exercise/settlement, forward keys and curve support before valuation. Fixed lagged 20/60-session historical volatility estimates are compared with bid/ask intervals by year, type and tenor. Vendor-IV repricing is a circular consistency check, not an independent forecast. The supplied market forward already embeds contemporaneous market information about carry.

Option, underlying and curve observation times may differ. End-of-day data do not establish executable prices, queue position or trade reconstruction. The [public synthetic quote fixture](https://github.com/Mingju-Zhang-CBS/derivatives-pricing-lab/blob/main/reports/quote-fixture/REPORT.md) exercises the same checks; licensed SPX records and derived real-data results remain private pending publication rights.

## Skills and contribution

The project connects probability, numerical analysis, contract conventions, data engineering and risk interpretation. New code, tests and documentation were AI-assisted; public models and QuantLib retain attribution. It does not publish classroom or employer implementations or claim an upstream contribution. [Provenance](https://github.com/Mingju-Zhang-CBS/derivatives-pricing-lab/blob/main/docs/PROVENANCE.md).

Continue to [Defined Outcome Research](defined-outcome-research.md) for the distinction between payoff structure, interim model value and investor entry price.

[Research directory](../README.md)
