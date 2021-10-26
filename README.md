# HierST

Source code for the paper,
["HierST: A Unified Hierarchical Spatial-temporal Framework for COVID-19 Trend Forecasting"](https://www.cikm2021.org/accepted-papers/applied),
accepted by CIKM 2021.

## Setup

- Install CUDA 10.1
- Run `setup_py.sh` to install necessary packages

## Usage

```shell
cd src/
# pull data
python data_utils.py
# train models
python run_models.py --forecast_date 2021-10-24
# ensemble
python run_ensemble.py --forecast_date 2021-10-24
# check the output file, '../outputs/2021-10-24_forecasts.csv'
```