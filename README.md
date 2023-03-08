# python-api-challenge

Part 1: WeatherPy

In this deliverable, I created a Python script to visualize the weather of over 500 cities of varying distances from the equator. I used the citipy Python library Links to an external site., the OpenWeatherMap API Links to an external site.


Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude

To fulfill the first requirement, I used the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code. Next, I created a series of scatter plots to showcase the following relationships:
Latitude vs. Temperature
Latitude vs. Humidity
Latitude vs. Cloudiness
Latitude vs. Wind Speed

Requirement 2: Compute Linear Regression for Each Relationship

To fulfill the second requirement, I computed the linear regression for each relationship. Separated the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). Y
Next, I created a series of scatter plots. 

I created the following plots:
Northern Hemisphere: Temperature vs. Latitude
Southern Hemisphere: Temperature vs. Latitude
Northern Hemisphere: Humidity vs. Latitude
Southern Hemisphere: Humidity vs. Latitude
Northern Hemisphere: Cloudiness vs. Latitude
Southern Hemisphere: Cloudiness vs. Latitude
Northern Hemisphere: Wind Speed vs. Latitude
Southern Hemisphere: Wind Speed vs. Latitude

After each pair of plots, I explained what the linear regression is modeling. 


Part 2: VacationPy

The main tasks were to use the Geoapify API and the geoViews Python library and employ  Python skills to create map visualizations.

Created a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.
For each city, used the Geoapify API to find the first hotel located within 10,000 meters of my coordinates.
Added the hotel name and the country as additional information in the hover message for each city on the map as in the following image:
