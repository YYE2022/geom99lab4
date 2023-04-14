# geom99 lab Technical log
### April 8, 2023
## OpenLayers desktop version
1. From the link https://openlayers.org/doc/quickstart.html, install Git, Node.js
2. locate the index.html, main.js, style.css files on my computer
3. open http://localhost:5173/ on the browser
4. make edit on the main.js ( the page from step 3 will automatically refresh 

 **Then realize there were not much example associated with arcgis rest service, then gave up on this

## Esri plugin OpenLayers
1. source code from https://developers.arcgis.com/openlayers/layers/add-a-feature-layer-as-geojson/
2. Replace the API key in the code, from https://developers.arcgis.com/dashboard/
3. Replace basemap, center latitude and longitude, zoom level
**Note: Openlayers uses LonLat, not LatLon
5. On the ArcGIS REST Services page https://ws.lioservices.lrc.gov.on.ca/arcgis2/rest/services/MOE/PWQMN/MapServer , choose a layer, srcoll down to query and generate a geojson format
6. add the layer to the map: replace the link in the code
7. Edit the pop-up window information to display the water quality data regarding the Chlorides, Nitrates and Phosphates level.

