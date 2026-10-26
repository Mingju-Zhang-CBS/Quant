# Equity Signals and Model Validation

**Method note / background.**

**Question:** Does a signal survive exposure controls and a defensible model-selection process?

The academic research background includes rolling factor exposures, residual returns, event studies and regularized cross-sectional prediction. These are related but distinct experiments. This original method note connects them without redistributing classroom submissions, teacher utilities, group code or licensed financial data.

## From returns to a testable question

Suppose an asset returns 1.2%, a market factor returns 0.8%, and its previously estimated beta is 1.2. With a zero intercept for illustration, the residual return is `0.012 - 1.2*0.008 = 0.0024`, or 24 basis points. Estimating beta using later observations would change the information set. A residual is a model-dependent unexplained return, not automatically a tradable alpha.

An event study asks about return behavior around a dated event. It needs an estimation window, a tradable event timestamp, an event window and treatment of overlapping events. A prediction model instead chooses features and regularization before evaluating later targets. Their statistics should not be pooled into a single success story.

## WLS, Ridge and Lasso

WLS changes observation weights, Ridge penalizes squared coefficients and Lasso promotes sparsity. Weights, imputation, scaling and hyperparameters must be fitted or selected within development. Nested or rolling evaluation must keep later labels outside selection. Comparing many signals also creates multiple-testing and research-search uncertainty beyond an individual coefficient's standard error.

## Skills and public route

This area demonstrates econometrics, feature definitions, exposure control, temporal validation and qualified interpretation. The [financial ML repository](https://github.com/Mingju-Zhang-CBS/financial-ml-validation) supplies a runnable model-comparison example; the [agent workflow](https://github.com/Mingju-Zhang-CBS/agentic-quant-research) makes freezing and a failed confirmation result visible. The [strategy account](https://github.com/Mingju-Zhang-CBS/systematic-strategy-lab) shows the additional work required to turn a score into holdings and net returns.

## Boundaries

The new [equity extension](https://github.com/Mingju-Zhang-CBS/financial-ml-validation/blob/main/docs/EQUITY_RESEARCH.md) implements these distinctions with eight explicit features, lagged risk estimates, five inner time windows and ten outer years. The source audit identified full-sample weight clipping, an ambiguous label clock, future-assisted identifier resolution and a reused period chart. The independent implementation uses training-only caps, dated identity quarantine, explicit label availability and period-keyed outputs. Those repairs do not retroactively validate saved course results.

Historical class labels and outcomes have already been inspected. A fresh directory or reshuffle does not recreate an unseen test. The local catalog records group attribution, unexecuted notebook versions and the distinction between lecture frameworks and new public code. This page reports methods and learning, not new results from the original data.

[Research directory](../README.md)
