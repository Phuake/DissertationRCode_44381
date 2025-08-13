## GY485 Dissertation – Migration and Crime in the West Midlands: A Spatial Analysis of Domestic, International, and Student Migration Effects ##
This repository contains the R code and datasets used for the empirical analysis in the GY485 dissertation.

### Repository Contents ###
**Code**

DissertationRCode_44381.Rmd – Complete R Markdown workflow for the dissertation’s empirical analysis.

**Datasets**

2021CensusDataandPopulationEstimates.zip – UK 2021 Census variables and population estimates at the LSOA level.

CrimeData_2021-2022.zip – Recorded crime data (2021.5–2022.4) by LSOA.

CrimeData_2022-2023.zip – Recorded crime data (2022.5–2023.4) by LSOA.

CrimeData_2023-2024.zip – Recorded crime data (2023.5–2024.4) by LSOA.

CrimeData_2024-2025.zip – Recorded crime data (2024.5–2025.4) by LSOA.

England_lsoa_2021_bgc.zip – Boundary shapefile for England’s Lower Layer Super Output Areas (2021).

England_utla_2022_bgc.zip – Boundary shapefile for England’s Upper Tier Local Authorities (2022).

ForceBoundaries.zip – UK police force area boundary shapefile.

### Analysis Workflow ###

The R code provided performs the complete workflow for the GY485 Dissertation’s empirical analysis. It includes:

**1. Data Import and Preprocessing** – Reading crime, demographic, and socioeconomic datasets; cleaning and merging data; projecting spatial layers.

**2. Exploratory Spatial Analysis** – Generating thematic maps for crime rates, immigration, deprivation, and unemployment.

**3. Statistical Regression Analysis** – Conducting Moran’s I and Lagrange Multiplier tests, OLS and fixed-effects panel regressions and SAR models.

**4. Visualisation** – Producing maps and charts used in the dissertation's main body of text.
