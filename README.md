This Python-api-challenge consists of two assignements. The first one is WeatherPY. The script visualizes the weather of 500+ cities across the world of varying distance from the equator. I utilized a simple Python library, the OpenWeatherMap API and  created a representative model of weather across world cities.
I created a series of scatter plots to showcase the following relationships:

Temperature (F) vs. Latitude
Humidity (%) vs. Latitude
Cloudiness (%) vs. Latitude
Wind Speed (mph) vs. Latitude
I also ran linear regression on each relationship. I separated the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

Northern Hemisphere - Temperature (F) vs. Latitude
Southern Hemisphere - Temperature (F) vs. Latitude
Northern Hemisphere - Humidity (%) vs. Latitude
Southern Hemisphere - Humidity (%) vs. Latitude
Northern Hemisphere - Cloudiness (%) vs. Latitude
Southern Hemisphere - Cloudiness (%) vs. Latitude
Northern Hemisphere - Wind Speed (mph) vs. Latitude
Southern Hemisphere - Wind Speed (mph) vs. Latitude

In my second assignment,VacationPy, I created a heat map that displays the humidity for every city from Part I. I narrowed down the DataFrame to find ideal weather condition.
Using Google Places API I found the first hotel for each city located within 5000 meters of my coordinates. I plotted the hotels on top of the humidity heatmap with each pin containing the Hotel Name, City, and Country.





