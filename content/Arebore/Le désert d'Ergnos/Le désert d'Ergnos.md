---
title: Le désert d'Ergnos
draft: true
tags:
  - Désert
  - Ergnos
  - Map
---

[[Regional Map Ergnos.png]]

```leaflet  
id: DesertErgnos ### Must be unique with no spaces  
image: [[Regional Map Ergnos.png]] ### Link to the map image file. Do not add a ! in front of the image  
bounds: [[0,0], [936, 1407]] ### Size of the map in px Height_y, Width_x. Ignore 0,0  
height: 650px ### Size of the leaflet embed in px on your screen  
width: 95% ### Size of the leaflet embed in your note  
lat: 468 ### To center the map, make this half of the map height.  
long: 703.5 ### To center the map, make this half of the map width.  
minZoom: -1 ### Controls how far away from the map you can zoom out. Hover over the target icon to see the current level.  
maxZoom: 2 ### Controls how far towards the map you can zoom in. Hover over the target icon to see the current level.  
defaultZoom: -1 ### Sets the default zoom level when the map loads. Hover over the target icon to see the current level.  
zoomDelta: 0.5 ### Adjust how much the zoom changes when you zoom in or out.  
unit: Km ### The value displayed when measuring so you know what type of unit is being measure.  
scale: 0.5 ### Real units/px (resolution) of your map  
recenter: false  
darkmode: false ### marker
```
