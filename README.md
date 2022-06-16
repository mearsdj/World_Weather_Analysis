# World Weather Analysis

In this repo we generate 2000 random latitude/longitude pairs and use the citipy module to find the city nearest to each set of coordinates.
Once we have our city, we use the OpenWeatherMap API to pull the weather for each city, and then filter our list of cities using user generated input on preferred temperate range for cities to vist.
With the list of preferred cities we then use the Google Nearby Search API to find a hotel in each potential travel destination and add them to a google map.
Finally we create a travel itinerary by selecting 4 of the users preferred travel cities and use the google directions service to add directions between the preferred cities. 
