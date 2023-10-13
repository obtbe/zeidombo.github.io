---
layout: project
title: "Forecasting the Weather Using Facebook's Prophet Algorithm"
date: 2023-01-22
tags: [eda, forecast]
type: "project"
author: "Zeid Ombotimbe"
disqus: false
---

<!-- <iframe src="https://nbviewer.org/github/zeidombo/weather-forecast-using-facebook-prophet/blob/master/weather_forecast.ipynb" width="811" height="667">
</iframe> -->

In this project, I applied the Facebook Prophet algorithm to predict the weather in New York City using local weather data. Utilizing an additive model, Prophet combines seasonal effects and trends to make accurate predictions. The notable advantage of Prophet is its automatic detection of seasonality in the data, making it a suitable choice for weather data which typically exhibits strong seasonal patterns. This eliminates the need for extensive feature engineering, providing a solid baseline accuracy.

The project began with the collection and preparation of local weather data specific to New York City, which served as the foundational dataset for the forecasting model. Leveraging the Prophet algorithm, I analyzed the data and generated forecasts for future weather conditions in the city. Additionally, I explored the scalability of Prophet, demonstrating its capability to handle multiple time series effortlessly, including data from adjacent weather stations.

Overall, the project showcased the effectiveness of the Facebook Prophet algorithm in accurately predicting the weather, establishing it as a valuable tool for weather forecasting tasks, particularly in datasets characterized by distinct seasonal variations.

Check the full project [here](https://nbviewer.org/github/zeidombo/weather-forecast-using-facebook-prophet/blob/master/weather_forecast.ipynb).
