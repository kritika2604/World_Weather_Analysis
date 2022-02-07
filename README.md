# World_Weather_Analysis
Weather \Py with Python APIs

## Purpose :
Deliverable 1: Retrieve Weather Data

Deliverable 2: Create a Customer Travel Destinations Map

Deliverable 3: Create a Travel Itinerary Map

The Analysis included the following steps:

***1. Collection of data***

  - NumPy module used to generate more than 1,500 random latitudes and longitudes.

  - Citipy module to list the nearest city to the latitudes and longitudes.

  - The OpenWeatherMap API was used to request the current weather data from each unique city in the list.

  - The JSON data was parsed from the API request and following data was collected - 

    	City, country, and date
    
    	Latitude and longitude
    
    	Maximum temperature
    
    	Humidity
    
    	Cloudiness
    
    	Wind speed
    
    
***2. Exploratory Analysis with Visualization***
      Various scatter plots of the weather data are presneted to show the variation of temperature, humidity, cloudiness and wind speed with respect to latitude. 
      The correlation of the weather data was determined. Heatmaps using google APIs and google maps were prepared.
      
      
      
      
***3. Visualize Travel Data***
      Hotel names from the cities coordinates were found using google maps and places API and search nearby function. 
      Pop up markers were added to the heatmpap to display information about the city, current maximum temperature and a hotel in the city. 

