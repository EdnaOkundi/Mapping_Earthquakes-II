# Mapping_Earthquakes

Maps allow us to explore, understand, and make decisions about our world. 
In this repository we will use javascript (GeoJSON) to create interactive maps to visualize earthquake data. 
GeoJSON data can be found in many apps that have a map feature such as ride-sharing, navigation, and food and package delivery services. 
Even location services on smart phones use GeoSJON format. 

The purpose of this project is to visually show the differences between the magnitudes of earthquakes all 
over the world for the last seven days.To complete this project, I used a URL for GeoJSON earthquake data from the  
and retrieved geographical coordinates and the magnitudes of earthquakes for the last seven days. Then added the data to a map.

Results
Each earthquake is visually represented by a circle and color, where a higher magnitude will have a 
larger diameter and will be darker in color. In addition, each earthquake has a popup marker that, when clicked, 
shows the magnitude of the earthquake and the location of the earthquake. The map has three views:
-Street View
-Satellite View
-Dark View

The viewer can also toggle between three layers to filter the data. These layers include: 
-All Earthquakes
-Tectonic Plates
-Major Earthquakes (greater than 6 magnitude)

Summary
To create the maps we used the JavaScript and the D3.js library to retrieve the coordinates and magnitudes of the earthquakes 
from the GeoJSON data. Calling the API's alllowed us to traverse and retrieve GeoJSON earthquake data and tectonic plate 
data in order to populate a map. I then used the Leaflet library to plot the data ona Mapbox map through an API request 
and create interactivity for the earthquake data. The viewer can toggle between different layers to view either all earthquakes, 
only major earthquakes (over 5 magnitude), and the earth's tectonic plates. By viewing this visualization, 
we can see it's pretty clear that the majority of the major earthquakes in the last week, 
have all occurred near or on the tectonic plates. Smaller earthquakes can occur farther away, 
but the major earthquakes all fall on or right next to the fault lines. 