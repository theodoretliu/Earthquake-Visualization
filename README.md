# Earthquake Visualization

**Earthquake Visualization** uses the WebGL Globe to display location and magnitude data of earthquakes that have occurred in the past year. Magnitudes are normalized by the largest earthquake to occur in the past year. Magnitudes are given in terms of absolute energy released instead of the moment magnitude scale in order to emphasize the size of large earthquakes. The thousands of small earthquakes that occur in a year help outline the fault lines of tectonic plates. 

The visualization updates on each reload of the webpage. Instead of relying on a static data set, the website uses an API provided by USGS Earthquakes to get GeoJSON data about earthquakes. The program then cleans up the data and then displays it on the globe.