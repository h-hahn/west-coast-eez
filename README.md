# Aquaculture in West Coast Exclusive Economic Zones
## Overview

This repository contains an analysis to understand the amount of suitable aquaculture area in West Coast Exclusive Economic Zones (EEZ). Using sea surface temperature data, depth data, and EEZ data, I use oyster conditions to find the amount of suitable oyster growing locations in each EEZ. This is then used to create maps demonstrating the total area of suitable locations as well as the percent of area in each EEZ. After establishing this workflow, I used it to create a function in which any species conditions could be inputted, and the appropriate maps would be created.

This analysis will assist in understanding which West Coast Exclusive Economic Zones are suitable for marine aquaculture of different species. This has large implications in supporting sustainable global food supply.

## About the Data
**Sea Surface Temperature**
* Average annual sea surface temperature (SST) from the years 2008 to 2012. The data was originally generated from [NOAA's 5km Daily Global Satellite Sea Surface Temperature Anomaly v3.1](https://coralreefwatch.noaa.gov/product/5km/index_5km_ssta.php).

**Bathymetry**
* Data on the depth of the ocean [General Bathymetric Chart of the Oceans (GEBCO)](https://www.gebco.net/data_and_products/gridded_bathymetry_data/#area).[^3]

[^3]: GEBCO Compilation Group (2022) GEBCO_2022 Grid (<doi:10.5285/e0f0bb80-ab44-2739-e053-6c86abc0289c>).

**Exclusive Economic Zones**
* Designate maritime boundaries using Exclusive Economic Zones off of the west coast of US from [Marineregions.org](https://www.marineregions.org/eez.php).

The data was too large to push to this repository, so download the data [here](https://drive.google.com/file/d/1u-iwnPDbe6ZK7wSFVMI-PpCKaRQ3RVmg/view?usp=sharing) and save it locally. 

## Structure 
The structure of the repo is as follows:
> ```
> west-coast-eez
> │   README.md
> │   west-coast-eez.Rproj
> │  .gitignore
> └───documents
>    │   west-coast-eez.html
>    │   west-coast-eez.Rmd
> ```

The full analysis is contained in the documents folder in the .Rmd file.
