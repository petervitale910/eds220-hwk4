
# Mapping Palisades and Eaton fires (January 2025)


##  About 
In this project we will be using true and false color imagery to examine the impacts of two fires which struck the Los Angeles area in early 2025. 

We will acomplish this by: 
- Extracting color bands from xarray
- Mapping using true and false color imagery
- Overlaying fire perimiters to see effect of fires

## Repository structure

eds220-hwk4
│--  README.md
│--  hwk4-task2-false-color-YOURLASTNAME.ipynb
|--  .gitignore

## Data
Datasets are publically available and can be found by following the reference section. 

#### Palisades and Eaton fire perimeters 
These contain dissolved fire perimeters/boundaries for Eaton and Palisades fires, with boundary polygons dissolved for each fire to create a single fire burn perimeter. Access given by the County of Los Angeles.

#### Netcdf landsat data
Landsat C2 L2 from Microsoft's Planetary Computer is a globally available, multi-decadal archive of atmospherically corrected, analysis-ready Landsat imagery. Surface reflectance for multispectral bands and derived land surface temperature from thermal bands are provided in cloud-optimized GeoTIFFs, accessible via a STAC API. Accordingly, it is primarily used for long-term environmental monitoring, spectral studies, and thermal remote sensing, and is designed for scalable, cloud-native remote sensing workflows.


“Data” section. Details regarding data access. Any necessary information on where data lives (e.g. is it housed in the repo, on a server, in a library / package etc.) and how to access it in order to run the code.
“References” section. In an appropriate, consistent format, including links, provide a reference to the course and any other sources that supported the development of the repository. Include formal references to the datasets. You can use the APA style to cite data sources as outlined here.

## References: 

### Data:
- Los Angeles GeoHub / NIFC FIRIS. (2025). Palisades-Eaton dissolved fire perimeters [data filel. Available: https://geohub/.lacity.org/maps/ad51845ea5fb4eb483bc2a7c38b2370c/about. [Accessed: Nov. 15, 2025]

- U.S. Geological Survey. Landsat Collection 2 Level-2 Surface Reflectance (Microsoft Planetary Computer version)  Idata file. Available: https://planetarycomputer.microsoft.com/dataset/landsat-c2-12. [Accessed: Nov. 15, 2025]


### Background information:
- NASA Earth Observatory. (2014, Mar. 4). Why is that forest red and that cloud blue? How to interpret a false-color satellite image. Available: https://earthobservatory.nasa.gov/features/FalseColor. [Accessed: Nov. 15, 2025]

- U.S. Geological Survey. (n.d.). What are the band designations for the Landsat satellites? Available: https://www.usgs.gov/faqs/ what-are-band-designations-landsat-satellites. [Accessed: Nov. 15, 2025]

- U.S. Geological Survey. (2021, Nov. 12). Common Landsat band combinations. Available: https://www.usgs.gov/media/images/ common-landsat-band-combinations. [Accessed: Nov. 15, 2025]