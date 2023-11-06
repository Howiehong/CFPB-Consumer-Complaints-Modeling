# CFPB Consumer Complaints Modeling

## Overview
This Jupyter notebook is dedicated to building and evaluating a machine learning model for predicting consumer disputes based on the Consumer Financial Protection Bureau (CFPB) consumer complaints dataset.

## Contents
- **Data Loading**: The notebook begins by loading the dataset for exploration.
- **Exploratory Data Analysis (EDA)**: Conducts initial EDA to understand the dataset, including the distribution of the target variable and missing values.
- **Data Preprocessing**: Handles missing values, encodes categorical variables, and splits the data into training and test sets.
- **Model Training**: Trains an XGBoost classifier on the undersampled dataset to predict consumer disputes.
- **Model Evaluation**: Evaluates the trained model using a test set with various performance metrics.
- **Cost Analysis**: Includes a cost function and performs a cost analysis to evaluate the financial impact of using the model.

## Libraries Used
- `NumPy`
- `Pandas`
- `imbalanced-learn`
- `Scikit-learn`
- `XGBoost`
- `Matplotlib`

## How to Use
1. Load the notebook in a Jupyter environment.
2. Ensure all the required libraries are installed.
3. Run the cells in order to reproduce the analysis and model training.

## Requirements
- Python 3.x
- Above-mentioned libraries installed in the Jupyter environment.

## Author
- Howard
