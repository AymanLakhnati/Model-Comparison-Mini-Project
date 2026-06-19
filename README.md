# Decision Trees Project

This repository contains a Jupyter notebook that explores decision tree models using classic datasets.

## Contents

- `notebook.ipynb` - Notebook demonstrating:
  - Decision Tree classification on the Iris dataset
  - Random Forest comparison on the Iris dataset
  - Model benchmarking on the Breast Cancer dataset
- `model_comparison.png` - Saved accuracy comparison chart for the Breast Cancer models

## Overview

The notebook trains and evaluates several classification models:

- Decision Tree
- Random Forest
- Logistic Regression

It also includes:

- train/test splitting
- feature importance visualization
- cross-validation with F1 score
- tree visualization and textual rule extraction

## How to run

1. Install required Python packages:

```bash
pip install scikit-learn pandas matplotlib seaborn
```

2. Open `notebook.ipynb` in Jupyter Lab or Jupyter Notebook.
3. Run the cells from top to bottom.

## Notes

- The Breast Cancer section scales features before training.
- The notebook compares a shallow decision tree against a random forest.

