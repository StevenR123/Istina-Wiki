---
aliases: 
draft: false
tags:
---
```leaflet
id: MapCalcExample ### Must be unique with no spaces
image: [[map1.jpeg]] ### Link to the map image file
bounds: [[0,0], [5794, 8192]] ### Size of the map in px Width_x, Height_y
height: 700px ### Size of the leaflet embed in px on your screen
width: 100% ### Size of the leaflet embed in your note
lat: 2000 ### To center the map, make this half of the map width.
long: 4750 ### To center the map, make this half of the map height.
minZoom: -1.5 ### Controls how far away from the map you can zoom out. Hover over the target icon to see the current level.
maxZoom: 1 ### Controls how far towards the map you can zoom in. Hover over the target icon to see the current level.
defaultZoom: -1 ### Sets the default zoom level when the map loads. Hover over the target icon to see the current level.
zoomDelta: 0.5 ### Adjust how much the zoom changes when you zoom in or out.
unit: km ### The value displayed when measuring so you know what type of unit is being measure.
scale: 0.09328358208955223 ### Only required if you are using the measurement tool. Real units/px (resolution) of your map
recenter: false
darkmode: false ### marker
marker: City,2049.1875,4738,Wagram,,,
marker: City,1861.1875,5036,Tradorn,,,
marker: City,2620,5638,Dech,,,
marker: City,3587.1875,5178,Sokarz,,,
marker: City,1903.531454954186,3832.518754031088,Beldurr,,,
marker: City,1512,3835,Phahn,,,
marker: City,1115,4447.5,Hearth,,,
marker: City,614.5,4449,Issun,,,marker: Outpost,2029,4729.5,Kovati,,0.9,

```