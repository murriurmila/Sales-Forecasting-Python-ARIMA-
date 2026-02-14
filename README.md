# Sales Forecasting using ARIMA (Python)

## Project Goal
Forecast future sales for the next 4 quarters using ARIMA time-series modeling.

## Dataset
- Cleaned “Sample Superstore” dataset aggregated by order date  
- Columns include Order Date and Sales

## Steps / Code Overview
1. Aggregate sales data by month.  
2. Check stationarity using Augmented Dickey-Fuller (ADF) test.  
3. Fit ARIMA model (example order ARIMA(1,1,1)).  
4. Forecast the next 4 periods.  
5. Visualize historical sales and forecast intervals using Matplotlib.  

## Tools & Technologies
- Python  
- Pandas, NumPy  
- Statsmodels (ARIMA)  
- Matplotlib, Seaborn

## Key Learnings
- Built an end-to-end time-series forecasting pipeline.  
- Practiced hyperparameter tuning and validation of ARIMA models.  
- Visualized forecasts for stakeholders to interpret trends.
