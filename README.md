# Quantitative Research Directory

Eight studies by Mingju Zhang on financial data, valuation, allocation and execution. Each entry points to the research question, the main result and the repository with methods and reproduction instructions.

[Profile](https://github.com/Mingju-Zhang-CBS) · [LinkedIn](https://www.linkedin.com/in/mingju-zhang-611b00223/) · [Evidence standards](docs/EVIDENCE_STANDARD.md)

## Modeling and data validation

- **[Financial ML Validation](projects/financial-ml-validation.md).** Does a yield-curve classifier beat a simple baseline? The selected classifier trails on historical confirmation log loss. Evidence includes public Treasury yields and a separate licensed equity workflow with a public synthetic fixture. [Treasury results](https://github.com/Mingju-Zhang-CBS/financial-ml-validation/blob/main/reports/real/REPORT.md)
- **[Financial Text Validation](projects/financial-text-validation.md).** Does text improve an already publication-aware price model? The public FOMC/FX comparison finds no established increment. [FOMC/FX results](https://github.com/Mingju-Zhang-CBS/financial-text-validation/blob/main/reports/demo/REPORT.md) · [Company-news ablation](https://github.com/Mingju-Zhang-CBS/financial-text-validation/blob/main/docs/company-news/STRATEGY_COMPARISON.md)
- **[Agentic Quant Research](projects/agentic-quant-research.md).** Can an offline controller preserve a failed confirmation result and resume a frozen run? The public demonstration uses synthetic data and fixed JSON proposals. [Workflow report](https://github.com/Mingju-Zhang-CBS/agentic-quant-research/blob/main/reports/demo/REPORT.md)

## Pricing, products and market microstructure

- **[Derivatives Pricing Lab](projects/derivatives-pricing-lab.md).** Check European prices and Greeks on a deterministic grid, then examine simulated hedging costs and a synthetic SPX quote fixture. [QuantLib comparison](https://github.com/Mingju-Zhang-CBS/derivatives-pricing-lab/blob/main/reports/quantlib/REPORT.md)
- **[Market Making Lab](projects/market-making-lab.md).** Who still trades when quotes widen? Simulated customer choice changes fills, adverse selection and the policy ranking. [Demand experiment](https://github.com/Mingju-Zhang-CBS/market-making-lab/blob/main/reports/demand/REPORT.md)
- **[Defined-Outcome Research](projects/defined-outcome-research.md).** How do entry timing and funding costs change a buffered payoff? Dated issuer terms anchor the case and synthetic scenarios supply the model marks. [Scenario results](https://github.com/Mingju-Zhang-CBS/defined-outcome-research/blob/main/reports/demo/REPORT.md)

## Allocation, rates and execution

- **[Systematic Strategy Lab](projects/systematic-strategy-lab.md).** Does momentum improve a funded allocation under common risk and cost rules? Modeled portfolios use official TSP NAVs. The repository also indexes ETF dual momentum, robust allocation, regimes and breakout, commodity funding, and intraday execution. [NAV results](https://github.com/Mingju-Zhang-CBS/systematic-strategy-lab/blob/main/reports/real/REPORT.md) · [ETF dual-momentum report](https://github.com/Mingju-Zhang-CBS/systematic-strategy-lab/blob/main/reports/dual-momentum/REPORT.md)
- **[Macro Rates Research](projects/macro-rates-research.md).** What curve risk survives DV01 and prior-PCA hedging? Public Federal Reserve curves drive hypothetical P&L attribution. A separate synthetic policy demo models monthly contract mechanics. [Curve results](https://github.com/Mingju-Zhang-CBS/macro-rates-research/blob/main/reports/curve/REPORT.md)

## Method notes

- [Equity signals and model validation](cases/equity-signal-research.md) · [Statistical learning](cases/statistical-learning-foundations.md)
- [Point-in-time financial data](cases/financial-data-engineering.md) · [Financial text and event clocks](cases/financial-text.md)
- [Trading and inventory risk](cases/trading-market-making.md) · [Products and portfolio decisions](cases/products-portfolio.md)
- [Housing and credit](cases/housing-credit.md) · [Research systems](cases/research-systems.md) · [Course-to-market connections](cases/class-to-market.md)

## Reproduction and contribution

Each study README links the recorded results, methods, data terms and run instructions. Evidence is identified by experiment. Licensed workflows require the reader's own access and permission to use the inputs. Historical confirmation results use the data vintages and publication assumptions stated in their reports.

Mingju Zhang selected the research direction. Implementation, experiments, tests and documentation were AI-assisted. Project provenance records distinguish original work, collaborators, public methods and dependencies.

[Machine-readable catalog](project-catalog.json)
