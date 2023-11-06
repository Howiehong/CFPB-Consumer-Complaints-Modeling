README for CFPB Consumer Complaints Modeling
Overview
This Jupyter notebook is dedicated to building and evaluating a machine learning model for predicting consumer disputes based on the Consumer Financial Protection Bureau (CFPB) consumer complaints dataset.

Contents
Data Loading: The notebook begins by loading the dataset for exploration.
Exploratory Data Analysis (EDA): An initial EDA is conducted to understand the dataset better, including checking the distribution of the target variable and missing values.
Data Preprocessing: This includes handling missing values, encoding categorical variables, and splitting the data into training and test sets.
Model Training: An XGBoost classifier is trained on the undersampled dataset to predict whether a consumer will dispute a complaint.
Model Evaluation: The trained model is evaluated using a test set, and various performance metrics are reported.
Cost Analysis: The notebook includes a cost function and performs a cost analysis to evaluate the financial impact of using the model.
Libraries Used
NumPy
Pandas
imbalanced-learn
Scikit-learn
XGBoost
Matplotlib
How to Use
Load the notebook in a Jupyter environment.
Ensure all the required libraries are installed.
Run the cells in order to reproduce the analysis and model training.
Requirements
Python 3.x
Above-mentioned libraries installed in the Jupyter environment.
Author
Howard
