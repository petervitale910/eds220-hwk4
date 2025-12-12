
# Mapping Palisades and Eaton fires (January 2025)


##  About 
In this project we will be using true and false color imagery to examine the impacts of two fires which struck the Los Angeles area in early 2025. 

We will acomplish this by: 
- Extracting color bands from `xarray`
- Mapping using true and false color imagery
- Overlaying fire perimiters to see effect of fires
- Mapping Environmental Justice Index values within the fire perimeter
## Repository structure

eds220-hwk4
│--  README.md
│--  hwk4-task2-false-color-vitale.ipynb
│--  blog_post.ipynb
│--  palisades_eaton_eji.ipynb 
|--  .gitignore

## Data
Datasets are publically available and can be found by following the reference section. 

#### Palisades and Eaton fire perimeters 
These contain dissolved fire perimeters/boundaries for Eaton and Palisades fires, with boundary polygons dissolved for each fire to create a single fire burn perimeter. Access given by the County of Los Angeles.

#### Palisades and Eaton fire perimeters 
These contain dissolved fire perimeters/boundaries for Eaton and Palisades fires, with boundary polygons dissolved for each fire to create a single fire burn perimeter. Access given by the County of Los Angeles.

#### Netcdf Landsat data
Landsat C2 L2 from Microsoft's Planetary Computer is a globally available, multi-decadal archive of atmospherically corrected, analysis-ready Landsat imagery. Surface reflectance for multispectral bands and derived land surface temperature from thermal bands are provided in cloud-optimized GeoTIFFs, accessible via a STAC API. Accordingly, it is primarily used for long-term environmental monitoring, spectral studies, and thermal remote sensing, and is designed for scalable, cloud-native remote sensing workflows.

#### Environmental Justice Index (EJI) 
The Environmental Justice Index (EJI) measures cumulative environmental, health, and social burdens to identify communities facing the highest environmental injustices. It combines indicators like pollution exposure, health vulnerabilities, and socioeconomic stressors into a single score for each census tract. Higher EJI values indicate greater cumulative impacts and greater need for targeted intervention and resources.


## References: 

### Data:
- Los Angeles GeoHub / NIFC FIRIS. (2025). Palisades-Eaton dissolved fire perimeters [data filel. Available: https://geohub.lacity.org/datasets/lacounty::palisades-and-eaton-dissolved-fire-perimeters-2025. [Accessed: Nov. 15, 2025]

- U.S. Geological Survey. Landsat Collection 2 Level-2 Surface Reflectance (Microsoft Planetary Computer version)  Idata file. Available: https://planetarycomputer.microsoft.com/dataset/landsat-c2-12. [Accessed: Nov. 15, 2025]

- Centers for Disease Control and Prevention (CDC). (2024). Environmental Justice Index (EJI) data for California [data file]. Available: https://www.cdc.gov/eji. [Accessed: Dec. 11, 2025]


### Background information:
- NASA Earth Observatory. (2014, Mar. 4). Why is that forest red and that cloud blue? How to interpret a false-color satellite image. Available: https://earthobservatory.nasa.gov/features/FalseColor. [Accessed: Nov. 15, 2025]

- U.S. Geological Survey. (n.d.). What are the band designations for the Landsat satellites? Available: https://www.usgs.gov/faqs/ what-are-band-designations-landsat-satellites. [Accessed: Nov. 15, 2025]

- U.S. Geological Survey. (2021, Nov. 12). Common Landsat band combinations. Available: https://www.usgs.gov/media/images/ common-landsat-band-combinations. [Accessed: Nov. 15, 2025]