# Leaflet Challenge

![image](https://github.com/AnaTipps/leaflet-challenge/assets/131827518/42d5434f-624c-4d8f-b56d-cd7947b6f28c)


## Background
The United States Geological Survey, or USGS for short, is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment, and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes.

The USGS is interested in building a new set of tools that will allow them to visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. In this challenge, you have been tasked with developing a way to visualize USGS data that will allow them to better educate the public and other government organizations (and hopefully secure more funding) on issues facing our planet.

## Deployment
Link: https://github.com/AnaTipps/leaflet-challenge/

## Instructions
The instructions for this activity are broken into two parts:

* Part 1: Create the Earthquake Visualization

* Part 2: Gather and Plot More Data

## Part 1: Create the Earthquake Visualization

![image](https://github.com/AnaTipps/leaflet-challenge/assets/131827518/baa0b86c-5edd-4939-a5d2-ab0680aa3501)


Your first task is to visualize an earthquake dataset. Complete the following steps:

1. Get your dataset. To do so, follow these steps:

    * The USGS provides earthquake data in a number of different formats, updated every 5 minutes. Visit the https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php
 page and choose a dataset to visualize. The following image is an example screenshot of what appears when you visit this link:
   ![image](https://github.com/AnaTipps/leaflet-challenge/assets/131827518/d9a4091c-77b5-43b6-a65d-d5cf091e908f)

    * When you click a dataset (such as "All Earthquakes from the Past 7 Days"), you will be given a JSON representation of that data. Use the URL of this JSON to pull in the data for the visualization. The following image is a sampling of earthquake data in JSON format:
    ![image](https://github.com/AnaTipps/leaflet-challenge/assets/131827518/1b0a6cb9-4c2f-44be-b567-4e3c3029ceed)

  
2. Import and visualize the data by doing the following:

    * Using Leaflet, create a map that plots all the earthquakes from your dataset based on their longitude and latitude.

        * Your data markers should reflect the magnitude of the earthquake by their size and the depth of the earthquake by color. Earthquakes with higher magnitudes should appear larger, and earthquakes with greater depth should appear darker in color.

        * **Hint**: The depth of the earth can be found as the third coordinate for each earthquake.
        
    * Include popups that provide additional information about the earthquake when its associated marker is clicked.

    * Create a legend that will provide context for your map data.

    * Your visualization should look something like the preceding map.

## Part 2: Gather and Plot More Data
Plot a second dataset on your map to illustrate the relationship between tectonic plates and seismic activity. You will need to pull in this dataset and visualize it alongside your original data. Data on tectonic plates can be found at [https://github.com/fraxen/tectonicplates](https://github.com/fraxen/tectonicplates).

The following image is an example screenshot of what you should produce:

![image](https://github.com/AnaTipps/leaflet-challenge/assets/131827518/b0f57cf6-f38a-47ef-aa4a-f6797df7cdb4)



Perform the following tasks:

  * Plot the tectonic plates dataset on the map in addition to the earthquakes.

  * Add other base maps to choose from.

  * Put each dataset into separate overlays that can be turned on and off independently.

  * Add layer controls to your map.

## Getting Started

Prerequisites

Make sure you have installed all of the following prerequisites on your development machine:

Your favoriate code editor (e.g. VScode, etc.)
A compatible browser (e.g. Google Chrome, etc.)

Get a mapbox API key
 
    Add and save your API key inside of a config.js file inside of the Static\Leaflet-Part-1\js folder
 
    export const api_key = "your API key"

