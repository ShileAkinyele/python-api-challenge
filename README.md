# python-api-challenge
This involves analysis using the Open Weather API.

Analysis is divided into Vacation and Weather. information for vactaion can be found in the VacationPy.ipynb file, while information for the weather analysis can be found in the WeatherPy.ipynb.

The following is performed in the weather Analysis:

creainge a series of scatter plots to showcase the following relationships:

Latitude vs. Temperature

Latitude vs. Humidity

Latitude vs. Cloudiness

Latitude vs. Wind Speed

Northern Hemisphere: Temperature vs. Latitude

Southern Hemisphere: Temperature vs. Latitude

Northern Hemisphere: Humidity vs. Latitude

Southern Hemisphere: Humidity vs. Latitude

Northern Hemisphere: Cloudiness vs. Latitude

Southern Hemisphere: Cloudiness vs. Latitude

Northern Hemisphere: Wind Speed vs. Latitude

Southern Hemisphere: Wind Speed vs. Latitude

After each pair of plots, explain what the linear regression is modeling. Describe any relationships that you notice and any other findings you may uncover. Results uncovered from the linear regression plots show the following:


There is a positive relationship/correlation between the temperature and latitude in the southern hemisphere while a negative relationship exists between temp and lat in the Northern hemisphere.72% of the changes in temperature is being predicted by the latitude in the northern hemisphere while 55% of the changes in temperature is being predicted by the latitude in the southern hemisphere.


There is a positive relationship/correlation between the Humidity and latitude in both the Northern and Southern Hemisphere.4.8%of the changes in Humidity is being predicted by the latitude in the northern hemisphere while 2.1% of the changes in Humidity is being predicted by the latitude in the southern hemisphere.


There is a negative relationship/correlation between the Cloudiness and latitude in both the Northern and Southern Hemisphere.1.9% of the changes in Cloudiness is being predicted by the latitude in the northern hemisphere while 3.5% of the changes in Cloudiness is being predicted by the latitude in the southern hemisphere


Analysis in the Vaction PY consists of the following:

Create a map that displays a point for every city in the city_data_df DataFrame as shown in the following image. The size of the point should be the humidity in each city.

Narrow down the city_data_df DataFrame to find your ideal weather condition

Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.

For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.

Add the hotel name and the country as additional information in the hover message for each city on the map

There is a positive relationship/correlation between the Windspeed and latitude in the southern hemisphere while a negative relationship exists between Windspeed and lat in the Northern hemisphere.1.2% of the changes in temperature is being predicted by the latitude in the northern hemisphere while 4.8% of the changes in Wind Speed is being predicted by the latitude in the southern hemisphere
