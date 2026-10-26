# Statistical learning foundations

**Background method note.** Undergraduate MATH446 work informs the validation questions used elsewhere in this portfolio. The original assignments, group versions, private score files and saved test results are excluded.

## What the earlier exercises teach

Life-expectancy data require a clear estimand: a random country/year split may answer interpolation across known countries, while a future-year forecast needs chronological separation. Backward filling can import future observations. The appropriate split follows the question.

MNIST work connects scaling, PCA and classification. Fitting transforms within each fold is useful, but a test set repeatedly consulted for feature or class-weight choices becomes part of development. Re-running the same split does not restore independence.

Dry Bean offers an interpretable feature-lineage example. Area and equivalent diameter have a deterministic geometric relationship, and other shape variables may also be derived from related measurements. The inspected Area-regression version already excludes equivalent diameter and convex area; the remaining predictors still require a dependency audit. Do not diagnose a feature as present merely because it exists in the source dataset.

## A disciplined new example

The [UCI Dry Bean dataset](https://archive.ics.uci.edu/dataset/602/dry%2Bbean%2Bdataset) is distributed under CC BY 4.0. A future independent example should cite the dataset authors, declare classification versus derived-target regression, map feature dependencies, fit preprocessing inside training and reserve a test set before comparing models. This note publishes no new model score and is not an additional flagship study.

These foundations connect directly to [financial model validation](https://github.com/Mingju-Zhang-CBS/financial-ml-validation): selection discipline matters more than transporting an attractive classroom accuracy into a new claim.

[Directory](../README.md)
