# Covid-19 Disease Affected Area Prediction based on JohnsHopkings Covid-19 Data

The COVID-19 pandemic has had a profound impact on the global population, with countries like the United States and India seeing significant case numbers and severe public health consequences. The aim of this report is to analyse the COVID-19 data for the United States and India, to understand key patterns in confirmed cases, recoveries, and deaths. The data utilized for this analysis was sourced from the Johns Hopkins University dataset, a reliable real-time source that provides global COVID-19 case updates. Through this analysis, we aim to provide insights that could aid in managing the pandemic and preparing for future waves.

## Data Collection and Description
The dataset used for analysis comes from the Johns Hopkins University COVID-19 repository, which consists of multiple datasets that capture the evolution of the pandemic worldwide. The key datasets include:
 Confirmed Cases: The cumulative number of reported COVID-19 infections.
 Deaths: The total number of confirmed COVID-19 related deaths.
 Recoveries: The number of individuals who have recovered from the virus.
The dataset includes daily updates for each country, with geographical breakdowns down to the state level for the United States and India. The primary focus of this analysis was on daily case counts, deaths, and recoveries.

## Model Evaluation
The models were evaluated based on Mean Squared Error (MSE), a key metric to measure prediction accuracy:
For India, the SARIMAX model provided the most accurate forecasts with the lowest MSE. This was attributed to its ability to account for seasonal fluctuations in cases, capturing both trends and periodic surges.
For the United States, the Holt-Winters (Triple Exponential Smoothing) model emerged as the best performer. The model effectively captured both the trend and seasonality of the US COVID-19 data, leading to the lowest MSE for predictions.

## Conclusion
This analysis provided valuable insights into COVID-19 trends in India and the United States. The SARIMAX model was the best-performing model for India, while Holt-Winters excelled in forecasting the US data. Both models demonstrated superior accuracy in predicting confirmed COVID-19 cases based on MSE, and their findings could help inform future pandemic management strategies
