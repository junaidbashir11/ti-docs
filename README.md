# ti-docs



# tecnical-indicators



## macd endpoint     /getmacd
### parameters for getmacd endpoint
?symbol=SQ&interval=30min&start_date=2022-12-10&end_date=2023-01-10&fast_period=12&slow_period=26&signal_period=15

## bollinger endpoint   /bollinger
### parameters for bollinger endpoint
?symbol=SQ&interval=30min&start_date=2022-12-10&end_date=2023-01-10&time_period=20&sd=2

## goldencross endpoint    /goldencross
### parameters for goldencross endpoint
?symbol=SNAP&interval=1h&start_date=2022-01-01&end_date=2023-01-20&fast=20min&slow=50min

## rsi endpoint   /rsi
### parameters for rsi endpoint
?symbol=SQ&interval=1h&start_date=2022-12-01&end_date=2023-01-24&time_period=20

## vwap endpoint    /vwap
### parameters for vwap endpoint
?symbol=SNAP&interval=1h&start_date=2022-01-15&end_date=2023-01-15

# Result

```python 
obj={
  portfolioamount:amount,
  portiofolioprofit:profit,
  dataframe:datatable,
  graph:graph

}```
