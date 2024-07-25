# LongRunMIP-dPdT
Code and partially-processed data for Kao and Pendergrass, to be submitted to GRL 
[![DOI](https://zenodo.org/badge/775534309.svg)](https://zenodo.org/doi/10.5281/zenodo.12827997)


The conda environment: 
```conda create -n lrmipdpdt jupyterlab scipy numpy xarray matplotlib netcdf4 dask nc-time-axis seaborn cartopy scikit-learn pillow```

Data needed to generate the figures are included are included in ```data/```. These include global-mean fluxes for all relevant simulations and fields, under ```data/orig/```, and for figure 4 (the maps), spatial anomalies of precipitation under ```data/processed```.  

