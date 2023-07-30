# Sales Forecasting using Prophet Model
 The goal of this project is to predict future sales based on historical data and identify patterns and trends that influence sales performance.

 * Sales forecasting is a critical task for businesses to effectively plan inventory, resources, and marketing strategies. In this project, we use the powerful Prophet model, developed by Facebook, to perform time series forecasting for sales data. The model captures seasonal patterns, holidays, and other important features inherent in sales data, making it well-suited for accurate predictions.

# Data
The dataset used in this project contains historical sales data. It includes the timestamps (dates) and corresponding sales values. It's collected from Kaggle https://www.kaggle.com/competitions/store-sales-time-series-forecasting

# Methodology
The sales forecasting process involves the following steps:

* Data Preprocessing: The data is cleaned and preprocessed to handle missing values, convert data types, and prepare it for analysis.

* Exploratory Data Analysis (EDA): We conduct an exploratory analysis to understand the data distribution, trends, and seasonality.

* Model Building: The Prophet model is fitted to the training data, capturing seasonality and trend components.

* Forecasting: Using the trained model, we make predictions for future sales values.

* Model Evaluation: The accuracy of the forecasting model is evaluated using the Mean Absolute Percentage Error (MAPE).
# Results
After training the Prophet model and forecasting future sales, we achieved an accuracy of approximately 93%. The Mean Absolute Percentage Error (MAPE) obtained was 6.211, indicating a high level of accuracy in the predictions.