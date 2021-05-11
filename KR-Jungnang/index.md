
# Jungnang, Seoul, South Korea (KR-Jungnang)

## Site observation metadata

|                           | observation_attributes                                                                                                                                                                                                               |
|:--------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| title                     | URBAN-PLUMBER forcing data for KR-Jungnang                                                                                                                                                                                           |
| summary                   | Observed and ERA5-derived surface meteorological data for Jungnang, Seoul, South Korea. Data is for use by registered participants of Urban-PLUMBER in this project only. Do not distribute. All times in UTC.                       |
| sitename                  | KR-Jungnang                                                                                                                                                                                                                          |
| long_sitename             | Jungnang, Seoul, South Korea                                                                                                                                                                                                         |
| version                   | v1                                                                                                                                                                                                                                   |
| conventions               | ALMA+CF.rev13                                                                                                                                                                                                                        |
| featureType               | timeSeries                                                                                                                                                                                                                           |
| time_coverage_start       | 2007-01-01 00:00:00                                                                                                                                                                                                                  |
| time_coverage_end         | 2019-04-29 06:30:00                                                                                                                                                                                                                  |
| time_analysis_start       | 2017-01-24 16:00:00                                                                                                                                                                                                                  |
| time_shown_in             | UTC                                                                                                                                                                                                                                  |
| local_utc_offset_hours    | 9.0                                                                                                                                                                                                                                  |
| timestep_interval_seconds | 1800.0                                                                                                                                                                                                                               |
| timestep_number_spinup    | 176480                                                                                                                                                                                                                               |
| timestep_number_analysis  | 39582                                                                                                                                                                                                                                |
| observations_contact      | Jinkyu Hong (jhong@yonsei.ac.kr), Je-Woo Hong (jwhong@kei.re.kr)                                                                                                                                                                     |
| observations_reference    | https://doi.org/10.22647/EAPL-OC_JN2021                                                                                                                                                                                              |
| project_contact           | Mathew Lipson: m.lipson@unsw.edu.au, Sue Grimmond: c.s.grimmond@reading.ac.uk, Martin Best: martin.best@metoffice.gov.uk                                                                                                             |
| date_created              | 2021-05-10 19:20:40                                                                                                                                                                                                                  |
| other_references          | ERA5: Copernicus Climate Change Service (C3S) (2017): https://cds.climate.copernicus.eu/cdsapp#!/home NCI Australia: http://doi.org/10.25914/5f48874388857                                                                           |
| acknowledgements          | Contains modified Copernicus Climate Change Service Information (ERA5 hourly data on single levels). Data from replica hosted by NCI Australia. With thanks to all involved in collecting, processing and hosting observational data |
| comment                   | No bias correction applied to ERA5 derived precipitation (no nearby long-term and complete GHCND site data)                                                                                                                          |

## Site images

|                                             |                                             |    
|:-------------------------------------------:|:-------------------------------------------:|
| [![Region](./images/KR-Jungnang_region_map.jpg)](./images/KR-Jungnang_region_map.jpg)  <sub>source: OpenStreetMap</sub>    | [![site_map](./images/KR-Jungnang_site_map.jpg)](./images/KR-Jungnang_site_map.jpg) <sub>source: OpenStreetMap</sub>    |
| [![site_photo](./images/KR-Jungnang_site_photo.jpg)](./images/KR-Jungnang_site_photo.jpg) <sub>source: Keunmin Lee</sub>  | [![site_sat](./images/KR-Jungnang_site_sat.jpg)](./images/KR-Jungnang_site_sat.jpg) <sub>source: OpenStreetMap, Microsoft</sub>    |

## Site characteristics

