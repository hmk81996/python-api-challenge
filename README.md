# python-api-challenge

# WeatherPy

## Goals

In this project, my goal was to use Python to visualize the weather of over 500 cities located varying distances from the equator. 

## Methodology

I used Jupyter notebook to access the the citipy Python library and the OpenWeatherMap API.

Building on the starter code, I generated 605 random geographic coordinates and retrieved weather data for the nearest city. 

I then created four scatter plots to show Latitude versus the following weather data: Temperature, Humidity, Cloudiness, and Windspeed. To further explore the relationship between these variables, I created two new DataFrames: northern hemisphere cities and southern hemisphere cities. 

I then defined a function to create the linear regression plots. Xpert Assistance reminded me how to create a function, position the linear equation position, and calculate the r^2 value.

After creating eight scatter plots to show linear regression for each of the four variables in both the northern and southern hempisheres, I provided a discussion of the linear relationship as shown in the plot and by the r^2 value.

## Results and Analysis

The only weather data variables with a very strong correlation was latitude and tempature in the northern hemisphere. Latitude and tempature correlation in the southern hemisphere was moderate. For all other variables compared with latitude (humidity, cloudiness and windspeed), the correlation was very weak (and perhaps none). These results provide evidence that a location's proximity to the equator does indeed have a strong effect on its temperature. 

## Challenges

The task that challenged me the most in this activity was just making sure that my api_keys and .gitignore were set up correctly. Initial errors when I was generating the random list of cities momentarily impeded the rest of the project. This project was a good reminder of how to create a function (linear regression being a pretty complex one) that I can repeatedly call as well as how to identify important variables (like the r^2 valueable) within that function to use for additional analysis. I ran into issues with two variables: Wind Speed and Tempature. For Wind Speed, my original variable didn't recognize that there were three values being returned so I had to add further index it for "speed". When my temperature data was being returned in Kelvins, I remembered to add "&units=metric" to my endpoint URL.

# VacationPy

## Goals


## Methodology


## Results and Analysis


## Challenges

