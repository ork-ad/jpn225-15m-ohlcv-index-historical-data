# JPN225 15m OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-12_523_rows-blue)](https://ork.ad/) [![Updated](https://img.shields.io/badge/weekly_update-every_Sunday-green)](https://ork.ad/) [![Full data on ork.ad](https://img.shields.io/badge/download-ork.ad-orange)](https://ork.ad/)

### → [**Download the full JPN225 dataset on ork.ad**](https://ork.ad/)

**JPN225 15m OHLCV Stock index historical data** — ultra high-quality 15m OHLCV for **Japan 225 (Nikkei)**. Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 15m OHLCV** for **Japan 225 (Nikkei)** (Stock index)
- **Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only**
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`15m`) · **13 timeframes** on [ork.ad](https://ork.ad/) · **12,523** `15m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [ork.ad](https://ork.ad/) every **Sunday**; GitHub `15m` sample updated in sync

> **Sample on GitHub** · `JPN225_15m.csv` (11,755 rows, `2026-01-04` → `2026-07-02`). **Full archive on [ork.ad](https://ork.ad/)** — **12,523** `15m` rows (~0.79 MB), **13 timeframes** (``1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W``), `2025-12-18` → `2026-07-02`.

## Download sample

**[JPN225_15m.csv](https://github.com/ork-ad/jpn225-15m-ohlcv-index-historical-data/blob/main/JPN225_15m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/ork-ad/jpn225-15m-ohlcv-index-historical-data/main/JPN225_15m.csv)) · [GitHub Releases](https://github.com/ork-ad/jpn225-15m-ohlcv-index-historical-data/releases) when the release workflow is active.

## GitHub Pages

Interactive chart & stats: **[https://ork-ad.github.io/jpn225-15m-ohlcv-index-historical-data/](https://ork-ad.github.io/jpn225-15m-ohlcv-index-historical-data/)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([ork.ad](https://ork.ad/))** |
|---|--:|---|
| Instrument | Japan 225 (Nikkei) · Stock index | Japan 225 (Nikkei) · Stock index |
| Timeframes | `15m` (sample) | **13** — `1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W` |
| 15m rows | 11,755 | **12,523** |
| Size | 0.74 MB | ~0.79 MB |
| Period | `2026-01-04` → `2026-07-02` | `2025-12-18` → `2026-07-02` |
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
| 2026-01-04T23:00:00Z | 51136.951 | 51297.443 | 51037.45 | 51079.441 | 224.0 |
| 2026-01-04T23:15:00Z | 51079.441 | 51119.431 | 51056.951 | 51076.931 | 123.0 |
| 2026-01-04T23:30:00Z | 51076.931 | 51086.931 | 50827.428 | 50856.949 | 331.0 |
| 2026-01-04T23:45:00Z | 50856.949 | 51291.953 | 50841.938 | 51256.943 | 1172.0 |
| 2026-01-05T00:00:00Z | 51256.943 | 51661.967 | 51256.943 | 51482.435 | 2333.0 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| time | open | high | low | close | volume |
| 2026-07-02T20:00:00Z | 68310.37 | 68310.39 | 68185.87 | 68265.37 | 796.0 |
| 2026-07-02T20:15:00Z | 68265.37 | 68315.39 | 68240.87 | 68275.37 | 222.0 |
| 2026-07-02T20:30:00Z | 68275.37 | 68317.89 | 68245.87 | 68262.88 | 360.0 |
| 2026-07-02T20:45:00Z | 68262.88 | 68330.39 | 68250.87 | 68325.39 | 386.0 |

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

The complete **JPN225** archive on **[ork.ad](https://ork.ad/)** includes **13 OHLCV timeframes** (`1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W`) — **12,523** rows at `15m`, plus all other timeframes in the same ZIP.

**[→ Get the full JPN225 dataset on ork.ad](https://ork.ad/)**

---
*GetData · JPN225 15m OHLCV sample on GitHub · Full historical data on [ork.ad](https://ork.ad/) · 2026-07-04 UTC*