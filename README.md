![Mingju Zhang — Research Studio](assets/header.svg)

# Research Directory

**Mingju Zhang · Columbia Business School MSFE ’27**  
[Profile](https://github.com/Mingju-Zhang-CBS) · [LinkedIn](https://www.linkedin.com/in/mingju-zhang-611b00223/)

I build testable research systems that connect financial evidence, models and decisions. Seven connected studies explore financial data, signals, valuation and implementation. Each provides code, methods, tests, recorded results and limitations; the data classification belongs to each experiment rather than the repository as a whole.

## Three flagship questions

|Study|What to inspect first|Evidence and limits|
|---|---|---|
|**[Financial ML Validation](https://github.com/Mingju-Zhang-CBS/financial-ml-validation)**|[Treasury findings](https://github.com/Mingju-Zhang-CBS/financial-ml-validation/blob/main/reports/real/REPORT.md) · [Equity methods](https://github.com/Mingju-Zhang-CBS/financial-ml-validation/blob/main/docs/EQUITY_RESEARCH.md)|Purged model comparison, historical stock selection, train-fitted preprocessing and regularization. Public Treasury observations; licensed equity extension and separate synthetic fixture.|
|**[Derivatives Pricing Lab](https://github.com/Mingju-Zhang-CBS/derivatives-pricing-lab)**|[QuantLib comparison](https://github.com/Mingju-Zhang-CBS/derivatives-pricing-lab/blob/main/reports/quantlib/REPORT.md) · [Quote methods](https://github.com/Mingju-Zhang-CBS/derivatives-pricing-lab/blob/main/docs/QUOTE_RESEARCH.md)|Numerical correctness, Greeks, simulation and quote conventions. Deterministic grid; simulated hedges; private licensed SPX diagnostics.|
|**[Market Making Lab](https://github.com/Mingju-Zhang-CBS/market-making-lab)**|[Demand experiment](https://github.com/Mingju-Zhang-CBS/market-making-lab/blob/main/reports/demand/REPORT.md)|Conditional value, price-sensitive fills, inventory and adverse selection. Predetermined simulated scenarios, shared paths and explicit cash accounting.|

**Research chain:** observation & identity → information set → signal or valuation → validation → implementation & risk.

## Complete study collection

|Study|Question|Data / result boundary|
|---|---|---|
|[Financial ML Validation](projects/financial-ml-validation.md)|Can transparent models improve a fixed baseline?|Public real Treasury data; equity protocol/code and licensed-data workflow; negative Treasury confirmation retained.|
|[Derivatives Pricing Lab](projects/derivatives-pricing-lab.md)|Do conventions explain numerical and quote discrepancies?|Parameter grid, synthetic paths and quote fixture; licensed SPX inputs/results remain private.|
|[Market Making Lab](projects/market-making-lab.md)|How does customer choice change quote-policy risk?|Simulated demand; no calibrated queue or real execution claim.|
|[Financial Text Validation](projects/financial-text-validation.md)|Does policy text add information beyond prices?|128 public FOMC statements and first-published FX references; incremental text value unproven.|
|[Systematic Strategy Lab](projects/systematic-strategy-lab.md)|Does momentum survive implementation?|Official fund NAVs with modeled allocations; confirmation advantage unproven.|
|[Agentic Quant Research](projects/agentic-quant-research.md)|Can research selection survive interruption and audit?|Synthetic offline JSON controller; no paid model, live LLM or Qlib integration claimed.|
|[Defined-Outcome Research](projects/defined-outcome-research.md)|What protection does a later buyer actually receive?|Public issuer facts with model scenarios; expiry payoff, interim value and observed quote distinguished.|

## Research map

These notes recover methods from earlier learning and experience; they are not additional empirical projects or redistributed course submissions.

- [Equity signals: risk adjustment, events and regularization](cases/equity-signal-research.md)
- [Financial data: identity, units and availability](cases/financial-data-engineering.md)
- [Financial text: raw-to-derived checks and event clocks](cases/financial-text.md)
- [Statistical learning foundations](cases/statistical-learning-foundations.md)
- [Trading and inventory risk](cases/trading-market-making.md)
- [Products and portfolio decisions](cases/products-portfolio.md)
- [Housing and credit](cases/housing-credit.md) · [Research systems](cases/research-systems.md)

## Reproduction & attribution

Start with a study README, then its methods, results and test directory. Default examples use lawful bundled inputs or simulation. CRSP and OptionMetrics workflows require the reader's own institutional access; original records and restricted derived outputs are excluded. Access does not imply redistribution rights. Historical splits do not create prospective unseen evidence from previously studied periods.

Mingju Zhang selected the portfolio questions and direction. Implementation, experiment design, tests and writing were AI-assisted; source coursework, collaborators, established methods and library authors retain their separate attribution. A recorded automated run does not establish unaided human mastery. Original employer, competition and group materials stay private.

[Canonical content catalog](project-catalog.json) · [Evidence standards](docs/EVIDENCE_STANDARD.md)
