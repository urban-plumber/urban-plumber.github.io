# US-WestPhoenix

## Site observation metadata

|                           | observation_attributes                                                                                                                                                                                                                                                                                  |
|:--------------------------|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| title                     | URBAN-PLUMBER forcing data for US-WestPhoenix                                                                                                                                                                                                                                                           |
| summary                   | Combined observational and ERA5-derived surface meteorological data for West Phoenix, Arizona, United States. For forcing of land surface models participating in Urban-PLUMBER. Data is for use by registered participants of Urban-PLUMBER in this project only. Do not distribute. All times in UTC. |
| sitename                  | US-WestPhoenix                                                                                                                                                                                                                                                                                          |
| version                   | v1                                                                                                                                                                                                                                                                                                      |
| conventions               | ALMA+CF.rev13                                                                                                                                                                                                                                                                                           |
| featureType               | timeSeries                                                                                                                                                                                                                                                                                              |
| time_coverage_start       | 2001-01-01 00:00:00                                                                                                                                                                                                                                                                                     |
| time_coverage_end         | 2013-01-01 06:30:00                                                                                                                                                                                                                                                                                     |
| time_analysis_start       | 2011-12-16 18:30:00                                                                                                                                                                                                                                                                                     |
| time_shown_in             | UTC                                                                                                                                                                                                                                                                                                     |
| local_utc_offset_hours    | -7.0                                                                                                                                                                                                                                                                                                    |
| timestep_interval_seconds | 1800.0                                                                                                                                                                                                                                                                                                  |
| timestep_number_spinup    | 192085                                                                                                                                                                                                                                                                                                  |
| timestep_number_analysis  | 18313                                                                                                                                                                                                                                                                                                   |
| observations_contact      | Stevan Earl: caplter.data@asu.edu, Winston Chow: winstonchow@smu.edu.sg                                                                                                                                                                                                                                 |
| observations_reference    | Chow (2017): https://doi.org/10.6073/pasta/fed17d67583eda16c439216ca40b0669; Chow et al (2014): https://doi.org/10.1002/joc.3947                                                                                                                                                                        |
| project_contact           | Mathew Lipson: m.lipson@unsw.edu.au, Sue Grimmond: c.s.grimmond@reading.ac.uk, Martin Best: martin.best@metoffice.gov.uk                                                                                                                                                                                |
| date_created              | 2021-02-22 22:24:17                                                                                                                                                                                                                                                                                     |
| other_references          | ERA5: Copernicus Climate Change Service (C3S) (2017): https://cds.climate.copernicus.eu/cdsapp#!/home                                                                                                                                                                                                   |
| acknowledgements          | Contains modified Copernicus Climate Change Service Information (ERA5 hourly data on single levels). With thanks to all involved in collecting, processing and sharing observational data                                                                                                               |

## Site characteristics

[![site_photo.jpg](site_photo.jpg)](site_photo.jpg)
image source: None


