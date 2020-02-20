# WeatherPy - What's the Weather Like? | Python-API Challenge
#### Submitted by : Sheetal Bongale | UT Data Analysis and Visualization | Feb 15, 2020

#### Objective: 
Python script to visualize the weather of 500+ cities across the world of varying distance from the equator, utilizing a [simple Python library](https://pypi.python.org/pypi/citipy), the [OpenWeatherMap API](https://openweathermap.org/api), and create a representative model of weather across world cities.

Technologies Used: `Python`, `Pandas`, `Matplotlib` and `API Calls`

* Randomly select **at least** 500 unique (non-repeat) cities based on latitude and longitude.
* Perform a weather check on each of the cities using a series of successive API calls.
* Include a print log of each city as it's being processed with the city number and city name.
* Save both a CSV of all data retrieved and png images for each scatter plot.
* Build a series of scatter plots to showcase the following relationships:
    * Temperature (F) vs. Latitude
    * Humidity (%) vs. Latitude
    * Cloudiness (%) vs. Latitude
    * Wind Speed (mph) vs. Latitude
