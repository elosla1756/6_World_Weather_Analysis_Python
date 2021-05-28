# World Weather Analysis


## **Overview of the World Weather analysis**: in this challenge, we developed an app that allows travelers to enter their minimum and maximum temperature preferences. The app is then sorting through a list of cities to retrieve the ones that would fit the travelers' criteria.


### Beyond what we developed through the module (i.e. city, country, latitude, longitude, maximum temperature), our improved app is now also displaying the weather conditions at each of the prefered cities. We have also picked 4 cities within driving distance of each other to create a travel itinerary and travel route using a Google Maps Directions API.

## **Deliverable 1**:

We generated a set of 2,000 random latitudes and longitudes, retrieved the nearest city, and performed an API call with the OpenWeatherMap. We also added the current weather description for each city, and created a DataFrame from it. In our Weather_Database folder, you will find the following files:
1. The Weather_Database.ipynb file
2. The WeatherPy_Database.csv file

## **Deliverable 2**:

Using input statements to retrieve customer weather preferences, we identified potential travel destinations and nearby hotels. Then, we showed those destinations on a marker layer map with pop-up markers. We also added the current weather description for each city, and created a DataFrame from it. In our Vacation_Search folder, you will find the following files:
1. The Vacation_Search.ipynb file
2. The WeatherPy_vacation.csv file
3. The WeatherPy_vacation_map.png image

## **Deliverable 3**:

Using the Google Directions API, we created a travel itinerary that showed the route between four cities chosen from the customer’s possible travel destinations. Subsequently, we created a marker layer map with a pop-up marker for each city on the itinerary. In our Vacation_Itinerary folder, you will find the following files:

1. The Vacation_Itinerary.ipynb file
2. The WeatherPy_travel_map.png image
3. The WeatherPy_travel_map_markers.png image
