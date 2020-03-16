# Project-2 

ENGO 551 Winter 2020
Jeffrey Thompson 30021871


Webpage utilizes Leaflet to create a webmap (accessible at https://jeffreythompson1.github.io/Project-2/index)

BaseMap is taken from OpenStreetMap.com

Building Permit Data is taken from data.calgary.ca

Date Range Picker code is taken from daterangepicker.com

OverlappingMarkerSpiderfier and MarkerCluster plugins are taken from the lab handout


-The map was initialized to be centered on downtown Calgary ([lat, lon] = [51.0444, -114.0706])

-After selecting a date range, the Calgary Building Permits API was queried by correlating the selected dates to the issueddate datafield

-Markers were created for each selected building permit using the lat/long data fields with popups bound to them including all required information as layed out in the lab handout

# Project-3

MapBox Style created, published, and added to webpage.

A button was added on the right of the page with an onClick() property that calls the function showTraffic().

showTraffic() is defined at the end of the page, it either adds or removes the TrafficIncidents Layer to the map accordingly and modifies the text in the button to reflect what the button will do if clicked again.


StyleLayer Properties:

- Circle: Radius ranging from 2px at Zoom11 to 12px at Zoom18. This changes the size of the circles to better match the size of the roads.

- Colour: A medium/dark orange colour was selected with approximately 33% opacity. This was to reflect the nature of traffic incidents (traditionally warm colours on maps) as well as allowing the underlying map to be seen through the circles
