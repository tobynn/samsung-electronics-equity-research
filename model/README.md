# Model Guide

`Samsung_Electronics_equity_research.xlsx` is the auditable model. Blue cells are input assumptions; formula cells are intentionally left uncolored.

| Sheet | Purpose | Primary update trigger |
|---|---|---|
| Summary | Decision dashboard and valuation range | New share price or model output |
| Actuals & Sources | Quarterly actuals, balance sheet and source links | Earnings release |
| SOTP | Segment EBIT and valuation multiples | Segment outlook or peer rerating |
| DCF | Free-cash-flow cross-check | Cash flow / WACC change |
| RIM | Equity-return downside framework | Equity, ROE or cost of equity change |
| Peer PER | Cycle-normalised EPS cross-check | Memory pricing / peer multiple change |
| Audit | Formula and evidence status | Every update |


## Valuation input interpretation

The current product-level memory multiples (HBM 9.0x, server DRAM 7.0x, client/mobile DRAM 4.5x, NAND 3.0x, other 2.5x) are scenario inputs. The weighted 6.23x result is arithmetic, not an empirically calibrated fair multiple. See `research/MEMORY_PREMIUM_FRAMEWORK.md` for evidence gates and double-count controls. `research/PEER_SELECTION_SCORECARD.md` distinguishes direct segment peers from operating benchmarks and demand proxies; `research/VALUATION_VINTAGE_POLICY.md` governs date alignment.
