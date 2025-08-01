# USFS Fire Ignition Data

This folder contains wildfire ignition point data sourced from the U.S. Forest Service’s Enterprise Data Warehouse (EDW). These datasets are used to analyze **geographic and temporal patterns of fire starts**, particularly in relation to **human-caused structure fires** and **potential links to Low-E window installations** in urban–wildland interface (WUI) zones.

---

## 📁 Dataset Contents
- Shapefiles or GeoJSON files from USFS Fire Occurrence Point layers
- Metadata (`.xml` or `.json` if available)
- Filtering documentation for identifying relevant incidents (e.g., `FIRE_CAUSE = Human`)

---

## 🔗 Source
All data in this folder originates from:
**U.S. Forest Service Geospatial Data Clearinghouse**  
🌐 [https://data.fs.usda.gov/geodata/edw/datasets.php](https://data.fs.usda.gov/geodata/edw/datasets.php)

To find ignition-related layers, search the page using the keyword:  
`ignition` or `fire occurrence`

---

## 🔍 Use in Project
These ignition datasets are used to:
- Map **fire start points** across western states
- Filter for **human-caused or structure-adjacent ignitions**
- Cross-reference with **urban density** and **climate rebate zones**
- Explore any spatial correlation with **increased Low-E window adoption**

---

## 📌 Notes
- Data may require filtering by date range, state, or ignition type
- Coordinate system: typically **WGS 84 (EPSG:4326)**—verify before loading into GIS tools
- When available, include fields like `FIRE_NAME`, `STATE`, `CAUSE_CLASS`, and `LATITUDE`/`LONGITUDE`

---

## 📅 Last Updated
Generated: August 1, 2025  
Latest dataset version should be verified on the [USFS EDW](https://data.fs.usda.gov/geodata/edw/datasets.php) site.
