
To merge files,

ogr2ogr -f ‘ESRI Shapefile’ merge.shp filename1.shp
Then merge the following files by using:

ogr2ogr -f ‘ESRI Shapefile’ -update -append merge.shp filename2.shp -nln merge
ogr2ogr -f ‘ESRI Shapefile’ -update -append merge.shp filename3.shp -nln merge
etc


some tools for map visualizations

#Google maps tools
=====================

## Tool
an online tool for customizing options
http://gmaps-samples-v3.googlecode.com/svn/trunk/styledmaps/wizard/index.html

## Samples
Snazzy Maps:
provide lots of samples for google maps style
https://snazzymaps.com/
Five Great Styled Maps Examples
http://googlegeodevelopers.blogspot.ae/2010/10/five-great-styled-maps-examples.html

````
