# python-api-challenge

This is code as related to MSU Data Analytics bootcamp. The first file, WeatherPY collects a random sample of cities and collects weather data via the open weather map API. After collection linear regression of temperature, cloudiness, humidity, and wind speed is done to determine correlation.  


After this is calculated VacationPy is used to determine "ideal" vacation spots. This selects the cities in a given range of temperature, under a certain wind speed, and no cloudiness. Those selected cities are used in conjuction with the geopify places API to find hotels within 10000 meters of the given city. Those cities are mapped and then the points will show the hotel name when hovered over.
