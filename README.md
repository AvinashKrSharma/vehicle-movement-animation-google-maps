# Vehicle Live Movement using Google Maps APIs

This is a very very basic web-app that does the following:
* Take two locations as inputs.
* Find the latlong values of those locations using the Geolocation API.
* Find a route between those latlong pairs.
* Draw a polyline route connecting those two values.
* Create a marker and a small infoWindow for source, destination and moving marker(stores the information related to that marker i.e. location name etc).
* Update the marker every 100 milliseconds till it reaches the destination starting from the source.

##### Note: Other implementation details can be found in the code as comments.

