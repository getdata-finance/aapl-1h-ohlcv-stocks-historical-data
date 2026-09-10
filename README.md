# AAPL 1h OHLCV US stocks Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-21_991_rows-blue)](https://getdata.finance/datasets/aapl) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/aapl)

### -> [**Download the full AAPL dataset on getdata.finance**](https://getdata.finance/datasets/aapl)

**AAPL 1h OHLCV stocks historical data** — ultra high-quality 1h OHLCV for **Apple**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 1h OHLCV** for **Apple** (US stocks)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1h`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/aapl) · **21,991** `1h` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1h` sample updated in sync

> **Sample on GitHub** · `AAPL_1h.csv` (876 rows, `2026-03-10` -> `2026-09-08`, 83.82 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/aapl)** — **21,991** `1h` rows (full `1m`: 636,557), **11 timeframes**, `2011-05-09` -> `2026-09-08`.

## Download sample

**[AAPL_1h.csv](https://github.com/getdata-finance/aapl-1h-ohlcv-stocks-historical-data/blob/main/AAPL_1h.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/aapl-1h-ohlcv-stocks-historical-data/main/AAPL_1h.csv)) · [GitHub Releases](https://github.com/getdata-finance/aapl-1h-ohlcv-stocks-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/aapl-1h-ohlcv-stocks-historical-data/](https://getdata-finance.github.io/aapl-1h-ohlcv-stocks-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/aapl](https://getdata.finance/datasets/aapl)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/aapl))** |
|---|--:|---|
| Instrument | Apple · US stocks | Apple · US stocks |
| Timeframes | `1h` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1h rows | 876 | **21,991** |
| Size | 83.82 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/aapl) |
| Period | `2026-03-10` -> `2026-09-08` | `2011-05-09` -> `2026-09-08` |
| File | `AAPL_1h.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/aapl) |
| Coverage report | — | [AAPL coverage](https://getdata.finance/coverage/aapl) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1h` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/aapl)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `1h` sample · [getdata.finance](https://getdata.finance/datasets/aapl) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `1h` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`AAPL_1h.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-10T19:00:00+00:00 | 261.21 | 261.5 | 260.22 | 260.68 | 22629 |
| 2026-03-11T13:00:00+00:00 | 260.68 | 261.6 | 259.74 | 260.89 | 8020 |
| 2026-03-11T14:00:00+00:00 | 260.89 | 261.75 | 259.17 | 260.36 | 20925 |
| 2026-03-11T15:00:00+00:00 | 260.36 | 260.59 | 259.48 | 260.23 | 16427 |
| 2026-03-11T16:00:00+00:00 | 260.23 | 260.82 | 259.76 | 260.33 | 11954 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-08T15:00:00+00:00 | 315.83 | 316.64 | 315.58 | 315.94 | 7066 |
| 2026-09-08T16:00:00+00:00 | 315.94 | 316.1 | 315.34 | 315.81 | 4896 |
| 2026-09-08T17:00:00+00:00 | 315.81 | 316.42 | 315.63 | 315.89 | 3885 |
| 2026-09-08T18:00:00+00:00 | 315.89 | 316.62 | 314.77 | 315.38 | 5008 |
| 2026-09-08T19:00:00+00:00 | 315.38 | 316.5 | 315.23 | 316.18 | 6645 |

## Schema

| Column | Description |
| --- | --- |
| `datetime` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
datetime,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('AAPL_1h.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('AAPL_1h.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)

class PandasData(bt.feeds.PandasData):
    params = (('datetime', None), ('open', 'open'), ('high', 'high'),
              ('low', 'low'), ('close', 'close'), ('volume', 'volume'))

cerebro = bt.Cerebro()
cerebro.adddata(PandasData(dataname=df))
# cerebro.addstrategy(YourStrategy)
# cerebro.run()
```

### vectorbt

```python
import pandas as pd
import vectorbt as vbt

df = pd.read_csv('AAPL_1h.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1h')
print(pf.stats())
```

## Download full data

The complete **AAPL** archive on **[getdata.finance](https://getdata.finance/datasets/aapl)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **21,991** rows at `1h`, plus all other timeframes in the same ZIP.

**[-> Get the full AAPL dataset on getdata.finance](https://getdata.finance/datasets/aapl)**

---
*GetData · AAPL 1h OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/aapl)*
