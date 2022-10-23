# World_Weather_Analysis
System: Google Map API Key and JSON

## Overview
  - Collect and presenting data for customers via serach page
  - Filter based on their preferrred travel criteria to find: ideal Hotels worldwide, traveling destinations
  - Include weather descriptions to the weather data
  - Using a beta testers to input statements to filter data for weather preferrences
  - Using a beta tester on 4 chities from the list to create a travel itinerary
  - Using Google Maps Directions API, creating a travel route between the 4 cities
  - Generate a marker layer map with the 4 cities
  - 
## Results
We were able to create three file for the Weather's Database, Vactaion's Search, and and Vacation's Itinerary. In the weather_database we were able to retrieve the Longitude, Latitude, maxi temperature, humidity's percentage, cloudiness' percentage, wind speed, and a description of the weather. We are able to generate 2000 randome cities and grabing a total of 778 citiesi for our DataFrame. As for our Vacation_search file we were able to import our weather_database as make a new DataFrame and give 2 input statements that will propt the user to enter their min and max temperature of their vacation search. We drop cities that had an empty row and included hotel names. Lastly for the vacation_itinerary file we were able to pick 4 cities that in clsoe promimity that customers will travel to and created a direction layer map. The cities we picked are in Japan. We then created a travel_mode that the customer will be traveling driving, bicycling, pr walking. 

## Summary
In conclusion, we were able to get locations, weathers, and hotel information for customers. PlanMyTrip can probably expand their search by including local restaurants, festival/celebrations, and other landmarks that customers can visit while they travel. 
