# Mapping Earthquakes

## Overview of Project

We are assisting Basil and Sadhana in creating interactive maps with easy to understand data visualizations on earthquakes around the world that have taken place in the span of a week.  The maps should show the differences between the magnitudes of the earthquakes.

## Resources

- style.css
- challenge_logic.js
- JavaScript (D3 and Leaflet libraries)
- Mapbox

## Functionality

The Earthquake Map has multiple interactive features to help visualize data, which can be accessed through the toolbox in the top right corner of the map.

#### Map Views

There are multiple types of map views supported:
- Street View
- Satellite View
- Dark View

#### Map Markers

For each instance of an earthquake recorded, there is a marker at the epicenter of the earthquake site.  When a marker is selected, the location of the earthquake and the magntiude are displayed.  The magnitude of the earthquake is represented by the diameter and color of each marker.  There is a legend in the bottom right corner of the map to provide information on which color represents each range of earthquake magnitudes.

#### Level Data

The map has different layers that can be selected to help visualize earthquakes and their proximities to tectonic plates.  The following levels of information can be seen on this map:

- All earthquakes
- Major earthquakes (with a focus on earthquakes with a magntiude greater than 4.5)
- Tectonic plates (divided by lines to represent each plate)
