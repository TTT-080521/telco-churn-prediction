# Telco Customer Churn Prediction

Binary classification project predicting whether a telecom customer will churn,
using the [Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) dataset.
Models: K-Nearest Neighbours, Logistic Regression and Random Forest.

## Dataset
- 7,043 customers, 21 columns
- Target `Churn`: 73.5% No / 26.5% Yes (imbalanced)
- `TotalCharges` is stored as text, with 11 blank values

## Project structure
- `data/raw/` – original dataset
- `data/processed/` – cleaned data
- `notebooks/` – EDA and modelling notebooks
- `src/` – reusable Python code
- `reports/figures/` – charts for the report
- `models/` – saved models

## Setup
```bash
pip install -r requirements.txt
```