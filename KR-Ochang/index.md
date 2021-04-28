
# Ochang, South Korea (KR-Ochang)

## Site observation metadata

|                           | observation_attributes                                                                                                                                                                                                               |
|:--------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| title                     | URBAN-PLUMBER forcing data for KR-Ochang                                                                                                                                                                                             |
| summary                   | Observed and ERA5-derived surface meteorological data for Ochang, South Korea. Data is for use by registered participants of Urban-PLUMBER in this project only. Do not distribute. All times in UTC.                                |
| sitename                  | KR-Ochang                                                                                                                                                                                                                            |
| long_sitename             | Ochang, South Korea                                                                                                                                                                                                                  |
| version                   | v1                                                                                                                                                                                                                                   |
| conventions               | ALMA+CF.rev13                                                                                                                                                                                                                        |
| featureType               | timeSeries                                                                                                                                                                                                                           |
| time_coverage_start       | 2005-01-01 00:00:00                                                                                                                                                                                                                  |
| time_coverage_end         | 2017-07-26 00:00:00                                                                                                                                                                                                                  |
| time_analysis_start       | 2015-06-07 15:00:00                                                                                                                                                                                                                  |
| time_shown_in             | UTC                                                                                                                                                                                                                                  |
| local_utc_offset_hours    | 9.0                                                                                                                                                                                                                                  |
| timestep_interval_seconds | 1800.0                                                                                                                                                                                                                               |
| timestep_number_spinup    | 182862                                                                                                                                                                                                                               |
| timestep_number_analysis  | 37411                                                                                                                                                                                                                                |
| observations_contact      | Jinkyu Hong (jhong@yonsei.ac.kr)                                                                                                                                                                                                     |
| observations_reference    | Hong, Hong, Chun, Lee, Chang, Lee, Yi, Park, Byun, Joo (2019): https://doi.org/10.1186/s13021-019-0128-6                                                                                                                             |
| project_contact           | Mathew Lipson: m.lipson@unsw.edu.au, Sue Grimmond: c.s.grimmond@reading.ac.uk, Martin Best: martin.best@metoffice.gov.uk                                                                                                             |
| date_created              | 2021-04-28 15:06:13                                                                                                                                                                                                                  |
| other_references          | ERA5: Copernicus Climate Change Service (C3S) (2017): https://cds.climate.copernicus.eu/cdsapp#!/home NCI Australia: http://doi.org/10.25914/5f48874388857                                                                           |
| acknowledgements          | Contains modified Copernicus Climate Change Service Information (ERA5 hourly data on single levels). Data from replica hosted by NCI Australia. With thanks to all involved in collecting, processing and hosting observational data |
| comment                   | Qair from co-located HMP155 relative humidity sensor, not EC-150 open path gas analyser (which gives >>100 RH)                                                                                                                       |

## Site images

|                                             |                                             |    
|:-------------------------------------------:|:-------------------------------------------:|
| [![Region](./images/KR-Ochang_region_map.jpg)](./images/KR-Ochang_region_map.jpg)  <sub>source: OpenStreetMap</sub>    | [![site_map](./images/KR-Ochang_site_map.jpg)](./images/KR-Ochang_site_map.jpg) <sub>source: OpenStreetMap</sub>    |
| [![site_photo](./images/KR-Ochang_site_photo.jpg)](./images/KR-Ochang_site_photo.jpg) <sub>source: Keunmin Lee</sub>  | [![site_sat](./images/KR-Ochang_site_sat.jpg)](./images/KR-Ochang_site_sat.jpg) <sub>source: OpenStreetMap, Microsoft</sub>    |

## Site characteristics

