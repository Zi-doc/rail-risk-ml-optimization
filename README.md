# Rail Accident Risk Modeling using Machine Learning and Network Analysis

This repository contains the code developed for Chapter 3 of my PhD research, where I built a data-driven framework to estimate the consequences of rail accidents and translate those predictions into a network-level risk analysis for identifying critical rail links.

The goal of this work was not only to build predictive models, but to connect accident data, machine learning, and network structure in a way that supports risk-aware decision making in rail transportation.

## What this project does
- Data preparation and imputation
- Predictive modeling of accident consequences (damage, injury/evacuation proxies)
- Handling class imbalance where applicable
- Ensemble modeling (AdaBoost/bagging variants)
- Network/path construction and link-level risk aggregation

## Start here
Open notebooks in this order:
1. `01_data_prep_imputation.ipynb`
2. `02_regression_acddmg_rfecv_linear.ipynb`
3. `03_classification_casinj_imbalance.ipynb`
4. `04_ensemble_adaboost_bagging_casinj.ipynb`
5. `05_network_path_creation.ipynb`
6. `06_risk_per_link_analysis.ipynb`
