# World_Weather_Analysis
## Purpose
Adding weather description to the weather data retrieved in the module. Then beta test with input statements to filter locations for weather preference. Finally, identify and plot travel routes using nearby hotels to create a travel itinerary using Google Maps Directions API.


## Programs
**Weather Database** is used to select 2000 ranomdized latitude and longitude and perform a API request for cities closest to the genergated locations. Then use JSON to retrieve data including latitude, longitude, maximum temperature, % humidity, % cloudiness, wind speed, country, and weather description and store it in a DataFrame. Lastly, store it in a csv file.

**Vacation Search** is used to create a customer's travel destinations map using the weather database generated. The program asks the user to input a minimum and maximum preferred temperature and filters the database, creating a filtered DataFrame. Lastly, it plots the location and mark the closest hotels on the Google Map.

**Vacation Itinerarary** is used to create an itinerary using the filtered DataFrame and plots a travel route for the selected four cities. 