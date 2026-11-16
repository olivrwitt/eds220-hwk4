# Assignment 4 - Visualizing fire scars through false color

### Authors
Code and analysis written by Oliver Witt, for an assignment written by Carmen Galaz García for the course EDS220 Environmental Data, part of the UCSB Bren School MEDS Curriculum. 


### About
This repository contains code, data, and analysis for Assignment 4 for EDS220 Environmental Data, a course for the UCSB Bren School MEDS Curriculum. 

The aim of this workflow is to create false color imagery to visualize fire scars left by the 2025 Eaton Fire and Palisades Fire in Los Angeles, CA.

### Repository Structure
The repository structure is shown below:
```{bash}
├── README.md
├── data
│   ├── Eaton_Perimeter_20250121
│   │   ├── Eaton_Perimeter_20250121.cpg
│   │   ├── Eaton_Perimeter_20250121.dbf
│   │   ├── Eaton_Perimeter_20250121.prj
│   │   ├── Eaton_Perimeter_20250121.shp
│   │   ├── Eaton_Perimeter_20250121.shx
│   │   └── Eaton_Perimeter_20250121.xml
│   ├── Palisades_Perimieter_20250121
│   │   ├── Palisades_Perimieter_20250121.cpg
│   │   ├── Palisades_Perimieter_20250121.dbf
│   │   ├── Palisades_Perimieter_20250121.prj
│   │   ├── Palisades_Perimieter_20250121.shp
│   │   ├── Palisades_Perimieter_20250121.shx
│   │   └── Palisades_Perimieter_20250121.xml
│   └── landsat8-2025-02-23-palisades-eaton.nc
└── hwk4-task2-false-color-WITT.ipynb
```

Data is stored in the "data" folder.
The `landsat8-2025-02-23-palisades-eaton.nc` data set is a simplified collection of bands (red, green, blue, near-infrared and shortwave infrared) from the Landsat Collection 2 Level-2 atmospherically corrected surface reflectance data, collected by the Landsat 8 satellite.
The Eaton and Palisades shapefiles contain the perimeters of their respective fire areas.

All code and analysis is contained in `hwk4-task2-false-color-WITT.ipynb`.

### Data
Eaton and Palisades fire perimeter datasets were downloaded from the County of Los Angeles Enterprise GIS official website (https://egis-lacounty.hub.arcgis.com).  

The original data came from CAL FIRE's Historical Fire Perimeter Dataset (https://services1.arcgis.com/jUJYIo9tSA7EHvfZ/arcgis/rest/services/California_Historic_Fire_Perimeters/FeatureServer). 

### References
Eaton and Palisades fire perimeter data sourced from:
“Palisades and Eaton Dissolved Fire Perimeters (2025).” County Of Los Angeles Enterprise GIS, January 21, 2025. https://egis-lacounty.hub.arcgis.com/maps/ad51845ea5fb4eb483bc2a7c38b2370c/about. 

The Landsat satellite band data is sourced from the Microsoft Planetary Computer data catalog:
“Microsoft Planetary Computer.” Landsat Collection 2 Level-2. Accessed November 16, 2026. https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2. 

Citations include: