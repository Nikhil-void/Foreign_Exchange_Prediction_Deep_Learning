# Forex Prediction Using Machine Learning

## Overview

This project aims to predict foreign exchange (Forex) rates using machine learning models. The goal is to assist traders and investors in making informed decisions by leveraging predictive analytics on historical forex data.

## Features

- **Data Preprocessing:** Clean and preprocess historical Forex data for model training.
- **Model Development:** Develop and train machine learning models to predict future Forex rates.
- **Model Evaluation:** Evaluate the performance of different models using metrics like RMSE, MAE, etc.
- **Prediction Visualization:** Visualize the predictions to help users understand model performance and forecast trends.

## Data

The project uses historical Forex data from various sources. The data includes features such as:

- Exchange rates (e.g., EUR/USD, GBP/USD)
- Volume of trade
- Macroeconomic indicators
- Market sentiment indicators

## Models Used

- **Linear Regression**
- **Random Forest**
- **XGBoost**
- **LSTM (Long Short-Term Memory) Networks**

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/forex-prediction.git
    ```
2. Navigate to the project directory:
    ```sh
    cd forex-prediction
    ```
3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```
4. Run the preprocessing script to prepare the data:
    ```sh
    python preprocess_data.py
    ```
5. Train the model:
    ```sh
    python train_model.py
    ```
6. Evaluate the model and visualize predictions:
    ```sh
    python evaluate_model.py
    ```

## Usage

- **Training:** Train the machine learning model on historical Forex data.
- **Prediction:** Generate future Forex rate predictions using the trained model.
- **Evaluation:** Assess the model's performance using evaluation metrics and visualize the results.

## Results

The model's performance is evaluated based on metrics like RMSE and MAE. The project demonstrates how machine learning models can be used for time series prediction in the Forex market.

## Future Work

- **Model Optimization:** Explore hyperparameter tuning to improve model accuracy.
- **Real-Time Prediction:** Implement real-time Forex prediction by integrating live data feeds.
- **Additional Features:** Incorporate additional features such as geopolitical events and sentiment analysis.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or new features.



