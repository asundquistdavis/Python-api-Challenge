# Python-api-Challenge
## Overview
This challenge explores using the Open Weather and Google Places APIs to analyse weather trends around the globe and find a cool place to vacation at. It is broken up into two parts: WeatherPy which uses the CitiPy Python module and Open Weather's API to get weather data 9temperature, humidity, cloudiness and wind speed) for 500 cities at random and than analyse the data, with linear regeressions, to see if there are any trends between the weather data and latitude. Specifically looking at, does weather cheange further away from the equator. The second part of the challenge, VacationPy, looks at the weather for the cities found in WeatherPy and finds cities that meat "ideal" weather conditions.
## Contents
- WeatherPy
    - WeatherPy.ipynb: Gets weather data using open weather api and analyses it with pandas and matplotlib
    - Output: Contains all scatter plots created within the .ipynb + weather_data.csv
- VacationPy
    - VacationPy.ipynb: Uses data created in the WeatherPy notebook and the Google Places api