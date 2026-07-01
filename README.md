
# IBM Exploratory Data Analysis for Machine Learning Project
# Federal Reserve Economic Dashboard

## An Exploratory Data Science Analysis of U.S. Macroeconomic Indicators Using FRED

### Overview

This project investigates the relationships between monetary policy, inflation, labor markets, and economic growth using publicly available data from the Federal Reserve Economic Data (FRED) database. By combining multiple macroeconomic indicators into a single analytical dataset, the project demonstrates the complete data science workflow—from data collection and exploratory analysis to hypothesis testing and machine learning preparation.

The project was developed as a final data science assignment with an emphasis on applying statistical analysis, economic reasoning, and visualization techniques to real-world financial data.

---

## Research Question

**How do monetary policy, inflation, financial markets, and economic activity interact over time, and what can these relationships tell us about the U.S. economy?**

---

## Objectives

The primary objectives of this project are to:

* Build a unified macroeconomic dataset using official FRED data.
* Explore long-term economic trends through visualization.
* Engineer meaningful macroeconomic features.
* Test economic hypotheses using statistical methods.
* Prepare the dataset for predictive machine learning models.
* Communicate findings using clear visualizations and economic interpretation.

---

## Dataset

The project uses monthly U.S. macroeconomic data from **January 2000 through December 2024**.

The dataset contains ten major economic indicators:

| Variable                   | Description                                      |
| -------------------------- | ------------------------------------------------ |
| Federal Funds Rate         | Primary monetary policy interest rate            |
| Consumer Price Index (CPI) | Overall inflation measure                        |
| Core CPI                   | Inflation excluding food and energy              |
| Unemployment Rate          | Labor market indicator                           |
| Real GDP                   | Inflation-adjusted economic output               |
| 10-Year Treasury Yield     | Long-term interest rate                          |
| M2 Money Supply            | Measure of money circulating in the economy      |
| Industrial Production      | Manufacturing and industrial activity            |
| Consumer Sentiment         | University of Michigan consumer confidence index |
| Recession Indicator        | Binary indicator for official U.S. recessions    |

All data are retrieved directly from the Federal Reserve Economic Data (FRED) database, ensuring that the analysis is fully reproducible.

---

## Project Workflow

The project follows a complete data science workflow:

1. Data collection from FRED
2. Dataset construction and preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature engineering
5. Statistical hypothesis testing
6. Econometric regression analysis
7. Machine learning preparation
8. Interpretation of economic findings

---

## Feature Engineering

Several additional variables were created to improve economic interpretation, including:

* 12-month inflation rate
* Core inflation rate
* GDP growth rate
* Real interest rate
* Yield spread (10-Year Treasury − Federal Funds Rate)
* Lagged Federal Funds Rate
* Lagged inflation
* 12-month moving average unemployment rate

These engineered variables better capture the delayed and dynamic relationships commonly observed in macroeconomic analysis.

---

## Statistical Analysis

The project includes several statistical techniques:

* Descriptive statistics
* Correlation analysis
* Pearson correlation tests
* Independent samples t-tests
* Ordinary Least Squares (OLS) regression
* Feature importance using Random Forest regression

These methods provide both explanatory and predictive perspectives on macroeconomic relationships.

---

## Visualizations

The notebook includes multiple visualizations designed to communicate economic trends clearly:

* Time-series plots
* Recession shading
* Correlation matrix
* Scatter plots with fitted trend lines
* Distribution plots
* Feature importance charts

---

## Key Findings

Some of the major findings include:

* Monetary policy follows clear business-cycle patterns, with lower interest rates during recessions and higher rates during inflationary periods.
* Unemployment increases sharply during economic downturns.
* Consumer sentiment declines significantly during recessions.
* GDP growth and unemployment exhibit a strong inverse relationship.
* Engineered macroeconomic variables improve the predictive value of the dataset for future machine learning applications.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* SciPy
* Statsmodels
* Scikit-learn
* Pandas DataReader
* Federal Reserve Economic Data (FRED)

---

## Repository Structure

```text
Federal_Reserve_Economic_Dashboard/
│
├── FRED_Economic_Dashboard_PROFESSIONAL.ipynb
├── README.md
├── figures/
│   ├── correlation_matrix.png
│   ├── unemployment_timeseries.png
│   ├── inflation_plot.png
│   ├── feature_importance.png
│   └── ...
└── requirements.txt
```

---

## Future Improvements

Potential extensions to this project include:

* Vector Autoregression (VAR) models
* Time-series forecasting using ARIMA or Prophet
* Granger causality testing
* SHAP value interpretation for machine learning models
* Interactive dashboards using Plotly or Dash
* Forecasting unemployment and inflation using advanced machine learning algorithms

---

## About

This project demonstrates practical applications of economics, finance, statistics, and data science using publicly available macroeconomic data. It is intended to showcase skills in data analysis, econometrics, visualization, and predictive modeling for opportunities in quantitative finance, economic consulting, financial analysis, and economic research.
