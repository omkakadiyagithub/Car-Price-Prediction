# Car Price Prediction using Regression Models

This project demonstrates the prediction of car selling prices using regression models. It includes data preprocessing, feature encoding, and model evaluation using **Linear Regression** and **Lasso Regression**.

---

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Project Steps](#project-steps)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Technologies Used](#technologies-used)
- [Acknowledgments](#acknowledgments)

---

## Overview

The goal of this project is to build a machine learning model that can accurately predict the selling price of cars based on several features such as fuel type, seller type, and transmission. 

The models used in this project are:
- **Linear Regression**
- **Lasso Regression**

Both models were evaluated on their ability to predict prices using R-squared error and scatter plots for visualization.

---

## Dataset

The dataset used in this project is named `car data.csv`, containing details of various cars like:
- **Car Name**
- **Selling Price**
- **Present Price**
- **Fuel Type**
- **Seller Type**
- **Transmission**
- **Owner**

---

## Project Steps

1. **Data Loading and Exploration**
   - Load the dataset and inspect its structure, missing values, and data types.

2. **Data Preprocessing**
   - Encode categorical variables (`Fuel_Type`, `Seller_Type`, `Transmission`) using numerical values.

3. **Feature Selection**
   - Exclude the `Car_Name` and target variable `Selling_Price` from the feature set.

4. **Splitting the Data**
   - Split the dataset into training and test sets (90% training, 10% testing).

5. **Model Training and Evaluation**
   - Train Linear Regression and Lasso Regression models on the training data.
   - Evaluate models using R-squared error and scatter plot visualizations.

---

## Model Training and Evaluation

### 1. Linear Regression
- **Training R-squared Error**: _Displayed during execution_
- **Testing R-squared Error**: _Displayed during execution_
- **Visualization**: Scatter plots comparing actual vs predicted prices.

### 2. Lasso Regression
- **Training R-squared Error**: _Displayed during execution_
- **Testing R-squared Error**: _Displayed during execution_
- **Visualization**: Scatter plots comparing actual vs predicted prices.

---

## Installation

1. Clone the repository:
   ```bash
   git clone [https://github.com/omkakadiyagithub/Car-Price-Prediction.git]
