# Borana Rangeland LULC Classification (1990)

This repository contains a reproducible workflow for classifying land use and land cover (LULC) of Borana, Ethiopia, for the year 1990 using Landsat 4/5 imagery and Google Earth Engine (GEE) Python API.

## Features

- Landsat 4 & 5 image collection preprocessing
- Cloud masking & scaling
- Spectral indices: NDVI, BSI, IBI, MNDWI
- DEM & slope inclusion
- Random Forest classification
- Accuracy assessment (train & validation)
- Export to Google Drive

## Requirements

- Python 3.10+
- earthengine-api
- geemap
- folium
- numpy

## How to Run

1. Clone the repository
```bash
git clone https://github.com/yourusername/Borana_LULC_1990.git
