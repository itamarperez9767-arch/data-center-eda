# Data Center EX2 — Regression and Classification Error Analysis

This repository contains Homework Assignment EX2: Regression and Classification Error Analysis.

## Main notebook

Please open:

`data_center_error_analysis_ex2.ipynb`

## Dataset

The notebook uses the same data-center energy consumption dataset from EX1.

The analysis includes:

- Regression target: `cooling_kw`
- Classification target: `high_cooling_load`
- k-fold cross-validation with `k=5`
- Regression residual analysis
- Extreme error analysis
- Regression model comparison
- Classification confusion matrix analysis
- Probability-based error analysis
- Threshold sensitivity analysis
- ROC-AUC and ROC curve
- Final reflection

## Reproducibility note

The notebook can load a compact processed file named:

`data_center_working_sample.csv`

If this file does not exist, the notebook tries to recreate the working sample from the original raw CSV files under:

`data/raw/`

Large raw CSV files should not be uploaded to GitHub. If the instructor needs to rerun the notebook without the raw files, include a compact working sample CSV.
