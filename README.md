# USDCAD 1w OHLCV Forex Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-1_294_rows-blue)](https://getdata.finance/datasets/usdcad) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/usdcad)

### -> [**Download the full USDCAD dataset on getdata.finance**](https://getdata.finance/datasets/usdcad)

**USDCAD 1w OHLCV forex historical data** — ultra high-quality 1w OHLCV for **US Dollar / Canadian Dollar**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 1w OHLCV** for **US Dollar / Canadian Dollar** (Forex)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1w`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/usdcad) · **1,294** `1w` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1w` sample updated in sync

> **Sample on GitHub** · `USDCAD_1w.csv` (106 rows, `2024-08-29` -> `2026-09-03`, 11.96 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/usdcad)** — **1,294** `1w` rows (full `1m`: 9,133,625), **11 timeframes**, `2001-11-22` -> `2026-09-03`.

## Download sample

**[USDCAD_1w.csv](https://github.com/getdata-finance/usdcad-1w-ohlcv-forex-historical-data/blob/main/USDCAD_1w.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/usdcad-1w-ohlcv-forex-historical-data/main/USDCAD_1w.csv)) · [GitHub Releases](https://github.com/getdata-finance/usdcad-1w-ohlcv-forex-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/usdcad-1w-ohlcv-forex-historical-data/](https://getdata-finance.github.io/usdcad-1w-ohlcv-forex-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/usdcad](https://getdata.finance/datasets/usdcad)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/usdcad))** |
|---|--:|---|
| Instrument | US Dollar / Canadian Dollar · Forex | US Dollar / Canadian Dollar · Forex |
| Timeframes | `1w` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1w rows | 106 | **1,294** |
| Size | 11.96 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/usdcad) |
| Period | `2024-08-29` -> `2026-09-03` | `2001-11-22` -> `2026-09-03` |
| File | `USDCAD_1w.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/usdcad) |
| Coverage report | — | [USDCAD coverage](https://getdata.finance/coverage/usdcad) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1w` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/usdcad)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `1w` sample · [getdata.finance](https://getdata.finance/datasets/usdcad) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `1w` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`USDCAD_1w.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2024-08-29T00:00:00+00:00 | 1.34875 | 1.35655 | 1.34604 | 1.35092 | 982240.28241 |
| 2024-09-05T00:00:00+00:00 | 1.35092 | 1.36332 | 1.34656 | 1.35902 | 1162172.04414 |
| 2024-09-12T00:00:00+00:00 | 1.35902 | 1.36215 | 1.35383 | 1.36071 | 1081364.53055 |
| 2024-09-19T00:00:00+00:00 | 1.36071 | 1.36461 | 1.34327 | 1.34972 | 1179506.64108 |
| 2024-09-26T00:00:00+00:00 | 1.34972 | 1.35547 | 1.34707 | 1.35196 | 1280285.30931 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-08-06T00:00:00+00:00 | 1.40132 | 1.40407 | 1.39002 | 1.39328 | 728011.71326 |
| 2026-08-13T00:00:00+00:00 | 1.39328 | 1.39504 | 1.37938 | 1.38054 | 763551.39152 |
| 2026-08-20T00:00:00+00:00 | 1.38054 | 1.38935 | 1.37248 | 1.38748 | 870181.46181 |
| 2026-08-27T00:00:00+00:00 | 1.38748 | 1.39398 | 1.38341 | 1.38453 | 970698 |
| 2026-09-03T00:00:00+00:00 | 1.38453 | 1.3872 | 1.37596 | 1.37783 | 760717 |

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

df = pd.read_csv('USDCAD_1w.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('USDCAD_1w.csv', parse_dates=['datetime'])
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

df = pd.read_csv('USDCAD_1w.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1W')
print(pf.stats())
```

## Download full data

The complete **USDCAD** archive on **[getdata.finance](https://getdata.finance/datasets/usdcad)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **1,294** rows at `1w`, plus all other timeframes in the same ZIP.

**[-> Get the full USDCAD dataset on getdata.finance](https://getdata.finance/datasets/usdcad)**

---
*GetData · USDCAD 1w OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/usdcad)*
