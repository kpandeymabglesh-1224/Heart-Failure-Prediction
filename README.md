# Heart Failure Prediction & Analysis

## Project Overview
This project is an end-to-end data science analysis using the Heart Failure Prediction dataset. The goal is to preprocess the data, perform exploratory data analysis (EDA) to find key insights, and build machine learning models (Random Forest, XGBoost) to predict the likelihood of a patient having cardiovascular disease.

## Dataset
The dataset used is the "Cardiovascular Disease dataset" from Kaggle. It contains 70,000 records of patient data with 11 features.

## Key Findings
* The Exploratory Data Analysis revealed strong correlations between age, cholesterol levels, and the presence of cardiovascular disease.
* The **XGBoost** model was the best-performing model, achieving an accuracy of **~72%** on the test set.
* Key predictors for the model included blood pressure, age, and BMI.

## How to Use
1.  Clone the repository.
2.  Ensure you have the required Python libraries (`pandas`, `numpy`, `seaborn`, `matplotlib`, `scikit-learn`, `xgboost`) installed.
3.  Open the `heart_Disease_Prediction.ipynb` file in a Jupyter Notebook environment and run the cells in order.
