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

This repository will investigate the impacts of urban expansion by analyzing a dataset that captures values for the Biodiversity Intactness Index (BII). The analysis finds changes in BII in the Phoenix county subdivision area between 2017 and 2020 to demonstrate on how urban growth affects biodiversity over time. The analysis is a result of the final project for course EDS 220, Working with Environmental Datasets, taught by Dr. Carmen Galaz Garcia and TA Annie Adams.

### Data

- The **Biodiversity Intactness Index (BII) Time Series** is a biodiversity indicator that measures changes in biodiversity using abudance data on plants, fungi, and animals. As a time series, the **BII** captures the effects of human interaction and resource use on species abundance over time. The **BII** collection, ID `io-biodiversity` can be accessed by signining into the **[Microsoft Planetary Computer (MPC)](https://planetarycomputer.microsoft.com/dataset/io-biodiversity)** using the `pystac-client` library to query the STAC API. The `planetary computer` signs items.

- The Phoenix, AZ subdivision area polygon is obtained from the U.S Census Bureau TIGER Shapefile of Arizona County Subdivisions, and is used to outline the area of interest in this analysis. The data can be accessed on the [Data.gov website](https://catalog.data.gov/dataset/tiger-line-shapefile-current-state-arizona-county-subdivision) and is tittled 'TIGER/Line Shapefile, Current, State of Arizona: County Subdivisions'.

### References 
Microsoft Planetary Computer. (n.d.). io-biodiversity [STAC collection]. Accessed December 4, 2025, from https://planetarycomputer.microsoft.com/dataset/io-biodiversity

U.S. Census Bureau. (2021). TIGER/Line Shapefile, Current, State of Arizona: County Subdivisions [Data set]. Data.gov. Accessed December 4, 2025, from https://catalog.data.gov/dataset/tiger-line-shapefile-current-state-arizona-county-subdivision
 
