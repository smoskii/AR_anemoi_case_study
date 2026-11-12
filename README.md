# Atmospheric River Anemoi Case Study
This repository contains scripts, notebooks and files to evaluate and compare NWP and Anemoi forecasts for the October 17-19th, 2023 atmospheric river event on the British Columbia coast.

**Useful Links** 

Link to Google Drive resource: https://drive.google.com/drive/u/0/folders/1iqwsFyJ6j5r8hkQA8rcx-EowqtlSDpkb. \
Link to Verif data format: https://github.com/WFRT/verif/wiki/Arranging-my-own-data.

## Directory Structure
**Point Verification**
* `wrf2verif.py` extract WRF point forecasts into Verif-format NetCDF.
* `run_wrf2verif.sh` extract multiple WRF forecast files from multiple WRF forecast folders into Verif-format NetCDF.
* `extract_obs.py` extract BC Wildfire weather stations data in CSV format.
* `fill_obs.py` fill observation values from CSV into Verif ready NetCDF.
* `slice_wrf.ipynb` manually slice WRF forecast NetCDF file for sanity check.
* `observation.ipynb` manually extract and clean the BC Wildfire weather stations observation data.
* `data/` output files from `run_wrf2verif.sh`, `extract_obs.py`, `fill_obs.py`.

**2D Verification**
* `satellite_imagery.ipynb` compare satellite observations, tifs with models forecasts.
* `gee_python_api_tutorial.ipynb` GEE Python API tutorial.
* `gee_extract.js` Backup code of GEE code editor for extracting satellite imagery.

## Getting Started
The case study is part of the evaluation of machine learning based forecasts produced by a "stretched-grid" model. \
Anemoi is an open-source platform used for machine learning weather forecasting models.

**Requirements**

- numpy
- matplotlib
- rasterio
- xarray
- cartopy

**Environment Variables**

## Methodology

**Important time periods (UTC)**


**Variables**


## Observation Data



Stations used: 
| ID  | Name          | Lat   | Lon      | Alt (m)   |
|-----|---------------|-------|----------|-----------|
|     |               |       |          |           |
|     |               |       |          |           |
|     |               |       |          |           |

**Satellite imagery**: https://drive.google.com/drive/folders/1oRro8_L23_qQ4Xyd_UUPo40_4Q-Zt_dE

## Forecast Data
* WRF: nextcloud:~/Share_Forecasts/WAC00WG-01
* Anemoi

**Authors**

<<<<<<< HEAD
Cosmo Pearson-Young

Adapted from the anemoi_case_study repository by Jessie Chen.
=======
Jessie Chen\
&emsp;Assisted by Claude by Anthropic (claude-sonnet-4-6, claude.ai) for coding and documentation.

Cosmo Pearson-Young\
&emsp;Assisted by Claude by Anthropic (claude-sonnet-4-6, claude.ai) for coding and documentation.
>>>>>>> 31cf367 (Updated README.md to include requirements)
