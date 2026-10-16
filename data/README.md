# Input data

These are the 8 prepared files the notebook needs in FAST_MODE. **Do not rename them.**

| File | Status | What it is |
| --- | --- | --- |
| `minute_local_only.csv` | required | one-minute bars (OHLC, trades, USD volume) |
| `hourly_local_only.csv` | required | 1,008 hour keys and the 48-of-60 coverage rule |
| `hourly_proxies_local_only.csv` | required | the eight proxies per hour |
| `hourly_benchmarks_local_only.csv` | required | QS, ES, PI, CRT25 per hour (quote age ≤ 60 s) |
| `hourly_benchmarks_age30_local_only.csv` | required | same with quote age ≤ 30 s |
| `qa_summary.json` | recommended | data-quality counts per market-day |
| `participant3_qa_summary.csv` | recommended | benchmark diagnostics per market-day |
| `participant3_sensitivity_age30_vs_60.csv` | recommended | 30 s vs 60 s comparison |

Source: Tardis.dev historical data (Bitfinex, Bitstamp, Coinbase; BTC/USD, ETH/USD; first day of each month, Jun–Dec 2019). Raw Tardis.dev files are not included.
