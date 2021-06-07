# World_Weather_Analysis


## Project Overview:

- Providing a real- time suggestions for the traveler's choice of weather temperature. 
- Narrowed down the hotels within a given range of latitude and longitude


## Resources: 

    - Python; Pandas; Gmaps; Jupyter Notebooks; Numpy
    
    
### Summary

    - Weather_Database.ipynb: By using Google API, I imported 2000 random coordinates and created a Data Frame showing the list of:  "City", "Country", "Date", "Lat", "Lng", "Max Temp", "Humidity", "Cloudiness", "Wind Speed", "Current Description". 
    
    - Vacation_Search.ipynb: Reading the CSV file was previously created with the output of Weather_Database.ipynb, taking the desired minimum and maximum temperature from the traveler and then showing series of possible options as City, Country, Max Temp, Current Weather Description, Latitude, Longitude adn the available Hotel names nearby. 
    
    - Vacation_Itinerary: From the previosly created Vacation Searches, chose the desired trip and selected cities to visit in Ireland and created a new Data Frame with the detailed information of those 4 cities, including the Hotel Name for the road trip. 