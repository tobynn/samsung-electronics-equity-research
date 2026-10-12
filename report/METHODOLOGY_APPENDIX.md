# Methodology Appendix — Samsung Electronics

**Project valuation snapshot:** 2026-10-10. Existing 3Q26 consolidated revenue and operating profit figures are marked preliminary; do not infer net income or segment outcomes from them. See [`VALUATION_VINTAGE_POLICY.md`](../research/VALUATION_VINTAGE_POLICY.md) for the refresh protocol.

## 1. Why sector and segment decomposition matters

Samsung’s memory, foundry, devices, display and automotive operations have different cycles, capital intensity and earnings denominators. A consolidated peer average would mix peak memory earnings with structurally different businesses. SOTP is therefore the primary structure; DCF tests cash conversion and RIM tests return fade. Segment PER is only a cross-check and uses normalized earnings pools.

## 2. Peer rationale and exclusion discipline

| Candidate | Allowed role | Inclusion rationale | Why it is not a plug-in multiple |
|---|---|---|---|
| SK hynix | HBM/server DRAM operating and valuation anchor | Integrated DRAM/HBM, own fabs, CAPEX and cycle exposure | Memory concentration, customer/mix and earnings duration differ |
| Micron | DRAM/NAND cycle cross-check | Memory manufacturing, ASP, yield and inventory economics | Normalize product mix, cycle timing, geography and accounting |
| TSMC | Foundry process/utilization/capex benchmark | Leading-edge foundry economics | Scale, utilization and external customer mix differ materially |
| Apple/Xiaomi | DX demand and mix proxy | Device pricing and end-market demand | Different asset and software/ecosystem economics |
| LG Display | OLED cycle/operations benchmark | Panel utilization, customer and investment cycle | Scale, balance sheet, product mix and customer concentration differ |

Numeric peer inclusion requires comparable segment exposure, usable normalized earnings, synchronized market date/forecast period, consistent EV or equity denominator, and dated source metadata. If any gate fails, show the company only as an operating benchmark or demand proxy. Never mix EV/EBIT with PER into one median.

## 3. Memory scenario multiple architecture

The current 2027E memory EBIT allocation is HBM 26% at 9.0x; server DRAM 34% at 7.0x; client/mobile DRAM 22% at 4.5x; NAND 14% at 3.0x; other 4% at 2.5x. The weighted result is 6.23x. Those are analyst scenarios, not disclosed profits by product or proven fair-value coefficients.

A future change requires dated evidence across qualification/yield, customer concentration, margin and cash conversion, supply response, cycle duration and incremental ROIC. Higher forecast EBIT already captures shipment/mix gains; the multiple captures only residual risk, duration and capital-return differences. An HBM mix increase mechanically changes the weighted result, so no second company-wide premium is applied. See [`MEMORY_PREMIUM_FRAMEWORK.md`](../research/MEMORY_PREMIUM_FRAMEWORK.md).

## 4. Distinct business tests

- **Memory:** ASP/bit mix, inventory, utilization, depreciation, maintenance and growth capex; normalize through a full cycle.
- **Foundry/S.LSI:** node yield, external customer production, utilization, loss and capex payback; do not assign PER during losses.
- **DX:** MX premium mix and sell-through; VD/DA promotion and inventory; avoid demand proxies as valuation peers.
- **SDC:** mobile OLED customer concentration, utilization and new IT/auto lines’ capital returns.
- **Harman:** backlog-to-revenue conversion, software/content mix, margin and working capital.

## 5. Vintage controls

Use one market-close date for Samsung and peers; preserve the latest reported period, preliminary periods, forecast provider/date, FX, shares, cash/debt and non-controlling interests. Keep old vintages in the changelog. Bridge valuation change into: (a) actuals, (b) operating forecast, (c) peer data, and (d) valuation parameters. The file [`2026-10-10_actuals_and_assumptions.csv`](../data/processed/2026-10-10_actuals_and_assumptions.csv) is an input snapshot, not a live feed.

## Detailed controls

- [`Peer Selection Scorecard`](../research/PEER_SELECTION_SCORECARD.md)
- [`Company-Specific Framework`](../research/COMPANY_SPECIFIC_FRAMEWORK.md)
- [`Memory Valuation Framework`](../research/MEMORY_PREMIUM_FRAMEWORK.md)
- [`Valuation Vintage Policy`](../research/VALUATION_VINTAGE_POLICY.md)
