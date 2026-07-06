# JPN225 15m OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-368_538_rows-blue)](https://ork.ad/) [![Updated](https://img.shields.io/badge/weekly_update-every_Sunday-green)](https://ork.ad/) [![Full data on ork.ad](https://img.shields.io/badge/download-ork.ad-orange)](https://ork.ad/)

### → [**Download the full JPN225 dataset on ork.ad**](https://ork.ad/)

**JPN225 15m OHLCV Stock index historical data** — ultra high-quality 15m OHLCV for **Nikkei 225**. Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on ork.ad](#timeframes-on-orkad)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on ork.ad](#download-full-data)

## Why this dataset?

- **Ultra high-quality 15m OHLCV** for **Nikkei 225** (Stock index)
- **Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only**
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`15m`) · **13 timeframes** on [ork.ad](https://ork.ad/) · **368,538** `15m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [ork.ad](https://ork.ad/) every **Sunday**; GitHub `15m` sample updated in sync

> **Sample on GitHub** · `JPN225_15m.csv` (11,830 rows, `2026-01-04` → `2026-07-03`). **Full archive on [ork.ad](https://ork.ad/)** — **368,538** `15m` rows (~20.88 MB), **13 timeframes** (``1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W``), `2008-09-01` → `2026-07-03`.

## Download sample

**[JPN225_15m.csv](https://github.com/ork-ad/jpn225-15m-ohlcv-index-historical-data/blob/main/JPN225_15m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/ork-ad/jpn225-15m-ohlcv-index-historical-data/main/JPN225_15m.csv)) · [GitHub Releases](https://github.com/ork-ad/jpn225-15m-ohlcv-index-historical-data/releases) when the release workflow is active.

## GitHub Pages

Interactive chart & stats: **[https://ork-ad.github.io/jpn225-15m-ohlcv-index-historical-data/](https://ork-ad.github.io/jpn225-15m-ohlcv-index-historical-data/)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([ork.ad](https://ork.ad/))** |
|---|--:|---|
| Instrument | Nikkei 225 · Stock index | Nikkei 225 · Stock index |
| Timeframes | `15m` (sample) | **13** — `1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W` |
| 15m rows | 11,830 | **368,538** |
| Size | 0.7 MB | ~20.88 MB |
| Period | `2026-01-04` → `2026-07-03` | `2008-09-01` → `2026-07-03` |
| File | `JPN225_15m.csv` | ZIP on [ork.ad](https://ork.ad/) |
| Updates | Weekly (Sunday) — GitHub sample | Weekly (Sunday) — all timeframes |

## Timeframes on ork.ad

This GitHub repository ships a **`15m` evaluation sample** only. On **[ork.ad](https://ork.ad/)**, each full asset archive is delivered as a ZIP with **13 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **2H** · **4H** · **8H** · **12H** · **16H** · **1D** · **1W**

GitHub = `15m` sample · [ork.ad](https://ork.ad/) = all **13** timeframes above for the same instrument.

## Weekly updates

- **[ork.ad](https://ork.ad/)** — Full datasets on ork.ad are updated every Sunday.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Sunday), in sync with ork.ad.

When a new `15m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`JPN225_15m.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-01-04T23:00:00Z | 51141.04 | 51301.55 | 51041.53 | 51083.53 | 224.0 |
| 2026-01-04T23:15:00Z | 51083.53 | 51123.52 | 51061.04 | 51081.02 | 127.0 |
| 2026-01-04T23:30:00Z | 51081.02 | 51091.02 | 50831.49 | 50856.52 | 332.0 |
| 2026-01-04T23:45:00Z | 50856.52 | 51296.06 | 50841.5 | 51256.06 | 1173.0 |
| 2026-01-05T00:00:00Z | 51256.06 | 51666.1 | 51256.06 | 51486.56 | 2334.0 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| time | open | high | low | close | volume |
| 2026-07-03T15:45:00Z | 69822.7 | 69845.17 | 69785.17 | 69792.67 | 207.0 |
| 2026-07-03T16:00:00Z | 69792.67 | 69822.66 | 69760.17 | 69810.17 | 150.0 |
| 2026-07-03T16:15:00Z | 69810.17 | 69840.17 | 69802.66 | 69805.17 | 159.0 |
| 2026-07-03T16:30:00Z | 69805.17 | 69862.68 | 69795.2 | 69850.17 | 149.0 |

## Schema

```text
time,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('JPN225_15m.csv', parse_dates=['time'])
df.set_index('time', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('JPN225_15m.csv', parse_dates=['time'])
df.set_index('time', inplace=True)

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

df = pd.read_csv('JPN225_15m.csv', parse_dates=['time'])
close = df.set_index('time')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='15min')
print(pf.stats())
```

## Download full data

The complete **JPN225** archive on **[ork.ad](https://ork.ad/)** includes **13 OHLCV timeframes** (`1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W`) — **368,538** rows at `15m`, plus all other timeframes in the same ZIP.

**[→ Get the full JPN225 dataset on ork.ad](https://ork.ad/)**

---
*GetData · JPN225 15m OHLCV sample on GitHub · Full historical data on [ork.ad](https://ork.ad/) · 2026-07-06 UTC*