# 📈 Time Series Analysis Using R

This repository contains my **Module 4 Time Series Analysis Assignment**, completed in **R** as part of coursework in predictive analytics and forecasting. The project demonstrates the application of several time series forecasting techniques and regression models to analyze historical data and generate future forecasts.

---

## 📋 Project Overview

The assignment is divided into three independent analyses, each using a different real-world dataset:

### Part 1 – U.S. Domestic Airfare Forecasting
**Dataset:** `airfare.csv`

Objective:
- Analyze historical average U.S. domestic airfare (2004–2018)
- Forecast average airfare for 2019

Methods Used:
- Time Series Visualization
- Simple Moving Average (3-Year)
- Simple Exponential Smoothing (α = 0.2)
- Simple Exponential Smoothing (α = 0.8)
- Forecast Accuracy Evaluation

Accuracy Measures:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Percentage Error (MAPE)

---

### Part 2 – Warner Music Group Revenue Forecasting
**Dataset:** `warner_music.csv`

Objective:
- Forecast quarterly revenue for 2022

Methods Used:
- Time Series Visualization
- Linear Regression (Trend Only)
- Linear Regression (Trend + Seasonality)
- Quarterly Dummy Variables
- Revenue Forecasting

Accuracy Measures:
- RMSE
- Model Comparison

---

### Part 3 – Amazon Web Services Revenue Forecasting
**Dataset:** `amazon_web_services.csv`

Objective:
- Forecast quarterly AWS revenue for 2022

Methods Used:
- Linear Trend Regression
- Nonlinear Regression Model
- Time Series Trend Analysis
- Revenue Forecasting

Accuracy Measures:
- MAPE
- Model Performance Comparison

---

## 🛠️ Technologies Used

- R
- RStudio
- TTR
- forecast
- ggplot2
- dplyr

---

## 📂 Repository Structure

```
time-series-analysis-using-r/
│
├── Module 4 Assignment_Time Series Analysis.docx
├── Module4_Assignment.Rmd
├── airfare.csv
├── warner_music.csv
├── amazon_web_services.csv
├── README.md
└── .gitignore
```

---

## 🚀 Skills Demonstrated

- Time Series Analysis
- Forecasting Techniques
- Regression Modeling
- Trend Analysis
- Seasonal Analysis
- Data Visualization
- Forecast Accuracy Evaluation
- Business Data Analytics
- R Programming

---

## 📊 Forecasting Techniques Covered

- Simple Moving Average
- Simple Exponential Smoothing
- Linear Regression
- Trend Modeling
- Seasonality Modeling
- Nonlinear Regression

---

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

- Building forecasting models using R
- Comparing forecasting methods using statistical accuracy measures
- Modeling trend and seasonality in time series data
- Interpreting regression coefficients
- Generating business forecasts from historical data

---

## ▶️ Running the Project

1. Clone this repository:

```bash
git clone https://github.com/raahim27-hash/time-series-analysis-using-r.git
```

2. Open the project in RStudio.

3. Install the required packages if needed:

```r
install.packages(c("forecast", "TTR", "ggplot2", "dplyr"))
```

4. Run the R Notebook (`Module4_Assignment.Rmd`) or the R script.

---

## 📄 License

This repository is intended for educational and portfolio purposes only.

---

## 👤 Author

**Raahim Muzaffar Ishtiaq**

GitHub: https://github.com/raahim27-hash

---

⭐ If you found this project interesting, feel free to star the repository.