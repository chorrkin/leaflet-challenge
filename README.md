# **Leaflet Earthquake Visualization Challenge**

This project applies **D3.js and Leaflet.js** to create an interactive map displaying earthquake data from the **United States Geological Survey (USGS)**. The dataset used is retrieved from:  

**[USGS Earthquake Data (Past 7 Days)](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson)**  

## **How It Works**
- The map is built using **Leaflet.js** and **OpenStreetMap** tiles.
- **D3.js** is used to fetch and process the earthquake data.
- Earthquakes are visualized as **circle markers**, where:
  - **Size** represents **magnitude** (larger circles for stronger earthquakes).
  - **Color** represents **depth** (deeper earthquakes have darker colors).
- Each marker includes a **popup** displaying the earthquake's **location, magnitude, and depth**.
- A **legend** is added to explain the depth-based color scale.

## **How to Use**
- Open `index.html` to view the map.
- The page includes a brief introduction and a link to access the interactive visualization.

**Note:** This project covers **only Part 1** (Earthquake Visualization). The optional Part 2 (Tectonic Plates Overlay) was **not implemented**. ChatGPT was used to format this ReadME properly.
