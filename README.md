# Plan My Trip

## Project Overview
### Purpose
The purpose of this project was to utilize APIs to create an app for customers to plan a vacation based on weather requirements, search for cities that meet the criteria, and map a travel itinerary. 

### Tools
*OpenWeatherMap API
*Geoampify
*Geoviews
*Python
*CitiPy

## Analysis
The OpenWeatherMap API was used to retrieve weather data for a random list of latitudes and longitudes. Cities were matched to the latitudes and longitudes using CitiPy and a dataframe was created. Input statements were used to filter the dataframe for the maximum and minimum temperature and the Geoampify API was used to match hotels to locations. After selecting four cities, Geoampify Routing API was called to gather routing data. The data was then mapped using GeoViews. 

## Results
### City and Hotel Map
![City and Hotel Map](../Vacation_Search/WeatherPy_vacation_map.png)

### Travel Itinerary
![Travel Itinerary](../Vacation_Itinerary/WeatherPy_travel_map.png)
