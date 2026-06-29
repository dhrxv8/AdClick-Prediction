# AdClick Prediction

A logistic regression project that predicts whether a user is likely to click an online advertisement based on behavioral and demographic features.

## Overview

This project explores an advertising dataset and builds a classification model for ad click prediction. The analysis focuses on understanding which user attributes are associated with ad engagement and how logistic regression can be used for binary classification.

## Objective

Predict the `Clicked on Ad` outcome and identify patterns in user behavior that may help improve ad targeting strategy.

## Features Used

The notebook analyzes variables such as:

- Daily time spent on site
- Age
- Area income
- Daily internet usage
- Gender
- Timestamp-derived behavior patterns

## Workflow

1. Load and inspect the advertising dataset.
2. Perform exploratory data analysis with pandas, Matplotlib, and Seaborn.
3. Prepare train/test splits for model evaluation.
4. Train a logistic regression classifier.
5. Evaluate model performance and interpret the results.

## Tech Stack

- Python
- pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn
- Jupyter Notebook

## Project Structure

```text
AdClick-Prediction/
├── Logistic Regression Project.ipynb
└── README.md
```

## Getting Started

```bash
git clone https://github.com/dhrxv8/AdClick-Prediction.git
cd AdClick-Prediction
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
jupyter notebook "Logistic Regression Project.ipynb"
```

## Notes

This is an educational machine learning project focused on classification workflow, model evaluation, and interpreting business-relevant patterns from user behavior data.

## Author

Dhruv Rao - [GitHub](https://github.com/dhrxv8)
