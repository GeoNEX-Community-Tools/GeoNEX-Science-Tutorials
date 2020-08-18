# Welcome to GeoNEX Science Tutorials

Here we provide easy-to-use tutorials for working with GeoNEX Geostationary Satellite Imagery. 

## [Getting started with GeoNEX data ](https://nbviewer.jupyter.org/github/GeoNEX-Community-Tools/GeoNEX-Science-Tutorials/blob/master/Getting_Started_with_GEONEX_TOA.ipynb)

This tutorial will walk you through how to get started working with the data including how to:
* Download GeoNEX data from the [NAS Data Portal](https://data.nas.nasa.gov/geonex/)
* Apply data corrections 
* Geolocate image tiles
* Calculate NDVI
* Extract NDVI time-series

### Prerequisites

* To run our jupyter notebook tutorial locally, we recommend using the [Anaconda Python distribution](https://www.anaconda.com/distribution/). 
* `wget` is used for downloading files


To create a conda environment with the required python libraries, run the following in terminal:

```
conda create -n geonex_tutorial python=3 jupyterlab pandas numpy matplotlib scipy pyhdf xarray hvplot geoviews pyproj

source activate geonex_tutorial

```

After activating your geonex_tutorial conda enviroment, download Getting_Started_with_GEONEX_TOA.ipynb.  Through terminal, navigate to the directory where Getting_Started_with_GEONEX_TOA.ipynb is saved and run the following:

```
jupyter lab Getting_Started_with_GEONEX_TOA.ipynb
```

This will launch the jupyter notebook in jupyter lab.


<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 International License</a>.
