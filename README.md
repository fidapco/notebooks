# Fidap
Python based Jupyter Notebooks that use the Fidap API for financial data analysis and machine learning.

## Installation
Installation via PyPI

```pip install fidap```

## Usage
Import package, and then use the ```.sql()``` function to execute SQL.

```
import fidap
fidap.sql("select ticker, name, marketcap from tickers limit 5")
```

## Notebooks
The notebooks below have additional details - 

| No. | Name | Description |
| ---- | ---- | ---- |
| 1 | Getting Started | Information on getting started with Fidap |
| 2 | Insider Trades | Learn about finding alpha in insider trades |
