# Stock Price Prediction using Random Forest

## Overview

This program utilizes historical stock data from Apple Inc. (AAPL) to predict future stock prices. By engineering lagged features and employing a Random Forest model, the program aims to capture historical patterns in data to forecast future prices.

## Features
* Data Loading: Automatically fetches stock data from an online CSV source.
* Cleaning and Preprocessing: Cleans the dataset and prepares it for analysis.
* Feature Engineering: Constructs lagged features to enhance prediction quality.
* Model Training: Utilizes a Random Forest regressor for improved accuracy.
* Evaluation and Visualization: Outputs the model's performance and plots results.

## Installation
#### To run this project locally, please ensure you have Python installed along with the necessary dependencies:
pip install -r requirements.txt
#### Contents of requirements.txt:
pandas\
scikit-learn\
matplotlib

## Usage
#### 1. Clone the Repository Clone this repository to your local machine using:
git clone https://github.com/yourusername/repositoryname.git
#### 2. Navigate to the Project Directory Change your directory to the cloned repository:
cd repositoryname
#### 3.Run the Prediction Script Execute the main script to initiate the data processing, training, and visualization:
python stock_price_prediction.py\

This script will load the data, preprocess it, train the Random Forest model, and produce a plot of actual vs. predicted stock prices.

## Process Breakdown

Setup and Data Loading: Packages are installed, libraries imported, and the dataset is fetched directly from an online source.\
Data Cleaning: Unnecessary columns are removed, and date formats are converted for analysis.\
Feature Engineering: Lagged features are created to enable the model to learn from previous stock data.\
Model Training: The data is split, and a Random Forest model is trained on the features.\
Evaluation and Visualization: The model’s performance is evaluated using MSE and visualized with Matplotlib.

## Contributing

This project is licensed under the MIT License. For more information, see the LICENSE file.

## License

This project is licensed under the MIT License. For more information, see the LICENSE file.


