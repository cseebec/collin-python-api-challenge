# collin-python-api-challenge
Gather data from APIs then create plots using matplotlib to show the fact that temperatures increase as the get closer to the equator. 

## Software / Libraries
- CSV Files 
- Jupyter Lab
- Python 3
   - Matplotlib
   - Numpy
   - Requests
   - Os
   - Time
   - Scipy
   - Pprint
   - Gmaps
   - Citipy

## APIs Need 
https://openweathermap.org/api

https://mapsplatform.google.com/

**The code will not work unless you create accounts at openweathermap.org and googleapis.com and get api_keys. The first cell in each code references api_keys.py which is not included in the repo because if you use api too much it costs money otherwise the api is free to use. For this reason I did not want to post my api key publicly.**

**If you do create accounts at these websites and get api keys the code in this repo will run without any problems**

## Part I Weather 
### Pseudocode
1. Create a list of random latitudes and longitudes 
2. Get nearest city to each latitude / longitude location
3. Get current humidity, cloudiness, windspeed and max daily temperature for each city
4. Create scatter plots for both the Northern and Southern Hemisphere showing Max Temperature vs Latitude, Humidity % vs Latitude, Cloudiness vs Latitude and  Windspeed vs Latitude

**Example of scatterplot: Southern Hemisphere Latitude vs Daily Max Temperature**
![](Weather/output_data/Southern_Lat_vs_MaxTemp.png)

**To see the conclusions I made based on this code please see Weather_Conclustions.docx in the Weather folder**

## Part II Vacation
Create a heat map that displays the humidity for every city from the Weather data

