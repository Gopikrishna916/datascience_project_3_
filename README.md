# 📈 Financial Data Analysis & Stock Price Prediction Using Yahoo Finance

## 📌 Project Overview
This project analyzes historical stock market data using **Yahoo Finance** and applies
**data science and machine learning techniques** to understand price behavior and predict
future movements.

The project includes **EDA, technical indicators, regression, and classification models**
to support financial insights.

---

## 🎯 Problem Statement
Stock market data is volatile and complex.
Manual analysis is inefficient and error-prone.

**Goal:**  
Use data science and machine learning to analyze stock trends and predict
**next-day movement and future prices**.

---

## 🎯 Objectives
- Fetch stock data using Yahoo Finance
- Perform Exploratory Data Analysis (EDA)
- Engineer technical indicators (MA, RSI)
- Predict next-day movement (Up/Down)
- Predict future stock prices
- Evaluate model performance

---

## 📊 Dataset Description
Features used in this project:
- Date
- Open, High, Low, Close prices
- Volume
- Moving Average (MA_10)
- RSI
- Next Day Movement
- Future Price

---

## 🔍 Exploratory Data Analysis (EDA)

### 🔹 Open vs Close Price
![Open vs Close](images/open_vs_close.png)

**Insight:**  
Shows the relationship between opening and closing prices and highlights price volatility.

---

### 🔹 Dataset Preview
![Dataset Preview](images/dataset_preview.png)

**Insight:**  
Displays cleaned and feature-engineered stock data.

---

### 🔹 Feature Engineering View
![Feature Engineering](images/feature_engineering.png)

**Insight:**  
Confirms successful creation of MA, RSI, and future price features.

---

## 📈 Technical Indicators

### 🔹 Moving Average & RSI
![Indicators Plot](images/indicators_plot.png)

**Insight:**  
- Moving Average smooths price trends  
- RSI identifies overbought/oversold zones  

---

## 🧠 Machine Learning Models Used

### 🔹 Regression
- Linear Regression
- Random Forest Regression

### 🔹 Classification
- Next Day Price Movement (Up / Down)

---

## 📐 Model Evaluation

### 🔹 Regression Results
![Regression Results](images/regression_results.png)

**Insight:**  
Random Forest performs better than Linear Regression due to non-linear patterns.

---

### 🔹 Classification Performance
![Classification Report](images/classification_report.png)

**Key Result:**  
Accuracy ≈ **88%**

---

## 🔗 Correlation Analysis
![Correlation Heatmap](images/correlation_heatmap.png)

**Insight:**  
Shows relationships between price features and future price.

---

## 📊 Distribution Analysis

### 🔹 Future Price Distribution
![Future Price Distribution](images/future_price_distribution.png)

---

### 🔹 Categorical Target Distribution
![Categorical Analysis](images/categorical_analysis.png)

---

## 🛠️ Tech Stack
- Python
- yfinance
- pandas, numpy
- matplotlib, seaborn
- scikit-learn

---

## 📂 Project Structure
