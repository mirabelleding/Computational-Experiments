# Decision Tree Classification

A supervised classification experiment that evaluates vehicle listings using a decision tree and examines how feature engineering and dataset modifications influence predictions.

## Overview

The project uses a car evaluation dataset with attributes including purchasing price, maintenance cost, and safety rating to predict one of four evaluation categories: unacceptable, acceptable, good, or very good.

## Approach

- Prepare and transform categorical vehicle attributes for modelling.
- Focus on price, maintenance, and safety features; experiment with numeric representations of price-related categories.
- Train a `DecisionTreeClassifier` and tune parameters using `GridSearchCV`.
- Evaluate class predictions and class-probability outputs.
- Explore how modifying the training data changes decision boundaries and predicted probabilities.
- Examine inconsistencies and trade-offs in feature selection, representation, and interpretation.

## Notes

The numeric price and maintenance values used in the exercise include simulated assignments derived from categorical ranges. Results should therefore be understood as a modelling experiment rather than a real-world vehicle valuation system.

**Tools:** Python, pandas, NumPy, scikit-learn, Matplotlib.

**Dataset:** [Car Evaluation Classification — Kaggle](https://www.kaggle.com/datasets/stealthtechnologies/car-evaluation-classification/data)

## Notebook

[Jupyter NoteBook](model_development.ipynb)
