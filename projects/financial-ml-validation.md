# Financial ML Validation

**Question:** Do apparently useful financial features survive a realistic information clock and honest model selection?

[Code](https://github.com/Mingju-Zhang-CBS/financial-ml-validation) · [Equity methods](https://github.com/Mingju-Zhang-CBS/financial-ml-validation/blob/main/docs/EQUITY_RESEARCH.md) · [Treasury result](https://github.com/Mingju-Zhang-CBS/financial-ml-validation/blob/main/reports/real/REPORT.md) · [Tests](https://github.com/Mingju-Zhang-CBS/financial-ml-validation/tree/main/tests)

## Equity: selection, risk adjustment and prediction

The independent extension connects historical month-end selection, eight explicit price/liquidity features, a lagged 252-session factor fit and WLS/weighted Ridge/weighted Lasso. Observation, decision, implementation, return-end and label-availability dates are separate fields. Feature clipping, standardization and inverse-variance weight caps are fitted only in training. Five expanding inner windows select regularization inside each preceding four-year window; ten historical outer years span 2016–2025.

The [executed synthetic fixture](https://github.com/Mingju-Zhang-CBS/financial-ml-validation/blob/main/reports/equity-fixture/REPORT.md) checks this chain without redistributing licensed records. CRSP inputs, security-level predictions and derived real-data results remain private pending applicable publication rights. The current historical factor vintage does not establish complete point-in-time availability.

Price-shock event windows are explicitly price-defined, rather than earnings or news events. A fixed eight-feature test family retains failed or unevaluable hypotheses. Quintile diagnostics keep raw stock returns, residual outcomes and costed target-weight turnover distinct; they are not funded NAVs or proven alpha.

## Treasury: a negative result worth keeping

The separate public-data experiment uses 9,005 H.15 Treasury observations and compares logistic regression, LightGBM and CatBoost with training-fitted probability baselines. Model-selection labels are purged before historical confirmation. The selected CatBoost/dynamics comparator has confirmation log loss 0.71866 versus 0.70915 for climatology; its paired gain is −0.00951, with a 63-session 95% interval [−0.01688, −0.00297]. It does not earn promotion over the baseline.

![Treasury uncertainty](../assets/financial-ml-validation-real-result.png)

Alternative models and block-length sensitivity remain visible without changing the selection after confirmation. Reference-yield signs are not bond total returns. Current-vintage revisions and missing historical release clocks limit interpretation.

## Skills and contribution

The evidence demonstrates econometric modeling, security/time joins, train-only transforms, nested temporal selection, baseline judgment and dependent inference. Public-method implementation, tests and documentation were AI-assisted; teacher frameworks, group submissions and licensed data are excluded. Individual review is separate from automated execution. [Contribution boundaries](https://github.com/Mingju-Zhang-CBS/financial-ml-validation/blob/main/docs/PROVENANCE.md).

[Research directory](../README.md)
