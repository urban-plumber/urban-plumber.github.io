
# KUOM Tall Tower, Minneapolis, Minnesota, United States (US-Minneapolis)

## Site observation metadata

|                           | observation_attributes                                                                                                                                                                                                                                                                    |
|:--------------------------|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| title                     | URBAN-PLUMBER forcing data for US-Minneapolis                                                                                                                                                                                                                                             |
| summary                   | Observed and ERA5-derived surface meteorological data for KUOM Tall Tower, Minneapolis, Minnesota, United States. Data is for use by registered participants of Urban-PLUMBER in this project only. Do not distribute. All times in UTC.                                                  |
| sitename                  | US-Minneapolis                                                                                                                                                                                                                                                                            |
| long_sitename             | KUOM Tall Tower, Minneapolis, Minnesota, United States                                                                                                                                                                                                                                    |
| version                   | v1                                                                                                                                                                                                                                                                                        |
| conventions               | ALMA+CF.rev13                                                                                                                                                                                                                                                                             |
| featureType               | timeSeries                                                                                                                                                                                                                                                                                |
| time_coverage_start       | 1996-01-01 00:00:00                                                                                                                                                                                                                                                                       |
| time_coverage_end         | 2009-05-29 13:00:00                                                                                                                                                                                                                                                                       |
| time_analysis_start       | 2006-06-01 18:00:00                                                                                                                                                                                                                                                                       |
| time_shown_in             | UTC                                                                                                                                                                                                                                                                                       |
| local_utc_offset_hours    | -6.0                                                                                                                                                                                                                                                                                      |
| timestep_interval_seconds | 1800.0                                                                                                                                                                                                                                                                                    |
| timestep_number_spinup    | 182628                                                                                                                                                                                                                                                                                    |
| timestep_number_analysis  | 52455                                                                                                                                                                                                                                                                                     |
| observations_contact      | Joe McFadden (mcfadden@ucsb.edu) University of California, Santa Barbara                                                                                                                                                                                                                  |
| observations_reference    | Peters, Hiller, McFadden (2011): https://doi.org/10.1029/2010JG001463; Menzer and McFadden (2017): https://doi.org/10.1016/j.atmosenv.2017.09.049                                                                                                                                         |
| project_contact           | Mathew Lipson: m.lipson@unsw.edu.au, Sue Grimmond: c.s.grimmond@reading.ac.uk, Martin Best: martin.best@metoffice.gov.uk                                                                                                                                                                  |
| date_created              | 2021-04-14 13:23:59                                                                                                                                                                                                                                                                       |
| other_references          | ERA5: Copernicus Climate Change Service (C3S) (2017): https://cds.climate.copernicus.eu/cdsapp#!/home                                                                                                                                                                                     |
| acknowledgements          | Contains modified Copernicus Climate Change Service Information (ERA5 hourly data on single levels). With thanks to all involved in collecting, processing and sharing observational data                                                                                                 |
| comment                   | Wind directions between 120-180° have interference from the tall tower structure and excluded. Radiation components (SWdown,SWup,LWdown,LWup) measured at 2 m above ground level, not at 40 m as other variables. Air pressure (PSurf) from Minneapolis-Saint Paul International Airport. |

## Site images

|                                             |                                             |    
|:-------------------------------------------:|:-------------------------------------------:|
| [![Region](./images/US-Minneapolis_region_map.jpg)](./images/US-Minneapolis_region_map.jpg)  <sub>source: OpenStreetMap</sub>    | [![site_map](./images/US-Minneapolis_site_map.jpg)](./images/US-Minneapolis_site_map.jpg) <sub>source: OpenStreetMap</sub>    |
| [![site_photo](./images/US-Minneapolis_site_photo.jpg)](./images/US-Minneapolis_site_photo.jpg) <sub>source: </sub>  | [![site_sat](./images/US-Minneapolis_site_sat.jpg)](./images/US-Minneapolis_site_sat.jpg) <sub>source: OpenStreetMap, Microsoft</sub>    |

## Site characteristics

