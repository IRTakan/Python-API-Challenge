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

## Pictures of Results

<img src="https://github.com/IRTakan/Python-API-Challenge/assets/132292790/f00039bb-b553-4fd9-aee0-007c55965403" width=400 height=300>

<img src="https://github.com/IRTakan/Python-API-Challenge/assets/132292790/6f02034d-792b-4584-b061-2cbce92bcda8" width=400 height=300>

<img src="https://github.com/IRTakan/Python-API-Challenge/assets/132292790/3501a5c5-40df-4211-b3f5-b876d52ce95f" width=400 height=300>

<img src ="https://github.com/IRTakan/Python-API-Challenge/assets/132292790/5954da2a-b453-4887-94aa-d0e771ff8f2e" width=400 height=300>

<img src ="https://github.com/IRTakan/Python-API-Challenge/assets/132292790/37a900a6-d5dc-47a7-82e9-31debd1cc4b7" width=500 height=300>

<img src ="https://github.com/IRTakan/Python-API-Challenge/assets/132292790/1f414d9b-cd31-45c6-81f1-83537550d1c2" width=500 height=300>


-Temperature vs. Latitude Linear Regression Plot

<img src ="https://github.com/IRTakan/Python-API-Challenge/assets/132292790/0b7a0de1-eaf6-474c-a14c-80e8c498755b" width=400 height=300>

<img src ="https://github.com/IRTakan/Python-API-Challenge/assets/132292790/972a4646-7801-4b98-84f9-44773755b5a6" width=400 height=300>


-Humidity vs. Latitude Linear Regression Plot

<img src ="https://github.com/IRTakan/Python-API-Challenge/assets/132292790/8ac64535-d1db-41a8-98e8-1bb2090105b7" width=400 height=300>

<img src ="https://github.com/IRTakan/Python-API-Challenge/assets/132292790/b1b22ace-2331-4e12-85a1-5507308f778d" width=400 height=300>

Cloudiness vs. Latitude Linear Regression Plot

<img src ="https://github.com/IRTakan/Python-API-Challenge/assets/132292790/cd8d5514-8c01-4e0d-bb5a-bb87b8cd43d7" width=400 height=300>

<img src ="https://github.com/IRTakan/Python-API-Challenge/assets/132292790/c17babb2-e505-45b7-9d43-f53a8108b027" width=400 height=300>

Wind Speed vs. Latitude Linear Regression Plot

<img src ="https://github.com/IRTakan/Python-API-Challenge/assets/132292790/deaf5382-08a9-425f-8e60-08dff8749622" width=400 height=300>

<img src ="https://github.com/IRTakan/Python-API-Challenge/assets/132292790/8252a05e-e2d0-4789-87d9-7c8b39815765" width=400 height=300>

*Technologies used: Microsoft Visual Studio Code. Citipy library and OpenWeatherMapAPI were also used.

*How to activate code:

-Save the repository in your desired location, then cd into that directory in git bash (or use terminal if you're OS user).

-Type jupyter notebook into the terminal.

-Once you're in jupyter notebook, open each of the .ipynb files and run through each section of the script.
