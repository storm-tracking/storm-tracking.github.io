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

**Rereference**

Feng, Z., Hardin, J., Barnes, H. C., Leung, L. R., Varble, A., & Zhang, Z. (2022). PyFLEXTRKR: a Flexible Feature Tracking Python Software for Convective Cloud Analysis. EGUsphere [preprint]. [https://doi.org/10.5194/egusphere-2022-1136](https://doi.org/10.5194/egusphere-2022-1136)

## TOOCAN

## TAMS


## tobac


## MOAAP 
