# Predictive Modeling for NFL Draft Selection

This project was completed as part of the GCI World 2026 competition. The goal was to build a machine learning model that predicts whether college football players would be drafted.

## Project Overview

- Built a classification model for NFL draft prediction
- Used player statistics and physical attributes as predictive features
- Optimized model performance using ROC-AUC
- Created position-adjusted features to improve prediction quality
- Generated a final competition submission file

## Tools Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Jupyter Notebook

## Methodology

1. Loaded and inspected the competition dataset
2. Cleaned missing values and prepared features
3. Built a baseline model
4. Engineered position-adjusted features
5. Used cross-validation to evaluate model performance
6. Generated final prediction probabilities for submission

## Evaluation Metric

The competition used ROC-AUC as the main evaluation metric.

## Results

## Results

| Evaluation Type | Metric | Score |
|---|---:|---:|
| Cross-validation | ROC-AUC | 0.813 |
| Public leaderboard / final submission | ROC-AUC | 0.851 |

## Files

- `baseline.ipynb`: baseline model notebook
- `final_model.ipynb`: final modeling notebook
- `submissions/final_submission.csv`: final competition submission file
