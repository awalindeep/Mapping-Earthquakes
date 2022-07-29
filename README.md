
# Mapping_Earthquakes

_An interactive earthquake map with JavaScript and Leaflet_

_**Note:**_  Final documents are stored in  [Earthquake_Challenge](https://github.com/awalindeep/Mapping-Earthquakes/tree/AwalinGHMAIN/Earthquake_challenge)  directory. Please find the explanation of the files below. Code needs an API Key from Mapbox in order to run. The API key is not included for safety reasons. Other files (i.e. Earthquakes_past7days, Simple_Map and json files) are included because of the detailed procedure of working with Mapbox, Leaflet and GitHub branching.

## Project Overview

Visually show the differences between the magnitudes of earthquakes all over the world for the last seven days.

#### Tasks

To complete this project, use a URL for GeoJSON earthquake data from the USGS website and retrieve geographical coordinates and the magnitudes of earthquakes for the last seven days. Then add the data to a map.

#### Approach

Your approach will be to use the JavaScript and the D3.js library to retrieve the coordinates and magnitudes of the earthquakes from the GeoJSON data. You'll use the Leaflet library to plot the data on a Mapbox map through an API request and create interactivity for the earthquake data.

Now that you have an overview of the project plan, let's set up a Mapbox account and get the API token you'll need to create geographical maps.## Purpose

## Purpose

For this project I am creating an  **interactive map**  that shows the latest  **earthquake activity around the world**. Maps allow us to explore, understand and make decisions about our world. Providing data-driven storytelling on disasters around the world and building insightful data visualization with interactive features is a valuable addition to the knowledge and awareness of planet Earth.

**The map of earthquakes around the world contains:**

-   Switch on/off button for  **fault lines**  of tectonic plates.
-   Switch on/off button for  **earthquakes of the past 7 days**.
-   Switch on/off button for  **major earthquakes of magnitude above 4.5**.
-   Three different  **map styles**:
    -   Street view.
    -   Satellite view.
    -   Dark view.
-   **A popup marker**  with information about the location and magnitude of the earthquake.
-   **The diameter**  and  **the color**  of a marker reflect the strength of the earthquake (darker color with larger diameter represent earthquakes with a higher magnitude).
-   **A legend**  with the context for the map.

![Map](https://github.com/awalindeep/Mapping-Earthquakes/blob/AwalinGHMAIN/MAP.gif)

An interactive world map of earthquakes

## Background

Creating interactive maps is supported by specifically developed tools. For this project I used the following:

-   **Mapbox API**, an open source mapping platform for custom designed maps.
    
-   **Leaflet**, a JavaScript library, designed to build the web mapping applications.
    
-   **GeoJson**  files that are specifically design to host geographical information. GeoJson files are the industry standard for representing simple geographical features, such as points, line strings and polygons and non-spatial attributes, such as magnitude of the earthquake, hurricane strength, hail size, elevation, etc.
