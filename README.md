# python-api-challenge

## WeatherPy
### The OpenWeatherMap API was used to get weather data from a generated list of cities to understand how the weather is affected as it approaches the equator.
### This was made into a dataframe and exported as a csv file.
### Four scatter plots were generated looking at the relationship between latitude and either temperature, humidity, cloudiness, or wind speed.
### In addition, linear regression analysis was performed and printed on each graph (for the northern and southern hemisphere).

## VacationPy
### A map was generated, highlighting cities listed in the csv file from WeatherPy.
### The cities were narrowed down to ideal weather conditions (temp 22 to 30 degree celcius, humidity 45% or lower, cloudiness below 40% and wind speed below 20 m/s). A data frame was generated from this and another column (hotel name) was added.
### The Geoapify API was used to locate the first hotels within 10,000 meteres of the cities in the new data frame.
### A map was generated highlighting the hotels listed in the previous step.
