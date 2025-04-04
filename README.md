# House Price Prediction Project

> A machine learning project that predicts house prices using multiple regression models. The project analyzes house features like square footage, bedrooms, bathrooms, and location to predict market values using Linear Regression and Gradient Boosting algorithms.

🌐 **Live Demo**: [View Project](https://aryan21904.github.io/House-Price-Prediction-Project/)

## Overview

This project implements a house price prediction system using machine learning algorithms. It analyzes various features of houses such as square footage, number of bedrooms, bathrooms, and location to predict their market value.

## Features

- Data preprocessing and cleaning
- Feature engineering
- Multiple regression models:
  - Linear Regression
  - Gradient Boosting Regressor
- Model evaluation and comparison
- Interactive Jupyter notebooks for analysis

## Dataset

The project uses two datasets:
- `kc_house_data.csv`: King County house sales dataset
- `Housing.csv`: Additional housing dataset for model validation

## Requirements

- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- jupyter

## Installation

1. Clone the repository:
```bash
git clone https://github.com/aryan21904/House-Price-Prediction-Project.git
cd House-Price-Prediction-Project
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

## Usage

1. Open the Jupyter notebooks:
   - `house_price_prediction.ipynb`: Main analysis notebook
   - `housesales.ipynb`: Additional analysis and visualization

2. Run the cells in sequence to:
   - Load and preprocess the data
   - Train the models
   - Evaluate predictions
   - Visualize results

## Model Performance

The project compares the performance of different regression models:
- Linear Regression
- Gradient Boosting Regressor

Metrics used for evaluation:
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R-squared Score

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Acknowledgments

- Original tutorial and write-up: [Create a Model to Predict House Prices Using Python](https://medium.com/towards-data-science/create-a-model-to-predict-house-prices-using-python-d34fe8fad88f)
- King County House Sales dataset
- Contributors and maintainers
