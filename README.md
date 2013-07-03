Using GitHub For Quick and Dirty Maps
===============

Intro
-----

So at one of the [TTC Info-Activism Camp 2013](https://camp2013.tacticaltech.org) skillshares, we tried to do an intro to publishing maps using Github. We thought it would be useful not necessarily for doing complex visualizations but just to get a quick visual overview of your data. For example, if you have a bunch of point data (like addresses) and you want to see if there are any important trends or clusters of locations close to each other, it's a lot easier to identify those patterns visually than by looking at a spreadsheet.

One flaw in this skillshare was realizing **most people who don't know much about visualizing data might not know much about Github**. And they definitely don't know much about the command line, so they're not going to understand the part about committing a repository to work from it--nor will they likely ever need to. (Or if they do, this is not the tutorial for helping them do that--[this GitHub tutorial](http://try.github.io/levels/1/challenges/1) probably is better for that!)

Rather than adding in steps introducing GitHub that might not be that important to someone who just wants to see their data on a map, I thought I'd make a repo with some examples that people could just [fork](https://help.github.com/articles/fork-a-repo). This creates a copy of the repository on GitHub in the user's account.

This is *not* a total solution for visualizing geodata. It's a good way to start scratching the surface of your data and learning how to use GitHub and open-source mapping libraries. The [GitHub Mapping Doucmentation](https://help.github.com/articles/mapping-geojson-files-on-github) is a great start, and the [LeafletJS documentation](http://leafletjs.com/examples/geojson.html) and [Mapbox Marker Styling](http://www.mapbox.com/developers/simplestyle/) also are helpful resources. 

Poke around this demo, fork it, go forth, make maps, and have fun! And if you want more tl;dr from me on mapping tools and options, read the ABOUT document. 

Instructions
------------

###1. Geocode Data

To put data points on a map, we need to geocode it (i.e. identify the exact lat/lon coordinates of the place we're looking at). If it's in a spreadsheet, this means we need 2 columns added to our data set: one for the latitute and one for the longitude. If you already have that data or you have shape or line data (like outlines of places or routes rather than points), skip this and go to the "Converting to GeoJSON" part of these instructions. 

I was originally going to write out all of these instructions again, but I realized it might be easier to send you to documentation that I used to learn how to do this. These are not the only methods, they're just the ones I know. 

+   [Mapbox's Geo for Google Docs plugin](http://www.mapbox.com/geo-for-google-docs/) | a plugin for Google Spreadsheets to geocode data. The only deprecated part of these instructions is you no longer have to install the plugin by copying the source code--you can just select 
+   [School of Data geocoding tutorial](http://schoolofdata.org/handbook/recipes/geocoding/) A different method--which I haven't actually tried--if you prefer. 
+   School of Data also has a nice [overview](http://schoolofdata.org/handbook/courses/geocoding/) on the concept of geocoding that is helpful if you want to get a more detailed overview of concepts. 

###2. Turn Data into GeoJSON file

In the [Mapbox tutorial](http://www.mapbox.com/geo-for-google-docs/) this already is covered. Once you have your geoJSON file, save it to your machine.

###3. Look at the example GeoJSON files

If you open the .geojson files in this repo, they'll initially render as maps. But if you go to view the code, you can see some comments I've added on styling conventions in use and just get a better understanding of GeoJSON syntax. 
 
