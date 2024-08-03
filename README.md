# NYC Temperature Prediction Using Linear Regression

This repository contains a project for predicting temperatures in New York City using linear regression. The dataset used consists of temperature records, and the model's performance was evaluated using different training/testing splits.

## Project Overview

The primary goal of this project is to build a linear regression model to predict temperatures and evaluate its performance using various train-test split ratios. The RMSE (Root Mean Squared Error) was used as the performance metric to compare different splits.

## Dataset

The dataset contains temperature records for New York City. The temperatures are in degrees Celsius.

## Train-Test Splits and RMSE Results

The dataset was split into training and testing sets using four different ratios: 80:20, 50:50, 90:10, and 75:25. The RMSE for each split is as follows:

- **80:20 Split**: RMSE = 4.22
- **50:50 Split**: RMSE = 4.36
- **90:10 Split**: RMSE = 4.26
- **75:25 Split**: RMSE = 4.28

### Analysis and Conclusion

- The **80:20 split** resulted in the lowest RMSE (4.22), indicating the best model performance.
- The **50:50 split** had the highest RMSE (4.36), suggesting that having less training data negatively impacted the model's performance.
- The RMSE values for the **90:10 split** (4.26) and **75:25 split** (4.28) were close to each other and slightly higher than the 80:20 split.

### Recommendation

Based on the RMSE values, the **80:20 split** is recommended for training and testing the linear regression model. It provides a good balance between the amount of training data and the size of the test set, leading to the best model performance.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook or any Python IDE

### Dependencies

Install the required Python libraries using:

```bash
pip install -r requirements.txt
