# Automobile Price Prediction

## Overview
This project aims to predict automobile prices based on a dataset containing information about various automobile attributes. It involves data analysis, preprocessing, modeling, and interpretability techniques. The primary goal is to develop a regression model that accurately predicts the price of automobiles.

## Table of Contents
- [Dataset](#dataset)
- [Data Analysis](#data-analysis)
- [Data Preprocessing](#data-preprocessing)
- [Modeling](#modeling)
- [Model Evaluation](#model-evaluation)
- [Model Interpretability](#model-interpretability)
- [Usage](#usage)

## Dataset
The dataset used in this project is named 'autos.csv.' It contains information about automobiles, including features such as 'price,' 'yearOfRegistration,' 'powerPS,' 'kilometer,' 'model,' 'vehicleType,' 'gearbox,' and more. The dataset is used to train and evaluate the regression model.

## Data Analysis
The project begins with data analysis, where we explore the dataset to understand its structure. This includes examining the shape, columns, data types, and summary statistics of the dataset.

![Capture d’écran 2023-11-05 222135](https://github.com/khames-lab/used-cars-price-prediction/assets/77197337/e1bf7ec4-dc3f-43f5-bfa8-9855fee4c619)


## Data Preprocessing
Data preprocessing involves several steps:
- Handling missing values in categorical features.
- Extracting date-related features from 'dateCreated,' 'dateCrawled,' and 'lastSeen.'
- Handling outliers in specific columns.
- Feature selection to remove constant and quasi-constant features.

## Modeling
The project implements and evaluates several regression models, including:
- Linear Regression
- Decision Tree Regression
- Random Forest Regression
- XGBoost Regression

The models are trained to predict automobile prices based on the dataset's features.

## Model Evaluation
The models' performance is evaluated on a test dataset. Metrics like R-squared (R2), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE) are used to assess model accuracy and generalization.

## Model Interpretability
To gain insights into the models' decision-making processes, SHAP (SHapley Additive exPlanations) values are used for interpretability. SHAP values help understand feature importances and the impact of each feature on predictions.

![Capture d’écran 2023-11-05 222059](https://github.com/khames-lab/used-cars-price-prediction/assets/77197337/eb5e5ede-2d12-4c05-8214-548c8f6345c2)


## Usage
You can use this project to:
- Predict automobile prices based on given attributes.
- Analyze the importance of different features in predicting prices.
- Customize and improve the regression models.

Feel free to adapt and extend the code and analysis for your specific needs.
