# About

The purpose of this project is to explore the Google Earth Engine (GEE) database and create tutorials on how to access and visualize data derived from GEE.

Information about California wildfires can be found on the GEE database and visualized via Plotly, a Python open source graphing library. In this project, we create a bubble map of wildfire brightnesses in order to represent the intensity of these fires.

# Data

The `data` folder contains `SoCal_fires.csv`, which is a .CSV of California wildfire data from September 1st, 2017 to September 1st, 2018. The file `ca1718.csv` is a file containing data from California's 2017-2018 fire season (October-April). This data is derived from NASA's Fire Information for Resource Management Systems (FIRMS). Information about the columns can be found [here](https://earthdata.nasa.gov/earth-observation-data/near-real-time/firms/c6-mcd14dl).

# Code

Two Jupyter notebooks are used to describe steps in the tutorial and display the interactive Plotly map:
- `Acquiring_data_from_GEE.ipynb` explains how to find datasets on GEE and describes how to  request and download data from the FIRMS website.
- `visualizing_FIRMS.ipynb` describes how to filter the dataset and ultimately plot the data in the form of a Plotly bubble map.

# Images

This folder contains various .PNG screenshots used in `Acquiring_data_from_GEE.ipynb`.
