# Stock Price Prediction Using Machine Learning

## Project Overview

This project focuses on predicting stock prices using Machine Learning techniques. Historical stock market data was collected from Yahoo Finance and analyzed to identify market trends, patterns, and future price movements.

The project applies multiple regression models and ensemble learning techniques to compare prediction performance and identify the most accurate forecasting model.

---

## Objectives

- Analyze historical stock market data.
- Predict future stock prices using Machine Learning.
- Compare multiple prediction models.
- Evaluate model performance using standard metrics.
- Identify the best-performing model for stock forecasting.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn
- Jupyter Notebook
- Yahoo Finance (yFinance)

---

## Dataset

Historical stock market data was collected from Yahoo Finance.

Dataset Features:

- Open Price
- High Price
- Low Price
- Close Price
- Adjusted Close
- Trading Volume

Netflix (NFLX) stock data from 2018–2024 was used for analysis and prediction. :contentReference[oaicite:0]{index=0} :contentReference[oaicite:1]{index=1}

---

## Project Workflow

Data Collection

↓

Data Cleaning & Preprocessing

↓

Feature Engineering

↓

Model Training

↓

Model Evaluation

↓

Stock Price Prediction

---

## Feature Engineering

The project uses:

- 100-Day Moving Average
- 200-Day Moving Average
- Historical Closing Prices

These features help capture long-term and short-term stock trends. :contentReference[oaicite:2]{index=2}

---

## Machine Learning Models

- Linear Regression
- Support Vector Regression (SVR)
- Decision Tree Regressor
- Random Forest Regressor
- Stacking Ensemble Regressor

The models were evaluated using:

- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score :contentReference[oaicite:3]{index=3}

---

## Key Results

The Stacking Ensemble model achieved the best performance among all models.

| Model | R² Score |
|---------|---------|
| Linear Regression | 0.7559 |
| SVR | 0.8138 |
| Decision Tree | 0.8833 |
| Random Forest | 0.9210 |
| Stacking Ensemble | 0.9230 |

The Stacking Ensemble was selected as the final model due to its highest prediction accuracy. :contentReference[oaicite:4]{index=4}

---

## Key Insights

- Machine Learning can effectively identify stock price trends.
- Moving averages significantly improve forecasting performance.
- Ensemble learning techniques outperform individual models.
- Historical stock data can provide valuable insights for investment decisions. :contentReference[oaicite:5]{index=5}

---

## Future Improvements

- Deep Learning (LSTM)
- News Sentiment Analysis
- Economic Indicator Integration
- Real-Time Stock Prediction Dashboard
- Portfolio Optimization Features :contentReference[oaicite:6]{index=6}

---

## Author

**Pushpa Kumari**

MCA Graduate | Aspiring Data Analyst

Skills:
- Python
- SQL
- Power BI
- Excel
- Machine Learning
- Data Analytics
