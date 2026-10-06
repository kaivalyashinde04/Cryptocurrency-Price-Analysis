# Cryptocurrency Price Analysis & Prediction

A Python-based cryptocurrency data analysis and machine learning project that analyzes historical market data and predicts Bitcoin (BTC) closing prices using multiple regression models.

## 📌 Project Overview

This project focuses on analyzing historical cryptocurrency market data for:

- Bitcoin (BTC)
- Ethereum (ETH)
- Tether (USDT)
- Binance Coin (BNB)

The project uses `yfinance` to collect historical data and applies Python-based data analysis, visualization, preprocessing, feature selection, and machine learning techniques.

Multiple regression models are trained and compared to identify their performance in predicting Bitcoin closing prices.

## 🎯 Objectives

- Collect historical cryptocurrency market data.
- Perform exploratory data analysis (EDA).
- Analyze cryptocurrency closing prices and trading volumes.
- Visualize trends and relationships between cryptocurrencies.
- Analyze correlations between cryptocurrency prices.
- Prepare data for machine learning.
- Select important features.
- Train multiple regression models.
- Compare model performance.
- Predict Bitcoin closing prices.
- Save the trained Random Forest model for future use.

## 🪙 Cryptocurrencies Analyzed

The project analyzes historical data for:

| Cryptocurrency | Symbol |
|---|---|
| Bitcoin | BTC |
| Ethereum | ETH |
| Tether | USDT |
| Binance Coin | BNB |

## 🛠️ Technologies Used

### Programming Language
- Python

### Data Collection
- yFinance

### Data Analysis
- Pandas
- NumPy

### Data Visualization
- Matplotlib
- Seaborn

### Machine Learning
- Scikit-learn

### Model Saving
- Pickle

## 📊 Data Analysis

The project performs several exploratory data analysis tasks, including:

### Closing Price Analysis
Analyzes historical closing prices of BTC, ETH, USDT, and BNB.

### Trading Volume Analysis
Analyzes the trading volume of the selected cryptocurrencies.

### Correlation Analysis
Uses correlation analysis and heatmaps to understand relationships between cryptocurrency prices.

### Distribution Analysis
Uses histograms and KDE plots to analyze the distribution of cryptocurrency prices.

### Pair Plot
A pair plot is used to visualize relationships between the selected cryptocurrency variables.

## ⚙️ Machine Learning Workflow

The machine learning workflow includes:

1. Data collection
2. Data cleaning and preparation
3. Exploratory Data Analysis
4. Feature selection
5. Train-test split
6. Feature scaling
7. Model training
8. Model evaluation
9. Model comparison
10. Random Forest model saving

## 🤖 Machine Learning Models

The project compares multiple regression algorithms:

- Linear Regression
- Ridge Regression
- Lasso Regression
- ElasticNet Regression
- Support Vector Regression (SVR)
- Decision Tree Regression
- Random Forest Regression
- Gradient Boosting Regression
- K-Nearest Neighbors Regression
- Multi-Layer Perceptron (MLP) Regression

## 🎯 Target Variable

The main target variable is:

**Bitcoin (BTC) Closing Price**

The project uses cryptocurrency market features to train regression models for Bitcoin closing-price prediction.

## 📏 Model Evaluation

The models are evaluated using:

- Mean Squared Error (MSE)
- R-squared (R²)

The performance of the different models is compared to determine their relative effectiveness.

## 🌲 Random Forest Model

A Random Forest Regression model is also trained and saved using Python's Pickle library.

The saved model can be loaded later for prediction without retraining the model.

## 📁 Project Structure

```text
Cryptocurrency-Price-Analysis/
│
├── Cryptocurrency_Price_Analysis.ipynb
├── README.md
├── random_forest_model.pkl
└── scaler.pkl
