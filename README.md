# ETA prediction Machine learning model using Python 

This is a local machine learning web application that predicts the Estimated Time of Arrival (ETA) for a trip based on travel distance, day of the week, time of day, and traffic conditions. 

## Features
Uses an XGBoost Regression model for accurate ETA prediction.
- Built with a Streamlit frontend for easy user interaction.
- Supports real-time input or Excel-based input.
- Distance calculation using OpenRouteService API and geopy.


## How it works
1. User Input  
The user fills in a form on the Streamlit web interface:
- Pickup location  
- Drop location  
- Day of the week  
- Time of day  

2. Distance Calculation  
- The app uses **OpenRouteService API** and `geopy` to calculate distance between locations.

3. Prediction  
- The trained model (XGBoost) processes the input features and predicts the ETA (in minutes).

4. Output  
- The predicted ETA is displayed instantly on the web interface.


## Folder Structure

eta-predictor/

├── python/ # Python scripts (training, app.py)

├── Analysis/ # Screenshots or plots for data analysis

├── eta_model.pkl # Saved ML model

├── ETA_BENGALURU_DATASET.xlsx # Dataset used for training

└── README.md # Project overview

## Requirements
 For Model Training
- pandas 
- numpy 
- scikit-learn  
- xgboost
- openpyxl

For Web Interface
- streamlit
- requests  
- geopy 
- openrouteservice

ETA Prediction Web App

[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://your-app-name.streamlit.app)
  
## Author
Kirana BV
