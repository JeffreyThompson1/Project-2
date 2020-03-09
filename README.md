# Project-2 

ENGO 551 Winter 2020 Semester
Jeffrey Thompson 30021871


Webpage utilizes Leaflet to create a webmap (accessible at https://jeffreythompson1.github.io/Project-2/)

BaseMap is taken from OpenStreetMap.com

Building Permit Data is taken from data.calgary.ca

Date Range Picker code is taken from daterangepicker.com

OverlappingMarkerSpiderfier and MarkerCluster plugins are taken from the lab handout


-The map was initialized to be centered on downtown Calgary ([lat, lon] = [51.0444, -114.0706])

-After selecting a date range, the Calgary Building Permits API was queried by correlating the selecting dates to the issueddate datafield

-Markers were created for each selected building permit using the lat/long data fields with popups bound to them including all required information as layed out in the lab handout
