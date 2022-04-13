# Add-Geotiff-Layer-on-Base-Map-using-Openlayers

### In this project, any data published on Geoserver can be fetched and placed directly on the base map using animation Technologies Used
•	QGIS
•	Geoserver
•	Openlayers 6 – JS Mapping Library
•	jQuery
•	Bootstrap

### Import all the necessary CSS files and JS files to your main file (index.html)
##### In this project, I have used a local server (Wampserver64) to fetch files from it and then imported them into my main file.
Files to be imported are (can be downloaded from the repository) –
•	ol.css
•	layout.css
•	ol-layerswitcher.css
•	ol.js
•	ol-layerswitcher.js
•	jquery.min.js
•	bootstrap.min.css
•	bootstrap.min.js
•	jquery-ui.css
•	jquery.js
•	jquery-ui.js

### Follow the comments in the main code for an explanation
Tiff files have to be hosted on geoserver and then has to be imported into the code.

##### Example:
url: 'http://localhost:8081/geoserver/yourworkspace/wms',
                params: {
                    'LAYERS': ' your workspace: your layer name'

# Follow the code for all the other functionalities


