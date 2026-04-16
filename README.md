# Software Quality Prediction Using Machine Learning
> CSE422 — Artificial Intelligence | BRAC University

A machine learning project that predicts software quality levels — **Low**, **Medium**, and **High** — using software metrics such as Cyclomatic Complexity, Lines of Code, Code Churn, and Bug Count.

Four classifiers were trained and compared — KNN, Decision Tree, Logistic Regression, and a Neural Network (MLP) — with the Neural Network achieving the best accuracy at **35.21%**. The project covers a full ML pipeline including preprocessing, feature engineering, scaling, and model evaluation.

## Tech Stack
`Python` `scikit-learn` `pandas` `NumPy` `Matplotlib` `Seaborn`

## Models Compared
| Model | Accuracy |
|---|---|
| K-Nearest Neighbors | 31.67% |
| Decision Tree | 30.83% |
| Logistic Regression | 28.54% |
| Neural Network (MLP) | **35.21%** ✓ |

## Dataset
- 1,600 samples · 9 features · 3-class classification
- 70/30 stratified train-test split
