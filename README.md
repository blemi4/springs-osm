# springs-osm

# OpenStreetMap Data Case Study

## Map Area: Colorado Springs, CO, USA

Exploring and wrangling Open Street Map data for Colorado Springs

https://www.openstreetmap.org/relation/113141#map=11/38.8758/-104.7588

I chose Colorado Springs because Colorado is my favorite state to visit in both winter and summer.  I would like to live somewhere in the state at some point, so I am interested to see what the queries turn up.

## Problems encountered in the OSM data

I downloaded the XML file and ran it thru my cosprings.ipynb code.  I also converted the file to a database and ran queries.  The three main problems I found were:
-Iconsistent formatting of street types (ex. '1107 W 4th st', 'Rockhill road')
-Inconsistent formatting of postal codes (ex. '12345-1234', '12345', 'CO12345')
-Inconsistent formatting of phone numbers (ex. '+1-123-456-7890', '1234567890', '(123) 456-7890')
-Incomplete data points (ex. Not all nodes that mark businesses contain addresses)
-Incomplete data (ex. Only three nodes represented grocery stores.  This can't be correct in a city the size of Colorado Springs.)


### Street types
