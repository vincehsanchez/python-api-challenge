# python-api-challenge

### Part 1: WeatherPy

***Create a Python script to visualize the weather of over 500 cities of varying distances from the equator.***

Create a representative model of weather across cities.

Generate random geographic coordinates and the nearest city to each latitude and longitude combination is provided.

Create Plots to Showcase the Relationship Between Weather Variables and Latitude.

Use the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code.

Create a series of scatter plots to showcase the following relationships:
- Latitude vs. Temperature
- Latitude vs. Humidity
- Latitude vs. Cloudiness
- Latitude vs. Wind Speed

***Compute Linear Regression for Each Relationship***

Compute the linear regression for each relationship. 

Separate the plots into:
- Northern Hemisphere (greater than or equal to 0 degrees latitude)
- Southern Hemisphere (less than 0 degrees latitude).

Create a series of scatter plots with:
- linear regression line
- model's formula
- r values

Create the following plots and explaining what the linear regression is modeling:
- Northern Hemisphere: Temperature vs. Latitude
- Southern Hemisphere: Temperature vs. Latitude
- Northern Hemisphere: Humidity vs. Latitude
- Southern Hemisphere: Humidity vs. Latitude
- Northern Hemisphere: Cloudiness vs. Latitude
- Southern Hemisphere: Cloudiness vs. Latitude
- Northern Hemisphere: Wind Speed vs. Latitude
- Southern Hemisphere: Wind Speed vs. Latitude

Describe any relationships that you notice and any other findings you may uncover.

### Part 2: VacationPy

Create map visualizations using the Geoapify API and the geoViews Python library.

Create a map that displays a point for every city in the city_data_df DataFrame:
- size of the point should be the humidity in each city

Narrow down the city_data_df DataFrame to find your ideal weather condition.

Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.
For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.
Add the hotel name and the country as additional information in the hover message for each city on the map as in the following image:
