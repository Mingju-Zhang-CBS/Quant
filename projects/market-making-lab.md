# Market Making Lab

**Question:** When customers can reject a quote, how do spread capture, fills, inventory and adverse selection trade off?

[Code](https://github.com/Mingju-Zhang-CBS/market-making-lab) · [Methods](https://github.com/Mingju-Zhang-CBS/market-making-lab/blob/main/docs/METHODS.md) · [Executed study](https://github.com/Mingju-Zhang-CBS/market-making-lab/blob/main/reports/demand/REPORT.md) · [Tests](https://github.com/Mingju-Zhang-CBS/market-making-lab/tree/main/tests)

## One mechanism, a complete account

A finite-state binary contract is valued by dynamic programming and independently checked by Monte Carlo. Three fixed quote rules share paths, cash, collateral, inventory limits and fees. Each accepted fill changes cash and inventory; terminal settlement reconciles to spread capture, inventory mark changes and fees. Markout is measured after the trade and cannot influence its quote.

## Demand changes the conclusion

The extension assigns uninformed customers random reservation prices. A quoted side must satisfy the reservation price to trade. Three widths, three informed fractions, three policies and three fixed seeds produce 108 declared scenarios, including the legacy price-insensitive baseline. Every environment uses 1,000 common paths of 100 steps; paired intervals and replication seeds remain visible.

In the primary-seed, 25%-informed, width-0.04 environment, inventory-plus-uncertainty quotes have mean simulated P&L −0.1157 and fill rate 11.75%, versus 0.0473 and 22.31% for fixed spread. Their lower worst-5% loss measure comes with reduced activity and adverse selection. The original wider-quote mean ranking reverses in this scenario; no policy is declared universally best.

All reservation distributions and order-flow parameters are assumptions, not market calibration. There is no real queue, latency, competition score or proven live profitability.

## Skills and contribution

The study demonstrates conditional expectations, risk constraints, ledger reconciliation, common-random-number experiments, paired inference and retention of unfavorable results. Code and documentation were AI-assisted. The public simulation is distinct from the private Akuna competition experience. [Provenance](https://github.com/Mingju-Zhang-CBS/market-making-lab/blob/main/docs/PROVENANCE.md).

[Research directory](../README.md)
