# Mapping_Earthquakes

## Purpose
Basil and Sadhana would like to see the earthquake data in relation to the tectonic plates’ location on the earth, and
they would like to see all the earthquakes with a magnitude greater than 4.5 on the map, and they would like to see the data on a third map. 

## Results

A Map Using my knowledge of JavaScript, Leaflet.js, and geoJSON data, added major earthquake data to the map using d3.json().

* Tectonic Plate Data
  Addied the data using tyhe geoJSO() layer and set the tectonic plate LineString data to stand out on the map, also added the tectonic plate data for the overlay object with the earthquake data. 


* Major Erarthquake Data
   Added color and set the radius of the circle markers based on the magnitude of earthquake, and add a popup marker for each earthquake that displays the magnitude and location of the earthquake using the GeoJSON layer, geoJSON().

* Additonal Map 
  A third map tile layer is created. 
  * Dark option
  Added an overlay object to show earthquakes in Dark.
  All the earthquake data and tectonic plate data are displayed on the all maps of the webpage and can be toggled on and off. 
