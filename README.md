# Anomaly Detection for Time Series

This repository is a collection of Jupyter Notebooks on anomaly detection for time series data.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/PierreExeter/anomaly_detection_time_series/master)

## Installation

```bash
conda env create -f environment.yml
conda activate time_series
python -m ipykernel install --user --name=time_series   # install environment in Jupyter notebook
```

## Note

Use this command to export the environment
```bash
conda env export --from-history -f environment.yml
```

not 
```bash
conda env export > environment.yml
```

## Run the notebooks

```bash
jupyter notebook 1_multivariate_time_series_anomaly_detection.ipynb
```
or use Binder

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/PierreExeter/anomaly_detection_time_series/master)

