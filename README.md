# Forecasting Imported Rice Prices With Triple Exponential Smoothing (Holt-WInters) Method

## Project Overview
The amount of imported rice in Indonesia affects the market price of rice. In 2022, rice imports in Indonesia increased to around 429,207.3 tons, compared to 407,741.4 tons in 2021. Most research suggests that importing rice helps keep rice prices affordable, but it can also lead to a trade imbalance. The Triple Exponential Smoothing (Holt-Winters) method is a simple yet effective forecasting technique that can model time series data with both trend and seasonal patterns.

## Methodology
- **Dataset:** Monthly Ricce Import Price 2018-2022 (https://www.bps.go.id/)
- **Models:** Triple Exponentional Smoothing (Holt-Winters Addictive and Multiplicative)
- **Tools:** Python (`pandas`, `matplotlib`, `statsmodels`, `sklearn`, `numpy`)
- **Metrics Evaluation:** MAE, RMSE and MAPE

## Key Result
- The Multiplicative Model was founded as the best model with lower MAPE (0,87%).
- Clear seasonal patterns were observed that rice prices tend to rise during Q3–Q4 each year.
- 95% Confidence Intervals were calculated to estimate forecast uncertainty.

## Visualization
<p align="center">
  <img width="1189" height="789" alt="download" src="https://github.com/user-attachments/assets/967fa58a-b959-454e-aca1-f7d545ebef7c" />
</p>
<h3 align="center">Decompose Imported Rice Price</h3>

<p align="center"><img width="868" height="470" alt="Model Mul"  src="https://github.com/user-attachments/assets/82ca8fb2-1e64-44fc-b14d-1ce577065ee9" />
  </p>
<h3 align="center">Multiplicative Model Triple Exponential Holt Winters with 95% CI/h3>

## Insight
- Seasonal fluctuations significantly impact to import rice prices.  
- Accurate forecasting can help the government and importers to make  decisions about stock planning and price stabilization policies.

## Recommendation
- Compared to other model such as ARIMA or many more.
- Used other indicators that effecting rice prices such as inflation rate, production, etc.


**Latisa Alifa Maura**  
Data Scientist | Time Series & Forecasting  


