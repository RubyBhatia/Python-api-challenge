** python-api-challenge**
   -Module 6 Challenge-

Introduction

The true power of Data is to explore a clear view to the question, whether its realted to financial, political or social. In this chapter it was a great opportunity to learn new knowledge of python requests, APIs and JSON traversals to address some basic questions like "How does the weather change as we move closer to the equator?"

This Challenge has two parts
Part 1: WeatherPy
Part 2: VacationPy

**Part:1 WeatherPy**
A Python script is developed to visulize the weather conditions of over 500 cities at various location from the equator, in this part. In order to analyse the data, citipy Python library, the OpeanWeatherMap API, and some analytical skill are used. 

Requirement 1: 
Create Plots to Showcase the Relationship Between Weather Variables and Latitude. Use the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code. Next, to create a series of scatter plots to showcase the following relationships:

Latitude vs. Temperature
Latitude vs. Humidity
Latitude vs. Cloudiness
Latitude vs. Wind Speed

Requirement 2: 
Compute Linear Regression for Each Relationship. Compute the linear regression for each relationship. Separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). And then, create a series of scatter plots. Be sure to include the linear regression line, the model's formula, and the r^2 values. The requirments is to create the following plots:

Northern Hemisphere: Temperature vs. Latitude
Southern Hemisphere: Temperature vs. Latitude
Northern Hemisphere: Humidity vs. Latitude
Southern Hemisphere: Humidity vs. Latitude
Northern Hemisphere: Cloudiness vs. Latitude
Southern Hemisphere: Cloudiness vs. Latitude
Northern Hemisphere: Wind Speed vs. Latitude
Southern Hemisphere: Wind Speed vs. Latitude

And at the end each pair of plots, explain what the linear regression is modeling. Describe any relationships that you notice and any other findings you may uncover. 

**Part:2  VacationPy**

In this task, you'll apply your weather data skills to plan future vacations. Additionally, you'll work with Jupyter notebooks, the geoViews Python library, and the Geoapify API. To help you get started, the necessary code to import the required libraries and load the CSV file containing the weather and coordinates data for each city from Part 1 has been provided. Your primary objectives will be to utilize the Geoapify API and the geoViews Python library, along with your Python expertise, to create map visualizations. 

To successfully complete this part of the assignment, open the VacationPy.ipynb starter code and follow these steps:

1. Generate a map that shows a point for each city in the city_data_df DataFrame, 
2. Filter the city_data_df DataFrame to identify cities that match your ideal weather conditions
3. Create a DataFrame named hotel_df to store information about the city, country, coordinates, and humidity.
4. For each city, use the Geoapify API to locate the nearest hotel within a 10,000-meter radius of your coordinates.
5. Include the hotel name and country as extra details in the hover message for each city on the map



Reference:
* BCS reading materials and classroom activites.
* AI tools like ChatGpT and Google Scolers
* Taking help from classmates 




















