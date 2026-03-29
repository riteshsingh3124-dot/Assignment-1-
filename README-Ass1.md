# COMPAS Recidivism Analysis — Python Translation

Python translation of the ProPublica COMPAS recidivism risk score analysis, originally written in R.
**Course:** DNSC 6330 — Responsible Machine Learning  
**Assignment:** Individual Assignment 1 — Translating an R Machine Learning Workflow into Python  
**Professor:** Michael Akinwumi, The George Washington University

## What This Does

This repository contains a Python translation of the ProPublica COMPAS recidivism analysis, originally implemented in R. The analysis examines whether the COMPAS risk assessment tool exhibits racial bias in its predictions of criminal recidivism.

The workflow covers:
1. **Exploratory Data Analysis** — data loading, cleaning, filtering, descriptive statistics, and visualizations
2. **Model Development** — logistic regression testing for racial bias in COMPAS score assignments
3. **Model Evaluation & Diagnostics** — confusion matrices by race, FPR/FNR disparity analysis, survival analysis (Cox PH and Kaplan-Meier)

## Libraries

- pandas, numpy
- matplotlib, seaborn
- statsmodels (logistic regression)
- lifelines (survival analysis)

## How to Run

1. Install dependencies: `pip install pandas numpy matplotlib seaborn statsmodels lifelines`
2. Open `Compas_Analysis_Python.ipynb` in Jupyter or Google Colab
3. Run all cells — data is loaded from ProPublica's GitHub repo, no local files needed

## Data Source

ProPublica COMPAS analysis: https://github.com/propublica/compas-analysis
No local data files are needed — the notebook fetches data via URL at runtime.

## References

- ProPublica COMPAS Analysis: https://www.propublica.org/article/how-we-analyzed-the-compas-recidivism-algorithm/
- Original R notebook: https://github.com/propublica/compas-analysis
- Lecture 01: Foundations of the Alignment Problem (DNSC 6330, Michael Akinwumi)