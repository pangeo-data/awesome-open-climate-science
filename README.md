# Awesome Open Atmospheric, Ocean, and Climate Science
> Atmospheric, ocean, and climate science are [awesome](awesome.md).

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://travis-ci.com/pangeo-data/awesome-open-climate-science.svg?branch=master)](https://travis-ci.com/pangeo-data/awesome-open-climate-science) [![Contributions](https://img.shields.io/github/issues-pr-closed-raw/pangeo-data/awesome-open-climate-science.svg?label=contributions)](https://github.com/pangeo-data/awesome-open-climate-science/pulls) [![Commits](https://img.shields.io/github/last-commit/pangeo-data/awesome-open-climate-science.svg?label=last%20contribution)](https://github.com/pangeo-data/awesome-open-climate-science/commits/master)  [![License](https://img.shields.io/github/license/pangeo-data/awesome-open-climate-science.svg)](https://github.com/pangeo-data/awesome-open-climate-science/blob/master/LICENSE)  

This is a curated list of open source software packages that  make our lives as scientists, hackers and data wranglers easier or just more awesome.
This list is intended to be the fluid-earth counterpart of
[awesome open geoscience](https://github.com/softwareunderground/awesome-open-geoscience),
although there is inevitably some overlap.
**It is not just climate science!** We use the word "climate" in the repo name just as shorthand for the fluid part of the earth.
Packages from atmospheric science, oceanography, climate science, and hydrology are all welcome.

In accordance with the [awesome manifesto](https://github.com/sindresorhus/awesome/blob/master/awesome.md),
we add awesome repositories. We are wide open to [contributions](contributing.md) of course!
Don't hesitate to add your favorite packages by making a [pull request]

## Contents

- [Awesome Open Atmospheric, Ocean, and Climate Science](#awesome-open-atmospheric-ocean-and-climate-science)
  - [Contents](#contents)
  - [Software](#software)
    - [General Purpose](#general-purpose)
    - [Frameworks](#frameworks)
    - [Meteorology](#meteorology)
    - [Oceanography](#oceanography)
    - [Climate](#climate)
    - [Remote Sensing](#remote-sensing)
    - [Glaciology](#glaciology)
    - [Spatiotemporal Statistics](#spatiotemporal-statistics)
    - [Regridding](#regridding)
    - [GIS](#gis)
    - [Data Storage](#data-storage)
    - [Simulation](#simulation)
    - [Visualization](#visualization)
  - [Data Repositories](#data-repositories)
  - [Tutorials](#tutorials)
  - [Cheat Sheets](#cheat-sheets)
  - [Miscellaneous](#miscellaneous)
  - [How to Contribute](#how-to-contribute)
  - [License](#license)

## Software
Awesome software projects sub-categorized by focus.

### General Purpose

| ▲ [Top](#awesome-open-geoscience) |
| --- |

While packages are not technically specific to AOCH science, they are so essential for scientific workflows that we can't not include them

- [Pandas](https://pandas.pydata.org/) - ![Python](media/icon/python.png) Data structures and computational tools for working with tabular datasets
- [Xarray](http://xarray.pydata.org/en/latest/) - ![Python](media/icon/python.png) Data structures and computational tools for multidimensional arrays, inspired by netCDF data model

### Frameworks

| ▲ [Top](#awesome-open-geoscience) |
| --- |

- [Iris](https://scitools.org.uk/iris/docs/latest/) - ![Python](media/icon/python.png) Expressive analysis and visualization of multi-dimensional datasets based on the CF conventions
- [CDMS](https://cdms.readthedocs.io/en/latest/index.html) - ![Python](media/icon/python.png) Object-oriented data management system for multidimensional, gridded data used in climate analysis and simulation

### Meteorology

| ▲ [Top](#awesome-open-geoscience) |
| --- |

- [MetPy](https://unidata.github.io/MetPy/) - ![Python](media/icon/python.png) Collection of tools for reading, visualizing, and performing calculations with weather data
- [windspharm](https://ajdawson.github.io/windspharm/index.html) - ![Python](media/icon/python.png) Spherical harmonic wind analysis
- [wrf-python](https://wrf-python.readthedocs.io/en/latest/) - ![Python](media/icon/python.png) A collection of diagnostic and interpolation routines for use with output of the Weather Research and Forecasting (WRF-ARW) Model

### Oceanography

| ▲ [Top](#awesome-open-geoscience) |
| --- |

- [GSW-Python](https://github.com/TEOS-10/GSW-Python) - ![Python](media/icon/python.png) Thermodynamic equation of state for seawater
- [WAVEWATCH III](https://github.com/NOAA-EMC/WW3) - ![Fortran](media/icon/fortran.png) NOAA's Ocean wave model
- [UMWM](https://github.com/umwm/umwm) - ![Fortran](media/icon/fortran.png) University of Miami's wave model

### Climate

| ▲ [Top](#awesome-open-geoscience) |
| --- |

- [climlab](https://climlab.readthedocs.io/en/latest/) - ![Python](media/icon/python.png) Process-oriented climate modeling
- [aospy](https://aospy.readthedocs.io/en/stable/) - ![Python](media/icon/python.png) Automated analysis and management of gridded climate data
- [Oocgcm](https://oocgcm.readthedocs.io/en/latest/) - ![Python](media/icon/python.png) Analysis of large gridded geophysical datasets
- [Pangaea:](https://pangaea.readthedocs.io/en/latest/) - ![Python](media/icon/python.png) xarray extension for gridded land surface & weather model output
- [xgcm](https://xgcm.readthedocs.io/en/latest/) - ![Python](media/icon/python.png) Extends the xarray data model to understand finite volume grid cells (common in General Circulation Models) and provides interpolation and difference operations for such grids
- [OpenClimateGIS](https://www.earthsystemcog.org/projects/openclimategis/) - ![Python](media/icon/python.png) Geospatial manipulation, subsetting, computation, and translation of spatiotemporal climate data

### Remote Sensing

| ▲ [Top](#awesome-open-geoscience) |
| --- |

- [SatPy](https://satpy.readthedocs.io/en/latest/)  - ![Python](media/icon/python.png) Read and manipulate meteorological remote sensing data and write it to various image and data file formats
- [Open Data Cube](https://www.opendatacube.org/) - ![Python](media/icon/python.png) Analysis toolkit for continental scale Earth Observation data from satellites
- [Earthdata Search](https://search.earthdata.nasa.gov/) - User interface for searching against the CMR (Common Metadata Repository). Supports data download, visualization, and subsetting in some cases.

### Glaciology

| ▲ [Top](#awesome-open-geoscience) |
| --- |

- [OGGM](https://oggm.org/) - ![Python](media/icon/python.png) Open Global Glacier Model

### Spatiotemporal Statistics

| ▲ [Top](#awesome-open-geoscience) |
| --- |

- [EOFs](https://ajdawson.github.io/eofs/) - ![Python](media/icon/python.png) EOF analysis

### Regridding

| ▲ [Top](#awesome-open-geoscience) |
| --- |

- [xESMF](https://xesmf.readthedocs.io/en/latest/) - ![Python](media/icon/python.png) Regridding for numpy and Xarray datasets based on the Earth Systems Modeling Framework (ESMF) library
- [Pyresample](https://pyresample.readthedocs.io/en/stable/) - ![Python](media/icon/python.png) Resample/reproject earth observing satellite data

### GIS

| ▲ [Top](#awesome-open-geoscience) |
| --- |

- [geopandas](http://geopandas.org/) - ![Python](media/icon/python.png) Spatial GIS operations on geometric types. 
- [salem](https://salem.readthedocs.io/en/latest/) - ![Python](media/icon/python.png) Adds geolocalised subsetting, masking, and plotting operations to xarray's data structures via accessors
- [Regionmask](https://regionmask.readthedocs.io/en/stable/) - ![Python](media/icon/python.png) plotting and creation of masks of spatial regions
- [xshape](https://xshape.readthedocs.io/en/latest/) - ![Python](media/icon/python.png) Tools for working with shapefiles, topographies, and polygons in xarray
- [Collocate](https://github.com/cistools/collocate) - ![Python](media/icon/python.png) Collocate xarray trajectories in arbitrary physical dimensions
- [QGIS](https://qgis.org/) - ![C++](media/icon/cplusplus.png) GIS platform to visualize, manage, edit, analyse data, and compose printable maps
- [GeoPHP](https://geophp.net/) - ![PHP](media/icon/php.png) The world's most popular geospatial library for PHP that works with WKT (including EWKT), WKB (including EWKB), GeoJSON, KML, GPX, GeoRSS and more

### Data Storage

| ▲ [Top](#awesome-open-geoscience) |
| --- |

- [netCDF](https://www.unidata.ucar.edu/software/netcdf/) - ![Python](media/icon/python.png) ![C++](media/icon/cplusplus.png) ![C](media/icon/c.png) ![Java](media/icon/java.png) ![Fortran](media/icon/fortran.png) NetCDF (Network Common Data Form) is a set of interfaces for array-oriented data access and a freely distributed collection of data access libraries for C, Fortran, C++, Java, Python, and other languages
- [HDF5](https://www.hdfgroup.org/solutions/hdf5/) - ![Python](media/icon/python.png) ![C++](media/icon/cplusplus.png) ![C](media/icon/c.png) ![Java](media/icon/java.png) ![Fortran](media/icon/fortran.png) HDF5 is a high-performance data management data storage format. HDF interfaces are available in C, Fortran, C++, Java, Python, and other languages
- [Zarr](https://zarr.readthedocs.io/en/stable/index.html) - ![Pyton](media/icon/python.png) chunked, compressed, N-dimensional arrays.
- [xmitgcm](https://xmitgcm.readthedocs.io/en/latest/) - ![Python](media/icon/python.png) Read MITgcm binary MDS files into xarray data structures.
- [xbpch](https://github.com/darothen/xbpch) - ![Python](media/icon/python.png) Xarray interface for bpch files
- [PyGDX](https://pygdx.readthedocs.io/en/latest/) - ![Python](media/icon/python.png) Access data stored in GAMS Data eXchange (GDX) files

### Simulation

| ▲ [Top](#awesome-open-geoscience) |
| --- |

- Do we list all the open source climate model codes? Are they awesome enough?
- [xarray-simlab](https://xarray-simlab.readthedocs.io/en/latest/) - ![Python](media/icon/python.png) xarray extension for computer model simulations

### Visualization

- [PyViz](http://pyviz.org/) - ![Python](media/icon/python.png) A coordinated effort to make data visualization in Python easier to use, easier to learn, and more powerful. Sub-components include:
  - [HoloViews](http://holoviews.org/) - ![Python](media/icon/python.png) Library designed to make data analysis and visualization seamless and simple
  - [GeoViews](http://geoviews.org/) - ![Python](media/icon/python.png) Library that makes it easy to explore and visualize geographical, meteorological, and oceanographic datasets, such as those used in weather, climate, and remote sensing research
  - [Datashader](https://github.com/pyviz/datashader) - ![Python](media/icon/python.png) graphics pipeline system for creating meaningful representations of large datasets quickly and flexibly
  - [Panel](https://panel.pyviz.org/) - ![Python](media/icon/python.png) Create custom interactive web apps and dashboards by connecting user-defined widgets to plots, images, tables, or text
  - [hvPlot](https://hvplot.pyviz.org/) - ![Python](media/icon/python.png) A high-level plotting API for the PyData ecosystem built on HoloViews
- [EarthSim](https://earthsim.pyviz.org/) -![Python](media/icon/python.png) Tools for working with and visualizing environmental simulations

- [Cartopy](https://scitools.org.uk/cartopy/docs/latest/) - ![Python](media/icon/python.png) Easy cartographic (maps) data visualization.
- [Geoviews](http://geo.holoviews.org/) - ![Python](media/icon/python.png) Explore and visualize geographic data using HoloViews. 

## Data Repositories

- [Quantarctica](http://quantarctica.npolar.no/data-catalog/) - user-configurable [QGIS](#gis) basemap for Antarctica with high-quality, peer-reviewed, free and open Antarctic scientific data

- [Common Metadata Repository](http://cmr.earthdata.nasa.gov/search) - Search API for NASA's remote-sensed earth science metadata

| ▲ [Top](#awesome-open-geoscience) |
| --- |

## Tutorials

- [Pangeo Tutorial at Fall AGU 2018](https://github.com/pangeo-data/pangeo-tutorial-agu-2018/blob/master/README.md) - Tutorial covering the basic Pangeo framework, including Dask, Xarray and JupyterHub
- [Pangeo SEA Tutorial](https://github.com/pangeo-data/pangeo-tutorial-sea-2018/blob/master/README.md) - Tutorial for folks working on the NCAR Cheyenne Supercomputer
## Cheat Sheets

## Miscellaneous

| ▲ [Top](#awesome-open-geoscience) |
| --- |

## How to Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first

| ▲ [Top](#awesome-open-geoscience) |
| --- |

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, all contributors have waived all copyright and
related or neighboring rights to this work