|   id | parameter                          |      value | units         | source                                   | doi                                                                                                                 |
|-----:|:-----------------------------------|-----------:|:--------------|:-----------------------------------------|:--------------------------------------------------------------------------------------------------------------------|
|    1 | latitude                           |    37.5907 | degrees_north | J Hong, pers. comm                       | -                                                                                                                   |
|    2 | longitude                          |   127.079  | degrees_east  | J Hong, pers. comm                       | -                                                                                                                   |
|    3 | ground_height                      |    22      | m             | J Hong, pers. comm                       | -                                                                                                                   |
|    4 | measurement_height_above_ground    |    41.5    | m             | J Hong, pers. comm                       | -                                                                                                                   |
|    5 | impervious_area_fraction           |     0.965  | 1             | J Hong, pers. comm                       | -                                                                                                                   |
|    6 | tree_area_fraction                 |     0      | 1             | J Hong, pers. comm                       | -                                                                                                                   |
|    7 | grass_area_fraction                |     0.019  | 1             | J Hong, pers. comm                       | -                                                                                                                   |
|    8 | bare_soil_area_fraction            |     0.016  | 1             | J Hong, pers. comm                       | -                                                                                                                   |
|    9 | water_area_fraction                |     0      | 1             | J Hong, pers. comm                       | -                                                                                                                   |
|   10 | roof_area_fraction                 |     0.588  | 1             | J Hong, pers. comm                       | -                                                                                                                   |
|   11 | road_area_fraction                 |     0.377  | 1             | J Hong, pers. comm                       | -                                                                                                                   |
|   12 | other_paved_area_fraction          |     0      | 1             | included in road fraction                | -                                                                                                                   |
|   13 | building_mean_height               |     8.648  | m             | J Hong, pers. comm                       | -                                                                                                                   |
|   14 | tree_mean_height                   |     0      | m             | J Hong, pers. comm                       | -                                                                                                                   |
|   15 | roughness_length_momentum          |     0.9    | m             | J Hong, pers. comm (morphometric method) | -                                                                                                                   |
|   16 | displacement_height                |     3.9    | m             | J Hong, pers. comm (morphometric method) | -                                                                                                                   |
|   17 | canyon_height_width_ratio          |     1      | 1             | estimated, see notes                     | derived from wall_to_plan_area_ratio and eq. 1 of [Masson et al. 2020](https://doi.org/10.1016/j.uclim.2019.100536) |
|   18 | wall_to_plan_area_ratio            |     0.825  | 1             | J Hong, pers. comm                       | -                                                                                                                   |
|   19 | average_albedo_at_midday           |     0.12   | 1             | median of observations                   | -                                                                                                                   |
|   20 | resident_population_density        | 21000      | person/km2    | J Hong, pers. comm                       | -                                                                                                                   |
|   21 | anthropogenic_heat_flux_mean       |    92.7    | W/m2          | Varquez et al. (2021)                    | [https://doi.org/10.1038/s41597-021-00850-w](https://doi.org/10.1038/s41597-021-00850-w)                            |
|   22 | topsoil_clay_fraction              |     0.2    | 1             | OpenLandMap                              | [https://doi.org/10.5281/zenodo.2525663](https://doi.org/10.5281/zenodo.2525663)                                    |
|   23 | topsoil_sand_fraction              |     0.4    | 1             | OpenLandMap                              | [https://doi.org/10.5281/zenodo.2525662](https://doi.org/10.5281/zenodo.2525662)                                    |
|   24 | topsoil_bulk_density               |  1270      | kg/m3         | OpenLandMap                              | [https://doi.org/10.5281/zenodo.2525665](https://doi.org/10.5281/zenodo.2525665)                                    |
|   25 | building_height_standard_deviation |     5.4    | m             | estimated, see notes                     | derived from avg. building height and eq. 2 of [Kanda et al. 2013](https://doi.org/10.1007/s10546-013-9818-x)       |
|   26 | roughness_length_momentum_mac      |     0.13   | m             | Macdonald method                         | derived from morphology using eq. 26 of [Macdonald et al. (1998)](https://doi.org/10.1016/S1352-2310(97)00403-2)    |
|   27 | displacement_height_mac            |     7.16   | m             | Macdonald method                         | derived from morphology using eq. 23 of [Macdonald et al. (1998)](https://doi.org/10.1016/S1352-2310(97)00403-2)    |
|   28 | roughness_length_momentum_kanda    |     0.41   | m             | Kanda method                             | derived from morphology using eq. 12a of [Kanda et al. (2013)](https://doi.org/10.1007/s10546-013-9818-x)           |
|   29 | displacement_height_kanda          |    15.35   | m             | Kanda method                             | derived from morphology using eq. 10a of [Kanda et al. (2013)](https://doi.org/10.1007/s10546-013-9818-x)           |

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