|   id | parameter                       |     value | units         | source               | doi                                                                              |
|-----:|:--------------------------------|----------:|:--------------|:---------------------|:---------------------------------------------------------------------------------|
|    1 | latitude                        |   33.4839 | degrees_north | Chow et al. (2014)   | [https://doi.org/10.1002/joc.3947](https://doi.org/10.1002/joc.3947)             |
|    2 | longitude                       | -112.143  | degrees_east  | Chow et al. (2014)   | [https://doi.org/10.1002/joc.3947](https://doi.org/10.1002/joc.3947)             |
|    3 | ground_height                   |  340      | m             | Chow et al. (2014)   | [https://doi.org/10.1002/joc.3948](https://doi.org/10.1002/joc.3948)             |
|    4 | measurement_height_above_ground |   22.1    | m             | Chow et al. (2014)   | [https://doi.org/10.1002/joc.3949](https://doi.org/10.1002/joc.3949)             |
|    5 | impervious_area_fraction        |    0.4844 | 1             | Chow et al. (2014)   | [https://doi.org/10.1002/joc.3950](https://doi.org/10.1002/joc.3950)             |
|    6 | tree_area_fraction              |    0.0461 | 1             | Chow et al. (2014)   | [https://doi.org/10.1002/joc.3951](https://doi.org/10.1002/joc.3951)             |
|    7 | grass_area_fraction             |    0.1001 | 1             | Chow et al. (2014)   | [https://doi.org/10.1002/joc.3952](https://doi.org/10.1002/joc.3952)             |
|    8 | bare_soil_area_fraction         |    0.3683 | 1             | Chow et al. (2014)   | [https://doi.org/10.1002/joc.3953](https://doi.org/10.1002/joc.3953)             |
|    9 | water_area_fraction             |    0.0011 | 1             | Chow et al. (2014)   | [https://doi.org/10.1002/joc.3954](https://doi.org/10.1002/joc.3954)             |
|   10 | roof_area_fraction              |    0.2642 | 1             | Chow et al. (2014)   | [https://doi.org/10.1002/joc.3955](https://doi.org/10.1002/joc.3955)             |
|   11 | road_area_fraction              |    0.2202 | 1             | Chow et al. (2014)   | [https://doi.org/10.1002/joc.3956](https://doi.org/10.1002/joc.3956)             |
|   12 | footpath_area_fraction          |    0      | 1             | Chow et al. (2014)   | [https://doi.org/10.1002/joc.3957](https://doi.org/10.1002/joc.3957)             |
|   13 | building_mean_height            |    4.5    | m             | Chow et al. (2014)   | [https://doi.org/10.1002/joc.3958](https://doi.org/10.1002/joc.3958)             |
|   14 | tree_mean_height                |    4      | m             | Chow et al. (2014)   | [https://doi.org/10.1002/joc.3959](https://doi.org/10.1002/joc.3959)             |
|   15 | roughness_length_momentum       |    0.6    | m             | Chow pers. comm.     | [nan](nan)                                                                       |
|   16 | displacement_height             |    3      | m             | Chow pers. comm.     | [nan](nan)                                                                       |
|   17 | canyon_height_width_ratio       |    0.4    | 1             | Chow et al. (2014)   | [https://doi.org/10.1002/joc.3959](https://doi.org/10.1002/joc.3959)             |
|   18 | wall_to_plan_area_ratio         |    0.59   | 1             | estimated, see notes | [nan](nan)                                                                       |
|   19 | average_albedo_at_midday        |    0.171  | 1             | Chow et al. (2014)   | -                                                                                |
|   20 | resident_population_density     |  nan      | person/km2    | XXXX                 | [nan](nan)                                                                       |
|   21 | anthropogenic_heat_flux_mean    |   21.1    | W/m2          | XXXX                 | [nan](nan)                                                                       |
|   22 | topsoil_clay_fraction           |    0.2    | 1             | OpenLandMap          | [https://doi.org/10.5281/zenodo.2525663](https://doi.org/10.5281/zenodo.2525663) |
|   23 | topsoil_sand_fraction           |    0.4    | 1             | OpenLandMap          | [https://doi.org/10.5281/zenodo.2525662](https://doi.org/10.5281/zenodo.2525662) |
|   24 | topsoil_bulk_density            | 1500      | kg/m3         | OpenLandMap          | [https://doi.org/10.5281/zenodo.2525665](https://doi.org/10.5281/zenodo.2525665) |

## Site observations

[![./obs_plots/all_obs_qc.png](./obs_plots/all_obs_qc.png)](./obs_plots/all_obs_qc.png)

## Site forcing

### SWdown forcing

[![./obs_plots/SWdown_gapfilled_forcing.png](./obs_plots/SWdown_gapfilled_forcing.png)](./obs_plots/SWdown_gapfilled_forcing.png)

### LWdown forcing

[![./obs_plots/LWdown_gapfilled_forcing.png](./obs_plots/LWdown_gapfilled_forcing.png)](./obs_plots/LWdown_gapfilled_forcing.png)

### Tair forcing

[![./obs_plots/Tair_gapfilled_forcing.png](./obs_plots/Tair_gapfilled_forcing.png)](./obs_plots/Tair_gapfilled_forcing.png)

### Qair forcing

[![./obs_plots/Qair_gapfilled_forcing.png](./obs_plots/Qair_gapfilled_forcing.png)](./obs_plots/Qair_gapfilled_forcing.png)

### PSurf forcing

[![./obs_plots/PSurf_gapfilled_forcing.png](./obs_plots/PSurf_gapfilled_forcing.png)](./obs_plots/PSurf_gapfilled_forcing.png)

### Rainf forcing

[![./obs_plots/Rainf_gapfilled_forcing.png](./obs_plots/Rainf_gapfilled_forcing.png)](./obs_plots/Rainf_gapfilled_forcing.png)

### Snowf forcing

[![./obs_plots/Snowf_gapfilled_forcing.png](./obs_plots/Snowf_gapfilled_forcing.png)](./obs_plots/Snowf_gapfilled_forcing.png)

### Wind_N forcing

[![./obs_plots/Wind_N_gapfilled_forcing.png](./obs_plots/Wind_N_gapfilled_forcing.png)](./obs_plots/Wind_N_gapfilled_forcing.png)

### Wind_E forcing

[![./obs_plots/Wind_E_gapfilled_forcing.png](./obs_plots/Wind_E_gapfilled_forcing.png)](./obs_plots/Wind_E_gapfilled_forcing.png)

## Quality control (qc) and gap filling procedure


**QC process on observations**
 
 - remove values outside the ALMAv3 protocol expected range values
 - remove night periods for shortwave between civil twilight times for site latitude and longitude
 - remove constant values of 4 or more timesteps (excluding rainfall and snowfall)
 - remove outliers by applying a filter for values outside 5 standard deviations for each hour in a rolling 30 day window. Applying that filter until no outliers exist.
 
**Gap-filling process**
  
 - for gaps of 2 hours or less, fill with linear interpolation of adjacent observation
 - fill remaining gaps with bias-corrected, ERA5 derived data (see below)
 - prepend flux tower data period with 10-years of ERA5 derived data (used for model spinup)
 
**ERA5 bias correction**
 
 - for downwelling longwave, temperature, humidity and pressure: calculate the mean bias between ERA5 and flux tower data in a 30-day rolling window for every hour and each day of the year, and apply that bias correction to all ERA5 data. For periods not covered by observations, linearly interpoloate between known biases for each hour seperately.
 - for rainfall: calculate total precipitation in a 10-year period and calculate the ratio between ERA5 data and the nearest GHCN-D station and apply that correction factor to ERA5 data.
 - for wind: apply wind log profile correction based on ERA5 reference height (10m) and flux tower measurement heights, plus ERA5 and local roughness and displacement.
 - for downwelling shortwave: use ERA5 data without correction

### SWdown diurnal qc

[![./obs_plots/SWdown_obs_qc_diurnal.png](./obs_plots/SWdown_obs_qc_diurnal.png)](./obs_plots/SWdown_obs_qc_diurnal.png)

### LWdown diurnal qc

[![./obs_plots/LWdown_obs_qc_diurnal.png](./obs_plots/LWdown_obs_qc_diurnal.png)](./obs_plots/LWdown_obs_qc_diurnal.png)

### Tair diurnal qc

[![./obs_plots/Tair_obs_qc_diurnal.png](./obs_plots/Tair_obs_qc_diurnal.png)](./obs_plots/Tair_obs_qc_diurnal.png)

### Qair diurnal qc

[![./obs_plots/Qair_obs_qc_diurnal.png](./obs_plots/Qair_obs_qc_diurnal.png)](./obs_plots/Qair_obs_qc_diurnal.png)

### PSurf diurnal qc

[![./obs_plots/PSurf_obs_qc_diurnal.png](./obs_plots/PSurf_obs_qc_diurnal.png)](./obs_plots/PSurf_obs_qc_diurnal.png)

### Wind_N diurnal qc

[![./obs_plots/Wind_N_obs_qc_diurnal.png](./obs_plots/Wind_N_obs_qc_diurnal.png)](./obs_plots/Wind_N_obs_qc_diurnal.png)

### Wind_E diurnal qc

[![./obs_plots/Wind_E_obs_qc_diurnal.png](./obs_plots/Wind_E_obs_qc_diurnal.png)](./obs_plots/Wind_E_obs_qc_diurnal.png)
