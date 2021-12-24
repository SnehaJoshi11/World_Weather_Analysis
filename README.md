# World_Weather_Analysis


## Overview

We are working on the PlanMyTrip app. In this app we are using open weather api to find out city specific details(City, country, and date,Latitude and longitude,Maximum temperature,Humidity,Cloudiness,Wind speed). There are some modifications on criteria like "weather descriptions" for specific places that customer want to visit.
From the list of potential travel destinations, will choose four cities to create a travel itinerary. 

## Purpose

Here we are going use the Google Maps Directions API, to create a travel route between the four cities as well as a marker layer map which will give descriptions respectively.


## Resources
  - Jupyter Notebook
  - Python 3.7.6
  - Dependencies
      - Python Pandas library
      - Python Numpy library
      - Python Request library
      - Json Library
      - Google maps API
      

## Requirements

**1. Weather DataBase**
    
   - Retrieve the following information from the API call:
     - Latitude and longitude
     - Maximum temperature
     - Percent humidity
     - Percent cloudiness
     - Wind speed
     - Weather description (for example, clouds, fog, light rain, clear sky)
   - Create a csv file and save it.
   
**2. Vacation Search**

   - Take user input for temperatures and find out the travel itinerary and retrieve the hotel info.
   - Set markers with following description:
       - Hotel name
       - City
       - Country
       - Current weather description with the maximum temperature

**3. Vacation Itinerary**
   - Use the Google Directions API 
   - Create a travel itinerary
   - Show the route between four cities chosen from the customer
   
   

## Results


*1.Weather DataBase which we created with the help of open weather api:*


  <p><img src=" /../Weather_Database/city_weather_database.png", width=800></p>
    

*2.Vacation Search for specific temprature criteria with the help of google maps api:*


  <p><img src=" /../Vacation_Search/WeatherPy_vacation_map.png", width=900></p>


*3.Vacation Itinerary with travel rout and description with the help of google maps direction api:*


<p><img src=" /../Vacation_Itinerary/WeatherPy_travel_map.png", width=900></p>


<p><img src=" /../Vacation_Itinerary/WeatherPy_travel_map_markers.png", width=900></p> 




 
