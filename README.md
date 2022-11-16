# World_Weather_Analysis
Project using the Python API's to visualize weather data

## Overview of the project 

The purpose of this project is to help customers plan their perfect vacation. The project is to collect and present data for customers via the search page, which they will then filter based on their preferred travel criteria in order to find their ideal hotel, anywhere in the world. 

### Instructions :-

1. A list of 2000 random latitude and longitude are generasted and the nearby cities are retireved using the 'citypi' module.

2. Using the 'OpenWeatherMap', API calls are made to get the weather data for each of the available cities.

3. Input statements are used to retrieve customer weather preferences.

4. Based on the preference, potential travel destinations and nearby hotels are selected using the 'GoogleMaps' API.

5. A marker layer map is created with 'gmaps' that will have pop-up markers for each city on the map. This is the [Vacation Search map](WeatherPy_vacation_map.png).

6. From the above map, four cities are selected that a customer may want to visit.

7. Using 'gmaps', a directions layer map is created to map out the travel plan for the four cities as shown in [Travel Map](WeatherPy_travel_map.png).

8. A new marker layer map of the four cities on the travel route is created to present to the customer as a [Vacation Itinerary](WeatherPy_travel_map_markers.png).