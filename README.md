![Mingju Zhang](assets/header.svg)

# Research Directory | Mingju Zhang

**Quantitative Research & Financial Machine Learning** · [Profile](https://github.com/Mingju-Zhang-CBS) · [LinkedIn](https://www.linkedin.com/in/mingju-zhang-611b00223/)

I build testable research systems that connect financial data, model validation and trading decisions. This directory separates runnable public studies, method notes about my research background, and future designs. Original course, company and competition materials remain private.

**Research thread:** Financial Data → Signals → Validation → Portfolio & Execution.

## Six featured studies

### 01 · [Financial Text Validation](https://github.com/Mingju-Zhang-CBS/financial-text-validation)

**Does policy text add information beyond prices?** I compare TF-IDF text, price and fusion models on 128 public FOMC statements and first-published EUR/USD references, separating measurement dates from release availability and freezing confirmation choices. Incremental text value remains unproven.

*Public FOMC/FX data · financial NLP · publication clocks*  
[Case study](projects/financial-text-validation.md) · [Code](https://github.com/Mingju-Zhang-CBS/financial-text-validation) · [Walkthrough](https://github.com/Mingju-Zhang-CBS/financial-text-validation/blob/main/docs/WALKTHROUGH.md) · [Results](https://github.com/Mingju-Zhang-CBS/financial-text-validation/blob/main/reports/demo/REPORT.md)

### 02 · [Financial ML Validation](https://github.com/Mingju-Zhang-CBS/financial-ml-validation)

**How much trust does a financial classifier earn?** I compare logistic regression, LightGBM and CatBoost with keyed label alignment, train-fitted transformations, fixed ablations and date-level uncertainty. The synthetic accuracy interval includes zero.

*Synthetic panel · financial ML · validation and uncertainty*  
[Case study](projects/financial-ml-validation.md) · [Code](https://github.com/Mingju-Zhang-CBS/financial-ml-validation) · [Walkthrough](https://github.com/Mingju-Zhang-CBS/financial-ml-validation/blob/main/docs/WALKTHROUGH.md) · [Results](https://github.com/Mingju-Zhang-CBS/financial-ml-validation/blob/main/reports/demo/REPORT.md)

### 03 · [Market Making Lab](https://github.com/Mingju-Zhang-CBS/market-making-lab)

**What changes when fair value becomes an affordable quote?** I connect backward dynamic programming to three inventory/collateral-aware policies across nine shared-path simulations. Every result can be traced through trade cash flows, markouts and settlement.

*Simulated market · probability · inventory and collateral*  
[Case study](projects/market-making-lab.md) · [Code](https://github.com/Mingju-Zhang-CBS/market-making-lab) · [Walkthrough](https://github.com/Mingju-Zhang-CBS/market-making-lab/blob/main/docs/WALKTHROUGH.md) · [Results](https://github.com/Mingju-Zhang-CBS/market-making-lab/blob/main/reports/demo/REPORT.md)

### 04 · [Agentic Quant Research](https://github.com/Mingju-Zhang-CBS/agentic-quant-research)

**Can an experiment remain auditable after selection and interruption?** I built an offline controller for JSON proposals, past-only factors, frozen confirmation and sealed-stage recovery. The synthetic winner fails confirmation; no live language model is called.

*Synthetic panel · offline workflow · lineage and recovery*  
[Case study](projects/agentic-quant-research.md) · [Code](https://github.com/Mingju-Zhang-CBS/agentic-quant-research) · [Walkthrough](https://github.com/Mingju-Zhang-CBS/agentic-quant-research/blob/main/docs/WALKTHROUGH.md) · [Results](https://github.com/Mingju-Zhang-CBS/agentic-quant-research/blob/main/reports/demo/REPORT.md)

### 05 · [Systematic Strategy Lab](https://github.com/Mingju-Zhang-CBS/systematic-strategy-lab)

**Does a signal still make sense inside a funded account?** I model delayed decisions, integer trades, fees, paid cash and dividend receivables. Four controls reconcile daily NAV before cost and execution-delay sensitivity is interpreted.

*Synthetic prices · portfolio accounting · execution assumptions*  
[Case study](projects/systematic-strategy-lab.md) · [Code](https://github.com/Mingju-Zhang-CBS/systematic-strategy-lab) · [Walkthrough](https://github.com/Mingju-Zhang-CBS/systematic-strategy-lab/blob/main/docs/WALKTHROUGH.md) · [Results](https://github.com/Mingju-Zhang-CBS/systematic-strategy-lab/blob/main/reports/demo/REPORT.md)

### 06 · [Defined-Outcome Research](https://github.com/Mingju-Zhang-CBS/defined-outcome-research)

**What does a buffer mean for a later buyer?** I connect public issuer terms to funded option claims, entry-time scenarios and fee conventions, keeping model marks separate from observed quotes.

*Public issuer terms + model scenarios · derivatives · funding*  
[Case study](projects/defined-outcome-research.md) · [Code](https://github.com/Mingju-Zhang-CBS/defined-outcome-research) · [Walkthrough](https://github.com/Mingju-Zhang-CBS/defined-outcome-research/blob/main/docs/WALKTHROUGH.md) · [Results](https://github.com/Mingju-Zhang-CBS/defined-outcome-research/blob/main/reports/demo/REPORT.md)

## Pricing foundations

### 07 · [Derivatives Pricing Lab](https://github.com/Mingju-Zhang-CBS/derivatives-pricing-lab)

**How do numerical error and hedge costs interact?** I connect analytical prices and Greeks to Monte Carlo variance reduction and common-path delta hedging. The study separates sampling uncertainty, model assumptions and the cost of more frequent trades.

*Mathematical finance · numerical methods · risk*  
[Case study](projects/derivatives-pricing-lab.md) · [Code](https://github.com/Mingju-Zhang-CBS/derivatives-pricing-lab) · [Walkthrough](https://github.com/Mingju-Zhang-CBS/derivatives-pricing-lab/blob/main/docs/WALKTHROUGH.md) · [Results](https://github.com/Mingju-Zhang-CBS/derivatives-pricing-lab/blob/main/reports/demo/REPORT.md)

## Research map

![From data to decisions](assets/research-map.svg)

The following are original method notes connecting prior learning and experience. They are not seven additional runnable implementations, republished employer projects or new empirical results.

- [Point-in-Time Financial Data](cases/financial-data-engineering.md)
- [Equity Signals and Model Validation](cases/equity-signal-research.md)
- [Financial Text and Event-Time Research](cases/financial-text.md)
- [Housing, Credit and Real-Estate Decisions](cases/housing-credit.md)
- [AI-Assisted Research Systems](cases/research-systems.md)
- [Trading and Inventory Risk](cases/trading-market-making.md)
- [Financial Products and Portfolio Decisions](cases/products-portfolio.md)

## Choose a reading route

### Quantitative Research

Start with [Financial Text](https://github.com/Mingju-Zhang-CBS/financial-text-validation) and [Financial ML](https://github.com/Mingju-Zhang-CBS/financial-ml-validation): data clocks, baselines, frozen selection and uncertainty. Add [Agentic Research](https://github.com/Mingju-Zhang-CBS/agentic-quant-research) for experiment engineering, or [Systematic Strategies](https://github.com/Mingju-Zhang-CBS/systematic-strategy-lab) for funded implementation. The synthetic studies establish process behavior; the real-data text result does not establish alpha.

### Data Science

Read [Financial Text](https://github.com/Mingju-Zhang-CBS/financial-text-validation), [Financial ML](https://github.com/Mingju-Zhang-CBS/financial-ml-validation) and the [offline research controller](https://github.com/Mingju-Zhang-CBS/agentic-quant-research) for source collection, keyed alignment, train-fitted features, comparable models and reproducible artifacts. These demonstrate research/data workflows; production serving and business A/B testing are outside their evidence.

### Trading and Product Research

Start with [Market Making](https://github.com/Mingju-Zhang-CBS/market-making-lab) for conditional values, inventory and simulated adverse selection; use [Defined Outcomes](https://github.com/Mingju-Zhang-CBS/defined-outcome-research) and [Pricing](https://github.com/Mingju-Zhang-CBS/derivatives-pricing-lab) for option economics, fees and model risk. Market-making results depend on an illustrative taker model; product marks are not executable quotes.

## Next research

- [Financial Text Validation](roadmap/financial-text-validation.md): implemented using public-domain official FOMC text and archived EUR/USD quotes; see the completed-study record and remaining extensions.
- [Defined-Outcome Research](roadmap/defined-outcome-research.md): implemented issuer-grounded scenarios; synchronized quotes, complete fund NAV replication and multi-period resets remain future work.

Both original briefs now have runnable first studies and separately labeled extensions. No competition entry, live execution or actual fund-return claim is implied.

## Evidence standard

Financial Text Validation uses real public Board text and archived FX references. Defined-Outcome Research combines issuer facts with modeled scenarios; five other studies use synthetic inputs or simulated paths. Read the complete report and assumptions before interpreting a metric. A valid factor is not an alpha, a synthetic policy ranking is not real profitability, and a local numerical benchmark is not exchange latency. Each project records its own source/data fingerprints and execution environment.

Development was AI-assisted. Personal implementation, public methods, library authorship and prior collaboration are distinguished in provenance notes. [Machine-readable content catalog](project-catalog.json).
