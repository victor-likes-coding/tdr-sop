# TDR - Final Pass Walk Through Guide

## Table of Contents
1. [How to get the roads](#how-to-get-the-roads)
2. [How to export the roads](#how-to-export-the-roads)
3. [How to convert GeoJSON to KML](#how-to-convert-geojson-to-kml)
4. Import KML into MyMaps
5. Uploading photos
6. Adding pins
7. Coloring Standards
8. Extra -- for time crunched projects
9. Extra -- for projects that aren't under time constraints

----------------------------------------------------------------
### How to get the roads

The first thing you have to do is log into your gis portal. Please reach out to your OM or PM to get the credentials to log in if you're authorized to do so. You should see something like the image below. You should turn on the `City roads` Layer in the `Layers List`.

<img src="src/images/map.png" style="width: 250px" />
<br />

<br />

### How to export the roads

Once you see that image, follow the steps in the gif, and also provided is the step by step instructions to select and export the roads:
<br />
<br />
<img src="src/gifs/select roads.gif" style="width: 600px; height: 400px"/>

#### Instructions:
1. Select the `Layers List`
2. (Optional) click on the debris zone or project zone layer
3. Click on the icon furthest to the right on the screen, it reads `select` when you hover over it.
4. Drag over the roads you want to select 
    * Shift + mouse drag is to to select an area but add it to what you've already selected from
    * CMD (Mac) / Ctrl (Windows) + mouse drag is to select an area but to deselect what you've already selected
5. Once you are satisfied, look in the `Select` box and under the `Layers`, go down to where it shows `State`, `City`, or `Alleys` (in this example), and click the `...` and select `Export to GeoJSON`

**NOTE: Do not export anything with 1,000+ items as you will experience an issue with moving the lines over to mymaps -- instead lessen your selection. Once you've selected an area it the Select box will tell you how many items have been selected (even if the supplied gif does this anyways because we are showing you how to export these lines)**

<br />

### How to convert GeoJSON to KML 
<br />
<img src="src/gifs/convert-geojson-to-kml.gif" style="width:600px">

This part is really simple. Take that `.geojson` file that you've just downloaded and head over to [mygeodata](https://mygeodata.cloud/converter/geojson-to-kml). You should rename it to something meaningful, like `zone-#.kml` or so. 

**NOTE: There may be limit of how many times you can do this, so google other tools to convert GeoJSON to KML or use incognito mode**