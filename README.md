# California Housing Prediction

**Author:** Liam White  
**Date:** December 8, 2024

## Project Overview

This project analyzes and predicts California housing prices using a machine learning approach. The dataset, provided on [Kaggle](https://www.kaggle.com/datasets/camnugent/california-housing-prices), originates from the 1990 California Census and includes demographic, geographical, and economic data.

The goal is to determine which machine learning model most accurately predicts median housing values and to understand the impact of socio-economic and locational factors on housing prices.

---

## Dataset

- **Source:** Kaggle – "California Housing Prices"
- **Size:** Originally ~20,000 rows; sample of 500 used
- **Features Include:**
  - Median income
  - Housing age
  - Total rooms and bedrooms
  - Population and households
  - Ocean proximity
  - Latitude and longitude

---

## Project Structure

1. **Data Cleaning**
   - Removed outliers (housing prices capped at $500,001)
   - Normalized numerical features
   - Encoded categorical variables
   - Dropped missing values

2. **Exploratory Data Analysis (EDA)**
   - Visualized distributions of target and predictors
   - Explored geographic housing patterns
   - Analyzed income–housing value relationships

3. **Modeling**
   - Train/test split (70/30)
   - 5-fold cross-validation
   - Models fitted:
     - Linear Regression
     - Random Forest
     - Gradient Boosting Machines
     - K-Nearest Neighbors
     - Support Vector Machines

4. **Evaluation Metrics**
   - RMSE (Root Mean Squared Error)
   - MAE (Mean Absolute Error)
   - R² (Coefficient of Determination)

---

## Key Results

- **Best Model:** Random Forest  
  - **RMSE:** 0.1197  
  - **MAE:** 0.0912  
  - **R²:** 0.6506  

Random Forest outperformed other models due to its strength in modeling non-linear relationships and handling complex inter
