
# Lipowa Street, Łódź, Poland (PL-Lipowa)

## Site observations

[![./obs_plots/all_obs_qc.png](./obs_plots/all_obs_qc.png)](./obs_plots/all_obs_qc.png)

## Site observation metadata

|                           | observation_attributes                                                                                                                                                                                                                   |
|:--------------------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| title                     | URBAN-PLUMBER forcing data for PL-Lipowa                                                                                                                                                                                                 |
| summary                   | Observed and ERA5-derived surface meteorological data for Lipowa Street, Łódź, Poland. Data is for use by registered participants of Urban-PLUMBER in this project only. Do not distribute. All times in UTC.                            |
| sitename                  | PL-Lipowa                                                                                                                                                                                                                                |
| long_sitename             | Lipowa Street, Łódź, Poland                                                                                                                                                                                                              |
| version                   | v1                                                                                                                                                                                                                                       |
| conventions               | ALMA+CF.rev13                                                                                                                                                                                                                            |
| featureType               | timeSeries                                                                                                                                                                                                                               |
| time_coverage_start       | 1998-01-01 00:00:00                                                                                                                                                                                                                      |
| time_coverage_end         | 2012-12-31 23:00:00                                                                                                                                                                                                                      |
| time_analysis_start       | 2008-01-01 00:00:00                                                                                                                                                                                                                      |
| time_shown_in             | UTC                                                                                                                                                                                                                                      |
| local_utc_offset_hours    | 1.0                                                                                                                                                                                                                                      |
| timestep_interval_seconds | 3600.0                                                                                                                                                                                                                                   |
| timestep_number_spinup    | 87648                                                                                                                                                                                                                                    |
| timestep_number_analysis  | 43848                                                                                                                                                                                                                                    |
| observations_contact      | Wlodzimierz Pawlak: wlodzimierz.pawlak@geo.uni.lodz.pl, Krzysztof Fortuniak: krzysztof.fortuniak@geo.uni.lodz.pl                                                                                                                         |
| observations_reference    | Fortuniak, Pawlak and Siedlecki (2013): https://doi.org/10.1007/s10546-012-9762-1; Pawlak, Fortuniak, Siedlecki (2011): https://doi.org/10.1002/joc.2247; Offerle, Grimmond, Fortuniak, Pawlak (2006): https://doi.org/10.1175/JAM2319.1 |
| project_contact           | Mathew Lipson: m.lipson@unsw.edu.au, Sue Grimmond: c.s.grimmond@reading.ac.uk, Martin Best: martin.best@metoffice.gov.uk                                                                                                                 |
| date_created              | 2021-05-20 16:11:12                                                                                                                                                                                                                      |
| other_references          | ERA5: Copernicus Climate Change Service (C3S) (2017): https://cds.climate.copernicus.eu/cdsapp#!/home NCI Australia: http://doi.org/10.25914/5f48874388857                                                                               |
| acknowledgements          | Contains modified Copernicus Climate Change Service Information (ERA5 hourly data on single levels). Data from replica hosted by NCI Australia. With thanks to all involved in collecting, processing and hosting observational data     |
| comment                   | Missing forcing filled with PL-Narutowicza tower site where available. Precipitation from IMGW Łódź Lublinek. Subset of available years included here.                                                                                   |

## Site images

|                                             |                                             |    
|:-------------------------------------------:|:-------------------------------------------:|
| [![Region](./images/PL-Lipowa_region_map.jpg)](./images/PL-Lipowa_region_map.jpg)  <sub>source: OpenStreetMap</sub>    | [![site_map](./images/PL-Lipowa_site_map.jpg)](./images/PL-Lipowa_site_map.jpg) <sub>source: OpenStreetMap</sub>    |
| [![site_photo](./images/PL-Lipowa_site_photo.jpg)](./images/PL-Lipowa_site_photo.jpg) <sub>source: Włodzimierz Pawlak</sub>  | [![site_sat](./images/PL-Lipowa_site_sat.jpg)](./images/PL-Lipowa_site_sat.jpg) <sub>source: OpenStreetMap, Microsoft</sub>    |

## Site characteristics

