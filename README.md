# GER30 30m OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-153_083_rows-blue)](https://getdata.finance/datasets/ger30) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/ger30)

### -> [**Download the full GER30 dataset on getdata.finance**](https://getdata.finance/datasets/ger30)

**GER30 30m OHLCV index historical data** — ultra high-quality 30m OHLCV for **DAX 40 (GER30)**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 30m OHLCV** for **DAX 40 (GER30)** (Index)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`30m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/ger30) · **153,083** `30m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `30m` sample updated in sync

> **Sample on GitHub** · `GER30_30m.csv` (5,031 rows, `2026-03-26` -> `2026-09-25`, 454.01 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/ger30)** — **153,083** `30m` rows (full `1m`: 2,329,742), **11 timeframes**, `2008-09-10` -> `2026-09-25`.

## Download sample

**[GER30_30m.csv](https://github.com/getdata-finance/ger30-30m-ohlcv-index-historical-data/blob/main/GER30_30m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/ger30-30m-ohlcv-index-historical-data/main/GER30_30m.csv)) · [GitHub Releases](https://github.com/getdata-finance/ger30-30m-ohlcv-index-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/ger30-30m-ohlcv-index-historical-data/](https://getdata-finance.github.io/ger30-30m-ohlcv-index-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/ger30](https://getdata.finance/datasets/ger30)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/ger30))** |
|---|--:|---|
| Instrument | DAX 40 (GER30) · Index | DAX 40 (GER30) · Index |
| Timeframes | `30m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 30m rows | 5,031 | **153,083** |
| Size | 454.01 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/ger30) |
| Period | `2026-03-26` -> `2026-09-25` | `2008-09-10` -> `2026-09-25` |
| File | `GER30_30m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/ger30) |
| Coverage report | — | [GER30 coverage](https://getdata.finance/coverage/ger30) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`30m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/ger30)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `30m` sample · [getdata.finance](https://getdata.finance/datasets/ger30) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `30m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`GER30_30m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-26T02:30:00+00:00 | 22837.75 | 22842.74 | 22765.75 | 22784.75 | 4131 |
| 2026-03-26T03:00:00+00:00 | 22784.75 | 22812 | 22771.75 | 22805.99 | 2115 |
| 2026-03-26T03:30:00+00:00 | 22805.99 | 22863.51 | 22801.74 | 22822.74 | 2748 |
| 2026-03-26T04:00:00+00:00 | 22822.74 | 22839.49 | 22804.74 | 22831.76 | 1663 |
| 2026-03-26T04:30:00+00:00 | 22831.76 | 22835.51 | 22810.75 | 22824 | 1382 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-25T17:30:00+00:00 | 25568.24 | 25577.24 | 25549.24 | 25566.24 | 2670 |
| 2026-09-25T18:00:00+00:00 | 25566.24 | 25580.24 | 25553.24 | 25574.23 | 2332 |
| 2026-09-25T18:30:00+00:00 | 25574.23 | 25585.25 | 25566.23 | 25577.25 | 1924 |
| 2026-09-25T19:00:00+00:00 | 25577.25 | 25587.73 | 25547.73 | 25551.24 | 1666 |
| 2026-09-25T19:30:00+00:00 | 25551.24 | 25577.24 | 25545.73 | 25574.48 | 2015 |

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

df = pd.read_csv('GER30_30m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('GER30_30m.csv', parse_dates=['datetime'])
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

df = pd.read_csv('GER30_30m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='30min')
print(pf.stats())
```

## Download full data

The complete **GER30** archive on **[getdata.finance](https://getdata.finance/datasets/ger30)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **153,083** rows at `30m`, plus all other timeframes in the same ZIP.

**[-> Get the full GER30 dataset on getdata.finance](https://getdata.finance/datasets/ger30)**

---
*GetData · GER30 30m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/ger30)*
