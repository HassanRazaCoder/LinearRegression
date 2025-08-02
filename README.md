# 📊 Linear Regression on Thyroid Dataset

This project implements a **Linear Regression model** using the Thyroid dataset to predict binary outcomes (Yes/No, mapped to 1/0). It demonstrates the full workflow from data loading to model evaluation and visualization.

## 📁 Files Included

- `logisticregression.py` – Main Python script implementing the model.
- `Thyroid_Diff.csv` – Dataset used for training and testing (you need to place it in the same directory or adjust the path).
- `README.md` – This documentation file.

## 🧪 Project Overview

The script performs the following steps:

1. Loads the thyroid dataset
2. Encodes the target column (`Yes`/`No`) into binary (1/0)
3. Applies one-hot encoding to categorical features
4. Splits data into training and testing sets (80/20)
5. Trains a Linear Regression model
6. Makes predictions and evaluates performance using:
   - Mean Squared Error (MSE)
   - Root Mean Squared Error (RMSE)
   - Mean Absolute Error (MAE)
   - R² Score
7. Plots actual vs predicted values for visual evaluation

## 🔧 Technologies Used

- Python
- pandas
- scikit-learn
- NumPy
- matplotlib

## 📈 Output Metrics Example

