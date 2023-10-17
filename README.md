# Weather Data Analysis

## Overview

This project entails using Python to analyze weather data, aiming to uncover the relationship between weather variables and latitude. The analysis is conducted through two Jupyter notebooks, WeatherPy.ipynb and VacationPy.ipynb, each concentrating on distinct analysis aspects.

## Table of Contents

- [Overview](#overview)
- [WeatherPy.ipynb](#weatherpyipynb)
  - [Data Retrieval](#data-retrieval)
  - [Data Visualization](#data-visualization)
- [VacationPy.ipynb](#vacationpyipynb)
  - [Heatmap Generation](#heatmap-generation)
  - [Ideal Vacation Spots](#ideal-vacation-spots)
- [Conclusions](#conclusions)

## WeatherPy.ipynb

[WeatherPy.ipynb](WeatherPy.ipynb) primarily focuses on the following aspects:

### Data Retrieval

- Generates random geographic coordinates and uses the OpenWeatherMap API to retrieve weather data for various cities.
- Stores the data in a Pandas DataFrame and saves it as a CSV file.

### Data Visualization

- Creates scatter plots to showcase the relationship between weather variables (temperature, humidity, cloudiness, wind speed) and latitude.
- Performs linear regression analysis to examine the correlation between these variables and latitude, both in the Northern and Southern Hemispheres.

## VacationPy.ipynb

[VacationPy.ipynb](VacationPy.ipynb) complements the WeatherPy analysis with the following:

### Heatmap Generation

- Utilizes Google Maps API and gmaps library to create a heatmap displaying humidity levels for various cities.
- Adds markers for ideal vacation spots based on user-defined criteria.

### Ideal Vacation Spots

- Identifies cities with ideal weather conditions for vacation based on temperature, humidity, and wind speed.
- Provides a list of potential vacation destinations.

## Conclusions

The analysis of weather data revealed several insights:

1. **Latitude and Temperature**: As expected, there is a strong correlation between latitude and temperature. As we move closer to the equator (latitude 0), temperatures tend to rise. This relationship holds true in both the Northern and Southern Hemispheres.

2. **Latitude and Humidity**: The analysis did not show a strong correlation between latitude and humidity. Humidity levels appeared to vary widely at different latitudes, suggesting that latitude alone may not be a reliable predictor of humidity.

3. **Latitude and Cloudiness**: Similarly, there was no significant correlation between latitude and cloudiness. Cloud cover appeared to be distributed unevenly across different latitudes.

4. **Latitude and Wind Speed**: Latitude also did not exhibit a strong correlation with wind speed. Wind speeds varied across different latitudes, but there was no clear trend indicating latitude as a primary factor.

In summary, while latitude has a clear impact on temperature, its influence on humidity, cloudiness, and wind speed is less pronounced. Other factors likely play a significant role in determining these weather variables. These findings provide valuable insights into the relationship between geography and weather patterns.
