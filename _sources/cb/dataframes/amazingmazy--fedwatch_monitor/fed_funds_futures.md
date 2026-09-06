# Dataframe: `amazingmazy/fedwatch_monitor:fed_funds_futures` - 30-Day Fed Funds Futures Daily Bars (Databento)

Daily bars from Databento's GLBX.MDP3 dataset (schema `ohlcv-1d`,
parent symbol `ZQ.FUT`). Includes outright monthly contracts and calendar
spreads; filter with `fedwatch.filter_outright_contracts`. Prices are in index
points; the implied average fed funds rate for a contract month is 100 minus
the price. Refresh with `doit forget pull && doit`.


## DataFrame Glimpse

```
Rows: 12120
Columns: 7
$ date   <datetime[ns]> 2026-09-04 00:00:00
$ symbol          <str> 'ZQN7-ZQQ7'
$ open            <f64> 1.0
$ high            <f64> 1.5
$ low             <f64> 1.0
$ close           <f64> 1.0
$ volume          <u64> 2345


```

## Dataframe Manifest

| Dataframe Name                 | 30-Day Fed Funds Futures Daily Bars (Databento)                                                          |
|--------------------------------|--------------------------------------------------------------------------------------|
| Dataframe ID                   | [fed_funds_futures](../dataframes/amazingmazy--fedwatch_monitor/fed_funds_futures.md)                                       |
| Sources                        |                                           |
| Providers                      |                                         |
| Provider Links                 |                                    |
| Tags                           | Monetary Policy, Futures, Databento                                             |
| Access Types                   |                                       |
| How is data pulled?            | Databento Historical API via src/pull_fed_funds_futures.py (cost-guarded)                                                   |
| Data available up to (min)     | 2026-09-04 00:00:00                                                             |
| Data available up to (max)     | 2026-09-04 00:00:00                                                             |
| Dataframe Path                 | /home/runner/work/fedwatch-monitor/fedwatch-monitor/_data/fed_funds_futures.parquet                                             |


**Linked Charts:**


- [amazingmazy/fedwatch_monitor:fedwatch_latest_forecast](../../charts/amazingmazy--fedwatch_monitor.fedwatch_latest_forecast.md)



## Pipeline Manifest

| Pipeline Name                   | HW 4 - FedWatch Monitor                       |
|---------------------------------|--------------------------------------------------------|
| Pipeline ID                     | [amazingmazy/fedwatch_monitor](../../../index.md)              |
| Maintainer                      | Jeremiah Bejarano               |
| Contributors                    | Jeremiah Bejarano |
| Repository                     |                   |
| Pipeline Web Page               | <a href="file:///home/runner/work/fedwatch-monitor/fedwatch-monitor/docs/index.html">Pipeline Web Page      |
| Date of Last Code Update        | 2026-09-06 12:11:12           |
| OS Compatibility                | Windows, Linux, macOS |
| Linked Dataframes               |  [amazingmazy/fedwatch_monitor:fed_funds_futures](../../dataframes/amazingmazy--fedwatch_monitor/fed_funds_futures.md)<br>  |


**Build Commands:**
```
doit

```

