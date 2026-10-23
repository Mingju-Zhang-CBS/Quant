# Financial Text and Event-Time Research

**Method note / background.**

**Question:** What information does text add, and when was that information available?

The background combines financial sentiment, firm-day aggregation, document topics, text similarity and event-return analysis. Several source notebooks are group work and use restricted news or transcript data. This page is a new methods explanation, not a release of those corpora or submissions.

## A small independent example

Consider three hypothetical articles about one firm, including a syndicated duplicate. Counting all three as independent evidence overweights the repeated story. The pipeline should deduplicate at an explicit article identity/text level, establish the firm mapping, retain the publication timestamp and aggregate only the unique eligible documents into the firm-time observation.

For a toy lexicon count, two positive and one negative matched tokens over 100 eligible tokens give `(2-1)/100 = 0.01`. This numerical score does not identify causality or the market's interpretation. Financial vocabulary, negation, boilerplate, coverage and document length can change the meaning of a count.

## Complete research chain

Start with the prediction or event question. Define publication time and the earliest modeled decision session. Fix preprocessing, vocabularies, topic models and thresholds using development only. Compare a price-only baseline, a text-only model and a combined model on the same eligible observations. Group duplicated or strongly related documents so they cannot leak across the evaluation boundary. Distinguish return direction, probability quality and economic returns after execution assumptions.

A fall in year-to-year cosine similarity can indicate unusual language, but it can also reflect changing document structure. An event chart is descriptive unless the design supports stronger identification. A later generated summary may carry information unavailable at the historical date; provenance matters even when the summary sounds plausible.

## Skills and next study

This area demonstrates NLP preprocessing, entity mapping, sparse representations, event-time alignment, model ablation and uncertainty. The [planned text-validation brief](../roadmap/financial-text-validation.md) turns these lessons into a specific future experiment. It is explicitly planned, with no new score or implemented model claimed.

## Limitations and source boundaries

The illustrative sentence counts are synthetic. Original Reuters/RavenPack text, transcript files, teacher frameworks and group contributions remain outside this portfolio. A source notebook with a saved dependency error is not treated as a successfully reproduced project. The new [ML validation study](https://github.com/Mingju-Zhang-CBS/financial-ml-validation) provides runnable evidence of train-only preprocessing and evaluation principles.

[Research directory](../README.md)
