# Predicting-House-Prices

🚀 How to Run
Download the Files

Download the .ipynb notebook file and the housing.csv dataset from this repository.

Open in Jupyter Notebook

Upload both files to your Jupyter Notebook environment (like Anaconda, Jupyter Lab, or Google Colab).

Run the Notebook

Open the notebook and run each code block step by step, from top to bottom.

Test the Model

At the end of the notebook, you can enter your own values to see the model predict the median house price.



🏠 California Housing Price Prediction
This project uses machine learning models to predict median house values based on various housing features from the California Housing Dataset.

📊 Project Overview
The goal of this project is to build and compare regression models that predict housing prices. It includes:

Data preprocessing and feature engineering

Implementation of three regression models:

Linear Regression

Random Forest Regressor

XGBoost Regressor

Evaluation of model performance using RMSE and R² metrics

Feature importance visualization for tree-based models

Interactive input section to test predictions on custom values

🛠️ Tech Stack
Python

Pandas, NumPy

Scikit-learn

XGBoost

Matplotlib

Jupyter Notebook

📁 Dataset
The dataset used is based on the California Housing dataset.
Make sure to have a housing.csv file in the same folder as your notebook. The file should include columns like:

longitude, latitude, housing_median_age, total_rooms, total_bedrooms, population, households, median_income, and ocean_proximity.

📌 Project Structure
Data Preprocessing: Handling missing values, encoding categorical features, and feature scaling.

Model Implementation: Training Linear Regression, Random Forest, and XGBoost models.

Model Evaluation: Comparing models using RMSE and R².

Feature Importance: Visualizing which features influence the model most (tree models).

User Input Prediction: Input values via command line to test the model on custom data.

📈 Results
The project compares three models.

Random Forest and XGBoost generally perform better than simple Linear Regression.

Feature importance helps understand what affects house prices the most.
