# XAUUSD 30m OHLCV Metals Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-201_184_rows-blue)](https://getdata.finance/datasets/xauusd) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/xauusd)

### -> [**Download the full XAUUSD dataset on getdata.finance**](https://getdata.finance/datasets/xauusd)

**XAUUSD 30m OHLCV metals historical data** — ultra high-quality 30m OHLCV for **Gold / US Dollar**. Global spot sessions — Asia, Europe and US coverage for precious metals trading. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 30m OHLCV** for **Gold / US Dollar** (Metals)
- **Global spot sessions — Asia, Europe and US coverage for precious metals trading**
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`30m`) · **9 timeframes** on [getdata.finance](https://getdata.finance/datasets/xauusd) · **201,184** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `30m` sample updated in sync

> **Sample on GitHub** · `XAUUSD_30m.csv` (5,906 rows, `2026-02-02` -> `2026-07-31`). **Full archive on [getdata.finance](https://getdata.finance/datasets/xauusd)** — **201,184** `1m` rows (~15.46 MB), **9 timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W), `2009-02-24` -> `2026-07-31`.

## Download sample

**[XAUUSD_30m.csv](https://github.com/getdata-finance/xauusd-30m-ohlcv-metals-historical-data/blob/main/XAUUSD_30m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/xauusd-30m-ohlcv-metals-historical-data/main/XAUUSD_30m.csv)) · [GitHub Releases](https://github.com/getdata-finance/xauusd-30m-ohlcv-metals-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/xauusd-30m-ohlcv-metals-historical-data/](https://getdata-finance.github.io/xauusd-30m-ohlcv-metals-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/xauusd](https://getdata.finance/datasets/xauusd)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/xauusd))** |
|---|--:|---|
| Instrument | Gold / US Dollar · Metals | Gold / US Dollar · Metals |
| Timeframes | `30m` (sample) | **9** — 1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W |
| 1m rows | 5,906 | **201,184** |
| Size | 0.49 MB | ~15.46 MB |
| Period | `2026-02-02` -> `2026-07-31` | `2009-02-24` -> `2026-07-31` |
| File | `XAUUSD_30m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/xauusd) |
| Coverage report | — | [XAUUSD coverage](https://getdata.finance/coverage/xauusd) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`30m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/xauusd)**, each full asset archive is delivered as a ZIP with **9 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **12H** · **3D** · **1W**

GitHub = `30m` sample · [getdata.finance](https://getdata.finance/datasets/xauusd) = all **9** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `30m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`XAUUSD_30m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-02-02T09:00:00+00:00 | 4640.61 | 4700.08 | 4602.78 | 4689.55 | 65916 |
| 2026-02-02T09:30:00+00:00 | 4689.55 | 4730.94 | 4678.88 | 4719.48 | 66558 |
| 2026-02-02T10:00:00+00:00 | 4719.48 | 4733.72 | 4670.4 | 4682.33 | 53641 |
| 2026-02-02T10:30:00+00:00 | 4682.33 | 4711.83 | 4656.93 | 4705.41 | 48184 |
| 2026-02-02T11:00:00+00:00 | 4705.41 | 4760.09 | 4703.28 | 4752.94 | 48408 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-31T18:30:00+00:00 | 4064.205 | 4064.755 | 4061.065 | 4063.855 | 8524 |
| 2026-07-31T19:00:00+00:00 | 4063.855 | 4066.095 | 4060.145 | 4063.715 | 8955 |
| 2026-07-31T19:30:00+00:00 | 4063.715 | 4068.665 | 4062.045 | 4064.005 | 17480 |
| 2026-07-31T20:00:00+00:00 | 4064.005 | 4064.925 | 4058.355 | 4060.725 | 9869 |
| 2026-07-31T20:30:00+00:00 | 4060.725 | 4066.095 | 4060.295 | 4064.025 | 4152 |

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

df = pd.read_csv('XAUUSD_30m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('XAUUSD_30m.csv', parse_dates=['datetime'])
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

df = pd.read_csv('XAUUSD_30m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1min')
print(pf.stats())
```

## Download full data

The complete **XAUUSD** archive on **[getdata.finance](https://getdata.finance/datasets/xauusd)** includes **9 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W) — **201,184** rows at `1m`, plus all other timeframes in the same ZIP.

**[-> Get the full XAUUSD dataset on getdata.finance](https://getdata.finance/datasets/xauusd)**

---
*GetData · XAUUSD 30m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/xauusd) · 2026-08-05 UTC*
