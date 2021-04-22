# Leaflet Homework - Visualizing Data with Leaflet

## Background

![1-Logo](Images/1-Logo.png)

This challenge is based off of data from United States Geological Survey which is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment, and the impacts of climate and land-use change.

In this challenge I visualized their earthquake data using html,Javascript, and Leaflet.


## The Task

### Level 1: Earthquakes Basic Visualization

I used [USGS GeoJSON Feed](http://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) to get the data, and I visualized all Earthquakes from the Past 7 Days. 
 
   * The map is created by using Leaflet that plots all of the earthquakes from the data set based on their longitude and latitude. 
   * A data markers also used to reflect the magnitude of the earthquake in their size and color. Earthquakes with higher magnitudes should appear larger the the color spectrum started from green to red, wich means when magnitude increases the color gose from green to red.
     * A popups included to provide additional information about the earthquake when a marker is clicked
     * legend added to provide context of the map data.
 
 #### Basic Map

![1](https://user-images.githubusercontent.com/74028387/115660246-c0d2b680-a309-11eb-9704-4df68e752316.png)


### Level 2: Earthquakes Advanced Visualization

In this task I added a second data(layer) set on the map to illustrate the relationship between tectonic plates and seismic activity. Data on tectonic plates can be found at <https://github.com/fraxen/tectonicplates>. 

In this task:
* I ploted a second data set on the map.

* Added a number of base maps to choose from as well as separate out our two different data sets into overlays that can be turned on and off independently.

* Add  a layer controls to the map.

#### Map with Layer Controls

![2](https://user-images.githubusercontent.com/74028387/115660283-c7612e00-a309-11eb-89dd-ed08cbe2b568.png)



### The Final View Looks as Follows :


![Final View](https://user-images.githubusercontent.com/74028387/115660557-2b83f200-a30a-11eb-9edc-be0da836bbdb.gif)



