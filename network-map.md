# Mobile Network Coverage Analysis

This interactive dashboard visualizes the expansion of mobile network generations (2G, 3G, and 4G) globally and provides high-resolution cluster-level data for 3G coverage.

## Interactive Dashboard

Use the tabs in the dashboard below to switch between the **Global Country Map** and the **3G Cluster Coverage** details. You can filter by year, technology, and buffer distance.

<div style="text-align: center;">
  <iframe 
    src="https://jmqduq-yujuan-gao.shinyapps.io/3G_Map_APP/" 
    style="border: 3px solid #18bc9c; width: 100%; height: 900px; border-radius: 10px;" 
    allowfullscreen>
  </iframe>
</div>

---

## About the Data
* **Global Country Map:** Displays national average coverage proportions. Data is merged with geographical boundaries using ISO-3 country codes.
* **3G Cluster Coverage:** Visualizes DHS survey cluster points. The color intensity represents the proportion of 3G coverage within specific buffer distances (ranging from 0.5km to 100km).

## Technical Implementation
The dashboard is built using:
* **R Shiny** for the web framework.
* **Leaflet** for interactive mapping.
* **bslib** for the professional "Flatly" Bootstrap 5 theme.
* **rnaturalearth** for spatial boundary data.

[Visit the full application here](https://jmqduq-yujuan-gao.shinyapps.io/3G_Map_APP/)
