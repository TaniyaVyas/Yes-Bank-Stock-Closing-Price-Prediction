# Yes Bank Stock Closing Price Prediction Using Machine Learning

## Project Overview

This project focuses on analyzing historical Yes Bank stock prices and developing machine learning models to estimate stock closing prices.

The project includes data cleaning, exploratory data analysis (EDA), feature engineering, and regression-based machine learning techniques to understand stock price patterns and evaluate predictive performance.

## Problem Statement

Stock prices are influenced by market conditions, investor sentiment, company performance, and economic factors. Predicting stock prices is challenging because financial markets are constantly changing.

The objective of this project is to analyze Yes Bank's historical stock price data, identify important relationships between variables, and develop regression models for closing price prediction.

## Business Objectives

- Understand historical stock price trends and fluctuations.
- Identify relationships between opening, highest, lowest, and closing prices.
- Analyze monthly returns and periods of significant price changes.
- Develop and compare machine learning regression models.
- Evaluate prediction accuracy using appropriate performance metrics.
- Support data-driven financial analysis and risk awareness.

## Dataset Information

The dataset contains 185 monthly observations of Yes Bank stock prices, covering July 2005 to November 2020.

| Feature | Description |
|---|---|
| Date | Month and year of the observation |
| Open | Opening stock price |
| High | Highest stock price during the month |
| Low | Lowest stock price during the month |
| Close | Closing stock price (target variable) |

**Dataset dimensions:** 185 rows × 5 original columns.

## Technologies Used

- **Programming Language:** Python
- **Development Environment:** Google Colab / Jupyter Notebook
- **Data Manipulation:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn and other regression libraries as required
- **Version Control:** GitHub

## Project Workflow

### 1. Data Understanding

Explored the dataset structure, variable types, missing values, duplicate records, and descriptive statistics.

### 2. Data Cleaning and Feature Engineering

Prepared the dataset by converting dates, validating stock prices, sorting observations chronologically, and creating additional features such as:

- Monthly price range
- Opening-to-closing price change
- Percentage price change
- Monthly closing-price return
- Moving averages
- Year and month

### 3. Exploratory Data Analysis

The EDA examines stock price distributions, trends, fluctuations, and relationships using different visualization techniques.

The planned analysis includes 20 meaningful visualizations organized into univariate, bivariate, and multivariate analysis.

**Visualizations covered so far:**

1. Closing Stock Price Distribution
2. Monthly Closing Stock Price Trend
3. Closing Price Box Plot
4. Monthly Opening-to-Closing Price Change
5. Year-Wise Average Closing Price
6. Monthly Stock Price Range
7. Monthly Returns Distribution
8. Opening Price vs Closing Price
9. Highest Price vs Closing Price
10. Lowest Price vs Closing Price
11. Year-Wise Closing Price Distribution
12. Year-Wise Positive and Negative Returns
13. Opening Price, Closing Price, and Price Range Bubble Chart
14. Correlation Heatmap
15. Pair Plot of Stock Price Variables

### 4. Machine Learning Model Development

The next stage involves training and evaluating regression models to estimate closing prices.

Candidate models include:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- XGBoost Regressor

Final model selection will depend on experimental results.

### 5. Model Evaluation

Models will be evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

For genuine future forecasting, chronological data splitting and historical features will be used to avoid data leakage.

## Key Learnings

The exploratory analysis helps examine:

- Changes in Yes Bank's stock prices over time.
- Differences between positive and negative monthly returns.
- Variations in monthly trading ranges.
- Relationships among Open, High, Low, and Close prices.
- Potential multicollinearity among numerical features.
- The importance of avoiding future information when forecasting stock prices.

## Business Recommendations

The project aims to support financial analysis through historical trend monitoring, risk assessment, and machine learning.

Recommended actions include evaluating multiple regression algorithms, monitoring prediction errors, reviewing significant price fluctuations, and combining model predictions with relevant financial information.

Stock price predictions should not be treated as guaranteed investment outcomes.

## How to Run the Project

1. Download or clone this GitHub repository.
2. Open the Jupyter notebook in Google Colab.
3. Upload the dataset file `data_YesBank_StockPrices.csv` to the Colab environment.
4. Run the notebook cells sequentially.
5. Review the EDA visualizations and model evaluation results.

The notebook currently references the dataset at `/content/data_YesBank_StockPrices.csv`.

## Future Improvements

- Complete the remaining EDA visualizations.
- Train and compare regression models.
- Perform hyperparameter tuning.
- Explore lagged features and rolling statistics.
- Evaluate forecasting performance on unseen future periods.
- Develop an interactive prediction dashboard.

## Author

**Taniya Vyas**

GitHub: [TaniyaVyas](https://github.com/TaniyaVyas)

## Repository

[Yes Bank Stock Closing Price Prediction](https://github.com/TaniyaVyas/Yes-Bank-Stock-Closing-Price-Prediction)

## Disclaimer

This project is developed for educational and analytical purposes. It does not provide financial or investment advice. Historical stock price patterns do not guarantee future performance.
