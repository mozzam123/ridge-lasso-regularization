# Ridge and Lasso Regularization for House Price Prediction

This project demonstrates the use of **Ridge** (L2 regularization) and **Lasso** (L1 regularization) regression techniques to predict house prices based on various features in the **Melbourne Housing** dataset. The dataset is preprocessed, cleaned, and used to build models that help understand how regularization impacts the prediction accuracy and feature selection.

## Project Overview

- **Objective:** Predict house prices in Melbourne using Ridge and Lasso regression models.
- **Dataset:** Melbourne Housing dataset, which includes features like number of rooms, property type, distance, and more.
- **Techniques:**
  - **Linear Regression**
  - **Ridge Regression** (L2 regularization)
  - **Lasso Regression** (L1 regularization)

## Steps

1. **Data Preprocessing:**
   - Handling missing values
   - One-hot encoding categorical variables
   - Feature selection
2. **Model Building:**
   - Train and evaluate models using Linear, Ridge, and Lasso regressions.
3. **Comparison of Performance:**
   - Evaluate test and train scores for all models.

## Requirements

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`

## How to Run

1. Clone this repository.
2. Install the necessary libraries:
   ```bash
   pip install -r requirements.txt
    ```
3. Run the code to observe the effect of Ridge and Lasso regularization on the prediction.

# Results

- The model's performance (test and train scores) is compared for Linear, Ridge, and Lasso regression.
- Ridge regression typically results in smaller coefficients but doesn't set them to zero.
- Lasso regression can remove features by setting their coefficients to zero, effectively performing feature selection.
