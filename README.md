# CART Classification with the PlayTennis Dataset

## Overview

This project explains how a **CART (Classification and Regression Tree)** works for a simple classification task. It uses the classic PlayTennis dataset to predict whether tennis can be played from weather conditions.

The notebook shows both the idea behind CART and a working implementation built from scratch.

## What is covered?

- Explore the 14-row PlayTennis dataset
- Calculate Gini impurity and find the best binary split
- Build a CART tree from scratch
- Apply pre-pruning and cost-complexity post-pruning
- Visualize and read the decision rules
- Evaluate the models with training accuracy and Leave-One-Out Cross-Validation (LOOCV)
- Compare the manual tree with a scikit-learn tree

## Dataset

**Input features**

- `Outlook`
- `Temperature`
- `Humidity`
- `Wind`

**Target:** `PlayTennis` (`Yes` or `No`)

## Requirements

- Python 3
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

Install the packages with:

```bash
pip install numpy pandas matplotlib scikit-learn jupyter
```

## Run the notebook

1. Open `CART_Supermarket_Promo_Assignment.ipynb` in Jupyter Notebook or VS Code.
2. Run the cells from top to bottom.
3. Review the tree diagrams, metrics, and predictions.

## Note

The dataset is very small, so the results are useful for learning CART but should not be treated as a production model.
