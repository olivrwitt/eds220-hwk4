# Assignment 4 - Visualizing fire scars through false color

### Authors
Code and analysis written by Oliver Witt, for an assignment written by Carmen Galaz García for the course EDS220 - Environmental Data, part of the UCSB Bren School MEDS Curriculum. 


### About
This repository contains code, data, and analysis for Assignment 4 for EDS220 Environmental Data, a course for the UCSB Bren School MEDS Curriculum. 

The aim of this workflow is to create false color imagery to visualize fire scars left by the 2025 Eaton Fire and Palisades Fire in Los Angeles, CA.

### Repository Structure
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

### Data
Eaton and Palisades fire perimeter datasets were downloaded from the County of Los Angeles Enterprise GIS official website (https://egis-lacounty.hub.arcgis.com).  

The original data came from CAL FIRE's Historical Fire Perimeter Dataset (https://services1.arcgis.com/jUJYIo9tSA7EHvfZ/arcgis/rest/services/California_Historic_Fire_Perimeters/FeatureServer). 

### References