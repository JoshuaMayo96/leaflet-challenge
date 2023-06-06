Module 5: leaflet-challenge

![1-Logo](https://github.com/JoshuaMayo96/leaflet-challenge/assets/125078377/d5b7d6c6-0707-4408-be6f-3d3d20ed22a2)

Background:
 - The United States Geological Survey, or USGS for short, is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment, and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes.

 - The USGS is interested in building a new set of tools that will allow them to visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. In this challenge, you have been tasked with developing a way to visualize USGS data that will allow them to better educate the public and other government organizations (and hopefully secure more funding) on issues facing our planet.



Part 1: Create the Earthquake Visualization

![2-BasicMap](https://github.com/JoshuaMayo96/leaflet-challenge/assets/125078377/40102d7f-01cf-45c9-8a10-392793b039d1)

- Your first task is to visualize an earthquake dataset. Complete the following steps:

    1. Get your dataset. To do so, follow these steps:
        - The USGS provides earthquake data in a number of different formats, updated every 5 minutes. Visit the USGS GeoJSON Feed page and choose a dataset to visualize. The following image is an example screenshot of what appears when you visit this link:

        ![3-Data](https://github.com/JoshuaMayo96/leaflet-challenge/assets/125078377/cb2fb648-9fa9-45ba-8497-58ebedc6f123)

        - When you click a dataset (such as "All Earthquakes from the Past 7 Days"), you will be given a JSON representation of that data. Use the URL of this JSON to pull in the data for the visualization. The following image is a sampling of earthquake data in JSON format:

        ![4-JSON](https://github.com/JoshuaMayo96/leaflet-challenge/assets/125078377/b7fa7e0a-c449-40eb-8438-894851dcc86b)

    2. Import and visualize the data by doing the following:

        - Using Leaflet, create a map that plots all the earthquakes from your dataset based on their longitude and latitude.

            - Your data markers should reflect the magnitude of the earthquake by their size and the depth of the earthquake by color. Earthquakes with higher magnitudes should appear larger, and earthquakes with greater depth should appear darker in color.

            - Hint: The depth of the earth can be found as the third coordinate for each earthquake.

        - Include popups that provide additional information about the earthquake when its associated marker is clicked.

        - Create a legend that will provide context for your map data.

        - Your visualization should look something like the preceding map.
