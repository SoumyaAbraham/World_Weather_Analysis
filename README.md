# World_Weather_Analysis

## Overview  

By taking into consideration user-preferred tempereatures, we will create optimum vacation areas and map out the route for user-specified cities.

---
### Deliverable 1: Creating a Weather Database  

Retrieving the following information for cities acquired based on latitudes and longitudes randomly created:
  
- Latitude and Longitude
- Maximum Temperature
- Percentage Humidity
- Percentage Cloudiness
- Wind Speed
- Weather Description  
    
This information is created into a dataframe:  

![city_data_df](https://github.com/SoumyaAbraham/World_Weather_Analysis/blob/main/Screenshots/city_data_df.png)

We then export this into a .csv file which can be found here: 
[WeatherPy_Database.csv](https://github.com/SoumyaAbraham/World_Weather_Analysis/blob/main/Weather_Database/WeatherPy_Database.csv)  

---

### Deliverable 2: Creating a Customer Travel Destinations Map  

* Creating a heatmap for the cities in *city_data_df*.  

![heatmap](https://github.com/SoumyaAbraham/World_Weather_Analysis/blob/main/Screenshots/heatmap.png)  

* Creating a new dataframe of cities based on User suggested Maximum and Minimum temperatures. This dataframe is used to find Hotels (lodging) within 5000m of the marked locations. Google APIs are used for this purpose.  

![hotel_df](https://github.com/SoumyaAbraham/World_Weather_Analysis/blob/main/Screenshots/hotel_df.png)  

* We then export this into a .csv file which can be found here: 
[WeatherPy_Vacation](https://github.com/SoumyaAbraham/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation.csv)

* Lastly, we create a map with markers that had information box with *Hotel Name, City, Country, Current Weather Description and Max Temp.*  

![WeatherPy_Vacation](https://github.com/SoumyaAbraham/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_Vacation_Map.png)

---

### Deliverable 3: Creating a travel Intinerary Map  

* Creating an itinerary map based on 4 cities in Brazil- _Vilhena, Jardim, Ribas do Rio Pardo and Guiratinga_.

* We can trace the travel route by Driving Mode to form the following route map:  

![WeatherPy_TravelMap](https://github.com/SoumyaAbraham/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png.png)  

* We create a DataFrame for the selected cities  

![itinerary_df](https://github.com/SoumyaAbraham/World_Weather_Analysis/blob/main/Screenshots/itinerary_df.png)  

* Lastly, we create a map with markers that had information box with *Hotel Name, City, Country, Current Weather Description and Max Temp.*  

![WeatherPy_marker_map](https://github.com/SoumyaAbraham/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png.png)

---













