# Visualizing fire scars through false color
## EDS 220 Homework 4 Task 2

## About
This repository contains materials for the fourth assignment for the course [EDS 220 - Working with Environmental Datasets](https://meds-eds-220.github.io/MEDS-eds-220-course/). This course is part of the [UCSB Masters in Environmental Data Science](https://bren.ucsb.edu/masters-programs/master-environmental-data-science). Per instructions, this repo visualizes fire scars from the January 2025 Eaton and Palisades Fires through false color satellite imagery. It contains the necessary script to clean the data and perform the analysis.

## Repository Structure
eds220-hwk4
     └── README.md 
     └── hwk4-task2-false-color-Busby.ipynb            # Contains all script for the analysis
     └── .gitignore 
        └── data                                       # Contains all data used in the analysis
           └── Palisades_Perimieter_20250121           # Contains Palisades perimeter shapefile
           └── Eaton_Perimieter_20250121               # Contains Eaton perimeter shapefile
           └── landsat8-2025-02-23-palisades-eaton.nc  # Contains NetCDF satellite data for area of interest

## Data
The analysis within this repository utilizes two datasets. The first is the shapefiles of the perimeters of both Eaton and Palisades fires. The data were originally pulled from CAL FIRE's Historical Fire Perimeter Dataset. The data were downloaded as two files from the [County of Los Angeles Open Data site](https://egis-lacounty.hub.arcgis.com/maps/ad51845ea5fb4eb483bc2a7c38b2370c/about). The second dataset includes landsat 8 satellite imagery of the area around the fire perimeters from 02/23/2025. The data were originally retrieved from the [Microsoft Planetary Computer data catalog](https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2) and clipped for the purposes of this assignment by the course instructor.

## References
- Galaz García, C. (n.d.). EDS 220 - working with environmental datasets. Github.Io. Retrieved November 20, 2026, from https://meds-eds-220.github.io/MEDS-eds-220-course/
- NASA Earth Observatory. (2014, March 14). Why is that Forest Red and that cloud blue? How to interpret a false-color satellite image. NASA Science. https://science.nasa.gov/earth/earth-observatory/how-to-interpret-a-false-color-satellite-image
- Landsat Missions. (2021, November 12). Common landsat band combinations. USGS. https://www.usgs.gov/media/images/common-landsat-band-combinations
- USGS. (2024, May 31). What are the band designations for the landsat satellites? | U.S. geological survey. Www.Usgs.Gov. https://www.usgs.gov/faqs/what-are-band-designations-landsat-satellites

### Data References
- CAL FIRE. (2025). _Palisades and Eaton Dissolved Fire Perimeters (2025)_ \[dataset]. County of Los Angeles Open Data. https://egis-lacounty.hub.arcgis.com/maps/ad51845ea5fb4eb483bc2a7c38b2370c/about  
- Earth Resources Observation and Science (EROS) Center. (2020). Landsat 8-9 Operational Land Imager / Thermal Infrared Sensor Level-2, Collection 2 \[dataset]. U.S. Geological Survey. https://doi.org/10.5066/P9OGBGM6