# Weather_Analysis_Challange
WeatherPy with Python APIs


## Overview
After working on an app, beta testers requested a new feature,weather description, be added to the markers that pop up after clicking on a pin.  
The beta testers also wanted to be able to pick their minimum and maximum temperatures for a trip.  
From there, four cities were chosen to create an itinerary map with pins and markers.

# Process

## Retrieve the Weather Data
An API was established with OpenWeatherMap and a DataFrame was created to get the initial list of potential cities. 
![Pic 1](https://github.com/josepcherian/Weather_Analysis_Challange/blob/main/Weather_Database/Resources/City_DF.PNG)

## Create a Customer Travel Destinations Map
After prompting the beta testers for their minimum and maximum temperature preferences, the data frame was cleaned for null hotel entries and empty rows.  Markers and pins were created for the remainder of the hotels. 
![Pic 2](https://github.com/josepcherian/Weather_Analysis_Challange/blob/main/Vacation_Search/WeatherPy_vacation_map.PNG)

## Create an Itinerary Map
The list was narrowed down to 4 cities in the same country and a travel map was created. 
![Pic 3](https://github.com/josepcherian/Weather_Analysis_Challange/blob/main/Vacation_Itinerary/WeatherPy_travel_map.PNG)

Makers were added to the map of four cities. 
![Pic 4](https://github.com/josepcherian/Weather_Analysis_Challange/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.PNG)
