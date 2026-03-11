# House Price Prediction Using Machine Learning

## Overview

This project implements a **house price prediction system** using machine learning techniques. It loads, cleans, and analyzes two housing datasets, then builds and evaluates regression models to predict property prices.

## Datasets

| Dataset | Description |
|---|---|
| `House_Price.csv` | Contains housing data with features like crime rate, residential area, air quality, number of rooms, age, distance metrics, teacher ratio, proximity to airports, hospitals, water bodies, and more. |
| `KC_BL_DATASET.csv` | King County housing dataset with features including price, bedrooms, bathrooms, living area (sqft), lot size, year built, and renovation details. |

## Features

- **Data Loading & Validation** – Checks for file existence before loading, with clear error messages if files are missing.
- **Data Cleaning & Preprocessing** – Handles missing values (mean imputation), removes duplicates, and selects relevant features.
- **Exploratory Data Analysis** – Generates correlation heatmaps and scatter plots to visualize relationships between features and target variables.
- **Model Training** – Builds and trains two regression models:
  - **Linear Regression**
  - **Random Forest Regressor**
- **Model Evaluation** – Evaluates model performance using:
  - Mean Absolute Error (MAE)
  - R² Score

## Technologies Used

- **Python 3**
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical computing
- **Matplotlib & Seaborn** – Data visualization
- **scikit-learn** – Machine learning models and evaluation metrics

## How to Run

1. Ensure Python 3 and the required libraries are installed:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
2. Place the dataset files (`House_Price.csv` and `KC_BL_DATASET.csv`) in the same directory as the notebook.
3. Open and run the Jupyter notebook:
   ```bash
   jupyter notebook major1.ipynb
   ```

## Project Structure

```
YOLO OBJECT DETECTION/
├── major1.ipynb          # Main Jupyter notebook with all code and analysis
├── House_Price.csv       # Housing dataset with environmental and infrastructural features
├── KC_BL_DATASET.csv     # King County housing dataset
└── README.md             # This file
```

## Author

Pranav Rathi
