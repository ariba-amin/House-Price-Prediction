## Task Title
House Prce Prediction

## Project Overview
This project focuses on predicting house prices using Machine Learning techniques. The model is trained on the California Housing Dataset and uses various features such as location, number of rooms, population, to estimate house prices.

## Objective
The main objective of this project is to build a regression model that can accurately predict median house values based on given input features.

## Dataset
- kaggle Dataset: California Housing Dataset
- Features include:
  - Longitude & Latitude
  - Housing Median Age
  - Total Rooms & Bedrooms
  - Population & Households
  - Median Income

## Technologies Used
The following tools and libraries were used in this project:

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib

## Data Preprocessing
- Handled missing values
- Applied feature engineering:
  - rooms_per_household
  - bedrooms_per_room
  - population_per_household

## Model Used
- XGBoost Regressor
- Used Pipeline with StandardScaler for proper cross-validation

## Model Evaluation
- R² Score (used for accuracy measurement)
- Mean Squared Error (MSE)
- Cross-validation applied for better performance validation

## Project Files:

This project folder contains:

1. house_price_predicion.ipynb  -> Jupyter notebook containing full implementation
2. housing.csv  -> Dataset used for training the model
3. house_price_model.pkl  -> saved trained model
4. scaler.pkl  -> saved scaler
5. Readme.md  -> contains project information   

## Results
The model achieved a good R² score, indicating strong predictive performance. Cross-validation results also confirmed the model's stability.
