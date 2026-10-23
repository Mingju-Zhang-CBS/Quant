# Planned research: Financial Text Validation

**Status: design brief only. No new model score, competition entry or implemented text pipeline is claimed.**

## Research question

How much incremental predictive information does text provide beyond price history, and how sensitive is that conclusion to time alignment and evaluation design?

## Candidate benchmark and access

[XForecast](https://arxiv.org/abs/2610.16131) is a candidate historical benchmark combining financial time series and paired text. Its paper describes four-week-ahead stock-movement prediction, training on 2019–2022 and evaluation on 2023. The [competition timeline](https://www.kaggle.com/competitions/xforecast-challenge-kdd/overview/how-to-submit) belongs to a completed 2026 challenge; it is not described as an open future competition.

Before execution, record exact input version, task schema, target construction, text provenance, redistribution permission, scoring-weight availability and any prior exposure to evaluation labels. A paper's license does not automatically license the data. Users obtain permitted data themselves. No news corpus, secret, original course Reuters/RavenPack data or account credentials are packaged.

If lawful inputs or required definitions are unavailable, mark the real-data experiment blocked and retain the design; do not substitute fabricated benchmark results. Synthetic interface checks can be labeled separately.

## Baselines and predeclared comparisons

Use the same eligible observations for a majority baseline, price-only logistic model, price-only gradient-boosted model, text-only TF-IDF/logistic model and a combined price/text model. Fit imputation, scaling, vocabulary and selection inside development. Select from one small registered parameter grid, retain all attempted configurations and freeze the choice before evaluating 2023. No paid LLM or new pretrained-language-model tuning is required for the first study.

Keep official train/evaluation boundaries. Within training, use chronological development folds and purge targets whose documented four-week end reaches a later fold. Deduplicate syndicated/near-identical documents and retain an issuer/date group key. A text timestamp or generated summary that carries later knowledge cannot be relabeled point-in-time simply because the associated price date is historical.

## Measurements

Implement the official weighted hit-rate only when its exact formula and required weights are available. Otherwise report clearly named unweighted accuracy or another explicitly defined proxy, never an official score. Also report Brier/log loss, group performance, coverage, runtime and paired date-block uncertainty in incremental performance. Classification accuracy is not trading P&L.

Primary contrasts are combined versus price-only and text-only versus the simple baseline. Report missing-data exclusions and performance by issuer/date period without selecting a new model from those outcomes. Compare at least the selected model and the fixed baseline on the same rows.

## Deliverables and acceptance

The future implementation must include an input/data-rights sheet, frozen split manifest, parameter/search log, aligned predictions, official-or-proxy scorer tests, ablation table, uncertainty plot and research judgment. Known label construction and publication timing are prerequisites for a forward claim. The conclusion may be that text does not improve the baseline.

## Current competition context

As checked on October 23, 2026, XForecast is a historical benchmark. [FinReason Cup](https://github.com/The-FinAI/IEEE-bigdata-cup) is a separate organizer-hosted financial-agent benchmark whose Task 1/3 system deadlines are October 25, 2026, 23:59 AoE; Task 2 had separate earlier action deadlines. It is recorded as an adjacent benchmark, not a commitment to compete or a Kaggle event. Recheck official rules and status before any future use.
