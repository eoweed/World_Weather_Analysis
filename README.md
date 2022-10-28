# World_Weather_Analysis

## Overview:

The purpose of this project is to create an application that will provide potential vacation itineraries for up to 2,000 destinations worldwide. Part 1 creates a database for the weather data on the 2,000 randomly generated cities. Part 2 asks for input on your preferred temperature at a destination. Part 3 creates a travel itinerary map between four nearby cities that have your preferred temperature. 

#### Part 1:
1)	Generate 2,000 random latitude and longitude coordinates.
2)	Create a list of cities that are closest to the generated coordinates.
3)	Perform API calls to OpenWeatherMap to gather weather data on each of the cities.
4)	Combine the weather data into a data frame and save as a csv file.

#### Part 2:
1)	Ask the user for input on preferred temperature at a vacation destination.
2)	Use the weather data file to filter cities that match the user’s preference.
3)	Perform API calls to Google Maps API and retrieve hotels that are in cities with the user’s preferred weather.
4)	Create a data frame to combine all the possible hotel options.
5)	Create a Google Map with markers that show all possible hotel options.
<img src=" https://github.com/eoweed/World_Weather_Analysis/blob/main/Images/WeatherPy_vacation_map.png" style="height:50; width:50;"/> 

#### Part 3:
1)	Use the Google Map of hotel options to choose four nearby cities in order to create a travel itinerary.
2)	Create a map showing a travel route to visit each of the four cities.
<img src=" https://github.com/eoweed/World_Weather_Analysis/blob/main/Images/WeatherPy_travel_map.png" style="height:50; width:50;"/> 


## References:

#### 1. Schork, Joachim (2022). Statistics Globe. *"Drop Rows with Blank Values from pandas DataFrame in Python (3 Examples)"*. https://statisticsglobe.com/drop-rows-blank-values-from-pandas-dataframe-python

## Software:
#### Pandas 1.4.3
#### Requests 2.28.1
#### Gmaps 0.9.0
#### Python 3.9.12
#### Jupyter Notebook 6.4.8
#### Matplotlib 3.5.1
#### Numpy 1.23.0
#### Citipy 0.0.5