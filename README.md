# Land-Cover
## Overview
**Land-Cover** is a comprehensive Python-based geospatial workflow that automates the process of downloading ESA WorldCover data, mosaicing and cropping the imagery to the Punjab region (Pakistan), 
generating a Digital Elevation Model (DEM) from SRTM data, resampling the land cover data to match the DEM resolution, and finally creating a polished 2D land cover map. This project is ideal for geospatial 
analysts and remote sensing specialists looking to integrate multi-source geodata and produce high-quality visualizations.

## Features
- **Data Acquisition**: Automatically queries and downloads ESA WorldCover tiles within the Punjab region and a specified date range.
- **Image Processing**: Merges downloaded tiles into a single mosaic and crops them to match the Punjab shapefile.
- **DEM Generation**: Creates a DEM using SRTM data based on the spatial extent of Punjab.
- **Data Resampling**: Aligns the resolution of the land cover data with that of the generated DEM.
- **Visualization**: Produces a high-quality, publication-ready 2D land cover map with customizable aesthetics and clear boundary overlays.

## Requirements

- **Python Version:** 3.7+
- **Python Libraries:**  
  - geopandas  
  - rasterio  
  - matplotlib  
  - pystac_client  
  - planetary_computer  
  - srtm  
  - affine  
  - numpy
 
![image](https://github.com/user-attachments/assets/9ba5af6c-5e21-4667-ae22-d79627749e89)


