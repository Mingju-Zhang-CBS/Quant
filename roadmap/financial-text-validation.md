# Financial Text Validation: completed first study and next extensions

**Status: implemented, real public-data study.** [Repository](https://github.com/Mingju-Zhang-CBS/financial-text-validation) · [Recorded report](https://github.com/Mingju-Zhang-CBS/financial-text-validation/blob/main/reports/demo/REPORT.md).

The original brief proposed testing whether text adds information beyond prices, with XForecast as a candidate subject to data-rights verification. The implemented first study answers that question on **official FOMC statements and archived H.10 EUR/USD references**. The Board's explicit public-domain reuse policy and non-revised release archive make the data rights and price-availability clocks inspectable. Third-party news rights for an equity benchmark were not assumed.

The task is not interchangeable with XForecast: one currency, policy events, delayed reference-quote entry and 20 subsequent observations. No official competition metric, entry or score is claimed. The earlier competition was historical; its state does not establish permission to redistribute news.

## Completed evidence

- 128 official statements; 4,041 first-vintage quote observations; retained train/validation/confirmation events 60/24/42.
- Five families: train-prior, price logistic, price gradient boosting, text logistic and fusion. Eleven development fits and frozen confirmation choices.
- Primary fusion log-loss advantage versus selected price: -0.00029, paired interval [-0.00280, 0.00211]. Results, uncertainty and unfavorable findings remain visible.
- Offline packaged snapshot, English methods and worked event, behavioral leakage checks, source fingerprints and CI.

## Remaining extensions, not completed claims

1. Extend to a separately licensed multi-currency or issuer-level population and a new locked period.
2. Establish original text vintages or quantify editorial corrections; current historical statement pages are a disclosed residual limitation.
3. Compare economic text-difference features and richer calibration with a budget fixed before seeing new confirmation data.
4. Use an equity/news benchmark only after permission, timestamps, target definitions and official scoring inputs have been verified separately.

Reusing the now-exposed 2020–2024 period for tuning must be labeled further historical development, not a new untouched holdout.
