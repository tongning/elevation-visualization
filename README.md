## elevation-visualization
Generates a line plot of elevation along a path using d3.js

####Usage
Input is read in geojson format from file elevation.geojson. The geojson file must contain a LineString representing the path you want to
generate an elevation graph for. The geojson file should also contain the elevation of each point on the path, stored as an array
in a `properties` field called `elevation`. See the elevation.geojson file included in this repository for an example of a valid geojson file.
