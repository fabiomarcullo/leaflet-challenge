# Background
The United States Geological Survey, or USGS for short, is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment, and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes.

The USGS is interested in building a new set of tools that will allow them to visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. In this challenge, you have been tasked with developing a way to visualize USGS data that will allow them to better educate the public and other government organizations (and hopefully secure more funding) on issues facing our planet.

## Deployment Link
![USGS Earthquakes Data Map](https://Fabio)

## Part 1: Create the Earthquake Visualization
### Get the Data Set
- The USGS provides earthquake data in a number of different formats, updated every 5 minutes
- The "All Earthquakes from the Past 7 Days" data set was selected from the [USGS GeoJSON Feed](https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) page
- The data was given in JSON format which was used to pull in the data for the visualization
### Import and Visualize the Data
Create a map using Leaflet that plots all of the earthquakes from the data set based on their longitude and latitude.
- The data markers reflect the magnitude of the earthquake by their size and and depth of the earth quake by color
- Earthquakes with higher magnitudes appear larger and earthquakes with greater depth should appear darker in color
- Popups that provide additional information about the earthquake were included when a marker is clicked
- A legend was created to provide context for the map data
<p align="center">
  <img src="Image">
</p>

## Level-2: More Data
Plot a second data set on the map above to illustrate the relationship between tectonic plates and seismic activity.
- Pull in [Tectonic Plates](https://github.com/fraxen/tectonicplates) data set
- Visualize it along side the original set of data
- Add a number of base maps (Satellite Map, Grayscale Map, Outdoors Map and Dark Map) to choose from
- Separate out the two different data sets (earthquakes and tectonic plates) into overlays that can be turned on and off independently
- Add layer controls to the map
<p align="center">
  <img src="Image">
</p>

---

