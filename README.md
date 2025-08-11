# Car Price Prediction

This is a beginner supervised machine learning regression project that predicts car prices based on the following features: **Make**, **Colour**, **Doors**, and **Odometer (KM)**.

---
## Project Overview

The goal of this project is to build a simple model to estimate car prices using the available dataset. 
Multiple models were tested, including **Ridge Regression**, **Support Vector Regression (SVR)**, and **Random Forest**.

Although the results were not highly accurate, this project serves as a learning experience to understand the full machine learning workflow: data preprocessing, model training, evaluation, and saving the model.

---
## Current Status

- **Ridge Regression** was chosen to proceed with due to its best R² score: approximately **0.25** (indicating modest predictive ability).  
- **SVR** and **Random Forest** models were tested but did not outperform Ridge in this project setup.


---
## How to Use

1. Clone this repository:
   git clone https://github.com/yourusername/car-price-prediction.git
   cd car-price-prediction


2. Install dependencies:
   pip install pandas scikit-learn joblib


3. Open and run the Jupyter notebook:
   jupyter notebook car-price.ipynb
   OR, if you use VSCode, just open car-price.ipynb and run the cells there.
---
### Notes:

.The saved model file (.joblib) is not included in this repo to keep it lightweight.

.You can train the model yourself by running the provided scripts or notebook.

.Future improvements could include: feature engineering, hyperparameter tuning, and trying more advanced models.

---
### License:

This project is open-source and available under the MIT License.

---
### Author:
Ali Kawar


