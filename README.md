# XAUUSD 30m OHLCV Metals Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-203_024_rows-blue)](https://getdata.finance/datasets/xauusd) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/xauusd)

### -> [**Download the full XAUUSD dataset on getdata.finance**](https://getdata.finance/datasets/xauusd)

**XAUUSD 30m OHLCV metals historical data** — ultra high-quality 30m OHLCV for **Gold / US Dollar**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`30m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/xauusd) · **203,024** `30m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `30m` sample updated in sync

> **Sample on GitHub** · `XAUUSD_30m.csv` (6,009 rows, `2026-03-26` -> `2026-09-25`, 519.48 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/xauusd)** — **203,024** `30m` rows (full `1m`: 5,887,627), **11 timeframes**, `2009-02-24` -> `2026-09-25`.

## Download sample

**[XAUUSD_30m.csv](https://github.com/getdata-finance/xauusd-30m-ohlcv-metals-historical-data/blob/main/XAUUSD_30m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/xauusd-30m-ohlcv-metals-historical-data/main/XAUUSD_30m.csv)) · [GitHub Releases](https://github.com/getdata-finance/xauusd-30m-ohlcv-metals-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/xauusd-30m-ohlcv-metals-historical-data/](https://getdata-finance.github.io/xauusd-30m-ohlcv-metals-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/xauusd](https://getdata.finance/datasets/xauusd)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/xauusd))** |
|---|--:|---|
| Instrument | Gold / US Dollar · Metals | Gold / US Dollar · Metals |
| Timeframes | `30m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 30m rows | 6,009 | **203,024** |
| Size | 519.48 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/xauusd) |
| Period | `2026-03-26` -> `2026-09-25` | `2009-02-24` -> `2026-09-25` |
| File | `XAUUSD_30m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/xauusd) |
| Coverage report | — | [XAUUSD coverage](https://getdata.finance/coverage/xauusd) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`30m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/xauusd)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `30m` sample · [getdata.finance](https://getdata.finance/datasets/xauusd) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `30m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`XAUUSD_30m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-26T02:30:00+00:00 | 4617.23 | 4619.89 | 4594.91 | 4598.07 | 29100 |
| 2026-03-26T03:00:00+00:00 | 4598.07 | 4603.04 | 4589.05 | 4595.87 | 26871 |
| 2026-03-26T03:30:00+00:00 | 4595.87 | 4608.13 | 4595.62 | 4606.05 | 13611 |
| 2026-03-26T04:00:00+00:00 | 4606.05 | 4611.62 | 4600.79 | 4610.01 | 9799 |
| 2026-03-26T04:30:00+00:00 | 4610.01 | 4613.68 | 4605.56 | 4609.58 | 9845 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-25T18:30:00+00:00 | 4287.43 | 4296.03 | 4287.06 | 4294.83 | 19130 |
| 2026-09-25T19:00:00+00:00 | 4294.83 | 4297.02 | 4287.82 | 4288.67 | 16096 |
| 2026-09-25T19:30:00+00:00 | 4288.67 | 4294.3 | 4287.7 | 4291.04 | 17904 |
| 2026-09-25T20:00:00+00:00 | 4291.04 | 4292.03 | 4286.8 | 4287.33 | 5279 |
| 2026-09-25T20:30:00+00:00 | 4287.33 | 4287.33 | 4284.52 | 4284.76 | 1696 |

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
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='30min')
print(pf.stats())
```

## Download full data

The complete **XAUUSD** archive on **[getdata.finance](https://getdata.finance/datasets/xauusd)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **203,024** rows at `30m`, plus all other timeframes in the same ZIP.

**[-> Get the full XAUUSD dataset on getdata.finance](https://getdata.finance/datasets/xauusd)**

---
*GetData · XAUUSD 30m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/xauusd)*
