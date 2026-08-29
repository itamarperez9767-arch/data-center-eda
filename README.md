# Final Homework / EX3 — Unsupervised Learning, Dimensionality Reduction, and Anomaly Detection

This repository contains the final Data Science homework submission for unsupervised learning, dimensionality reduction, clustering, and multi-dimensional anomaly detection.

## Main notebook

Please open:

`data_center_unsupervised_anomaly_ex3.ipynb`

The notebook has already been executed and saved with outputs, tables, and figures.

## Dataset

The notebook uses the compact data-center working sample used in the previous assignments:

`data_center_working_sample.csv`

The dataset contains 1,500 chronological observations and 26 columns from data-center energy and outside weather measurements. The analysis uses a selected numerical feature set for PCA, clustering, feature-space clustering, and anomaly detection.

## Main methods included

- Structural exploratory data analysis
- Missing values, data types, statistical summary, and correlation matrix
- Histograms, boxplots, skewness, kurtosis, and outlier exploration
- PCA explained variance, cumulative variance, scree plot, 2D and 3D projections
- PCA loading interpretation
- K-Means clustering
- DBSCAN clustering
- Hierarchical clustering
- Feature-space clustering on the transposed data matrix
- Z-score anomaly detection
- Isolation Forest anomaly detection
- Local Outlier Factor anomaly detection
- Agreement analysis between anomaly methods
- Sensitivity analysis for scaling and dimensionality
- Final visualization dashboard
- Critical analysis, ethical reflection, and final conclusions

## Reproducibility

The notebook is designed to run from the same directory as `data_center_working_sample.csv`.

No raw large CSV files are required for this final notebook.
