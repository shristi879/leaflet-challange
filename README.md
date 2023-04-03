# leaflet-challange 


Before You Begin

Create a new repository for this project called leaflet-challenge. Do not add this Challenge to an existing repository.

Clone the new repository to your computer.

Inside your local git repository, create a directory for the Leaflet challenge. Use the folder names to correspond to the challenges: Leaflet-Part-1 and Leaflet-Part-2.

This Challenge uses both HTML and JavaScript, so be sure to add all the necessary files. These will be the main files to run for analysis.



Instructions

The instructions for this activity are broken into two parts:

Part 1: Create the Earthquake Visualisation

Part 2: Gather and Plot More Data (Optional with no extra points earning)


Dataset created by the United States Geological SurveyLinks to an external site.




 Overall,this API link for retrieving earthquake data. It also defines two functions markerSize and markerColor that are used to determine the size and color of the markers that represent the earthquakes on the map,code makes a GET request to the API using the d3.json function and passes the earthquake data to the createFeatures function.
The createFeatures function creates a geoJSON layer for the earthquake data and defines the behavior of each feature on the layer.
 createMap function creates the Leaflet map, adds base layers and overlay layers to it, and adds a legend to the map to show the magnitude scale of the earthquakes.


