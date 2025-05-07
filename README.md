# Automobile Price Prediction Project

## Overview
This project aims to predict the prices of automobiles based on various features using machine learning techniques. The dataset contains information about different car models, including technical specifications and their corresponding prices. The analysis includes exploratory data analysis (EDA), data preprocessing, model building, and evaluation.


## Technologies Used
- **Python**: The primary programming language used for data analysis and model building.
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computations.
- **Matplotlib & Seaborn**: For data visualization.
- **TensorFlow**: For building and training machine learning models.
- **Scikit-learn**: For data preprocessing and model evaluation.

## Data Description
The dataset used in this project is sourced from a public repository and contains the following features:
- `symboling`: A numerical value representing the risk factor of the car.
- `normalized-losses`: The average loss in the event of a claim.
- `make`: The manufacturer of the car.
- `fuel-type`: The type of fuel used by the car (e.g., gas, diesel).
- `aspiration`: The aspiration type of the engine (e.g., std, turbo).
- `num-of-doors`: The number of doors in the car.
- `body-style`: The style of the car body (e.g., sedan, hatchback).
- `drive-wheels`: The type of drive wheels (e.g., fwd, rwd).
- `engine-location`: The location of the engine (e.g., front, rear).
- `wheel-base`, `length`, `width`, `height`: Dimensions of the car.
- `curb-weight`: The weight of the car.
- `engine-type`: The type of engine.
- `num-of-cylinders`: The number of cylinders in the engine.
- `engine-size`: The size of the engine.
- `fuel-system`: The fuel system used.
- `bore`, `stroke`: Engine specifications.
- `compression-ratio`: The compression ratio of the engine.
- `horsepower`: The power output of the engine.
- `peak-rpm`: The maximum engine speed.
- `city-mpg`, `highway-mpg`: Fuel efficiency metrics.
- `price`: The target variable representing the price of the car.

## Model Evaluation
The model's performance is evaluated using metrics such as:

- R-squared (R²)
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

These metrics help in understanding how well the model predicts the prices based on the input features.

## Contributing
Contributions are welcome! If you have suggestions for improvements or want to add features, feel free to fork the repository and submit a pull request.
