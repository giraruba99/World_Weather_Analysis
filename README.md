# World_Weather_Analysis
 *  This project is all about weather data analysis for a travel company to help them map 500 cities in the world. With the help of Python (jupyter notebook, Pandas library, SciPy statistics and matplotlib), API and other tools, we are creating an analysis that will give the travel company to have an informed decision about their future plan.

 ## Purpose: The main purpose of the analysis is as follows:-
  
  * To create a data base of cities from random 2000 lat-lng coordinates from the whole world.
  * To perform an API call with OpenWeatherMap and retrieve different weather data per the cities in the defined geographic coordinates. 
  * To run a vacation search based on customer weather preferences, and search nearest hotels.
  * To provide a visual marker of hotels that meet the customer criteria and display on google map.
  * To provide a 3 different means of transport between 4 target cities and show a google map visualization of those destinations.

## Results and Analysis:
  ### Performing an API call from OpenWeatherMap:-
  * A great deal of weather data was retrieved and here is the DataFrame out of our API call.
  
![city_data_df](https://user-images.githubusercontent.com/89214854/138582583-fa95518a-1c16-400e-b41b-373045e52923.png)

  * A CSV was successfully saved for further analysis... the adventure of analyzing the data continues below.

  ### Identifying potential travel destinations:-
  * From the CSV data created above, we were able to retrieve hotel data that meets customer weather preferences.
  * The following marker layer map was created with a pop-up marker for each city.

![WeatherPy_vacation_map](https://user-images.githubusercontent.com/89214854/138582865-4cf625d1-749d-44da-a369-53715b4c0222.png)


  ### Creating a Travel Itinerary map

  * From our cities that meet customer weather preferences, 4 US cities were chosen (Saint George, Steamboat Springs, Saint Anthony and Ponca City).
  * Three ways of travelling among those destinations was created (driving, bicycling and walking routes).

  - Driving Route:-
![WeatherPy_travel_map_driving](https://user-images.githubusercontent.com/89214854/138582890-96d48695-4be5-4617-8ca6-1d9ad1b1a020.png)

  - Bicycling Route:-
![WeatherPy_travel_map_bicycling](https://user-images.githubusercontent.com/89214854/138582883-4489c4c0-63e3-430f-9315-0dc705543dbf.png)

  - Walking Route:-
![WeatherPy_travel_map_walking](https://user-images.githubusercontent.com/89214854/138582897-377e07b5-f837-4079-9043-f878b88d3513.png)

  * Finally, we were able to display the 4 cities on google map to visualize their relative locations.
![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/89214854/138582907-87747e96-c6ad-470f-9bcb-bc7fcd49c0e1.png)

## Conclusion
* In conclusion, we successfully built a system that uses OpenWeatherMap API and GoogleMap API to create a worldwide database of hotels that meet customer preferences. There was no obstacle faced during the analysis and extremely clean data was retrieved.


