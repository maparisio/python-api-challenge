# Module 6-Python_APIs

## python-api-challenge

#### Data's true power is its ability to definitively answer questions. So, I'm going to take what I've learned about Python requests, APIs, and JSON traversals to answer a fundamental question: "What is the weather like as we approach the equator?"
#### Now, we know what you may be thinking: “That’s obvious. It gets hotter.” But, if pressed for more information, how would you prove that?
#### In the first part of this assignment, called WeatherPy, I created a Python script to visualize the weather of over 500 cities of varying distances from the equator. I used the citipy Python library, the OpenWeatherMap API, and my awesome problem-solving skills to create a representative model of weather across cities.

#### In the file WeatherPy, I created plots to showcase the relationship between weather variables and latitude, and used the OpenWeatherMap API to retrieve weather data from the cities list generated in a starter code csv file. Next, I created a series of scatter plots to showcase the following relationships:

####  Latitude vs. Temperature
#### Latitude vs. Humidity
#### Latitude vs. Cloudiness
#### Latitude vs. Wind Speed

#### In the second part, I computedl Linear Regression for each relationship by separateing the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). I used the slope fdrmula, y=mx + b, to assist in creating the linear regression line. Then I created a series of scatter plots, with the linear regression line, the model's formula, and the r-values, to explainthe relationships between different relationships:

#### Northern Hemisphere: Temperature vs. Latitude, Southern Hemisphere: Temperature vs. Latitude
#### Northern Hemisphere: Humidity vs. Latitude, Southern Hemisphere: Humidity vs. Latitude
#### Northern Hemisphere: Cloudiness vs. Latitude, Southern Hemisphere: Cloudiness vs. Latitude
#### Northern Hemisphere: Wind Speed vs. Latitude, Southern Hemisphere: Wind Speed vs. Latitude
#### After each modeling pair, I briefly summarized my findings  for each relationship.

#### Armed with the data that I worked with, I wanted to use my weather data skills to plan future vacations. I used the geoViews Python library, and the Geoapify API, to get the code needed to import the required libraries and load the CSV file with the weather and coordinates data for each city I created in Part 1. then I used them both to employ my excellent Python skills to create map visualizations. The first map was to show every city in the world with their corresponding weather data, with the largest bubbles representing cities with high humidity(yuck!), and the smaller ones represent smaller humidities, with the sizws representing a scale.

Lastly each city, I used the Geoapify API to find the first hotel located within 10,000 meters of my coordinates. Then I added the hotel name and the country as additional information in the hover message for each city on the map!

 

 
