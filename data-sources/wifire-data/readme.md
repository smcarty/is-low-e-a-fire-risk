# WIFIRE Ignition Cause Dataset (1992–2020)

This folder contains point data from the **CLM Ignition Cause dataset**, hosted by the WIFIRE Lab at the San Diego Supercomputer Center (SDSC). The dataset includes detailed ignition points for wildfires occurring between **1992 and 2020**, with ignition cause categories, spatial coordinates, and additional metadata.

---

## 📁 Dataset Contents
- Downloaded CSV or GeoJSON files with ignition point data
- Ignition cause types (e.g., `Lightning`, `Human`, `Undetermined`)
- Temporal and spatial data (latitude, longitude, date, time, etc.)

---

## 🔗 Source
**WIFIRE Lab – San Diego Supercomputer Center**  
🔗 [https://wifire-data.sdsc.edu/dataset/clm-ignition-cause-1992-2020-original-point-data](https://wifire-data.sdsc.edu/dataset/clm-ignition-cause-1992-2020-original-point-data)

---

## 🔍 Use in Project
This dataset supports:
- Mapping ignition origins across western U.S. states
- Filtering by **human-caused ignition points**
- Analyzing **ignition frequency over time** in WUI (wildland–urban interface) areas
- Comparing fire clusters to regions with high adoption of Low-E windows or rebate incentives

---

## 🗂️ Suggested Folder Structure

```
data-sources/
└── wifire-ignition-cause/
    ├── readme.md
    ├── clm-ignition-cause-1992-2020.csv
    ├── filtering-notes.md
    └── metadata.yaml
```

---

## 📅 Last Verified
Accessed: August 1, 2025  
Original data maintained by the WIFIRE Lab at SDSC.
