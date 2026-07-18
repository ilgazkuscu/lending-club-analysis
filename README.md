# Lending Club Analysis Scaffold

## Status

This repository is an **incomplete project scaffold**. It currently contains dependency and data-exclusion configuration, but no notebooks, pipeline source, trained models, or evaluation output.

The earlier README described planned logistic-regression, random-forest, and XGBoost work as though it had already been implemented. Those claims have been removed until reproducible source and results are committed.

## Intended question

Can borrower and loan attributes help estimate Lending Club default risk without introducing target leakage?

Potential source dataset: [Lending Club loan data on Kaggle](https://www.kaggle.com/datasets/wordsforthewise/lending-club). Dataset terms, target definition, time split, leakage controls, and class-imbalance handling must be documented before analysis begins.

## Completion requirements

- a versioned data contract and acquisition instructions
- deterministic cleaning and feature preparation
- a chronological evaluation split
- simple and model-based baselines
- ROC AUC, precision/recall, calibration, and threshold analysis
- tests for target construction and leakage exclusions
- reproducible environment and recorded results

Until these exist, this repository should not be pinned or presented as a completed credit-risk project.
