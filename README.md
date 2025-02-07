# Car Price Prediction Model

## Project Overview
This project focuses on developing a machine learning model to predict car prices based on various features. The aim is to help both buyers and sellers make informed decisions by analyzing historical data and relevant attributes. 

## Objectives
- Develop a machine learning model to accurately predict car prices.
- Analyze historical car sales data to identify patterns and correlations.
- Provide a valuable tool for consumers and industry professionals.

## Dataset
- **Source:** [Kaggle - Car Prices Dataset](https://www.kaggle.com/datasets/sidharth178/car-prices-dataset)
- **Features:** 18 columns including Price, Manufacturer, Model, Production Year, Category, Engine Volume, and more.
- **Records:** 19,237 rows

## Methodology
### 1. **Data Collection and Exploration**
- Collected and explored the dataset containing car specifications and prices.

### 2. **Data Preprocessing**
- Checked and removed null values.
- Handled missing values and updated columns according to data types.
- Dropped unwanted columns and encoded categorical features.
- Classified rare values under "Other" and split the dataset into training and testing sets.

### 3. **Model Building and Evaluation**
- **Algorithms Used:**
  - Random Forest Regressor
  - XGBoost (XGB) Algorithm
  - Gradient Boosting Regressor (GBR)
- **Best Model:** Gradient Boosting Regressor (GBR) achieved the highest testing accuracy.

## Technologies Used
- **Programming Language:** Python
- **Development Environment:** Google Colaboratory Notebook, VS Code
- **Version Control:** GitHub

## Key Features
- Accurate car price predictions based on user input.
- High model accuracy using GBR algorithm.

## Conclusion
This project successfully developed a car price prediction system using machine learning techniques. The solution provides valuable insights and serves as a helpful tool for both consumers and industry professionals.
