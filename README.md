# WeatherPy_HW

What's the Weather Like?

Whether financial, political, or social -- data's true power lies in its ability to answer questions definitively. This assignment uses Python requests, APIs, and JSON traversals to answer a fundamental question: "What's the weather like as we approach the equator?"

# WeatherPy

This assigment includes a Python script that was created to visualize the weather of 500+ cities across the world of varying distance from the equator. It utilyzes a Python library and the OpenWeatherMap API to create a representative model of weather across world cities.

The objective was to build a series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

The final report:

* Randomly selects at least 500 unique (non-repeat) cities based on latitude and longitude.
* Performs a weather check on each of the cities using a series of successive API calls.
* Includes a print log of each city as it's being processed with the city number and city name.
* Saves both a CSV of all data retrieved and png images for each scatter plot.
