﻿# Texas in QGIS: Geo-referencing Historical Maps
[originally used Monday, April 4, 2016]
### This tutorial is designed so you can practice the skills you learned in  the [Programming Historian QGIS Tutorial “Geo-referencing in QGIS”]( http://programminghistorian.org/lessons/georeferencing-qgis "Links to Programming Historian")

1. [Note for future work: Each time you install a new version of QGIS, be sure to activate the Georeferencing toolbar in that installation]
2. Open a new project; set the CRS by typing 3081 in the filter box and choosing “NAD83 / Texas State Mapping System”
3. Set up your modern georeferencing ‘canvas’
   * Add Vector and load StratMap\_County\_poly.shp [a modern shapefile] to serve as georeferencing canvas.
   * Add Vector: txdot-2015-city-point\_tx.shp
   * Add Vector: txdot-2015-city-poly\_tx.shp
   * For all – change the “properties” so they are not solid. Turn “labels” on for one of the city files [you may have to use both of them]
4. Download an 1800s map from UTA's Cartographic Connections website: http://libguides.uta.edu/ccon
   * Use your image viewer software [ie Microsoft Picture Manager] to convert the JPG file to TIFF
   * Use the georeferencer to add the TIFF version as a raster layer and add 6 or more control points
     * Use manmade boundaries, not coastline or rivers which can change
     * Use large cities, ports, or military bases that would have had precise lat/long readings in the 1800s
     * Have at least 3 in the western part of the state
     * Have more than 3 in the eastern part of the state, in heavily populated areas
5. Specify transformation settings
6. Compare geo-referenced map to modern shapefile
7. Possible: create new vector layers to capture data on the old map

# Data sources for this tutorial
1. Basemaps: https://tnris.org/maps-and-data/ -- search for political boundaries
2. Historic maps: UTA’s Cartographic Connections: http://libguides.uta.edu/ccon 
# How to Convert map-image files
- From JPG to TIFF: Most image viewers will do this. For PC, use  www.irfanview.com [pc] or Microsoft Picture Manager
- From SID to TIFF; irfanview can do this; search the web for other utilities
