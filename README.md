# NYSERDA-MW-Block
LST-NDVI Correlation Coefficient on NYSERDA MW Block

---

## Description
Visualizes the Land Surface Temperature (LST) - Normalized Difference Vegetation Index (NDVI) Correlation Coefficient of Pre-Construction (2010-2014) and Post-Construction (2018-2022) of NYSERDA MW Block Solar Farms built during 2015-2017.

---

#### Subdirectory Info:
1. raw-data
    + NYSERDA MW Block shapefile
        + *Note: could not include .dbf file for NYSERDA shapefile b/c it is too large*
2. processed-data
    + NYSERDA LST-NDVI Excel
3. scripts
    + Script to generate pixel frequency histogram
        + *Note: need to import Excel dataset in `results` subdirectory to run script*
4. results
    + Pre- & Post-Construction pixel frequency Excels
5. figures
    + Images of histograms
6. rmarkdowns
    + Copy of `scripts` but in rmarkdown code chunks