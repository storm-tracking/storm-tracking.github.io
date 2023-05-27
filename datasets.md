---
layout: page
title: "MCS datasets"
---

Overview of databases that contain information on mesoscale convective systems (MCSs tracked based on satellite observations.  


# Global MCS datasets

---

## PyFLEXTRKR Global MCS Tracking Data

A global (60°S–60°N) long-term (**2000–2020**) high-resolution (**∼10 km, hourly**) mesoscale convective system (MCS) database was developed by tracking MCS jointly using geostationary satellite infrared brightness temperature (Tb) and precipitation feature (PF) characteristics from the Integrated Multi-satellitE Retrievals for GPM (IMERG) precipitation data sets ([Feng et al. 2021](https://doi.org/10.1029/2020JD034202)). Independent validation shows that the satellite-based MCS data set is able to reproduce important MCS statistics derived from ground-based radar network observations in the United States and China. By carefully considering key PF characteristics in addition to Tb signatures, the new method significantly improves upon previous Tb-only methods in detecting MCSs in the midlatitudes for all seasons. The [PyFLEXTRKR](https://doi.org/10.5194/gmd-16-2753-2023) algorithm used to produce the MCS tracking dataset is available on [GitHub](https://github.com/FlexTRKR/PyFLEXTRKR).

**Climatology** of global MCS annual mean number, precipitation amount, and fraction to total precipitation derived from the dataset is shown below.

![](https://portal.nersc.gov/project/m1867/mcs_global_v2/figures/annual_mcs_number_rain_rainfrac_map_small.gif)

### Description of the MCS Dataset

The detailed documentation of the MCS tracking dataset can be found [**here**](https://portal.nersc.gov/project/m1867/mcs_global_v2/PyFLEXTRKR_MCS_Tracking_Data_Readme.pdf). In the current V2 MCS database (**June 2000 - December 2020**), there are two sets of files: 1. track statistics data, 2. pixel-level data.

1. Contains summary MCS statistics such as time, location, lifetime, size, rainfall statistics, movement, etc. (full global data volume is ~5 GB). 

2. Contains the full Tb, IMERG precipitation, and tracked MCS masks on the native IMERG 0.1 degree grid at hourly resolution (full global data volume is ~2.3TB). An example of a snapshot MCS mask file is provided below.

![](https://portal.nersc.gov/project/m1867/mcs_global_v2/figures/MCS_mask_tracks_example_MC_small.gif)


### Data Access

To accesss the data, please contact: [Zhe.Feng@pnnl.gov](mailto:zhe.feng@pnnl.gov)

### References

Feng, Z., Leung, L. R., Liu, N., Wang, J., Houze, R. A., Li, J., et al. (2021). A Global High‐Resolution Mesoscale Convective System Database Using Satellite‐Derived Cloud Tops, Surface Precipitation, and Tracking. Journal of Geophysical Research: Atmospheres, 126(8), doi:[10.1029/2020JD034202](https://doi.org/10.1029/2020JD034202).

Feng, Z., Hardin, J., Barnes, H. C., Li, J., Leung, L. R., Varble, A., & Zhang, Z. (2023). PyFLEXTRKR: a flexible feature tracking Python software for convective cloud analysis. Geosci. Model Dev., 16(10), 2753-2776, doi:[10.5194/gmd-16-2753-2023](https://doi.org/10.5194/gmd-16-2753-2023)


# Regional MCS datasets

---

## MCS Database over the United States

The MCS database over Contiguous United States (CONUS) is a long-term (**2004-2017**) high-resolution (**4 km, 1 hourly**) storm system dataset that tracks individual MCS events. The MCS database is produced by tracking MCS jointly using geostationary satellite infrared brightness temperature (Tb) and the GridRad mosaic 3D NEXRAD radar data set ([Feng et al. 2019](https://doi.org/10.1175/JCLI-D-19-0137.1)). The database also contains the multi-sensor Stage IV precipitation data.

### Description of the MCS Dataset

The detailed documentation of the MCS tracking dataset can be found [**here**](https://portal.nersc.gov/project/m1867/mcs_gridrad_v2/MCS_Database_GridRad_Readme_v2.pdf).

**Climatology** of U.S. MCS convective feature echo-top heights and PF areas derived from the dataset is shown below.

![](https://portal.nersc.gov/project/m1867/mcs_gridrad_v2/figures/US_MCS_Database_climatology_small.gif)

### Data Access

The U.S. MCS database is available on the U.S. Department of Energy Atmospheric Radiation Measurement (ARM) program website: [https://doi.org/10.5439/1571643](https://doi.org/10.5439/1571643). A free account registration is required: [https://adc.arm.gov/armuserreg/#/new](https://adc.arm.gov/armuserreg/#/new).

### References

Feng, Z., Houze, R. A., Leung, L. R., Song, F., Hardin, J. C., Wang, J., et al. (2019). Spatiotemporal Characteristics and Large-scale Environments of Mesoscale Convective Systems East of the Rocky Mountains. Journal of Climate, 32(21), 7303-7328, doi:[10.1175/JCLI-D-19-0137.1](https://doi.org/10.1175/JCLI-D-19-0137.1).