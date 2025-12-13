# Biodiversity Intactness Index Change in Phoenix, AZ (2017-2020)

### By Kaiju Morquecho

[Github Repository](https://github.com/kaimorquecho/eds220_biodiversity_phoenix_az.git)

### Repository Structure 
```
├── .gitignore
├── biodiversity_intactness_arizona.ipynb
├── README.md
└── data  
    │   tl_2020_04_countsub
        | tl_2020_04_countsub.shp
```

### About

This repository will investigate the impacts of urban expansion by analyzing a dataset that captures values for the Biodiversity Intactness Index (BII). The analysis finds changes in BII in the Phoenix county subdivision area between 2017 and 2020 to demonstrate how urban growth affects biodiversity over time. The analysis is a result of the final project for course EDS 220, Working with Environmental Datasets, taught by Dr. Carmen Galaz Garcia and Annie Adams.

<div style="text-align: center;">
  <img src="https://arizona-content.usedirect.com/storage1/gallery/3A31D7D859F14752BB8D987B1300EDBB/medium.jpg"
       alt="roadrunner"
       width="300">
  <p style="font-size: 0.9em; color: gray;">
    Roadrunner in Arizona. Source: Arizona Game & Fish Department.
  </p>
</div>

### Learning Highlights 
- Query BII rasters directly from Python via the Microsoft Planetary Computer STAC API and clip them to Phoenix boundaries
- Identify and visualize areas of high biodiversity intactness in Phoenix from 2017 to 2020
- Calculate and visualize areas of loss of high-quality habitat over time 

### Takeaways 
The BII analysis reveals pronounced spatial disparities in ecological condition across Phoenix:

- Lower BII values are concentrated in highly urbanized and developed areas, indicating reduced biodiversity intactness in regions experiencing greater human pressure.

- Areas with higher BII values tend to occur in less developed or peripheral zones, where habitat quality has been comparatively better preserved.

Together, these findings highlight the uneven distribution of biodiversity impacts within urban environments and underscore the value of spatially explicit indicators for informing conservation and restoration priorities.

### Data

- The **Biodiversity Intactness Index (BII) Time Series** is a biodiversity indicator that measures changes in biodiversity using abundance data on plants, fungi, and animals. As a time series, the **BII** captures the effects of human interaction and resource use on species abundance over time. The **BII** collection, ID `io-biodiversity`, can be accessed by signing into the **[Microsoft Planetary Computer (MPC)](https://planetarycomputer.microsoft.com/dataset/io-biodiversity)** using the `pystac-client` library to query the STAC API. The `planetary computer` signs items.

- The Phoenix, AZ subdivision area polygon is obtained from the U.S Census Bureau TIGER Shapefile of Arizona County Subdivisions, and is used to outline the area of interest in this analysis. The data can be accessed on the [Data.gov website](https://catalog.data.gov/dataset/tiger-line-shapefile-current-state-arizona-county-subdivision) and is titled 'TIGER/Line Shapefile, Current, State of Arizona: County Subdivisions'.

### Data Setup
To run the Phoenix Biodiversity Intactness Index analysis notebook, the data must be organized as follows. First, create a folder named 'data' in the same directory as this notebook. Next, download the required datasets as described in the **Data** section and place all downloaded files (TIGER Shapefiles) inside the data folder. Once the data are stored in this location, the notebook will be able to load the files using relative paths and run without modification.

### References 
Microsoft Planetary Computer. (n.d.). io-biodiversity [STAC collection]. Accessed December 4, 2025, from https://planetarycomputer.microsoft.com/dataset/io-biodiversity

U.S. Census Bureau. (2021). TIGER/Line Shapefile, Current, State of Arizona: County Subdivisions [Data set]. Data.gov. Accessed December 4, 2025, from https://catalog.data.gov/dataset/tiger-line-shapefile-current-state-arizona-county-subdivision

Galaz Garcia, C., & Adams, A. (2025). EDS 220: Working with environmental datasets [Course website]. University of California, Santa Barbara, Master of Environmental Data Science Program. https://meds-eds-220.github.io/MEDS-eds-220-course/
 
