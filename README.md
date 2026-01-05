# Housing Price Prediction using Linear Regression

This project focuses on predicting median house values using demographic and geographic features from the California Housing dataset. The goal is to apply a complete data science workflow including data exploration, visualization, feature engineering, and machine learning modeling.

---

## Project Overview

Accurate house price prediction is an important problem in real estate and urban planning. This project demonstrates how linear regression can be used as a baseline model to understand relationships between housing prices and factors such as income levels, population density, and proximity to the ocean.

---

## Dataset

- Source: California Housing Dataset
- Rows: 20,640
- Target Variable: `median_house_value`

### Features include:
- Geographic coordinates (latitude, longitude)
- Median income
- Population and household statistics
- Housing age and room counts
- Ocean proximity (categorical)

---

## Project Workflow

1. Data loading and inspection  
2. Handling missing values  
3. Exploratory Data Analysis (EDA)  
4. Data visualization  
5. Feature encoding  
6. Train-test split  
7. Linear Regression model training  
8. Model evaluation  

---

## Exploratory Data Analysis

Key visual analyses performed:
- Distribution of median house values
- Relationship between median income and house prices
- House price comparison by ocean proximity
- Feature correlation heatmap

These analyses helped identify strong predictors and validate the choice of a linear model.

---

## Model Used

- **Linear Regression**
- Evaluation Metrics:
  - Mean Squared Error (MSE)
  - R² Score

### Results:
- R² Score ≈ 0.62  
- Indicates a strong baseline performance for a linear model

---

## Key Insights

- Median income is the strongest predictor of house prices
- Houses closer to the ocean tend to have higher values
- Linear relationships dominate, making Linear Regression suitable as a baseline

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## How to Run the Project

1. Clone the repository
   git clone https://github.com/Priyank0809/housing-price-prediction.git

2. Navigate to the project directory
    cd housing-price-prediction

3. Install dependencies
    pip install -r requirements.txt

4. Open the notebook
    jupyter notebook notebooks/housing_price_prediction.ipynb

