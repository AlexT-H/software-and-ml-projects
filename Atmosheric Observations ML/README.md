# Atmospheric Observations ML

## Overview

This project uses a linear regression machine-learning workflow to analyze atmospheric observation data. The model compares multiple atmospheric data columns against a target **Health Risk Score (HRS)** metric and applies optimization techniques to reduce prediction error.

The project demonstrates data preparation, regression modeling, iterative evaluation, and basic model optimization.

---

## Project Goal

The goal was to build and improve a regression model that could estimate a target atmospheric risk score from structured observation data.

Overall workflow:

1. Load atmospheric observation data.
2. Sort or evaluate records based on the HRS target.
3. Calculate relationships between input columns and the target metric.
4. Develop a regression-based model.
5. Train, test, evaluate, and adjust the model.
6. Compare original and optimized performance.

---

## Skills Demonstrated

- Python programming
- CSV data handling
- Linear regression
- Feature weighting
- Model evaluation
- Error analysis
- Iterative ML optimization
- Data-driven experimentation

---

## Project Structure

```text
Atmosheric Observations ML/
├── atmosphereData.csv
├── main.py
└── README.md
```

---

## How to Run

Requirements:

- Python 3.10+
- `atmosphereData.csv` in the project folder

Run:

```bash
python main.py
```

The script analyzes the provided atmospheric dataset and outputs model performance information.

---

## Model Evaluation

The project compares original and optimized model behavior using metrics such as:

- average error
- mean absolute percentage error
- R-squared
- root mean squared error

Optimization techniques explored include weighted averaging, pruning, regularization, quantization, and boosting-style adjustment.

---

## Future Improvements

- Refactor the code into reusable data, training, and evaluation modules.
- Add visualizations for model predictions and residuals.
- Add train/test split configuration.
- Add feature-importance reporting.
- Improve documentation around the dataset and target metric.
- Adapt the workflow to new atmospheric or environmental datasets.

---

## Portfolio Relevance

This project supports my GIS and environmental-data interests by showing experience with atmospheric data, regression modeling, and iterative ML evaluation.
