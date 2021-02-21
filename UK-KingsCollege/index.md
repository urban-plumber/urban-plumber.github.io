# UK-KingsCollege

## Site observation metadata

|                           | observation_attributes                                                                                                                                                                                                                                                                                   |
|:--------------------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| title                     | URBAN-PLUMBER forcing data for UK-KingsCollege                                                                                                                                                                                                                                                           |
| summary                   | Combined observational and ERA5-derived surface meteorological data for Kings College, London, United Kingdom. For forcing of land surface models participating in Urban-PLUMBER. Data is for use by registered participants of Urban-PLUMBER in this project only. Do not distribute. All times in UTC. |
| sitename                  | UK-KingsCollege                                                                                                                                                                                                                                                                                          |
| version                   | v1                                                                                                                                                                                                                                                                                                       |
| conventions               | ALMA+CF.rev13                                                                                                                                                                                                                                                                                            |
| featureType               | timeSeries                                                                                                                                                                                                                                                                                               |
| time_coverage_start       | 2000-01-01 00:00:00                                                                                                                                                                                                                                                                                      |
| time_coverage_end         | 2014-01-01 00:00:00                                                                                                                                                                                                                                                                                      |
| time_analysis_start       | 2011-01-01 01:00:00                                                                                                                                                                                                                                                                                      |
| time_shown_in             | UTC                                                                                                                                                                                                                                                                                                      |
| local_utc_offset_hours    | 0.0                                                                                                                                                                                                                                                                                                      |
| timestep_interval_seconds | 3600.0                                                                                                                                                                                                                                                                                                   |
| timestep_number_spinup    | 96433                                                                                                                                                                                                                                                                                                    |
| timestep_number_analysis  | 26304                                                                                                                                                                                                                                                                                                    |
| observations_contact      | Sue Grimmond: c.s.grimmond@reading.ac.uk; Simone Kotthaus: kotthaus@ipsl.polytechnique.fr                                                                                                                                                                                                                |
| observations_reference    | Kotthaus and Grimmond (2013a): https://doi.org/10.1016/j.uclim.2013.10.002; Kotthaus and Grimmond (2013b): https://doi.org/10.1016/j.uclim.2013.10.001; Bjorkegren et al. (2015): https://doi.org/10.1016/                                                                                               |
| project_contact           | Mathew Lipson: m.lipson@unsw.edu.au, Sue Grimmond: c.s.grimmond@reading.ac.uk, Martin Best: martin.best@metoffice.gov.uk                                                                                                                                                                                 |
| date_created              | 2021-02-21 21:40:51                                                                                                                                                                                                                                                                                      |
| other_references          | ERA5: Copernicus Climate Change Service (C3S) (2017): https://cds.climate.copernicus.eu/cdsapp#!/home                                                                                                                                                                                                    |
| acknowledgements          | Contains modified Copernicus Climate Change Service Information (ERA5 hourly data on single levels). With thanks to all involved in collecting, processing and sharing observational data                                                                                                                |

## Site characteristics

[![site_photo.jpg](site_photo.jpg)](site_photo.jpg)
image source: None


