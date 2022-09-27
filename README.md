# Mapping_Earthquakes

## Overview
The purpose of this project is to visually show the differences between the magnitudes of earthquakes all over the world for the last seven days, using Javascript APIs.

# Approach

Using JavaScript and the D3.js library to retrieve the coordinates and magnitudes of the earthquakes from the GeoJSON data. You'll use the Leaflet library to plot the data on a Mapbox map through an API request and create interactivity for the earthquake data.

## Objectives
- Create a branch from the main branch on GitHub.Add, commit, and push data to a GitHub branch.
- Merge a branch with the main branch on GitHubRetrieve data from a GeoJSON file.
- Make API requests to a server to host geographical maps.
- Populate geographical maps with GeoJSON data using JavaScript and the Data-Driven Documents (D3) library.
- Use Mapbox to create the geographical maps.
- Add multiple map layers to geographical maps using Leaflet control plugins to add user interface controls.Use JavaScript ES6 functions to add GeoJSON data, features, and interactivity to maps.
- Render maps on a hosted server.

## Results

Each earthquake is visually represented by a circle and color, where a higher magnitude will have a larger diameter and will be darker in color. Additionaly, each earthquake has a popup marker that, when clicked, shows the magnitude of the earthquake and the location of the earthquake. 

The map has three views:

- Street View
- Satellite View
- Dark Mode

The map can also toggle between three data layers:
- All earthquakes in a 7-day period
- Tectonic plates around the world 
- Earthquake magnitudes above 4.5

## Tasks

This project uses a URL for GeoJSON earthquake data from the USGS website and retrieves geographical coordinates and the magnitudes of earthquakes for the last seven days. Then, adds the data to a map.


[Live demo](https://devtrav.github.io/earthquake/)

![image](Earthquake_Challenge/demo.gif)