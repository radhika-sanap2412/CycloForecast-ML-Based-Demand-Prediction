# CycloForecast-ML-Based-Demand-Prediction
## Summary
Developed machine learning models to predict demand and revenue for Santander Cycles in London, utilizing Big Data, PySpark on GCP, and models like GBT and SARIMA. Incorporated weather and transport proximity data using BigQuery GIS for accurate forecasting. Aimed to optimize bike-sharing operations and support sustainable urban mobility.
## Methods
Utilized PySpark for big data processing, integrating cycling, weather, and geospatial data from various sources. Implemented machine learning models, including Gradient Boosted Trees (GBT), Random Forests, and time series models such as ARIMA, SARIMA, and LSTM, for predicting bike rental demand and revenue. Geospatial analysis was performed using BigQuery GIS to assess the impact of proximity to public transportation on bike usage.
## Results 
The GBT model demonstrated the best performance in demand prediction with an RMSE of 435.066. For revenue forecasting, the SARIMA model achieved the highest accuracy with an RMSE of 321.350, closely followed by LSTM. These models provided actionable insights for optimizing bike availability and revenue generation, contributing to more efficient bike-sharing operations in London