|   id | parameter                       |      value | units         | source                        | doi                                                                                            |
|-----:|:--------------------------------|-----------:|:--------------|:------------------------------|:-----------------------------------------------------------------------------------------------|
|    1 | latitude                        |    51.5119 | degrees_north | Kotthaus and Grimmond (2013a) | [https://doi.org/10.1016/j.uclim.2013.10.002](https://doi.org/10.1016/j.uclim.2013.10.002)     |
|    2 | longitude                       |    -0.1166 | degrees_east  | Kotthaus and Grimmond (2013a) | [https://doi.org/10.1016/j.uclim.2013.10.003](https://doi.org/10.1016/j.uclim.2013.10.003)     |
|    3 | ground_height                   |    14.5    | m             | Bjorkegren et al. (2015)      | [http://doi.org/10.1016/j.atmosenv.2015.10.012](http://doi.org/10.1016/j.atmosenv.2015.10.012) |
|    4 | measurement_height_above_ground |    50.3    | m             | Ward et al. (2016)            | [https://doi.org/10.1016/j.uclim.2016.05.001](https://doi.org/10.1016/j.uclim.2016.05.001)     |
|    5 | impervious_area_fraction        |     0.81   | 1             | Ward et al. (2016)            | [https://doi.org/10.1016/j.uclim.2016.05.001](https://doi.org/10.1016/j.uclim.2016.05.001)     |
|    6 | tree_area_fraction              |     0.02   | 1             | Ward et al. (2016)            | [https://doi.org/10.1016/j.uclim.2016.05.001](https://doi.org/10.1016/j.uclim.2016.05.001)     |
|    7 | grass_area_fraction             |     0.03   | 1             | Ward et al. (2016)            | [https://doi.org/10.1016/j.uclim.2016.05.002](https://doi.org/10.1016/j.uclim.2016.05.002)     |
|    8 | bare_soil_area_fraction         |     0      | 1             | Ward et al. (2016)            | [https://doi.org/10.1016/j.uclim.2016.05.003](https://doi.org/10.1016/j.uclim.2016.05.003)     |
|    9 | water_area_fraction             |     0.14   | 1             | Ward et al. (2016)            | [https://doi.org/10.1016/j.uclim.2016.05.004](https://doi.org/10.1016/j.uclim.2016.05.004)     |
|   10 | roof_area_fraction              |     0.38   | 1             | Ward et al. (2016)            | [https://doi.org/10.1016/j.uclim.2016.05.005](https://doi.org/10.1016/j.uclim.2016.05.005)     |
|   11 | road_area_fraction              |   nan      | 1             | nan                           | [nan](nan)                                                                                     |
|   12 | footpath_area_fraction          |   nan      | 1             | nan                           | [nan](nan)                                                                                     |
|   13 | building_mean_height            |    22      | m             | Ward et al. (2016)            | [https://doi.org/10.1016/j.uclim.2016.05.005](https://doi.org/10.1016/j.uclim.2016.05.005)     |
|   14 | tree_mean_height                |    13.1    | m             | Ward et al. (2016)            | [https://doi.org/10.1016/j.uclim.2016.05.005](https://doi.org/10.1016/j.uclim.2016.05.005)     |
|   15 | roughness_length_momentum       |     1.9    | m             | Ward et al. (2016)            | [https://doi.org/10.1016/j.uclim.2016.05.005](https://doi.org/10.1016/j.uclim.2016.05.005)     |
|   16 | displacement_height             |    14.2    | m             | Ward et al. (2016)            | [https://doi.org/10.1016/j.uclim.2016.05.005](https://doi.org/10.1016/j.uclim.2016.05.005)     |
|   17 | canyon_height_width_ratio       |   nan      | 1             | nan                           | [nan](nan)                                                                                     |
|   18 | wall_to_plan_area_ratio         |   nan      | 1             | nan                           | [nan](nan)                                                                                     |
|   19 | average_albedo_at_midday        |   nan      | 1             | nan                           | -                                                                                              |
|   20 | resident_population_density     | 20458      | person/km2    | nan                           | [nan](nan)                                                                                     |
|   21 | anthropogenic_heat_flux_mean    |    69.2    | W/m2          | XXXX                          | [XXXX](XXXX)                                                                                   |
|   22 | topsoil_clay_fraction           |     0.25   | 1             | OpenLandMap                   | [https://doi.org/10.5281/zenodo.2525663](https://doi.org/10.5281/zenodo.2525663)               |
|   23 | topsoil_sand_fraction           |     0.46   | 1             | OpenLandMap                   | [https://doi.org/10.5281/zenodo.2525662](https://doi.org/10.5281/zenodo.2525662)               |
|   24 | topsoil_bulk_density            |  1010      | kg/m3         | OpenLandMap                   | [https://doi.org/10.5281/zenodo.2525665](https://doi.org/10.5281/zenodo.2525665)               |

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

### SWup diurnal qc

[![./obs_plots/SWup_obs_qc_diurnal.png](./obs_plots/SWup_obs_qc_diurnal.png)](./obs_plots/SWup_obs_qc_diurnal.png)

### LWup diurnal qc

[![./obs_plots/LWup_obs_qc_diurnal.png](./obs_plots/LWup_obs_qc_diurnal.png)](./obs_plots/LWup_obs_qc_diurnal.png)

### Qh diurnal qc

[![./obs_plots/Qh_obs_qc_diurnal.png](./obs_plots/Qh_obs_qc_diurnal.png)](./obs_plots/Qh_obs_qc_diurnal.png)

### Qle diurnal qc

[![./obs_plots/Qle_obs_qc_diurnal.png](./obs_plots/Qle_obs_qc_diurnal.png)](./obs_plots/Qle_obs_qc_diurnal.png)

