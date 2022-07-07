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
      The correlation of the weather data was determined. Heatmaps using google APIs and google maps were prepared. </br>
      <img width="529" alt="image" src="https://user-images.githubusercontent.com/94858846/177815164-0068d377-4889-49e1-a7fa-b777f6f1c3c7.png"> 
      <img width="529"  alt="image" src="https://user-images.githubusercontent.com/94858846/177815258-14006189-6383-4574-932e-c15c35fed6ab.png"> </br>
     <img width="529" alt="image" src="https://user-images.githubusercontent.com/94858846/177815353-c1a391c5-e087-445e-80e3-f203961c9425.png"> </br>
     <img width="529" alt="image" src="https://user-images.githubusercontent.com/94858846/177815415-eb766fc5-359a-4cb2-8f84-47d32013b36b.png">




 
      
      
      
      
      
***3. Visualize Travel Data***
      Hotel names from the cities coordinates were found using google maps and places API and search nearby function. 
      Pop up markers were added to the heatmpap to display information about the city, current maximum temperature and a hotel in the city. </br>
      <img width="725" alt="image" src="https://user-images.githubusercontent.com/94858846/177814707-7920ce08-78d9-4171-8c99-9ac3e57ca8d8.png"> </br>
      <img width="725" alt="image" src="https://user-images.githubusercontent.com/94858846/177816872-53076ae2-98e9-44a3-bb3f-6f5cb75b6f3d.png">


