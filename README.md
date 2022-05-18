# World_Weather_Analysis

## Project Overview
The goal of this project is to generate a potential travel itinerary of four cities to a client utilizing various analysis and visualizations.


## Resources
APIs: Open Weather website, citipy and Google gmaps and directions

Software: Python 3.7.6, Pandas, Matplotlib, Jupyter Notebook, JSON

## Summary
The project was broken down into three different sections.

1. Retrieve Weather Data
2. Customer Travel Destinations MaP
3. Travel Itinerary Map

## Results
1. In order to complete the first deliverable, I generated 2000 pairs of random latitude and longitude coordinates. I utilized Open Weather maps and APIs in order to display the cities and their current weather in a new DataFrame shown below. 

![WeatherDatabase](https://github.com/annietresca/World_Weather_Analysis/blob/main/Weather_Database/DataFrame_WeatherDatabase.png)

2. In order to complete the second deliverable, I utilized pre-established customer weather preferences in order to generate potential travel destinations. Each of these destinations is identifiable in the image below and contains a pop-up marker that includes a Hotel Name, City, Country, Current Weather and Max Temp. 

![destinationmap](https://github.com/annietresca/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png)

3. In order to complete the third and final deliverable, I utilized Google Directions API in order to show the route between four cities that were selected from the customer's potential travel destination. Additionally, I created a marker layer with a pop-up marker for each city on the itinerary. 

![itinerary](https://github.com/annietresca/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png)

![popupitinerary](https://github.com/annietresca/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png) 
