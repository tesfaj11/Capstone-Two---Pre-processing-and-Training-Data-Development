# Capstone-Two---Pre-processing-and-Training-Data-Development
# Capstone Two – Preprocessing and Training Data Development

## Overview

This notebook completes the preprocessing step of the Data Science Method (DSM) for the California Housing Prices dataset. The main goal is to clean and prepare the dataset for model training by completing the following tasks:

### ✅ Tasks Completed

1. **Loaded the California Housing dataset** using `fetch_california_housing()` from `sklearn.datasets`.
2. **Confirmed that the dataset does not contain any categorical features** – all columns are numeric, so no dummy variables were necessary.
3. **Standardized all numeric features** using `StandardScaler()` to normalize the feature ranges for model training.
4. **Split the dataset into training and testing sets** using `train_test_split()` with an 80/20 split.
5. **Saved the preprocessed training and test sets** to `.csv` files for future modeling steps.

### 📁 Files Saved
- `X_train.csv`
- `X_test.csv`
- `y_train.csv`
- `y_test.csv`

This notebook satisfies all rubric requirements for Capstone Two: Preprocessing and Training Data Development.
