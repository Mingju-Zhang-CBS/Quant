# Point-in-Time Financial Data

**Method note / background.**

**Question:** What did an investor actually know at a historical decision time?

Academic work with security identifiers, accounting data and financial panels made data availability a central research concern. This note explains the method with newly written illustrative examples. It does not distribute WRDS/CRSP/Compustat records or the supplied course framework, and it does not claim the complete classroom pipeline was independently authored.

## Follow one observation

A company closes its fiscal year on December 31. It files an original revenue fact of 100 on February 15 and an amendment of 105 on May 1. A March 1 historical decision can use 100, not 105. Filtering on fiscal year alone leaks the amendment. The valid operation first filters filing timestamps to the decision cutoff, then resolves versions within the correct accounting definition and reporting period.

Security mapping is another dated relationship. A ticker string is not a permanent firm key. Mapping tables should have explicit validity intervals; overlapping or missing intervals belong in an exception report. A successful database merge does not establish that its economic join was correct.

## Implementation logic to preserve

Define the observation key and units before joining. Check duplicates and unmatched keys before and after a merge. Resolve publication time separately from reporting-period end. Use lagged market values where a portfolio weight requires prior information. Keep coverage diagnostics and identify records excluded by filters. Verify that a later data revision does not change a historical output when its as-of snapshot is held fixed.

## Skills and evidence

This area demonstrates relational data modeling, timestamp reasoning, SQL/Python transformations, exception handling and financial measurement. The [public research workflow](https://github.com/Mingju-Zhang-CBS/agentic-quant-research) demonstrates strict panel contracts; the [ML study](https://github.com/Mingju-Zhang-CBS/financial-ml-validation) demonstrates exact label joins. Neither is presented as a reproduction of the licensed historical source database.

The [SEC EDGAR API documentation](https://www.sec.gov/search-filings/edgar-application-programming-interfaces) is a useful public route for future filing research. Historical availability must still be reconstructed from individual filing records; a current aggregate is not automatically a point-in-time history.

## Limits

The independent [CIZ adapter](https://github.com/Mingju-Zhang-CBS/financial-ml-validation/blob/main/ml_validation/equity/data.py) records source units, monthly historical identity filters, duplicate conflicts and return-duration flags. Backward filling or selecting a latest restated record may fit a descriptive current-vintage analysis, but cannot silently become an as-of historical decision. The adapter does neither. CIZ total returns are not supplemented a second time with dividends or delisting returns.

The numbers above are invented teaching values. No new empirical return result is reported. Templates, collaborators, vendor permissions and personal implementation need separate attribution before any historical source can become a public artifact.

[Research directory](../README.md)
