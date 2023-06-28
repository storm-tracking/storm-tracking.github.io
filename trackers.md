---
layout: page
title: "Tracking algorithms"
---

## [PyFLEXTRKR](https://github.com/FlexTRKR/PyFLEXTRKR)

---
The Python FLEXible object TRacKeR (PyFLEXTRKR) is a flexible atmospheric feature tracking software package. The software can track any 2D objects and handle merging and splitting explicitly. PyFLEXTRKR has specific capabilities to track convective clouds from a variety of observations and model simulations. The package uses Dask for scalable parallelization and has been optimized to work on large datasets including global kilometer-scale data. PyFLEXTRKR uses Xarray for I/O and writes netCDF files as tracking outputs.

Currently PyFLEXTRKR supports tracking: 

1. Individual convective cells, 
2. Mesoscale convective systems (MCSs), 
3. General atmospheric objects defined by customizable feature identification functions.

![](https://portal.nersc.gov/project/m1867/PyFLEXTRKR/figures/cover_image.png)

**Tracking** in PyFLEXTRKR primarily uses object overlap technique, with an option to use advection estimates (2D cross-correlation) to increase overlap probability. Largest overlap objects are tracked continuously, and smaller overlap objects are marked as merging/splitting.

![](https://portal.nersc.gov/project/m1867/PyFLEXTRKR/figures/tracking_merging_splitting.png)

**Reference**

Feng, Z., Hardin, J., Barnes, H. C., Li, J., Leung, L. R., Varble, A., & Zhang, Z. (2023). PyFLEXTRKR: a flexible feature tracking Python software for convective cloud analysis. Geosci. Model Dev., 16(10), 2753-2776, doi:[10.5194/gmd-16-2753-2023](https://doi.org/10.5194/gmd-16-2753-2023)

## [tobac](https://tobac.readthedocs.io/en/latest/)

*tobac* (Tracking and Object-based Analysis of Clodus) is a scientific Python package for detecting, tracking, and analyzing clouds and other atmospheric phenomena.  *tobac* is unique in its ability to track phenomena using **any variable** on **any grid**, including radar data, satellite observations, and numerical model output. Due to its modular and flexible design, *tobac* is a general toolset that can be used for tracking all kinds of atmosheric phenomena related to storm formation, from small scales (e.g. updrafts) to large scales (e.g. atmospheric rivers). 

The main elements of *tobac* are:

1. **Data input and output** - Xarray and pandas 
2. **Data filtering** - Gaussian smoothing and wave-length based filtering
3. **Feature detection** - works in 3D and with multiple thresholds
4. **Segmentation of cloud areas and volumes** - works in 3D and across different data sets (e.g. get the precipitation volume associated with detected clouds) 
5. **Trajectory linking** - uses propagation speed and works across periodic boundaries 
6. **Object-based analysis and visualization** - includes the identification of mergers and splitters in the track database


*tobac* developed with an open, multi-institutional international community, and has been built from the ground up in support of open science. Detailed documentation can be found [here](https://tobac.readthedocs.io/en/latest/). Any user feedback is welcome and users are invited to leave commentsand questions in the [GitHub discussion forum of *tobac*](https://github.com/tobac-project/tobac/discussions) or, if it concerns bug reports or specific user requests, a [GitHub issue](https://github.com/tobac-project/tobac/issues). Release announcements, workshop and conference announcements, and other information of interest to the broader *tobac* users group are sent to the [tobac core group](https://groups.google.com/g/tobac/about) mailing list. If you are interested in contributing to the development of tobac, users are invited to join the [tobac developers](https://groups.google.com/u/0/g/tobac-developers) mailing list. 


**References**

Heikenfeld, M., Marinescu, P. J., Christensen, M., Watson-Parris, D., Senf, F., van den Heever, S. C., and Stier, P.: tobac 1.2: towards a flexible framework for tracking and analysis of clouds in diverse datasets, Geosci. Model Dev., 12, 4551–4570, [https://doi.org/10.5194/gmd-12-4551-2019](https://doi.org/10.5194/gmd-12-4551-2019), 2019.


## TOOCAN

## [TAMS](https://tams.readthedocs.io)

TAMS (**T**racking **A**lgorithm for **M**esoscale Convective **S**ystems) is an MCS tracker and classifier.
TAMS was [originally developed](https://doi.org/10.1175/MWR-D-19-0070.1) for tracking and analyzing MCSs associated with African easterly waves (AEWs).

The currently developed TAMS is a scientific Python package.
TAMS uses the [GeoPandas dataframe](https://geopandas.org/en/stable/docs/reference/api/geopandas.GeoDataFrame.html) data structure to store polygon shapes of the elements to be tracked.

## MOAAP 
