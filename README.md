# World Weather Analysis

## Overview
Travel and tourism offer individuals a glimpse of the world. Weather conditions influence travel behavior and impact overall travel experience. The purpose of this project is to collect, analyze and visualize weather data across cities worldwide and to provide travelers with a tool that will allow them to determine their travel destination based on weather conditions.

### Resources Utilized to Complete Analysis
* **CSV Files:** 
[Weather_Database.csv]( https://github.com/cmmgw/World_Weather_Analysis/blob/main/Weather_Database/WeatherPy_Database.csv), 
[WeatherPy_vacation.csv]( https://github.com/cmmgw/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation.csv)
* **Jupyter Notebook Files:**: 
[Weather_Database.ipynb](https://github.com/cmmgw/World_Weather_Analysis/blob/main/Weather_Database/Weather_Database.ipynb), 
[Vacation_Search.ipynb](https://github.com/cmmgw/World_Weather_Analysis/blob/main/Vacation_Search/Vacation_Search.ipynb),
[Vacation_Itinerary.ipynb]( https://github.com/cmmgw/World_Weather_Analysis/blob/main/Vacation_Itinerary/Vacation_Itinerary.ipynb)

* **Python**: Python v3.7.6, Dependencies: Pandas, Matplotlib, CitiPy, SciPy, Python Requests, APIs, JSON Traversals

## Weather Database
A random set of 2,000 latitudes and longitudes were generated, and an API call was made on current weather data for the nearest corresponding cities. 

The following data was retrieved from the API call: 
* Latitude and longitude
* Maximum temperature
* Percent humidity
* Percent cloudiness
* Wind speed
* Current Weather description 

## Vacation Search
Based on traveler's weather preferences, travelers can identify potential travel destinations and nearby hotels. The map showcases destinations using pop-up markers on a marker layer-map.

### Sample Travel Destinations

![WeatherPy_vacation_map](https://github.com/cmmgw/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png)

## Vacation Itinerary 
Using the Google Directions API, a sample itinerary was created that shows the route between four cities in Kazakhstan.

![WeatherPy_travel_map](https://github.com/cmmgw/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.PNG)

## Statistical Analysis
Global city data was plotted, and linear regression was used to find the relationship between the following variables: 

* Latitude and Maximum Temperature
* Latitude and Humidity
* Latitude and Cloudiness
* Latitude and Wind Speed

### Scatter Plots 
Scatter plots were created for each weather parameter against the latitude for all cities to show how different weather parameters change based on latitude. 

![City Latitude vs. Max Temperature](https://github.com/cmmgw/World_Weather_Analysis/blob/main/weather_data/Fig1.png)
![City Latitude vs. Max Humidity](https://github.com/cmmgw/World_Weather_Analysis/blob/main/weather_data/Fig2.png)
![City Latitude vs. Cloudiness](https://github.com/cmmgw/World_Weather_Analysis/blob/main/weather_data/Fig3.png)
![ City Latitude vs. Wind Speed](https://github.com/cmmgw/World_Weather_Analysis/blob/main/weather_data/Fig4.png)

### Linear Regression on the Northern and Southern Hemispheres
Linear regression was performed for the Northern and Southern Hemispheres, on all four weather parameters: maximum temperature, humidity, cloudiness, and wind speed.

#### Maximum Temperature
![Linear Regression on the Northern Hemisphere for Maximum Temperature](https://github.com/cmmgw/World_Weather_Analysis/blob/main/weather_data/Fig5.png)
![Linear Regression on the Southern Hemisphere for Maximum Temperature](https://github.com/cmmgw/World_Weather_Analysis/blob/main/weather_data/Fig6.png)

#### Percent Humidity
![Linear Regression on the Northern Hemisphere for Percent Humidity](https://github.com/cmmgw/World_Weather_Analysis/blob/main/weather_data/Fig7.png)
![Linear Regression on the Southern Hemisphere for Percent Humdity](https://github.com/cmmgw/World_Weather_Analysis/blob/main/weather_data/Fig8.png)

#### Percent Cloudiness
![Linear Regression on the Northern Hemisphere for Percent Cloudiness](https://github.com/cmmgw/World_Weather_Analysis/blob/main/weather_data/Fig9.png)
![Linear Regression on the Southern Hemisphere for Percent Cloudiness](https://github.com/cmmgw/World_Weather_Analysis/blob/main/weather_data/Fig10.png)

#### Wind Speed
![ Linear Regression on the Northern Hemisphere for Wind Speed](https://github.com/cmmgw/World_Weather_Analysis/blob/main/weather_data/Fig11.png)
![ Linear Regression on the Southern Hemisphere for Wind Speed](https://github.com/cmmgw/World_Weather_Analysis/blob/main/weather_data/Fig12.png)
