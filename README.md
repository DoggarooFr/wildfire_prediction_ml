# wildfire_prediction_ml
Machine learning models for predicting notable wildfires using the 1.8M US wildfire dataset (1992–2015) from Kaggle

# Wildfire Prediction Using Machine Learning

This project analyzes the 1.8 million wildfire dataset (1992–2015) to predict the probability of notable wildfire events occurring in the next month at the county level.

## Models Used
- Logistic Regression (baseline)
- XGBoost

## Features
- Lagged wildfire counts
- Rolling fire statistics
- Seasonal variables (sin/cos month encoding)
- Spatial clustering (K-means)

## Evaluation
Model performance was evaluated using AUC with a rolling time-based cross-validation scheme.

## Dataset
1.88 Million US Wildfires 24 years of geo-referenced wildfire records (https://www.kaggle.com/datasets/rtatman/188-million-us-wildfires/data)

## Author
Frank M — UC Davis
