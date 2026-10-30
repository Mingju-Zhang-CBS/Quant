# From Classroom Questions to Market Research

Coursework is a source of questions, not a substitute for a publishable research result. Public implementations here reconstruct methods independently; group submissions, licensed extracts, lecture figures and case text remain private.

| Learning thread | Public destination | What must change before drawing a market conclusion |
|---|---|---|
| GMI policy views and calendar trades | [Macro Rates Research](https://github.com/Mingju-Zhang-CBS/macro-rates-research) | Map effective policy dates into monthly-rate contracts; separate scenarios, market pricing and risk premia; reconcile cash and costs |
| GMI Treasury risk and PCA | [Curve risk report](https://github.com/Mingju-Zhang-CBS/macro-rates-research/blob/main/reports/curve/REPORT.md) | Estimate risk only on prior windows, age the positions, reprice them, retain hedge residuals and source-vintage limitations |
| SIS intraday momentum | [Execution methods](https://github.com/Mingju-Zhang-CBS/systematic-strategy-lab/blob/main/docs/INTRADAY_RESEARCH.md) | Separate signal and fill clocks, handle incomplete sessions, quote capacity, borrowing and failed exits |
| SIS carry and momentum | [Systematic Strategy Lab](https://github.com/Mingju-Zhang-CBS/systematic-strategy-lab) | Distinguish funding carry, futures curves and realized returns; retain costs, delivery boundaries and negative comparisons |
| SIS statistical arbitrage and asset-pricing ML | [Financial ML Validation](https://github.com/Mingju-Zhang-CBS/financial-ml-validation) | Require economic interpretation, historical identity, label isolation and comparisons against simple controls |

## FX carry and protection: the next bounded extension

**Question:** how much carry remains after consistent currency quotation, funding and an explicitly paid tail hedge?

If `S` is quote currency per unit of base currency, the simple inverse return is `-R/(1+R)`, not `-R`. A positive average in both quoted directions can arise from nonlinear arithmetic and different numeraires; it is not a free round-trip profit. Spot appreciation, deposit accrual and forward points must remain separate. National policy rates are not executable borrowing and lending quotes.

The next design will compare an unhedged currency basket, a predeclared risk-scaled version and a protective-option overlay. It requires synchronized spot and forward observations, compatible tenors/day counts, funding spreads and option bid/ask/expiry evidence. Public spot/rate series can support an economic diagnostic; without those trading inputs, they cannot establish executable carry or cheap crash insurance. FX-option pricing can extend the existing derivatives lab, keeping premiums, delta hedge, numeraire and financed notional consistent. No new repository or claimed empirical result exists for this roadmap item.

## Sovereign and crisis cases

Keep a concise decision framework: what is priced, the legal claim and currency, refinancing needs, recovery scenarios, catalysts, loss budget and evidence that would invalidate the view. A spread is not a physical default probability without recovery and pricing assumptions. Course case material is not redistributed, and a persuasive historical narrative is not presented as a backtested rule.

## Contribution and evidence

Mingju Zhang selected these research directions. Public code, experiments and writing were developed with AI assistance. Historical coursework includes collaborators and teaching frameworks; that contribution boundary stays in private evidence records. New code and results have their own source fingerprints, frozen protocols and tests. They are not the original submitted assignment or an employer system.
