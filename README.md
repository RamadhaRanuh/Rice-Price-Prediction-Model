# Rice Price Prediction using ARIMA and SARIMAX

This project focuses on predicting rice prices using ARIMA and SARIMAX forecasting models. The dataset is obtained through web scraping from a government databank. The predictions are then deployed using a Tkinter-based GUI application.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Methods](#methods)
  - [ARIMA](#arima)
  - [SARIMAX](#sarimax)
- [Implementation](#implementation)
  - [Web Scraping](#web-scraping)
  - [Modeling](#modeling)
  - [Deployment](#deployment)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Introduction

The purpose of this project is to predict rice prices using advanced time series forecasting techniques. Accurate price prediction is crucial for stakeholders in the agricultural sector, including farmers, traders, and policymakers. By leveraging ARIMA and SARIMAX models, this project aims to provide reliable forecasts based on historical price data.

## Dataset

The dataset used in this project is sourced from a government databank. The data is collected through web scraping and includes historical rice prices over a significant period. The dataset is preprocessed to handle missing values and anomalies before being used for modeling.

## Methods

### ARIMA

ARIMA (AutoRegressive Integrated Moving Average) is a popular time series forecasting method that combines autoregression, differencing, and a moving average model. It is suitable for univariate time series data.

### SARIMAX

SARIMAX (Seasonal AutoRegressive Integrated Moving Average with eXogenous regressors) extends ARIMA by including seasonal components and exogenous variables. It is useful for capturing seasonality and external factors influencing the rice prices.

## Implementation

### Web Scraping

The data is scraped from a government databank using Python libraries such as BeautifulSoup and requests. The script extracts the necessary information, cleans it, and stores it in a structured format for analysis.

### Modeling

The cleaned dataset is used to train ARIMA and SARIMAX models. The models are evaluated based on their accuracy in predicting historical prices. Hyperparameters are tuned to optimize the models' performance.

### Deployment

A user-friendly GUI application is developed using Tkinter to make the forecasting tool accessible. Users can input parameters, view historical data, and get rice price predictions through the application.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/rice-price-prediction.git
    ```

2. Navigate to the project directory:
    ```sh
    cd rice-price-prediction
    ```

3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

4. Run the application:
    ```sh
    python app.py
    ```

## Usage

1. Launch the application by running `python app.py`.
2. Use the interface to input parameters and view predictions.
3. The application will display historical rice prices and forecasted prices based on the selected model.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes. For major changes, please open an issue to discuss your proposed changes.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/YourFeature`)
3. Commit your Changes (`git commit -m 'Add some feature'`)
4. Push to the Branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

