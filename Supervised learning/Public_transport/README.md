
# Public Transport Delays Prediction  
This repository contains an end‑to‑end project for predicting public transport delays using weather data, city events, traffic conditions and scheduling information. The project covers both classification and regression tasks. It also includes threshold calibration for imbalanced classification.

---

## Dataset  
The dataset comes from Kaggle: [Public Transport Delays with Weather and Events](https://www.kaggle.com/datasets/khushikyad001/public-transport-delays-with-weather-and-events/data)

### About the dataset  
This dataset simulates public transport delays influenced by several real‑world factors such as:

Transport timetables: scheduled and actual arrival or departure times  
Weather conditions: temperature, precipitation, wind and humidity  
City events: concerts, sports, protests, festivals and parades  
Traffic congestion: road conditions affecting surface transport  
Contextual features: holidays, peak hours, weekdays and seasons  

The main challenge is to predict if a trip will be delayed (0 or 1) using all these conditions.

This dataset can be used for:

Classification: predict if the trip will be delayed  
Regression: predict how many minutes the delay will be  
Time series forecasting: study delay patterns across days or seasons  
Feature engineering practice: combine weather, events and scheduling data  

---

## Project Goals  
The project explores two modeling approaches:

Classification  
Predict if a trip will be delayed.  
Includes handling of class imbalance, threshold calibration and evaluation focused on the minority class.

Regression  
Predict the number of minutes of delay.  
Includes feature engineering, model selection and error analysis.

---

## Tech Stack  
The project uses the following tools and libraries:

Python  
pandas  
numpy  
scikit‑learn  
XGBoost  
matplotlib  
seaborn  

These tools are used for data cleaning, feature engineering, model training, evaluation and threshold calibration.

---

## Main Features  
Data exploration and cleaning  
Feature engineering for weather, events and scheduling  
Binary classification with imbalanced data  
Threshold calibration for better minority class detection  
Regression modeling for delay duration  
Model evaluation with multiple metrics  
