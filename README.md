---
title: "Predicting Taxi Trip Duration in NYC"
---
Description:
This project aims to predict the duration of taxi trips in New York City using machine learning models. It leverages a dataset containing taxi trip records with details such as pickup/dropoff locations, timestamps, and trip duration. Two primary models, Linear Regression and Random Forest, were trained and evaluated based on their performance in predicting trip durations.

Dataset: `nyc-taxi-trip-duration.zip` (train.zip)
- 1,458,644 records
- Features: `id`, `vendor_id`, `pickup_datetime`, `dropoff_datetime`, `passenger_count`, `pickup_longitude`, `pickup_latitude`, `dropoff_longitude`, `dropoff_latitude`, `store_and_fwd_flag`, `trip_duration`

Methodology:
- Data Preprocessing: Extracted timestamps, engineered datetime and geographical features.
- Models: Linear Regression, Random Forest
- Evaluation: MSE, RMSE, MAE, R², Custom Accuracy

Results:
- Linear Regression:
  - Train RMSLE: 0.65, Valid RMSLE: 0.64
  - RMSE: 3,117.70, MAE: 317.26, R²: 0.03, Custom Accuracy: 0.26

- Random Forest:
  - Train RMSLE: 0.41, Valid RMSLE: 0.43
  - RMSE: 3,117.70, MAE: 317.26, R²: 0.03, Custom Accuracy: 0.26

Conclusion:
- Similar performance observed between Linear Regression and Random Forest models.
- Potential for further improvement through feature engineering and model tuning.
