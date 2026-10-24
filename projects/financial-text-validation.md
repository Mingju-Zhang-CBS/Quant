# Financial Text Validation | Real public-data research

**Question:** Does FOMC statement text improve subsequent EUR/USD direction forecasts beyond publication-aware price history?

I implemented an official-source collector, first-vintage quote reconstruction, event-time alignment, trained text/numeric transformations, five model families and paired uncertainty. The experiment uses 128 statements and 4,041 reference observations, with 42 retained historical confirmation events.

The primary comparison is log-loss reduction, validation-selected price minus fusion: **-0.00029**, 95% paired event-block interval **[-0.00280, 0.00211]**. The complete conclusion, controls and small-sample limitations remain in the report; no trading profitability or official benchmark score is implied.

[Code](https://github.com/Mingju-Zhang-CBS/financial-text-validation) · [Walkthrough](https://github.com/Mingju-Zhang-CBS/financial-text-validation/blob/main/docs/WALKTHROUGH.md) · [Results](https://github.com/Mingju-Zhang-CBS/financial-text-validation/blob/main/reports/demo/REPORT.md)

## What to inspect

- Data rights: Board policy permits reuse of its public-domain information with attribution; no commercial news corpus or government logo is included.
- Timing: observation and weekly release dates differ. Inputs must already be released; labels not public across a later split are purged.
- Modeling: price logistic/gradient controls, TF-IDF with preserved negation, feature fusion, fixed settings and identical event rows.
- Evidence: source/data hashes, eleven development fits, frozen selection, keyed probabilities, bootstrap contrasts, calibration, all years and predetermined stresses.

The task differs from the earlier XForecast candidate design: different population, reference quotes and target definition. It is a standalone official-source study, not an official-score reproduction. Existing academic text work remains separately attributed; no original course/group/employer code or data was migrated. Development was AI-assisted.
