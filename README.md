# World_Weather_Analysis

## Purpose
Jack wants to take his app to the next level. They want to add the weather description to the app. We can then use the info to have app beta testers input their prefrences to identify their ideal travel destinaions and the nearby hotels based on the critera. We will also be using Google Maps API to create a travel route. 


### Vacation Map
After making an API call of 2,000 random latitudes and longitudes and pairing them with the nearest city amd retreiving a series of weather data we were able to create a new data frame. Once we had the WeatherPy_Database.csv we could then create a new dataframe that was based on the min and max temperature critera. Once we cleaned the data we created a hotel database. Now with this file we have a map of possible locations to vacation.

#### WeatherPy Vacation
![WeatherPy_vacation_map](https://github.com/Andrew-E-Walters/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png)

### Travel Map
We were then able to use the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations and then create a marker layer map with a pop-up marker for each city on the itinerary. This example is going to outline a possible travel map for a family visiting Texas. 

#### WeatherPy_travel_map
![Texas with no markers_map](https://github.com/Andrew-E-Walters/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png)

#### WeatherPy_travel_map_markers
We also are able to show the data that we collected for each stop in the Texas roadtrip!
![Texas with no markers_map](https://github.com/Andrew-E-Walters/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png)
