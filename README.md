# Car Price Prediction 🚗

Welcome to the **Car Price Prediction** project! This project utilizes machine learning techniques to predict car prices based on various features.

## Overview

In this project, we developed a model to estimate car prices using a dataset that includes several features relevant to car pricing. Our approach involved preprocessing the data and employing a Linear Regression model to achieve high accuracy in predictions.

## Dataset

The dataset used for this project consists of various car attributes, which can include but are not limited to:
- Make and Model
- Year
- Mileage
- Engine Size
- Fuel Type
- Transmission Type

We split the dataset into two parts: training and testing sets. This allows us to train the model on one subset of the data and evaluate its performance on another.

## Data Preprocessing

1. **Train-Test Split**: The dataset was divided into training and testing sets to ensure the model can generalize well to unseen data.
  
2. **Standard Scaling**: We applied standard scaling to numerical features to normalize the data, which improves the performance of the linear regression model.

3. **One-Hot Encoding**: Categorical features were transformed into a format that can be provided to machine learning algorithms to improve prediction accuracy.

## Model

We implemented a **Linear Regression** model for predicting car prices. Linear regression is a powerful technique for modeling the relationship between a dependent variable (car prices) and one or more independent variables (car features).

## Achievements

We achieved a high accuracy in our predictions using the Linear Regression model, demonstrating the effectiveness of our preprocessing techniques and model selection.

## Web Interface

You can interact with the car price prediction model through the web interface hosted on Hugging Face Spaces:
[Car Price Prediction Model](https://huggingface.co/spaces/bilgeee/CarPricePrediction)
