# World_Weather_Analysis
## Purpsoe
The purpose of this project was to create a vacation map that allows users to apply weather criteria to identify potential travel destinations. In order to create the vacation map, I generated a list of 2,000 random latitudes and longitudes. With those cooridnates, I retrieved and compiled a list of the nearest cities using the citipy module in Pandas. I then used the OpenWeatherMap API to request the current weather data from each unique city on the list. The list will filter itself based on the weather criteria set by the user. The resulting map provides users with descriptions of the potential destinations found on the list: hotel name, city, country, and current weather with a description. Lastly, four cities were chosen to create a travel itinerary by using the Google Maps Directions API that created a route between the four cities as well as a marker layer map.
## Deliverable 1: Retrieve Weather Data
![Deliverable_1](https://github.com/dgeroux/World_Weather_Analysis/blob/main/deliverable_one.png)
## Deliverable 2: Create a Customer Travel Destinations Map
![Deliverable_2](https://github.com/dgeroux/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png)
## Deliverable 3: Create a Travel Itinerary Map
![Deliverable_3](https://github.com/dgeroux/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png)
