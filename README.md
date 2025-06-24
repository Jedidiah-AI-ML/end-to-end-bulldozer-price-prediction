# Bulldozer Price Prediction with Machine Learning
This project predicts the sale price of used bulldozers using historical data and machine learning techniques. It follows an end-to-end workflow, from preprocessing to model tuning and evaluation.

## Features
- Time Series Feature Engineering from sale dates

- Data Cleaning & Imputation for missing values

- Categorical Encoding for model compatibility

- Random Forest Regressor with hyperparameter tuning

- Performance Evaluation using RMSLE, MAE, and R²

- Feature Importance Visualization

- Prediction on Test Set formatted for Kaggle submission

## Tech Stack
Python

Pandas, NumPy

Scikit-learn

Matplotlib

## Setup
Install dependencies:

bash
Copy
Edit
pip install pandas numpy scikit-learn matplotlib
Prepare your dataset:

Place the TrainAndValid.csv and Test.csv files in a data/ folder.

Run the script:

bash
Copy
Edit
python end-end-bulldozer-price-regression.py
Output
Predicted bulldozer prices on unseen data

Feature importance bar chart

Metrics: RMSLE, MAE, and R² for training and validation set
