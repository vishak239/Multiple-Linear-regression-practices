# Multiple Linear Regression — Practice

Practice notebook that uses scikit-learn to fit multiple linear regression models on small hand-written datasets.

## Overview

The notebook has two short experiments. Each one combines two input features with `numpy.column_stack`, splits the data 50 / 50 into training and test sets, fits a `LinearRegression` model, and plots the test targets against the predictions.

| Experiment | Inputs | Target |
|---|---|---|
| 1 | hours studied, practice tests | marks obtained |
| 2 | hours studied, practice tests | sleep hours |

The data is a set of 10 manually written samples. It is meant for learning the scikit-learn workflow, not for drawing conclusions.

## Tech Stack

- Python
- NumPy
- scikit-learn
- Matplotlib
- Jupyter Notebook

## Project Structure

```text
.
├── multiple linear regression.ipynb
└── README.md
```

## Usage

```bash
pip install numpy pandas scikit-learn matplotlib jupyter
jupyter notebook "multiple linear regression.ipynb"
```

## What I Practised

- Building a feature matrix from several inputs
- `train_test_split` and `LinearRegression` from scikit-learn
- Plotting predictions with Matplotlib

## Author

**V Vishak** · [github.com/vishak239](https://github.com/vishak239)
