# Housing Price Prediction using Machine Learning

This project predicts median house values using demographic and geographic features from the California Housing dataset. It demonstrates a complete end-to-end data science workflow including data preprocessing, exploratory data analysis, visualization, and machine learning modeling.

---

## Project Overview

House price prediction is a classic regression problem in data science. This project applies both a baseline linear model and a more powerful ensemble model to understand feature relationships and improve prediction accuracy.

---

## Dataset

- **Source:** California Housing Dataset
- **Total Rows:** 20,640
- **Target Variable:** `median_house_value`

### Features
- Longitude, Latitude
- Housing median age
- Total rooms and bedrooms
- Population and households
- Median income
- Ocean proximity (encoded)

---

## Project Workflow

1. Data loading and inspection  
2. Handling missing values  
3. Exploratory Data Analysis (EDA)  
4. Data visualization  
5. Feature encoding  
6. Train-test split  
7. Linear Regression model  
8. Random Forest Regressor  
9. Model evaluation and comparison  

---

## Exploratory Data Analysis

The following analyses were performed:

- Distribution of median house values  
- Relationship between median income and house prices  
- House prices by ocean proximity  
- Feature correlation heatmap  

These visualizations helped identify key predictors and justify model selection.

---

## Models Implemented

### 1️⃣ Linear Regression (Baseline Model)

- Simple and interpretable regression model
- Used as a baseline for performance comparison

**Results:**
- R² Score ≈ **0.62**
- Indicates a reasonable linear relationship between features and house prices

---

### 2️⃣ Random Forest Regressor

- Ensemble-based machine learning model
- Captures non-linear relationships and feature interactions

**Results:**
- R² Score significantly higher than Linear Regression
- Demonstrates improved predictive performance

---

## Model Comparison

| Model | R² Score |
|----|----|
| Linear Regression | ~0.62 |
| Random Forest | Higher |

Random Forest outperforms Linear Regression by capturing complex patterns in the data.

---

## Key Insights

- Median income is the strongest predictor of house prices
- Ocean proximity significantly impacts house value
- Ensemble models perform better than linear models for this dataset

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

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
