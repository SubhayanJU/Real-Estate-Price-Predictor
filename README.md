# Real-Estate-Price-Predictor

This project aims to predict house prices using various regression models. The models implemented include Linear Regression, Decision Tree Regression, and Random Forest Regression. After evaluating their performance, the Random Forest Regressor was selected as the best model due to its highest accuracy.

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Models Used](#models-used)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Results](#results)
7. [License](#license)
8. [Acknowledgements](#acknowledgements)

## Introduction

This project involves predicting house prices based on various features using machine learning techniques. The dataset contains multiple attributes related to properties which are used to train and test the regression models. 

The final model chosen for prediction is the Random Forest Regressor due to its superior performance in terms of accuracy.

## Features

- **Dataset**: A comprehensive dataset of real estate properties with features such as square footage, number of bedrooms, number of bathrooms, location, etc.
- **Models Implemented**:
  - Linear Regression
  - Decision Tree Regression
  - Random Forest Regression

## Models Used

### Linear Regression

Linear Regression is a fundamental regression technique that models the relationship between dependent and independent variables as a linear equation.

### Decision Tree Regression

Decision Tree Regression involves creating a decision tree that splits the data into branches based on feature values to make predictions.

### Random Forest Regression

Random Forest Regression is an ensemble method that combines multiple decision trees to improve prediction accuracy and control overfitting.

## Installation

To run this project, you need Python and the following libraries:

- `numpy`
- `pandas`
- `scikit-learn`
- `matplotlib`
- `seaborn`

You can install the required libraries using pip:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

## Usage

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/real-estate-house-price-prediction.git
    ```

2. Navigate to the project directory:

    ```bash
    cd real-estate-house-price-prediction
    ```

3. Run the script to execute the models and evaluate their performance:

    ```bash
    python house_price_prediction.py
    ```

4. The script will output the performance metrics of each model and indicate the best-performing model.

## Results

After evaluating all three models using cross-validation, the Random Forest Regressor achieved the highest accuracy of **95.11%**, making it the chosen model for house price prediction.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements

- The dataset used in this project is sourced from [dataset source or provider].
- Special thanks to the contributors and community for providing valuable resources and support.

---
