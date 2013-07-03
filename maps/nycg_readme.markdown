From Shapefile to GeoJSON
=========================

This is New York Congressional District data. I downloaded it as a shapefile from the [NYC Planning Office website](www.nyc.gov/html/dcp/html/bytes/applbyte.shtml#zdata). Then I converted it to a geoJSON using this [free online converter](http://converter.mygeodata.eu/). There are lots of other options for doing this step, that's just the one I happened to use. 


This is taking hella long to load. 
---------------------------------=

Polygons are a lot more complicated as data objects than single points. A point just has two coordinates you need to know: the latitute and the longitude. A polygon has lots and lots of points that are linked together to make one single shape. More points, more data, bigger file. 

Boo, I can't edit this one!
---------------------------

Yeah, I don't know what the deal is there. Sorry. Ask GitHub about it. I really just included this to show you what was actually possible and explain how polygons work. 
