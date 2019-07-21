# Homework Unit 6 | Assignment - API What's the Weather Like? WeatherPy
![alt text](https://github.com/DanielMJones2005/HW_Unit6_API/blob/master/equatorsign.png)

# Background
Create a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. 
Utilize a simple Python library, the OpenWeatherMap API, and a little common sense to create a representative model of weather across world cities.

# Objective
Build a series of scatter plots to showcase the following relationships:
• Temperature (F) vs. Latitude 
• Humidity (%) vs. Latitude 
• Cloudiness (%) vs. Latitude 
• Wind Speed (mph) vs. Latitude

# Source Files:
- Citypy
- OpenWeather API

# A written description of three observable trends based on the data
- 1. The hottest max temperature of cities tends to cluster between -20 and 40 degrees of latitude based on a random sample of greater than 500 cities. As the distance becomes farther away from either -20 or 40 degrees, the max temperature of the cities also decreases.

![alt text](https://github.com/DanielMJones2005/HW_Unit6_API/blob/master/output_data/20190721%20City_Lat_vs_Max_Temp.png)
- 2. Varying percentages of humidity in cities seems to be well distributed across latitudes.  In other words, latitude is not necessarily a predictor of a city’s humidity.

![alt text](https://github.com/DanielMJones2005/HW_Unit6_API/blob/master/output_data/20190721%20City_Lat_vs_Humidity.png)
- 3. While wind speed also seems to be well distributed across latitudes, the average wind speed is 8.35 mph and the median wind speed is 6.93 mph.  The standard deviation is 5.7 mph.
  -- Average Wind Speed: 8.35
  -- Median Wind Speed:6.93
  -- Standard Deviation Wind Speed:5.7
  
![alt text](https://github.com/DanielMJones2005/HW_Unit6_API/blob/master/output_data/20190721%20City_Lat_vs_Windspeed.png)
