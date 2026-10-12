# Valuation Vintage Policy — Samsung Electronics

## 1. Scope and current freeze

This project is an equity research snapshot with a stated date of **2026-10-10** and reported actuals through **2Q26**, plus the company's **3Q26 preliminary revenue and operating-profit announcement**. Preliminary 3Q values are not audited segment results, net income, cash flow, or a substitute for the confirmed earnings release. They must remain explicitly labelled preliminary until official results are published.

The valuation inputs combine reported financials, analyst forecasts, market multiples, and scenario assumptions. Every refreshed version must state the same information cutoff for the stock price, share count, FX and peer data, and the latest information cutoff for reported actuals. Do not quietly roll forward only the target-company price while leaving peer multiples stale.

| Input | Current project label | Refresh / control |
|---|---|---|
| 2Q26 consolidated actuals | Reported, quarter ended 2026-06-30 | Reconcile release, earnings deck, DART filing, KRW bn/trillion units |
| 3Q26 consolidated sales / operating profit | Preliminary announcement; confirmed release expected in existing project calendar on 2026-10-29 | Keep net income, business segments, balance sheet, cash flow blank until confirmed |
| 2027E memory EBIT and product weights | Analyst scenario | Rebuild from latest volume, ASP, mix, cost, qualification and supply assumptions |
| Peer multiples | Cross-company market snapshot | Store date, market close, EPS period, source, currency, shares and adjustment policy per peer |
| Discount rates and terminal parameters | Analyst assumptions | Show sensitivity; don't update them merely because the share price moved |
| Shares, net cash/debt, non-controlling interest | Latest confirmed balance-sheet/capital data | Refresh corporate actions and equity bridge together |

## 2. Evidence labels

- **Reported**: filed financial statements / company-confirmed results.
- **Preliminary**: explicitly identified by company as preliminary; can support near-term run-rate context only.
- **Management outlook**: language from earnings presentation or call; quote the period and conditions.
- **Consensus**: named provider, retrieval date, forecast period; not silently substituted for the analyst case.
- **Analyst assumption**: explicit driver such as margin, utilization, multiple, WACC, cost of equity, terminal growth or ROE.
- **Scenario**: alternative case; never presented as a reported fact.

## 3. Monthly/quarterly refresh sequence

1. Match DART filing and official IR release; reconcile consolidated versus segment and quarterly versus year-to-date figures.
2. Record earnings date, information cutoff, stock/peer prices, FX, share count, cash and debt date.
3. Replace actuals without overwriting prior vintages; retain old inputs in a dated snapshot/changelog.
4. Bridge changes in revenue and EBIT by HBM/server DRAM/client DRAM/NAND/foundry/S.LSI/DX/SDC/Harman where disclosed; isolate unallocated corporate items.
5. Update HBM generation qualification and shipments, DRAM/NAND ASP and bit supply, utilization, inventory, CAPEX, depreciation and cash conversion.
6. Rebuild SOTP/DCF/RIM/Segment PER. Attribute valuation movement to actuals, operating forecast, peer data, and valuation parameters separately.
7. Reconcile valuation per share to common-equity value, share count, net cash/debt, minority interests, and treasury shares.

## 4. Sources

- [Samsung Electronics IR results](https://www.samsung.com/global/ir/financial-information/earnings-release/)
- [Samsung earnings presentations](https://www.samsung.com/global/ir/reports-disclosures/earnings-release/)
- [DART](https://dart.fss.or.kr/)
- [KRX KIND](https://kind.krx.co.kr/)

All time-sensitive inputs need a direct filing/IR link and a date. The source registry is the record of what was known at each cutoff.