|   id | parameter                          |     value | units         | source                     | doi                                                                                                                                                                    |
|-----:|:-----------------------------------|----------:|:--------------|:---------------------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|    1 | latitude                           |   44.9984 | degrees_north | Peters et al. (2011)       | [https://doi.org/10.1029/2010JG001463](https://doi.org/10.1029/2010JG001463)                                                                                           |
|    2 | longitude                          |  -93.1884 | degrees_east  | Peters et al. (2011)       | [https://doi.org/10.1029/2010JG001463](https://doi.org/10.1029/2010JG001463)                                                                                           |
|    3 | ground_height                      |  301      | m             | site metadata              | [https://ameriflux.lbl.gov/sites/siteinfo/US-KUO#overview](https://ameriflux.lbl.gov/sites/siteinfo/US-KUO#overview)                                                   |
|    4 | measurement_height_above_ground    |   40      | m             | Peters et al. (2011)       | [https://doi.org/10.1029/2010JG001463](https://doi.org/10.1029/2010JG001463)                                                                                           |
|    5 | impervious_area_fraction           |    0.15   | 1             | Peters et al. (2011)       | [https://doi.org/10.1029/2010JG001463](https://doi.org/10.1029/2010JG001463)                                                                                           |
|    6 | tree_area_fraction                 |    0.3    | 1             | Peters et al. (2011)       | [https://doi.org/10.1029/2010JG001463](https://doi.org/10.1029/2010JG001463)                                                                                           |
|    7 | grass_area_fraction                |    0.53   | 1             | Peters et al. (2011)       | [https://doi.org/10.1029/2010JG001463](https://doi.org/10.1029/2010JG001463)                                                                                           |
|    8 | bare_soil_area_fraction            |    0      | 1             | Peters et al. (2011)       | [https://doi.org/10.1029/2010JG001463](https://doi.org/10.1029/2010JG001463)                                                                                           |
|    9 | water_area_fraction                |    0.02   | 1             | Peters et al. (2011)       | [https://doi.org/10.1029/2010JG001463](https://doi.org/10.1029/2010JG001463)                                                                                           |
|   10 | roof_area_fraction                 |    0.05   | 1             | estimated, see notes       | partitioned from 0.15 "impervious surface" in footprint reported in [Peters, HIller and McFadden (2011)](https://doi.org/10.1029/2010JG001463) using satellite imagery |
|   11 | road_area_fraction                 |    0.05   | 1             | estimated, see notes       | partitioned from 0.15 "impervious surface" in footprint reported in [Peters, HIller and McFadden (2011)](https://doi.org/10.1029/2010JG001463) using satellite imagery |
|   12 | other_paved_area_fraction          |    0.05   | 1             | estimated, see notes       | partitioned from 0.15 "impervious surface" in footprint reported in [Peters, HIller and McFadden (2011)](https://doi.org/10.1029/2010JG001463) using satellite imagery |
|   13 | building_mean_height               |    5      | m             | estimate                   | -                                                                                                                                                                      |
|   14 | tree_mean_height                   |   12      | m             | Peters et al. (2011)       | [https://doi.org/10.1029/2010JG001463](https://doi.org/10.1029/2010JG001463)                                                                                           |
|   15 | roughness_length_momentum          |    1.07   | m             | Peters and McFadden (2012) | [https://doi.org/10.1029/2011JG001933](https://doi.org/10.1029/2011JG001933)                                                                                           |
|   16 | displacement_height                |    2.27   | m             | estimate, see notes        | derived from morphology using [Kent et al. 2017](https://doi.org/10.1016/j.jweia.2017.07.016)                                                                          |
|   17 | canyon_height_width_ratio          |    0.05   | 1             | estimated, see notes       | derived from estimate of wall to plan area ratio and Eq. 1 from [Masson et al. (2020)](htpps://doi.org/10.1016/j.uclim.2019.100536)                                    |
|   18 | wall_to_plan_area_ratio            |    0.097  | 1             | estimated, see notes       | derived from perimeter of building footprint (from satellite imagery) times estimated average building height                                                          |
|   19 | average_albedo_at_midday           |    0.213  | 1             | median of observations     | -                                                                                                                                                                      |
|   20 | resident_population_density        | 1000      | person/km2    | Peters and McFadden (2012) | [https://doi.org/10.1029/2011JG001933](https://doi.org/10.1029/2011JG001933)                                                                                           |
|   21 | anthropogenic_heat_flux_mean       |    1.8    | W/m2          | Varquez et al. (2021)      | [https://doi.org/10.1038/s41597-021-00850-w](https://doi.org/10.1038/s41597-021-00850-w)                                                                               |
|   22 | topsoil_clay_fraction              |    0.15   | 1             | OpenLandMap                | [https://doi.org/10.5281/zenodo.2525663](https://doi.org/10.5281/zenodo.2525663)                                                                                       |
|   23 | topsoil_sand_fraction              |    0.46   | 1             | OpenLandMap                | [https://doi.org/10.5281/zenodo.2525662](https://doi.org/10.5281/zenodo.2525662)                                                                                       |
|   24 | topsoil_bulk_density               | 1490      | kg/m3         | OpenLandMap                | [https://doi.org/10.5281/zenodo.2525665](https://doi.org/10.5281/zenodo.2525665)                                                                                       |
|   25 | building_height_standard_deviation |  nan      | m             | unknown                    | -                                                                                                                                                                      |

## Site observations

[![./obs_plots/all_obs_qc.png](./obs_plots/all_obs_qc.png)](./obs_plots/all_obs_qc.png)

## Site forcing

### SWdown forcing

[![SWdown](./obs_plots/SWdown_gapfilled_forcing.png)](./obs_plots/SWdown_gapfilled_forcing.png)

### LWdown forcing

[![LWdown](./obs_plots/LWdown_gapfilled_forcing.png)](./obs_plots/LWdown_gapfilled_forcing.png)

### Tair forcing

[![Tair](./obs_plots/Tair_gapfilled_forcing.png)](./obs_plots/Tair_gapfilled_forcing.png)

### Qair forcing

[![Qair](./obs_plots/Qair_gapfilled_forcing.png)](./obs_plots/Qair_gapfilled_forcing.png)

### PSurf forcing

[![PSurf](./obs_plots/PSurf_gapfilled_forcing.png)](./obs_plots/PSurf_gapfilled_forcing.png)

### Rainf forcing

[![Rainf](./obs_plots/Rainf_gapfilled_forcing.png)](./obs_plots/Rainf_gapfilled_forcing.png)

### Snowf forcing

[![Snowf](./obs_plots/Snowf_gapfilled_forcing.png)](./obs_plots/Snowf_gapfilled_forcing.png)

### Wind_N forcing

[![Wind_N](./obs_plots/Wind_N_gapfilled_forcing.png)](./obs_plots/Wind_N_gapfilled_forcing.png)

### Wind_E forcing

[![Wind_E](./obs_plots/Wind_E_gapfilled_forcing.png)](./obs_plots/Wind_E_gapfilled_forcing.png)


## Quality control (qc) and gap filling procedure

**QC process on observations**
 
 - remove values outside the [ALMAv3 protocol expected range values](https://urban-plumber.github.io/AU-Preston/plots/modelattrs/variable_definitions.html)
 - remove night periods of non-zero shortwave radiation between civil twilight times for site latitude and longitude
 - remove constant values of 4 or more timesteps (excluding zero values for shortwave, rainfall and snowfall)
 - remove outliers by applying a filter for values outside 4 standard deviations for each hour in a rolling 30 day window. Applying filter again at 5 standard deviations until no outliers exist.
 
**Gap-filling process**

 - first fill with nearby local tower observations where available
 - for gaps of 2 hours or less, fill with linear interpolation of adjacent observation
 - fill remaining gaps with bias-corrected, ERA5 derived data (see below)
 - snowfall from ERA5, with water equivalent removed from rainfall to retain mass balance
 - prepend flux tower data period with 10-years of ERA5 derived data (used for model spinup)
 
**ERA5 bias correction**
 
 - for downwelling longwave, temperature, humidity and pressure: calculate the mean bias between ERA5 and flux tower data in a 30-day rolling window for every hour and each day of the year, and apply that bias correction to all ERA5 data. For periods not covered by observations, linearly interpoloate between known biases for each hour seperately.
 - for precipitation: calculate total precipitation in a 10-year period and calculate the ratio between ERA5 data and the nearest GHCN-D station and apply that correction factor to ERA5 data.
 - for wind: apply wind log profile correction from ERA5 10m wind to tower measurement height using site roughness and displacement, with ERA5 roughness to match observed mean wind speeds.
 - for downwelling shortwave: use ERA5 data without correction

### SWdown diurnal qc

[![./obs_plots/SWdown_obs_qc_diurnal.png](./obs_plots/SWdown_obs_qc_diurnal.png)](./obs_plots/SWdown_obs_qc_diurnal.png)

### LWdown diurnal qc

[![./obs_plots/LWdown_obs_qc_diurnal.png](./obs_plots/LWdown_obs_qc_diurnal.png)](./obs_plots/LWdown_obs_qc_diurnal.png)

### Tair diurnal qc

[![./obs_plots/Tair_obs_qc_diurnal.png](./obs_plots/Tair_obs_qc_diurnal.png)](./obs_plots/Tair_obs_qc_diurnal.png)

### Qair diurnal qc

[![./obs_plots/Qair_obs_qc_diurnal.png](./obs_plots/Qair_obs_qc_diurnal.png)](./obs_plots/Qair_obs_qc_diurnal.png)

### Rainf diurnal qc

[![./obs_plots/Rainf_obs_qc_diurnal.png](./obs_plots/Rainf_obs_qc_diurnal.png)](./obs_plots/Rainf_obs_qc_diurnal.png)

### PSurf diurnal qc

[![./obs_plots/PSurf_obs_qc_diurnal.png](./obs_plots/PSurf_obs_qc_diurnal.png)](./obs_plots/PSurf_obs_qc_diurnal.png)

### Wind_N diurnal qc

[![./obs_plots/Wind_N_obs_qc_diurnal.png](./obs_plots/Wind_N_obs_qc_diurnal.png)](./obs_plots/Wind_N_obs_qc_diurnal.png)

### Wind_E diurnal qc

[![./obs_plots/Wind_E_obs_qc_diurnal.png](./obs_plots/Wind_E_obs_qc_diurnal.png)](./obs_plots/Wind_E_obs_qc_diurnal.png)

### Qle diurnal qc

[![./obs_plots/Qle_obs_qc_diurnal.png](./obs_plots/Qle_obs_qc_diurnal.png)](./obs_plots/Qle_obs_qc_diurnal.png)

### Qh diurnal qc

[![./obs_plots/Qh_obs_qc_diurnal.png](./obs_plots/Qh_obs_qc_diurnal.png)](./obs_plots/Qh_obs_qc_diurnal.png)

