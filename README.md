# Python_API_Challenge

## Background
There's two parts to this project. API request, and Python script to visualize the weather date of 500+ cities across the world of varying distance from the equator, and sourced under WeatherPy folder. To accomplish this, I used, Python the OpenWeatherMap API, and created a representative model of weather across world cities. The cities dataset found in output_data folder which includes the following columns City_ID,City,Cloudines,Country,Date, Humidity,Lat,Lng,Max,Temp,Wind Speed. The data analyzed, and displayed on in my jupyter notebook, and the results are exported in CSV format city_weather_data.csv, and the regression plots in the output folder.

The other project VacationPy is used the output data from the previous task city_weather_data.csv, and investigate the data to plan for future vacations, and to select hotels. For this part of the analysis the a jupyter-gmaps, and the Google Places were used, and the results are displayed in VacationPy jupyter notebook. The analysis covers humidity heatmap in the cities that sourced from the weather data, and spot the hotels on top of the humidity heatmap. You can look at the images in the output folder for both the heatmap and the hotel heatmap images.



## Observable Trends and Insights 

*  The findings of these analysis showed that there is a higher temperature for cities that found near to the equator (Latitude 0), however, when we go farther from the equator towards the north the temperature decreases highly. However, when we go to the south the temperature decreases but it is much lower comparing to the north. The regression analysis and plot also showed that there is a strong negative correlation between temperature, and latitude in the northern hemisphere however, the correlation between temperature and latitude in the south Hemisphere is negative but very week to conclude. 

* The findings from the data, plots, and the regression line in the case of testing if there is a relation between humidity and cloudiness of cities nearer or farther to the equator (latitude 0) doesn't show any significant results. The correlation between humidity and latitude for both northern and southern hemisphere cities is very week, a negative correlation, and the result for cloudiness and latitude also very week and negative. Therefore, We can infer that humidity can be fairly distributed in both northern and southern hemisphere cities regardless of their distance from the equator.

* The finding from the analysis of  the relationship between wind speed (mph), and latitude showed that the lower wind speed when the cities closer to the equater (latitude 0), and somehow the wind speed increase for the cities farther from the equater. The regression analysis also showed that there is a very week, posetive correlation between Wind Speed (mph (%) and Latitude in the Northern Hemisphere cities.

* In the second task VacationPy, I understand that creating an exploratory-interactive geospatial, Weather information, heat maps, and visualization through Google API, and other similar API applications play a remarkable role to exploit the potential socio-economic value buried inside monotonously large datasets.

