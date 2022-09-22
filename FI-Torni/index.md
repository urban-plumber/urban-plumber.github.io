
# Hotel Torni, Helsinki, Finland (FI-Torni)

### Jump to section:

 - [Site forcing metadata](#site-forcing-metadata)
 - [Site images](#site-images)
 - [Site characteristics](#site-characteristics)
 - [Site forcing](#site-forcing)
 - [Quality control and gap filling procedure](#quality-control-qc-and-gap-filling-procedure)
 - [Bias correction diurnal comparison](#bias-correction-diurnal-comparison)

## Observations (before additional gap filling)

[![./obs_plots/all_obs_qc.png](./obs_plots/all_obs_qc.png)](./obs_plots/all_obs_qc.png)

## Site forcing metadata

|                           | observation_attributes                                                                                                                                                                                                                                                                                          |
|:--------------------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| title                     | Continuous meterological forcing from FI-Torni                                                                                                                                                                                                                                                                  |
| summary                   | Flux tower observations from Hotel Torni, Helsinki, Finland after quality control, with gap filling from bias corrected ERA5 surface meteorological data. Developed for use in the Urban-PLUMBER model evaluation project. Attribute any use to "Harmonized, gap-filled dataset from 20 urban flux tower sites" |
| sitename                  | FI-Torni                                                                                                                                                                                                                                                                                                        |
| long_sitename             | Hotel Torni, Helsinki, Finland                                                                                                                                                                                                                                                                                  |
| version                   | v1                                                                                                                                                                                                                                                                                                              |
| keywords                  | urban, flux tower, eddy covariance, observations                                                                                                                                                                                                                                                                |
| conventions               | ALMA, CF, ACDD-1.3                                                                                                                                                                                                                                                                                              |
| featureType               | timeSeries                                                                                                                                                                                                                                                                                                      |
| license                   | CC-BY-4.0: https://creativecommons.org/licenses/by/4.0/                                                                                                                                                                                                                                                         |
| time_coverage_start       | 2000-01-01 00:00:00                                                                                                                                                                                                                                                                                             |
| time_coverage_end         | 2013-12-31 22:00:00                                                                                                                                                                                                                                                                                             |
| time_analysis_start       | 2010-12-31 22:30:00                                                                                                                                                                                                                                                                                             |
| time_shown_in             | UTC                                                                                                                                                                                                                                                                                                             |
| local_utc_offset_hours    | 2.0                                                                                                                                                                                                                                                                                                             |
| timestep_interval_seconds | 1800.0                                                                                                                                                                                                                                                                                                          |
| timestep_number_spinup    | 192861                                                                                                                                                                                                                                                                                                          |
| timestep_number_analysis  | 52608                                                                                                                                                                                                                                                                                                           |
| project                   | Urban-PLUMBER multi-site model evaluation project for urban areas                                                                                                                                                                                                                                               |
| references                | Data from "Harmonized gap-filled dataset from 20 urban flux tower sites": https://doi.org/10.5281/zenodo.5517550                                                                                                                                                                                                |
| project_contact           | Mathew Lipson (m.lipson@unsw.edu.au), Sue Grimmond (c.s.grimmond@reading.ac.uk), Martin Best (martin.best@metoffice.gov.uk)                                                                                                                                                                                     |
| observations_contact      | Leena Järvi (leena.jarvi@helsinki.fi)                                                                                                                                                                                                                                                                           |
| observations_reference    | Järvi, Rannik, Kokkonen, Kurppa, Karppinen, Kouznetsov, Rantala, Vesala and Wood (2018): https://doi.org/10.5194/amt-11-5421-2018; Nordbo, Järvi, Haapanala, Moilanen, Vesala, (2013): https://doi.org/10.1007/s10546-012-9773-y                                                                                |
| date_created              | 2022-09-22 15:26:53                                                                                                                                                                                                                                                                                             |
| source                    | https://github.com/matlipson/urban-plumber_pipeline                                                                                                                                                                                                                                                             |
| other_references          | ERA5: Copernicus Climate Change Service (C3S) (2017): https://cds.climate.copernicus.eu/cdsapp#!/home NCI Australia: http://doi.org/10.25914/5f48874388857                                                                                                                                                      |
| acknowledgements          | Contains modified Copernicus Climate Change Service Information 2021 (ERA5 hourly data on single levels). Data from replica hosted by NCI Australia.                                                                                                                                                            |
| comment                   | Flow distortion in sectors 40-150 degrees excluded from flux analyses. Air pressure, relative humidity, wind and rainfall filled from nearby Kumpula tower.                                                                                                                                                     |
| history                   | v0.9 (2021-09-08): beta issue; v1 (2022-09-15): with publication in ESSD                                                                                                                                                                                                                                        |

## Site images

|                                             |                                             |    
|:-------------------------------------------:|:-------------------------------------------:|
| [![Region](./images/FI-Torni_region_map.jpg)](./images/FI-Torni_region_map.jpg)  <sub>Regional map. © OpenStreetMap</sub>    | [![site_map](./images/FI-Torni_site_map.jpg)](./images/FI-Torni_site_map.jpg) <sub>Site map with 500 m radius. © OpenStreetMap</sub>    |
| [![site_photo](./images/FI-Torni_site_photo.jpg)](./images/FI-Torni_site_photo.jpg) <sub>Site photo. © L. Järvi</sub>    | [![site_sat](./images/FI-Torni_site_sat.jpg)](./images/FI-Torni_site_sat.jpg) <sub>Site aerial photo with 500 m radius. © OpenStreetMap, Microsoft</sub>    |

<sub>Maps developed from:
    Hrisko, J. (2020). [Geographic Visualizations in Python with Cartopy](https://makersportal.com/blog/2020/4/24/geographic-visualizations-in-python-with-cartopy). Maker Portal.</sub> 

## Site characteristics

|   id | parameter                          |     value | units         | source                              | doi                                                                                                                                                                                             |
|-----:|:-----------------------------------|----------:|:--------------|:------------------------------------|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|    1 | latitude                           |   60.1678 | degrees_north | Karsisto et al. (2016)              | [https://doi.org/10.1002/qj.2659](https://doi.org/10.1002/qj.2659)                                                                                                                              |
|    2 | longitude                          |   24.9387 | degrees_east  | Karsisto et al. (2016)              | [https://doi.org/10.1002/qj.2659](https://doi.org/10.1002/qj.2659)                                                                                                                              |
|    3 | ground_height                      |   15.2    | m             | Karsisto et al. (2016)              | [https://doi.org/10.1002/qj.2659](https://doi.org/10.1002/qj.2659)                                                                                                                              |
|    4 | measurement_height_above_ground    |   60      | m             | Karsisto et al. (2016)              | [https://doi.org/10.1002/qj.2659](https://doi.org/10.1002/qj.2659)                                                                                                                              |
|    5 | impervious_area_fraction           |    0.77   | 1             | Karsisto et al. (2016)              | [https://doi.org/10.1002/qj.2659](https://doi.org/10.1002/qj.2659)                                                                                                                              |
|    6 | tree_area_fraction                 |    0.15   | 1             | Karsisto et al. (2016)              | [https://doi.org/10.1002/qj.2659](https://doi.org/10.1002/qj.2659)                                                                                                                              |
|    7 | grass_area_fraction                |    0.07   | 1             | Karsisto et al. (2016)              | [https://doi.org/10.1002/qj.2659](https://doi.org/10.1002/qj.2659)                                                                                                                              |
|    8 | bare_soil_area_fraction            |    0      | 1             | Karsisto et al. (2016)              | [https://doi.org/10.1002/qj.2659](https://doi.org/10.1002/qj.2659)                                                                                                                              |
|    9 | water_area_fraction                |    0.01   | 1             | Karsisto et al. (2016)              | [https://doi.org/10.1002/qj.2659](https://doi.org/10.1002/qj.2659)                                                                                                                              |
|   10 | roof_area_fraction                 |    0.37   | 1             | Karsisto et al. (2016)              | [https://doi.org/10.1002/qj.2659](https://doi.org/10.1002/qj.2659)                                                                                                                              |
|   11 | road_area_fraction                 |    0.25   | 1             | estimated, see notes                | calculated using OpenStreetMap data in same footprint as [Nordbo et al. (2015)](10.1016/j.uclim.2015.05.004)                                                                                    |
|   12 | other_paved_area_fraction          |    0.15   | 1             | estimated, see notes                | calculated using OpenStreetMap data in same footprint as [Nordbo et al. (2015)](10.1016/j.uclim.2015.05.004)                                                                                    |
|   13 | building_mean_height               |   17.9    | m             | Karsisto et al. (2016)              | [https://doi.org/10.1002/qj.2659](https://doi.org/10.1002/qj.2659)                                                                                                                              |
|   14 | tree_mean_height                   |    8.3    | m             | Karsisto et al. (2016)              | [https://doi.org/10.1002/qj.2659](https://doi.org/10.1002/qj.2659)                                                                                                                              |
|   15 | roughness_length_momentum          |    1.4    | m             | Nordbo et al. (2013) (morphometric) | [https://doi.org/10.1007/s10546-012-9773-y](https://doi.org/10.1007/s10546-012-9773-y)                                                                                                          |
|   16 | displacement_height                |   14.9    | m             | Nordbo et al. (2013) (morphometric) | [https://doi.org/10.1007/s10546-012-9773-y](https://doi.org/10.1007/s10546-012-9773-y)                                                                                                          |
|   17 | canyon_height_width_ratio          |    1.1    | 1             | estimated, see notes                | derived from 0.44 frontal area index reported in [Nordbo et al. 2013](https://doi.org/10.1007/s10546-012-9773-y) and Eq. 7 & 8 in [Porson et al. 2010](https://doi.org/10.1002/qj.668)          |
|   18 | wall_to_plan_area_ratio            |    1.38   | 1             | estimated, see notes                | derived from 0.44 frontal area index reported in [Nordbo et al. 2013](https://doi.org/10.1007/s10546-012-9773-y) and Eq. 1 in [Masson et al. 2020](https://doi.org/10.1016/j.uclim.2019.100536) |
|   19 | average_albedo_at_midday           |    0.11   | 1             | median of observations              | -                                                                                                                                                                                               |
|   20 | resident_population_density        | 8100      | person/km2    | Karsisto et al. (2016)              | [https://doi.org/10.1002/qj.2659](https://doi.org/10.1002/qj.2659)                                                                                                                              |
|   21 | anthropogenic_heat_flux_mean       |   14.2    | W/m2          | Dong et al. (2017)                  | https://doi.org/10.1016/j.atmosenv.2016.11.040                                                                                                                                                  |
|   22 | topsoil_clay_fraction              |    0.25   | 1             | OpenLandMap                         | [https://doi.org/10.5281/zenodo.2525663](https://doi.org/10.5281/zenodo.2525663)                                                                                                                |
|   23 | topsoil_sand_fraction              |    0.48   | 1             | OpenLandMap                         | [https://doi.org/10.5281/zenodo.2525662](https://doi.org/10.5281/zenodo.2525662)                                                                                                                |
|   24 | topsoil_bulk_density               |  940      | kg/m3         | OpenLandMap                         | [https://doi.org/10.5281/zenodo.2525665](https://doi.org/10.5281/zenodo.2525665)                                                                                                                |
|   25 | building_height_standard_deviation |    4.9    | m             | Nordbo et al. (2013)                | [https://doi.org/10.1007/s10546-012-9773-y](https://doi.org/10.1007/s10546-012-9773-y)                                                                                                          |
|   26 | roughness_length_momentum_mac      |    1.78   | m             | Macdonald method                    | derived from morphology using eq. 26 of [Macdonald et al. (1998)](https://doi.org/10.1016/S1352-2310(97)00403-2)                                                                                |
|   27 | displacement_height_mac            |   11.4    | m             | Macdonald method                    | derived from morphology using eq. 23 of [Macdonald et al. (1998)](https://doi.org/10.1016/S1352-2310(97)00403-2)                                                                                |
|   28 | roughness_length_momentum_kanda    |    1.5    | m             | Kanda method                        | derived from morphology using eq. 12a of [Kanda et al. (2013)](https://doi.org/10.1007/s10546-013-9818-x)                                                                                       |
|   29 | displacement_height_kanda          |   20.94   | m             | Kanda method                        | derived from morphology using eq. 10a of [Kanda et al. (2013)](https://doi.org/10.1007/s10546-013-9818-x)                                                                                       |

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

 1. **Out-of-range**: removal of unphysical values (e.g.  negative shortwave radiation) using the [ALMA expected range](https://www.lmd.jussieu.fr/~polcher/ALMA/qc_values_3.html) protocol.
 2. **Night**: nocturnal shortwave radiation set to zero, excluding civil twilight (when the sun is 6° below the horizon).
 3. **Constant**: four or more timesteps with the same value (excluding zero values for shortwave radiation, rainfall and snowfall) are removed as suspicious.
 4. **Outlier**: remove values outside ±4 standard deviations for each hour in a rolling 30-day window (to account for diurnal and seasonal variations). Repeat with a larger tolerance (± 5 standard deviations) until no outliers remain. The outlier test is not applied to precipitation.
 5. **Visual**: remaining suspect readings are removed manually via visual inspection.

**Gap-filling process**

 - contemporaneous and nearby flux tower or weather observing sites (where available and provided by observing groups)
 - small gaps (≤ 2 hours) are linearly interpolated from the adjoining observations
 - larger gaps (and a 10-year spin-up period) are filled with bias corrected ERA5 data (see below)
 - snowfall from ERA5, with water equivalent removed from rainfall to retain mass balance
 

### LWdown diurnal qc

[![./obs_plots/LWdown_obs_qc_diurnal.png](./obs_plots/LWdown_obs_qc_diurnal.png)](./obs_plots/LWdown_obs_qc_diurnal.png)

### LWup diurnal qc

[![./obs_plots/LWup_obs_qc_diurnal.png](./obs_plots/LWup_obs_qc_diurnal.png)](./obs_plots/LWup_obs_qc_diurnal.png)

### PSurf diurnal qc

[![./obs_plots/PSurf_obs_qc_diurnal.png](./obs_plots/PSurf_obs_qc_diurnal.png)](./obs_plots/PSurf_obs_qc_diurnal.png)

### Qair diurnal qc

[![./obs_plots/Qair_obs_qc_diurnal.png](./obs_plots/Qair_obs_qc_diurnal.png)](./obs_plots/Qair_obs_qc_diurnal.png)

### Qh diurnal qc

[![./obs_plots/Qh_obs_qc_diurnal.png](./obs_plots/Qh_obs_qc_diurnal.png)](./obs_plots/Qh_obs_qc_diurnal.png)

### Qle diurnal qc

[![./obs_plots/Qle_obs_qc_diurnal.png](./obs_plots/Qle_obs_qc_diurnal.png)](./obs_plots/Qle_obs_qc_diurnal.png)

### Rainf diurnal qc

[![./obs_plots/Rainf_obs_qc_diurnal.png](./obs_plots/Rainf_obs_qc_diurnal.png)](./obs_plots/Rainf_obs_qc_diurnal.png)

### SWdown diurnal qc

[![./obs_plots/SWdown_obs_qc_diurnal.png](./obs_plots/SWdown_obs_qc_diurnal.png)](./obs_plots/SWdown_obs_qc_diurnal.png)

### SWup diurnal qc

[![./obs_plots/SWup_obs_qc_diurnal.png](./obs_plots/SWup_obs_qc_diurnal.png)](./obs_plots/SWup_obs_qc_diurnal.png)

### Snowf diurnal qc

[![./obs_plots/Snowf_obs_qc_diurnal.png](./obs_plots/Snowf_obs_qc_diurnal.png)](./obs_plots/Snowf_obs_qc_diurnal.png)

### Tair diurnal qc

[![./obs_plots/Tair_obs_qc_diurnal.png](./obs_plots/Tair_obs_qc_diurnal.png)](./obs_plots/Tair_obs_qc_diurnal.png)

### Wind_E diurnal qc

[![./obs_plots/Wind_E_obs_qc_diurnal.png](./obs_plots/Wind_E_obs_qc_diurnal.png)](./obs_plots/Wind_E_obs_qc_diurnal.png)

### Wind_N diurnal qc

[![./obs_plots/Wind_N_obs_qc_diurnal.png](./obs_plots/Wind_N_obs_qc_diurnal.png)](./obs_plots/Wind_N_obs_qc_diurnal.png)


## Bias correction diurnal comparison


Four methods drawing on ERA5 reanalysis are compared relative to the quality-controlled flux tower data. The methods are:

 1.  **ERA5**: the nearest land based 0.25° resolution ERA5 grid (i.e. without bias correction)
 2.  **WFDE5**: the nearest WFDE5 grid (which use 0.5° gridded monthly observations for bias correction)
 3.  **UP**: the Urban-PLUMBER methods used in this collection (using site observations for bias correction)
 4.  **LN**: linear methods based on FLUXNET2015 (using site observations for bias correction)

 **ERA5 bias correction**

The UP methods are as follows:
 
 - for downwelling longwave, temperature, humidity and pressure: calculate the mean bias between ERA5 and flux tower data in a 30-day rolling window for every hour and each day of the year, apply that bias correction to all ERA5 data. For periods not covered by observations, linearly interpolate between known biases for each hour separately.
 - for precipitation: calculate total precipitation in a 10-year period and calculate the ratio between ERA5 data and the nearest GHCN-D station and apply that correction factor to ERA5 data.
 - for wind: apply wind log profile correction from ERA5 10m wind to tower measurement height using site roughness and displacement, with original grid roughness iteratively revised so that mean corrected wind speed matches observation.
 - for downwelling shortwave: use ERA5 data without correction

Mean absolute error (MAE) is shown in the legend.
### Tair diurnal bias correction

[![./era_correction/FI-Torni_Tair_all_diurnal.png](./era_correction/FI-Torni_Tair_all_diurnal.png)](./era_correction/FI-Torni_Tair_all_diurnal.png)
### Qair diurnal bias correction

[![./era_correction/FI-Torni_Qair_all_diurnal.png](./era_correction/FI-Torni_Qair_all_diurnal.png)](./era_correction/FI-Torni_Qair_all_diurnal.png)
### PSurf diurnal bias correction

[![./era_correction/FI-Torni_PSurf_all_diurnal.png](./era_correction/FI-Torni_PSurf_all_diurnal.png)](./era_correction/FI-Torni_PSurf_all_diurnal.png)
### LWdown diurnal bias correction

[![./era_correction/FI-Torni_LWdown_all_diurnal.png](./era_correction/FI-Torni_LWdown_all_diurnal.png)](./era_correction/FI-Torni_LWdown_all_diurnal.png)
### SWdown diurnal bias correction

[![./era_correction/FI-Torni_SWdown_all_diurnal.png](./era_correction/FI-Torni_SWdown_all_diurnal.png)](./era_correction/FI-Torni_SWdown_all_diurnal.png)
### Wind diurnal bias correction

[![./era_correction/FI-Torni_Wind_all_diurnal.png](./era_correction/FI-Torni_Wind_all_diurnal.png)](./era_correction/FI-Torni_Wind_all_diurnal.png)
### Rainf diurnal bias correction

[![./era_correction/FI-Torni_Rainf_all_diurnal.png](./era_correction/FI-Torni_Rainf_all_diurnal.png)](./era_correction/FI-Torni_Rainf_all_diurnal.png)


### Jump to section:

 - [Site forcing metadata](#site-forcing-metadata)
 - [Site images](#site-images)
 - [Site characteristics](#site-characteristics)
 - [Site forcing](#site-forcing)
 - [Quality control and gap filling procedure](#quality-control-qc-and-gap-filling-procedure)
 - [Bias correction diurnal comparison](#bias-correction-diurnal-comparison)