|   id | parameter                          |     value | units         | source                    | doi                                                                                                                 |
|-----:|:-----------------------------------|----------:|:--------------|:--------------------------|:--------------------------------------------------------------------------------------------------------------------|
|    1 | latitude                           |   36.7197 | degrees_north | Hong et al. (2019)        | [https://doi.org/10.1186/s13021-019-0128-6](https://doi.org/10.1186/s13021-019-0128-6)                              |
|    2 | longitude                          |  127.434  | degrees_east  | Hong et al. (2019)        | [https://doi.org/10.1186/s13021-019-0128-6](https://doi.org/10.1186/s13021-019-0128-6)                              |
|    3 | ground_height                      |   60      | m             | J Hong, pers. comm.       | -                                                                                                                   |
|    4 | measurement_height_above_ground    |   19      | m             | J Hong, pers. comm.       | -                                                                                                                   |
|    5 | impervious_area_fraction           |    0.47   | 1             | J Hong, pers. comm.       | -                                                                                                                   |
|    6 | tree_area_fraction                 |    0.184  | 1             | J Hong, pers. comm.       | -                                                                                                                   |
|    7 | grass_area_fraction                |    0.333  | 1             | J Hong, pers. comm.       | -                                                                                                                   |
|    8 | bare_soil_area_fraction            |    0.013  | 1             | J Hong, pers. comm.       | -                                                                                                                   |
|    9 | water_area_fraction                |    0      | 1             | J Hong, pers. comm.       | -                                                                                                                   |
|   10 | roof_area_fraction                 |    0.133  | 1             | J Hong, pers. comm.       | -                                                                                                                   |
|   11 | road_area_fraction                 |    0.337  | 1             | J Hong, pers. comm.       | -                                                                                                                   |
|   12 | other_paved_area_fraction          |    0      | 1             | included in road fraction | -                                                                                                                   |
|   13 | building_mean_height               |    7.384  | m             | J Hong, pers. comm.       | -                                                                                                                   |
|   14 | tree_mean_height                   |    7.5    | m             | J Hong, pers. comm.       | -                                                                                                                   |
|   15 | roughness_length_momentum          |    1.06   | m             | estimated, see notes      | derived from morphology based on [Kanda et al. 2013](https://doi.org/10.1007/s10546-013-9818-x)                     |
|   16 | displacement_height                |    3.5    | m             | estimated, see notes      | derived from morphology based on [Kanda et al. 2013](https://doi.org/10.1007/s10546-013-9818-x)                     |
|   17 | canyon_height_width_ratio          |    0.32   | 1             | estimated, see notes      | derived from wall_to_plan_area_ratio and eq. 1 of [Masson et al. 2020](https://doi.org/10.1016/j.uclim.2019.100536) |
|   18 | wall_to_plan_area_ratio            |    0.551  | 1             | J Hong, pers. comm.       | -                                                                                                                   |
|   19 | average_albedo_at_midday           |    0.166  | 1             | median of observations    | -                                                                                                                   |
|   20 | resident_population_density        |  770      | person/km2    | Hong et al. (2019)        | [https://doi.org/10.1186/s13021-019-0128-6](https://doi.org/10.1186/s13021-019-0128-6)                              |
|   21 | anthropogenic_heat_flux_mean       |    3.3    | W/m2          | Varquez et al. (2021)     | [https://doi.org/10.1038/s41597-021-00850-w](https://doi.org/10.1038/s41597-021-00850-w)                            |
|   22 | topsoil_clay_fraction              |    0.19   | 1             | OpenLandMap               | [https://doi.org/10.5281/zenodo.2525663](https://doi.org/10.5281/zenodo.2525663)                                    |
|   23 | topsoil_sand_fraction              |    0.43   | 1             | OpenLandMap               | [https://doi.org/10.5281/zenodo.2525662](https://doi.org/10.5281/zenodo.2525662)                                    |
|   24 | topsoil_bulk_density               | 1360      | kg/m3         | OpenLandMap               | [https://doi.org/10.5281/zenodo.2525665](https://doi.org/10.5281/zenodo.2525665)                                    |
|   25 | building_height_standard_deviation |    4.1    | m             | estimated, see notes      | derived from avg. building height and eq. 2 of [Kanda et al. 2013](https://doi.org/10.1007/s10546-013-9818-x)       |

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