|   id | parameter                          |      value | units         | source                               | doi                                                                                                                               |
|-----:|:-----------------------------------|-----------:|:--------------|:-------------------------------------|:----------------------------------------------------------------------------------------------------------------------------------|
|    1 | latitude                           |    51.7625 | degrees_north | Fortuniak et al. (2013)              | [http://doi.org/10.1007/s10546-012-9762-1](http://doi.org/10.1007/s10546-012-9762-1)                                              |
|    2 | longitude                          |    19.4453 | degrees_east  | Fortuniak et al. (2013)              | [http://doi.org/10.1007/s10546-012-9762-1](http://doi.org/10.1007/s10546-012-9762-1)                                              |
|    3 | ground_height                      |   204      | m             | Fortuniak et al. (2013)              | [http://doi.org/10.1007/s10546-012-9762-1](http://doi.org/10.1007/s10546-012-9762-1)                                              |
|    4 | measurement_height_above_ground    |    37      | m             | Offerle et al. (2006)                | [https://doi.org/10.1175/JAM2319.1](https://doi.org/10.1175/JAM2319.1)                                                            |
|    5 | impervious_area_fraction           |     0.76   | 1             | Offerle et al. (2006)                | [https://doi.org/10.1175/JAM2319.1](https://doi.org/10.1175/JAM2319.1)                                                            |
|    6 | tree_area_fraction                 |     0.16   | 1             | estimated, see notes                 | derived from 0.24 vegetation (tree and grass) in [Offerle et al. (2006)](https://doi.org/10.1175/JAM2319.1) and satellite imagery |
|    7 | grass_area_fraction                |     0.08   | 1             | estimated, see notes                 | derived from 0.24 vegetation (tree and grass) in [Offerle et al. (2006)](https://doi.org/10.1175/JAM2319.1) and satellite imagery |
|    8 | bare_soil_area_fraction            |     0      | 1             | Offerle et al. (2006)                | [https://doi.org/10.1175/JAM2319.1](https://doi.org/10.1175/JAM2319.1)                                                            |
|    9 | water_area_fraction                |     0      | 1             | Offerle et al. (2006)                | [https://doi.org/10.1175/JAM2319.1](https://doi.org/10.1175/JAM2319.1)                                                            |
|   10 | roof_area_fraction                 |     0.35   | 1             | Offerle et al. (2006)                | [https://doi.org/10.1175/JAM2319.1](https://doi.org/10.1175/JAM2319.1)                                                            |
|   11 | road_area_fraction                 |     0.21   | 1             | estimated, see notes                 | derived from 0.41 impervious (road and other) in [Offerle et al. (2006)](https://doi.org/10.1175/JAM2319.1) and satellite imagery |
|   12 | other_paved_area_fraction          |     0.2    | 1             | estimated, see notes                 | derived from 0.41 impervious (road and other) in [Offerle et al. (2006)](https://doi.org/10.1175/JAM2319.1) and satellite imagery |
|   13 | building_mean_height               |    10.2    | m             | Offerle et al. (2006)                | [https://doi.org/10.1175/JAM2319.1](https://doi.org/10.1175/JAM2319.1)                                                            |
|   14 | tree_mean_height                   |    12.5    | m             | Pawlak, pers. comms                  | -                                                                                                                                 |
|   15 | roughness_length_momentum          |     1.7    | m             | Offerle et al. (2006) (anemometric)  | [https://doi.org/10.1175/JAM2319.1](https://doi.org/10.1175/JAM2319.1)                                                            |
|   16 | displacement_height                |     7.4    | m             | Offerle et al. (2006) (morphometric) | [https://doi.org/10.1175/JAM2319.1](https://doi.org/10.1175/JAM2319.1)                                                            |
|   17 | canyon_height_width_ratio          |     0.75   | 1             | Offerle et al. (2006)                | [https://doi.org/10.1175/JAM2319.1](https://doi.org/10.1175/JAM2319.1)                                                            |
|   18 | wall_to_plan_area_ratio            |     1.05   | 1             | estimated, see notes                 | derived from canyon h/w ratio and eq 1 from [Masson et al (2020)](htpps://doi.org/10.1016/j.uclim.2019.100536)                    |
|   19 | average_albedo_at_midday           |     0.085  | 1             | median of observations               | -                                                                                                                                 |
|   20 | resident_population_density        | 10380      | person/km2    | Pawlak, pers. comms                  | derived from Statistics of Łódź, 2018                                                                                             |
|   21 | anthropogenic_heat_flux_mean       |     7.1    | W/m2          | Varquez et al (2021)                 | [https://doi.org/10.1038/s41597-021-00850-w](https://doi.org/10.1038/s41597-021-00850-w)                                          |
|   22 | topsoil_clay_fraction              |     0.16   | 1             | OpenLandMap                          | [https://doi.org/10.5281/zenodo.2525663](https://doi.org/10.5281/zenodo.2525663)                                                  |
|   23 | topsoil_sand_fraction              |     0.46   | 1             | OpenLandMap                          | [https://doi.org/10.5281/zenodo.2525662](https://doi.org/10.5281/zenodo.2525662)                                                  |
|   24 | topsoil_bulk_density               |  1240      | kg/m3         | OpenLandMap                          | [https://doi.org/10.5281/zenodo.2525665](https://doi.org/10.5281/zenodo.2525665)                                                  |
|   25 | building_height_standard_deviation |     7.01   | m             | estimated, see notes                 | derived from morphology using eq. 2 of [Kanda et al. (2013)](https://doi.org/10.1007/s10546-013-9818-x)                           |
|   26 | roughness_length_momentum_mac      |     0.94   | m             | Macdonald method                     | derived from morphology using eq. 26 of [Macdonald et al. (1998)](https://doi.org/10.1016/S1352-2310(97)00403-2)                  |
|   27 | displacement_height_mac            |     6.26   | m             | Macdonald method                     | derived from morphology using eq. 23 of [Macdonald et al. (1998)](https://doi.org/10.1016/S1352-2310(97)00403-2)                  |
|   28 | roughness_length_momentum_kanda    |     1.58   | m             | Kanda method                         | derived from morphology using eq. 12a of [Kanda et al. (2013)](https://doi.org/10.1007/s10546-013-9818-x)                         |
|   29 | displacement_height_kanda          |    15.71   | m             | Kanda method                         | derived from morphology using eq. 10a of [Kanda et al. (2013)](https://doi.org/10.1007/s10546-013-9818-x)                         |

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

