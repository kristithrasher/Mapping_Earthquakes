
# Mapping_Earthquakes

## Purpose
Basil and Sadhana would like to see the earthquake data in relation to the tectonic plates’ location on the earth, and
they would like to see all the earthquakes with a magnitude greater than 4.5 on the map, and they would like to see the data on a third map. 

## Results

A Map Using my knowledge of JavaScript, Leaflet.js, and geoJSON data, added major earthquake data to the map using d3.json().

* Tectonic Plate Data
  Addied the data using tyhe geoJSO() layer and set the tectonic plate LineString data to stand out on the map, also added the tectonic plate data for the overlay object with the earthquake data. 
Image is of all earthquakes and tetonic data.
![Screenshot (64)](https://user-images.githubusercontent.com/94208810/154193892-e819d6d8-5648-4f9a-844f-9e052ec8b380.png)


* Major Erarthquake Data
   Added color and set the radius of the circle markers based on the magnitude of earthquake, and add a popup marker for each earthquake that displays the magnitude and location of the earthquake using the GeoJSON layer, geoJSON().
![Screenshot (65)](https://user-images.githubusercontent.com/94208810/154193699-4bc1e8ed-0934-42a1-a8d4-6c68abd91270.png)

* Additonal Map 
  A third map tile layer is created. 
  * Dark option
  Added an overlay object to show earthquakes in Dark.
  All the earthquake data and tectonic plate data are displayed on the all maps of the webpage and can be toggled on and off. 
![Screenshot (70)](https://user-images.githubusercontent.com/94208810/154194376-34d708e4-fa26-445c-b157-f38145d0e95f.png)
