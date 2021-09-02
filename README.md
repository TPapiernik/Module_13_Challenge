# Module 13 Challenge - Mapping Earthquakes - JavaScript, D3.js, Leaflet.js

## Overview

Project Origination Date: 2021-09-02

### Purpose

The purpose of this project is to visually show the differences between the
magnitudes of earthquakes all over the world for the last seven days.

It builds on previous work to add Linestring Overlays representing
the boundaries of the Tectonic Plates covering the Earth.

### Tasks

1. Use a URL for GeoJSON earthquake data from the USGS website and retrieve
geographical coordinates and the magnitudes of earthquakes for the last seven days.
2. Retrieve Tectonic Plate Boundaries in GeoJSON Format
3. Add the data to a map

### Approach

- Use base JavaScript and the D3.js library to retrieve the coordinates and
magnitudes of the earthquakes from the GeoJSON data.
- Use the Leaflet library to plot the data on a Mapbox map through an API
request and create interactivity for the earthquake data.

### Deliverables

1. Add Tectonic Plate Data
2. Add Major Earthquake Data
3. Add an Additional Map

*(Must have JavaScript Enabled)*

### Resources

- Software:
	- D3.js JavaScript Library loaded from Cloud via HTML
	- Leaflet.js JavaScript Library loaded from Cloud via HTML
- Data:
	- USGS GeoJSON Summary Feed, All Earthquakes of the Past 7 Days
		- Imported directly via d3.json JavaScript
		- URL: https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson
		- Explanation of Metadata: https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php
	- `PB2002_boundaries.json`
		- Origin: *An Updated Digital Model of Plate Boundaries* by Peter Bird (Geochemistry Geophysics Geosystems, 4(3), 1027, [doi:10.1029/2001GC000252](http://scholar.google.se/scholar?cluster=1268723667321132798), 2003)
		- Converted to ArcGIS Shapefiles by Hugo Ahlenius of Nordpil (http://nordpil.com/) then to GeoJSON by [csterling](https://github.com/csterling)
		- GitHub Repository: https://github.com/fraxen/tectonicplates
		- URL: https://github.com/fraxen/tectonicplates/blob/master/GeoJSON/PB2002_boundaries.json

## Deliverables

### Deliverable 1



### Deliverable 2



### Deliverable 3



-- END --
