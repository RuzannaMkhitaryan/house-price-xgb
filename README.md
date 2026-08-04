# House Price Prediction with XGBoost

A Machine Learning project that predicts house prices using **XGBoost Regression**.

## Project Overview
This project takes housing data, cleans it up, and uses a machine learning model called **XGBoost** to estimate house prices.

* **Train the Model:** Clean data and build the XGBoost model.
* **Save the Model:** Save the trained model so it can be reused.
* **Make Predictions:** Load the saved model to predict prices on new data.

---

## What’s in This Repository?

* **`_XGBoost_model.ipynb`**  
  The main notebook where data is explored, cleaned, and used to train the model.
* **`prediction_notebook.ipynb`**  
  The notebook used to test and make predictions using the trained model.
* **`house_price_xgb.pkl`**  
  The saved, pre-trained XGBoost model file.
* **`requirements.txt`**  
  A list of Python libraries needed to run the project.
* **`houses_train.csv`**  
  The training dataset containing house features and target sale prices.

---

## How to Run This Project

### 1. Install Required Libraries
Open your terminal (or command prompt) in the project folder and run:

**pip install -r requirements.txt** 

### 2. Run the Notebooks
* Open **`_XGBoost_model_final.ipynb`** if you want to see how the model was built and trained.
* Open **`prediction_notebook.ipynb`** if you just want to load the trained model (`house_price_xgb.pkl`) and make new predictions!
