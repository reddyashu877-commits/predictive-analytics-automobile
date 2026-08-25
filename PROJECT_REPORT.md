# Predictive Analytics Using Historical Data

## Automobile Sales Forecasting

### 1. Objective

The objective of this project is to use historical automobile sales data to build a predictive model and forecast future automobile sales.

### 2. Dataset

The dataset contains automobile sales information such as:

- Advertising Spend
- Average Vehicle Price
- Fuel Price
- Economic Index
- Year
- Month
- Sales Units

### 3. Data Preprocessing

The historical data was cleaned and prepared for analysis. Date information was converted into useful features such as year and month.

The data was divided into training and testing sets using a chronological split.

### 4. Machine Learning Models

Two machine learning models were used:

1. Linear Regression
2. Random Forest Regression

### 5. Model Evaluation

The models were evaluated using:

- MAE
- RMSE
- R² Score

### 6. Results

Linear Regression produced the better results.

| Model | MAE | RMSE | R² |
|---|---:|---:|---:|
| Linear Regression | 34.91 | 41.56 | 0.488 |
| Random Forest | 49.80 | 62.21 | -0.149 |

### 7. Sales Forecast

The Linear Regression model was used to forecast automobile sales for six months.

| Month | Forecast Sales |
|---|---:|
| January 2026 | 1866 |
| February 2026 | 1893 |
| March 2026 | 1908 |
| April 2026 | 1907 |
| May 2026 | 1890 |
| June 2026 | 1862 |

### 8. Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Machine Learning
- Predictive Analytics

### 9. Conclusion

This project demonstrates how historical automobile sales data can be used for predictive analytics. The model can help automobile companies with sales planning, inventory management, production planning and marketing decisions.
