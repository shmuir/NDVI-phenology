# Plant phenology and NDVI near the Santa Clara River

This is a project for EDS223: Geospatial Analysis and Remote Sensing for the Masters of Environmental Data Science program at the Bren School at UCSB.

The goal of this project is to become more comfortable working with environmental and raster data in R by landsat data to look at the NDVI changes with seasonal phenology for differnet vegetation types near the Santa Clara River. This includes:

1. Reading in the various raster files/scenes
2. Creating a function to calculate NDVI
3. Creating a function to apply the NDVI function across all scenes
4. Finding the average NDVI within each study site
5. Plot the mean NDVI for different vegetation types over time.

### Credit
This project is based on materials developed by Chris Kibler. 

### File Structure

    NDVI-phenology
    │   README.md
    │   ndvi_phenology.qmd    
    │
    └───data
        └───landsat .tifs
        └───study_sites shapefiles
