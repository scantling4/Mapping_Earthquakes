# Mapping_Earthquakes

[Mapping Earthquakes](/Leaflet_Map.png)

## Overview 

The purpose of this analysis was to first create an earthquake map with two different maps and an earthquake overlay. The second part of the analysis, which was completed as a part of the challenge (earthquake_challenge), consisted of showing the earthquake data in relation to techtonic plates' location, showing all the earthquakes with a magnitude greater than 4.5 on the map, and the creation of a third map. Leaflet.js, MapBox API, and Javascript were utlized to accomplish this. 

## Different aspects of Mapping that were explored 

# 1. Map a Single Point 

-added a single marker and circle for Los Angeles, CA to the map 

# 2. Map Multiple Points 

-created an array of multiple cities (New York City, Chicago, Houston, Los Angeles, and Phoenix) and looped through them to create a marker for each. Also binded a popup to each marker that shows the city, state, and population size. 

# 3. Map Lines 

-mapped airline route from Los Angeles to San Francisco. Then added two more airport stops: SLC and SEA. 

# 4. Map GeoJSON Point Type

-added a single point on the map using GeoJSON data which is a FeatureCollection object that has properties and geometry for the San Francisco Airport. Used the onEachFunction to add a marker for each feature and to add data from the properties of the JavaScript object. 

# 5. Add Multiple Maps 

-utilized Leaflet Layers Control to control which styles we'll see on our map. We worked with streets and dark layers. The white box in the top right hand corner of the map allows you to switch between layers. 

# 6. Map GeoJSON LineStrings

-mapped the nonstop routes from Toronto on two map styles: light and dark. 

# 7. Map GeoJSON Polygons

-mapped polygons around the different neighborhoods in Toronto

# 8. Add Earthquake data from the past 7 days to the map

1. Utilized d3.json to obtain earthquake data
2. Added styling to the data 
      -example: passing the magnitude of the earthquake into a function to calculate the radius 
3. Added color and a popup for each earthquake
4. Added Earthquake Data as an Overlay
5. Added a legend to the map

# 9. Challenge 
 
 1. Added Techtonic Plate Data to the map 
 2. Added Major Earthquake Data
 3. Added an additional map 
    
