# Python APIs Challenge

## Data Analytics and Visualization boot camp homework

This challenge is about creating a sample of cities in the world, get weather information about them and use this information to find relationships between weather condtions and the latitude of the cities.

It is divided in two parts. First all weather data is gathered for 1000 cities (sample out of a total of +200K cities). Scatter plots are created out of this data and relationships are found between temperature, wind speed, humidity and cloudiness with the latitude of the cities. To gather the weather data the OpenWeather API is used.

The second part is looking up the best places with the best possible weather conditions that would be agreadable for vacation spots. Besides that, using the Google Places API, information about one of the closets hotels is found. Maps are created to show the humidty and the hotel information.

Before opening and running any of the jupyter notebooks the configuration file needs to be created and have the APIs keys added.

Configuration file: api_keys.py

With this properties:
OpenWeather API ```weather_api_key```
Goodle Place API ```g_key```

### jupyter notebooks
- WeatherPy.ipynb
- RunningVacationPy.ipynb
