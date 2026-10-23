# Housing, Credit and Real-Estate Decisions

**Method note / background.**

**Question:** How do data engineering and model limits change an investment or credit conclusion?

The academic background includes housing portfolios, mortgage delinquency models and office-REIT comparisons. The private review identified both a large-data preparation layer and smaller analytical extracts. This original note explains the structure; original loan records, licensed rent observations, course instructions and investment submissions are not distributed.

## Data engineering before regression

A large mortgage file should be processed in chunks or with a query engine, selecting necessary columns and documenting filters before materializing an analytical table. Preserve observation counts through each step. Loan state, delinquency definition, reporting month and borrower attributes must refer to a consistent observation time. Multiple records from the same loan are not independent borrowers.

A housing portfolio index also needs a clear weighting convention. If hypothetical region weights are 60% and 40%, and their price changes are +4% and -2%, the fixed-weight portfolio change is `0.6*0.04 + 0.4*(-0.02) = 1.6%`. It is not the unweighted average of 1%. Rebalancing or missing regions would require a separate rule.

## Credit and real-estate modeling

A linear probability model is easy to inspect but can predict outside [0,1]. Classification, calibration, borrower grouping and later-period evaluation offer different diagnostics. A statistically useful association is not a causal effect or an underwriting decision rule.

For a REIT, equity return, de-levered return, accounting cash-flow proxy and local rent index answer different questions. Debt changes, geographic exposure weights, fiscal periods and reporting availability must be reconciled. A rent proxy is not a property-level cash-flow valuation, and a historical recommendation should not be presented as current investment advice.

## Skills and public evidence

This area demonstrates large-file processing, SQL-style extraction, joins, regression diagnostics and translating quantitative assumptions into a decision memo. Public runnable counterparts demonstrate [data/model validation](https://github.com/Mingju-Zhang-CBS/financial-ml-validation) and [account conventions](https://github.com/Mingju-Zhang-CBS/systematic-strategy-lab). No original large-sample performance claim is transplanted into these demonstrations.

## Limitations

Future public replication needs source-specific permission checks for loan, housing, rental and market data, as well as individual/group attribution. Public availability alone does not establish unrestricted redistribution. This page contains only newly written reasoning and invented arithmetic.

[Research directory](../README.md)
