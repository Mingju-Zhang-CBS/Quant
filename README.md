![Mingju Zhang: Quantitative Finance](assets/header.svg)

# Quantitative Finance Research | Mingju Zhang

I am an MSFE candidate at Columbia Business School, interested in quantitative research, systematic investing, derivatives and financial data science. I build Python studies that connect financial assumptions to statistical evidence and inspectable implementations.

My work asks three connected questions: **Can the validation be trusted? Does the account make economic sense? How do numerical error and hedging costs interact?**

## Three studies, one research standard

| Study | Central question | Strongest evidence |
| --- | --- | --- |
| [Financial ML Validation](projects/financial-ml-validation.md) · [Code](https://github.com/Mingju-Zhang-CBS/financial-ml-validation) | What survives a separate evaluation stage? | Exact label joins, training-only transformations, date isolation and an uncertainty interval. |
| [Systematic Strategy Lab](projects/systematic-strategy-lab.md) · [Code](https://github.com/Mingju-Zhang-CBS/systematic-strategy-lab) | What changes when a signal becomes an account? | Delayed decisions, cash constraints, dividend timing and daily NAV reconciliation. |
| [Derivatives Pricing Lab](projects/derivatives-pricing-lab.md) · [Code](https://github.com/Mingju-Zhang-CBS/derivatives-pricing-lab) | How do numerical accuracy and hedge costs interact? | Analytical references, pair-based MC errors and common-path hedge comparisons. |

The linked case studies are self-contained and include local visual/evidence assets. Each implementation is published in its own public repository as a separate Python distribution with its own tests, methods, examples and license.

## Choose a reading route

| Interest | Start with | Then inspect |
| --- | --- | --- |
| Quantitative research | Financial ML Validation | Selection protocol, ablations and uncertainty; strategy assumptions. |
| Systematic investing | Systematic Strategy Lab | Decision timing, account flows, risk and cost sensitivity. |
| Derivatives and quantitative risk | Derivatives Pricing Lab | Greek units, model assumptions and discrete hedge errors. |
| Quantitative development | Pricing and strategy implementations | Input contracts, numerical identities, memory and batch measurements. |
| Financial data science | Financial ML Validation | Keyed alignment, feature definitions, grouped evaluation and diagnostics. |

## Demonstrated capabilities

| Capability | Where to inspect it |
| --- | --- |
| Statistical learning and validation | Fold-fitted preprocessing, grouped/forward evaluation, model ablations and paired uncertainty. |
| Financial modeling and accounting | Signal timing, constrained trades, corporate actions and a self-financing daily ledger. |
| Numerical methods and derivatives | Analytical sensitivities, variance reduction, simulation and discrete hedging. |
| Research software | Explicit input contracts, behavioral tests, standalone packaging, manifests and reproducible artifacts. |

## How the evidence should be read

The public experiment snapshots are synthetic or simulated. They demonstrate implementation and controlled reasoning, with unfavorable results retained. Accuracy is not trading P&L; synthetic Sharpe is not historical ETF performance; batch-pricing speed is not exchange latency. Each case study makes the scope of its conclusion explicit.

Read a study's question and result first, then its workflow, worked example, tests and source. When revisiting a result, use its configuration, input fingerprint and package-source hashes rather than a detached screenshot.

Development was AI-assisted. The newly written implementations are distinct from original academic, employer and recruitment materials. [Browse the account](https://github.com/Mingju-Zhang-CBS?tab=repositories).
