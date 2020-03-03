## Python API Challenge

Objective: Demonstrate my knowledge on API interactions
[technologies utilized: Pandas, Matplotlib]

<b> Part 1 - WeatherPy </b>

Goal: Visualize the weather of 500+ cities across the world of varying distances from the equator using OpenWeatherMap API to create a representative model of weather across world cities. 

Step 1: Collect data 
- Randomly select at least 500 unique cities based on latitude and longitude
- Perform weather check on each city using a series of API calls 

Step 2: Build a series of scatter plots:
- Temperature vs. Latitude
- Humidity vs. Latitude
- Cloudiness vs. Latitude
- Wind Speed vs. Latitude

Step 3: Categorize cities based off of Northern and Southern hemispher then run linear regression on the following relationships:
- Northern Hemisphere - Temperature (F) vs. Latitude
- Southern Hemisphere - Temperature (F) vs. Latitude
- Northern Hemisphere - Humidity (%) vs. Latitude
- Southern Hemisphere - Humidity (%) vs. Latitude
- Northern Hemisphere - Cloudiness (%) vs. Latitude
- Southern Hemisphere - Cloudiness (%) vs. Latitude
- Northern Hemisphere - Wind Speed (mph) vs. Latitude
- Southern Hemisphere - Wind Speed (mph) vs. Latitude

<b> Part 2 - VacationPy </b>

Goal: From the data collected above in Part 1 - identify locations for future vacations

Step 1: Create a heat map that displays the humidity for every city

Step 2: Identify cities with your ideal weather condition (lower than 80 degrees but higher than 70 degrees with wind speed less than 10 mph and zero cloudiness. 

Step 3: Use Google Places API to find the first hotel for each city located within 5000 meters of coordinates

Step 4: Plot the hotels on top of the humidity heatmap with each pin containing the Hotel Name, City, and Country.
