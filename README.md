# python-api-challenge
Background: This code utilizes Python requests, APIs, and JSON traversals to answer a fundamental question: "What is the weather like as we approach the equator?"

The code generates tables, plots, and necessary maps to assist in identifying relevant data points to assist in a better understanding of weather in the northern and southern hemispheres. 

A repository labeled python-api-challenge contains the following files:
*	Weatherpy folder with hidden api keys
** Output_data folder containing a cities csv. and relevant scatterplots
*	Two Jupyter Notebook files labeled VactionPy and WeatherPy

WeatherPy, uses Citipy via Jupyter Notebook to randomly select 500 cities of varying distances from the equator, then OpenWeatherMap.api is utilized to pull in weather data for the respective cities.  The code also generated scatterplots for City Latitude vs. Temperature, City Latitude vs. Humidity, City Latitude vs. Cloudiness, City Latitude vs. Wind Speed, Temperature vs. Latitude Linear Regression Plots, Humidity vs. Latitude Linear Regression Plots, Cloudiness vs. Latitude Linear Regression Plots, and Wind Speed vs. Latitude Linear Regression Plots.

VacationPy, reads the outputted cities.csv generated from WeatherPy, which then plots a point on a map that is based on the size of Humidity for each city.  Select parameters are listed in the code to captures ideal weather conditions for each city, which is then searched against hotel data from the geoapify api. Lastly, a map is generated to display the points for hotels and country.

Resources used for this project include, Instructor provided starter code, Office hours, Tutor assistance, Study-Group, course material, Stack Overflow, OpenWeatherMap documentation, Geoapify documentation, and matplotlib documentation.

The dataset random and provides a sample of approximately 500 cities of interest and doesn’t fully represent all of the worldwide cities in the northern and southern hemisphere.  Of the data retrieved however, ideal cities meeting our set criteria for ideal weather conditions occurred in the northern hemisphere with six events, whereas only four appeared in the southern hemisphere. 
