# Python-API-Challenge

The Python API challenge is broken down into two deliverables, WeatherPy and VacationPY. For part 1 (WeatherPy), I created a Python
script that was able to visualize the weather of over 500 cities of varying distances from the equator. A OpenWeatherMap API was used to retrieve 
weather data from the cities list generated in the starter code. I then created a series of scatter plots to showcase the following relationships:

-Latitude vs. Temperature.

-Latitude vs. Humidity.

-Latitude vs. Cloudiness.

-Latitude vs. Wind Speed.

I was then able to compute the linear regression for each relationship. Separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) 
and Southern Hemisphere (less than 0 degrees latitude). Defined a function in order to create the linear regression plots, and described teh relationships that
I notcied in my findings.

Part 2 of the challenge (VacationPy) I used the data from the previous section to plan future vacations. I had to narrrow down the city_data_df to find
my idead weather conditions. So mine were a max temp greater than 18 degrees but equal to or less than 30, with humidity equal to or less than 40 and 
cloudiness less than 60. A new dataframe called hotle_df was creted to store the city, country, coordinates, and humidity. Geoapify API was used to find the first hotel 
located within 10,000 meters of my coordinates. The hotel names and the country were added as additional information in the hover message for each city on the map.

*Technologies used: Microsoft Visual Studio Code. Citipy library and OpenWeatherMapAPI were also used.

*How to activate code:

-Save the repository in your desired location, then cd into that directory in git bash (or use terminal if you're OS user).

-Type jupyter notebook into the terminal.

-Once you're in jupyter notebook, open each of the .ipynb files and run through each section of the script.
