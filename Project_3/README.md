# Linear Regression for Tips Prediction

## Overview
This project demonstrates the implementation of linear regression using PyTorch for predicting tips based on total price. It aims to build a simple predictive model that can estimate the tip amount given the total bill.

## Dataset
The dataset used for this project contains information about the total bill and the corresponding tip amount. It is a small dataset collected from a restaurant.

## Files
- `linear_regression_tips_prediction.ipynb`: The main Python script implementing the linear regression model for tips prediction.
- `tips = sns.load_dataset('tips')`: The dataset file containing total price and tips information.

## Usage
1. **Install Dependencies**: Make sure you have PyTorch installed. You can install it using pip:
    ```sh
    pip install torch
    ```

2. **Clone the Repository**: Clone this repository to your local machine:
    ```sh
    git clone https://github.com/YOUR-USERNAME/Linear-Regression-for-Tips-Prediction.git
    ```

3. **Navigate to Project Directory**: Go to the project directory:
    ```sh
    cd Linear-Regression-for-Tips-Prediction
    ```

4. **Run the Script**: Execute the Python script to train the model and make predictions:
    ```sh
    python linear_regression_tips.py
    ```

## Results
After running the script, you will see the model training process and the predicted tip amounts for the given total prices. Additionally, evaluation metrics such as Mean Absolute Error (MAE) will be displayed.

