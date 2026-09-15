# Bike Rental Demand Prediction

## Project Overview

This project focuses on predicting bike rental demand using machine learning. The objective is to estimate the number of bike rentals based on factors such as time, season, weather, temperature, humidity, and windspeed.

## Machine Learning Approach

- Problem Type: Regression
- Model: Linear Regression
- Target Variable: `count`

## Features Used

- year
- hour
- season
- holiday
- workingday
- weather
- temp
- atemp
- humidity
- windspeed

The `id` column was excluded because it is an identifier rather than a feature that determines bike rental demand.

## Exploratory Data Analysis

The analysis showed that rental demand varies significantly with time and weather conditions.

The highest average rental demand was observed at **5 PM (hour 17)**, with approximately **472 rentals**.

The strongest positive correlations with rental demand were observed for:

- Hour: 0.404101
- Temperature: 0.397235
- Feels-like Temperature: 0.392014

Humidity showed a negative correlation with demand:

- Humidity: -0.324662

## Model Evaluation

The Linear Regression model achieved the following evaluation results:

- MAE: 75.1
- MSE: 10400.7
- RMSE: 101.98
- R² Score: 0.6879

## Prediction Application

A prediction application was developed using Gradio. Users can enter time and weather conditions and receive an estimated bike rental demand.

## Project Files

- `Phase_1.ipynb` — Problem understanding and project planning
- `Phase_5.ipynb` — Model training and evaluation
- `Phase_7.ipynb` — Final implementation and prediction application
- `bike_rental_predictions.csv` — Generated prediction results

## Internship Project

This project was developed as part of a Machine Learning internship at **Big Brains**.

## Conclusion

The project demonstrates how machine learning can be used to estimate bike rental demand from historical time and weather-related data. The final model and prediction application provide a practical demonstration of the complete machine learning workflow.
