---
title: Example Title
draft: true
tags:
  - Arebore
  - Map
---
 
[[Arebore.png]]

```leaflet  
id: AreboreMain ### Must be unique with no spaces  
image: [[Arebore.png]] ### Link to the map image file. Do not add a ! in front of the image  
bounds: [[0,0], [2566, 3594]] ### Size of the map in px Height_y, Width_x. Ignore 0,0  
height: 650px ### Size of the leaflet embed in px on your screen  
width: 95% ### Size of the leaflet embed in your note  
lat: 1283 ### To center the map, make this half of the map height.  
long: 1797 ### To center the map, make this half of the map width.  
minZoom: -2.5 ### Controls how far away from the map you can zoom out. Hover over the target icon to see the current level.  
maxZoom: 1 ### Controls how far towards the map you can zoom in. Hover over the target icon to see the current level.  
defaultZoom: -1 ### Sets the default zoom level when the map loads. Hover over the target icon to see the current level.  
zoomDelta: 0.5 ### Adjust how much the zoom changes when you zoom in or out.  
unit: Km ### The value displayed when measuring so you know what type of unit is being measure.  
scale: 1.3 ### Real units/px (resolution) of your map  
recenter: false  
darkmode: true ### markermarker: default,1162.2890625,2230.75,,,,

```
