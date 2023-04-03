# leaflet-challange



This code creates a map that displays earthquake data from a GeoJSON API link using Leaflet.js. It defines functions to set the size and color of markers based on the magnitude of the earthquake. It then makes a GET request to the API link to retrieve the earthquake data and passes it to the createFeatures function. The createFeatures function then creates a Leaflet layer with circles for each earthquake and adds a popup with the place and magnitude information for each earthquake. The createMap function then defines the base and overlay layers, creates the map object, and adds the layers and a control to toggle them. Finally, the code defines a legend control to show the magnitude ranges and corresponding colors.
