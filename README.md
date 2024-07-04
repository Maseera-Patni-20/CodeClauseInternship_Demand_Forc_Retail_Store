# Demand Forecasting for a Retail Store

This project aims to develop a demand forecasting model for a retail store. By analyzing historical sales data, the model predicts future product demand, considering seasonality and trends. This enables better inventory management and helps meet customer demand more effectively.

## Features

- **Historical Data Analysis**: Analyze past sales data to understand trends and seasonality.
- **Feature Engineering**: Create lagged features, rolling means, and exponentially weighted moving averages.
- **Time Series Forecasting**: Implement various forecasting models such as ARIMA, SARIMA, and Holt-Winters.
- **Machine Learning**: Use LightGBM for regression and sales prediction.
- **Visualization**: Compare actual and predicted sales with improved visualization techniques.

## Technologies Used

- **Python**: Programming language for data analysis and modeling.
- **Pandas**: Data manipulation and analysis.
- **Statsmodels**: Time series analysis and forecasting.
- **LightGBM**: Gradient boosting framework for regression tasks.
- **Matplotlib** and **Seaborn**: Data visualization.

## Project Workflow

1. **Data Preprocessing**:
    - Load and concatenate training and testing datasets.
    - Analyze and describe data statistics.
    - Perform feature engineering (lag features, rolling means, EWMA).

2. **Model Training**:
    - Split data into training and validation sets.
    - Define and train the LightGBM model with custom SMAPE evaluation.
    - Predict and evaluate model performance on the validation set.

3. **Predictions**:
    - Generate sales predictions for the test set.
    - Aggregate predictions to a weekly level for better visualization and comparison.

4. **Visualization**:
    - Plot actual vs. predicted sales on the validation set.

## Evaluation Metric

- **SMAPE** (Symmetric Mean Absolute Percentage Error): Used to evaluate the accuracy of the forecasts.

## Results

- Achieved accurate sales predictions with a well-tuned LightGBM model.
- Visualized actual vs. predicted sales, demonstrating the model's effectiveness in capturing trends and seasonality.

## Conclusion

The demand forecasting model provides valuable insights into future sales trends, aiding in inventory management and decision-making processes for the retail store.

## Future Work

- Further tuning of model parameters.
- Exploration of additional machine learning models.
- Deployment of the model in a production environment for real-time predictions.

