
# West Phoenix, Arizona, United States (US-WestPhoenix)

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

|                           | observation_attributes                                                                                                                                                                                                                                                                                                |
|:--------------------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| title                     | Continuous meterological forcing from US-WestPhoenix                                                                                                                                                                                                                                                                  |
| summary                   | Flux tower observations from West Phoenix, Arizona, United States after quality control, with gap filling from bias corrected ERA5 surface meteorological data. Developed for use in the Urban-PLUMBER model evaluation project. Attribute any use to "Harmonized, gap-filled dataset from 20 urban flux tower sites" |
| sitename                  | US-WestPhoenix                                                                                                                                                                                                                                                                                                        |
| long_sitename             | West Phoenix, Arizona, United States                                                                                                                                                                                                                                                                                  |
| version                   | v0.9                                                                                                                                                                                                                                                                                                                  |
| keywords                  | urban, flux tower, eddy covariance, observations                                                                                                                                                                                                                                                                      |
| conventions               | ALMA, CF, ACDD-1.3                                                                                                                                                                                                                                                                                                    |
| featureType               | timeSeries                                                                                                                                                                                                                                                                                                            |
| license                   | CC-BY-4.0: https://creativecommons.org/licenses/by/4.0/                                                                                                                                                                                                                                                               |
| time_coverage_start       | 2001-01-01 00:00:00                                                                                                                                                                                                                                                                                                   |
| time_coverage_end         | 2013-01-01 06:30:00                                                                                                                                                                                                                                                                                                   |
| time_analysis_start       | 2011-12-16 18:30:00                                                                                                                                                                                                                                                                                                   |
| time_shown_in             | UTC                                                                                                                                                                                                                                                                                                                   |
| local_utc_offset_hours    | -7.0                                                                                                                                                                                                                                                                                                                  |
| timestep_interval_seconds | 1800.0                                                                                                                                                                                                                                                                                                                |
| timestep_number_spinup    | 192085                                                                                                                                                                                                                                                                                                                |
| timestep_number_analysis  | 18313                                                                                                                                                                                                                                                                                                                 |
| project                   | Urban-PLUMBER: "Harmonized, gap-filled dataset from 20 urban flux tower sites"                                                                                                                                                                                                                                        |
| project_contact           | Mathew Lipson (m.lipson@unsw.edu.au), Sue Grimmond (c.s.grimmond@reading.ac.uk), Martin Best (martin.best@metoffice.gov.uk)                                                                                                                                                                                           |
| observations_contact      | Stevan Earl: caplter.data@asu.edu, Winston Chow: winstonchow@smu.edu.sg                                                                                                                                                                                                                                               |
| observations_reference    | Chow (2017): https://doi.org/10.6073/pasta/fed17d67583eda16c439216ca40b0669; Chow et al (2014): https://doi.org/10.1002/joc.3947                                                                                                                                                                                      |
| date_created              | 2021-09-19 02:55:18                                                                                                                                                                                                                                                                                                   |
| source                    | https://github.com/matlipson/urban-plumber_pipeline                                                                                                                                                                                                                                                                   |
| other_references          | ERA5: Copernicus Climate Change Service (C3S) (2017): https://cds.climate.copernicus.eu/cdsapp#!/home NCI Australia: http://doi.org/10.25914/5f48874388857                                                                                                                                                            |
| acknowledgements          | Contains modified Copernicus Climate Change Service Information 2021 (ERA5 hourly data on single levels). Data from replica hosted by NCI Australia.                                                                                                                                                                  |
| comment                   | SoilTemp at 2cm depth.                                                                                                                                                                                                                                                                                                |
| history                   | v0.9 (2021-09-08): beta issue                                                                                                                                                                                                                                                                                         |

## Site images

|                                             |                                             |    
|:-------------------------------------------:|:-------------------------------------------:|
| [![Region](./images/US-WestPhoenix_region_map.jpg)](./images/US-WestPhoenix_region_map.jpg)  <sub>Regional map. © OpenStreetMap</sub>    | [![site_map](./images/US-WestPhoenix_site_map.jpg)](./images/US-WestPhoenix_site_map.jpg) <sub>Site map with 500 m radius. © OpenStreetMap</sub>    |
| [![site_photo](./images/US-WestPhoenix_site_photo.jpg)](./images/US-WestPhoenix_site_photo.jpg) <sub>Site photo. © S. Earl</sub>    | [![site_sat](./images/US-WestPhoenix_site_sat.jpg)](./images/US-WestPhoenix_site_sat.jpg) <sub>Site aerial photo with 500 m radius. © OpenStreetMap, Microsoft</sub>    |

<sub>Maps developed from:
    Hrisko, J. (2020). [Geographic Visualizations in Python with Cartopy](https://makersportal.com/blog/2020/4/24/geographic-visualizations-in-python-with-cartopy). Maker Portal.</sub> 

## Site characteristics

|   id | parameter                          |     value | units         | source                    | doi                                                                                                                                                            |
|-----:|:-----------------------------------|----------:|:--------------|:--------------------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------|
|    1 | latitude                           |   33.4839 | degrees_north | Chow et al. (2014)        | [https://doi.org/10.1002/joc.3947](https://doi.org/10.1002/joc.3947)                                                                                           |
|    2 | longitude                          | -112.143  | degrees_east  | Chow et al. (2014)        | [https://doi.org/10.1002/joc.3947](https://doi.org/10.1002/joc.3947)                                                                                           |
|    3 | ground_height                      |  340      | m             | Chow et al. (2014)        | [https://doi.org/10.1002/joc.3948](https://doi.org/10.1002/joc.3948)                                                                                           |
|    4 | measurement_height_above_ground    |   22.1    | m             | Chow et al. (2014)        | [https://doi.org/10.1002/joc.3949](https://doi.org/10.1002/joc.3949)                                                                                           |
|    5 | impervious_area_fraction           |    0.48   | 1             | Chow et al. (2014)        | [https://doi.org/10.1002/joc.3950](https://doi.org/10.1002/joc.3950)                                                                                           |
|    6 | tree_area_fraction                 |    0.05   | 1             | Chow et al. (2014)        | [https://doi.org/10.1002/joc.3951](https://doi.org/10.1002/joc.3951)                                                                                           |
|    7 | grass_area_fraction                |    0.1    | 1             | Chow et al. (2014)        | [https://doi.org/10.1002/joc.3952](https://doi.org/10.1002/joc.3952)                                                                                           |
|    8 | bare_soil_area_fraction            |    0.37   | 1             | Chow et al. (2014)        | [https://doi.org/10.1002/joc.3953](https://doi.org/10.1002/joc.3953)                                                                                           |
|    9 | water_area_fraction                |    0      | 1             | Chow et al. (2014)        | [https://doi.org/10.1002/joc.3954](https://doi.org/10.1002/joc.3954)                                                                                           |
|   10 | roof_area_fraction                 |    0.26   | 1             | Chow et al. (2014)        | [https://doi.org/10.1002/joc.3955](https://doi.org/10.1002/joc.3955)                                                                                           |
|   11 | road_area_fraction                 |    0.22   | 1             | Chow et al. (2014)        | [https://doi.org/10.1002/joc.3956](https://doi.org/10.1002/joc.3956)                                                                                           |
|   12 | other_paved_area_fraction          |    0      | 1             | included in road fraction | -                                                                                                                                                              |
|   13 | building_mean_height               |    4.5    | m             | Chow et al. (2014)        | [https://doi.org/10.1002/joc.3958](https://doi.org/10.1002/joc.3958)                                                                                           |
|   14 | tree_mean_height                   |    4      | m             | Chow et al. (2014)        | [https://doi.org/10.1002/joc.3959](https://doi.org/10.1002/joc.3959)                                                                                           |
|   15 | roughness_length_momentum          |    0.6    | m             | Chow, pers. comms         | -                                                                                                                                                              |
|   16 | displacement_height                |    3      | m             | Chow, pers. comms         | -                                                                                                                                                              |
|   17 | canyon_height_width_ratio          |    0.4    | 1             | Chow et al. (2014)        | [https://doi.org/10.1002/joc.3959](https://doi.org/10.1002/joc.3959)                                                                                           |
|   18 | wall_to_plan_area_ratio            |    0.59   | 1             | estimated, see notes      | derived from Eq. 1 in [Masson et al. 2020](https://doi.org/10.1016/j.uclim.2019.100536)                                                                        |
|   19 | average_albedo_at_midday           |    0.172  | 1             | median of observations    | -                                                                                                                                                              |
|   20 | resident_population_density        | 2500      | person/km2    | Statistical Atlas (2020)  | [https://statisticalatlas.com/neighborhood/Arizona/Phoenix/Maryvale/Population](https://statisticalatlas.com/neighborhood/Arizona/Phoenix/Maryvale/Population) |
|   21 | anthropogenic_heat_flux_mean       |   21.1    | W/m2          | Varquez et al (2021)      | [https://doi.org/10.1038/s41597-021-00850-w](https://doi.org/10.1038/s41597-021-00850-w)                                                                       |
|   22 | topsoil_clay_fraction              |    0.2    | 1             | OpenLandMap               | [https://doi.org/10.5281/zenodo.2525663](https://doi.org/10.5281/zenodo.2525663)                                                                               |
|   23 | topsoil_sand_fraction              |    0.4    | 1             | OpenLandMap               | [https://doi.org/10.5281/zenodo.2525662](https://doi.org/10.5281/zenodo.2525662)                                                                               |
|   24 | topsoil_bulk_density               | 1500      | kg/m3         | OpenLandMap               | [https://doi.org/10.5281/zenodo.2525665](https://doi.org/10.5281/zenodo.2525665)                                                                               |
|   25 | building_height_standard_deviation |    1.025  | m             | estimated, see notes      | derived using eq. 2 of [Kanda et al. 2013](https://doi.org/10.1007/s10546-013-9818-x)                                                                          |
|   26 | roughness_length_momentum_mac      |    0.42   | m             | Macdonald method          | derived from morphology using eq. 26 of [Macdonald et al. (1998)](https://doi.org/10.1016/S1352-2310(97)00403-2)                                               |
|   27 | displacement_height_mac            |    2.24   | m             | Macdonald method          | derived from morphology using eq. 23 of [Macdonald et al. (1998)](https://doi.org/10.1016/S1352-2310(97)00403-2)                                               |
|   28 | roughness_length_momentum_kanda    |    0.31   | m             | Kanda method              | derived from morphology using eq. 12a of [Kanda et al. (2013)](https://doi.org/10.1007/s10546-013-9818-x)                                                      |
|   29 | displacement_height_kanda          |    4.47   | m             | Kanda method              | derived from morphology using eq. 10a of [Kanda et al. (2013)](https://doi.org/10.1007/s10546-013-9818-x)                                                      |

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

### Qtau diurnal qc

[![./obs_plots/Qtau_obs_qc_diurnal.png](./obs_plots/Qtau_obs_qc_diurnal.png)](./obs_plots/Qtau_obs_qc_diurnal.png)

### Rainf diurnal qc

[![./obs_plots/Rainf_obs_qc_diurnal.png](./obs_plots/Rainf_obs_qc_diurnal.png)](./obs_plots/Rainf_obs_qc_diurnal.png)

### SWdown diurnal qc

[![./obs_plots/SWdown_obs_qc_diurnal.png](./obs_plots/SWdown_obs_qc_diurnal.png)](./obs_plots/SWdown_obs_qc_diurnal.png)

### SWup diurnal qc

[![./obs_plots/SWup_obs_qc_diurnal.png](./obs_plots/SWup_obs_qc_diurnal.png)](./obs_plots/SWup_obs_qc_diurnal.png)

### Snowf diurnal qc

[![./obs_plots/Snowf_obs_qc_diurnal.png](./obs_plots/Snowf_obs_qc_diurnal.png)](./obs_plots/Snowf_obs_qc_diurnal.png)

### SoilTemp diurnal qc

[![./obs_plots/SoilTemp_obs_qc_diurnal.png](./obs_plots/SoilTemp_obs_qc_diurnal.png)](./obs_plots/SoilTemp_obs_qc_diurnal.png)

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

[![./era_correction/US-WestPhoenix_Tair_all_diurnal.png](./era_correction/US-WestPhoenix_Tair_all_diurnal.png)](./era_correction/US-WestPhoenix_Tair_all_diurnal.png)
### Qair diurnal bias correction

[![./era_correction/US-WestPhoenix_Qair_all_diurnal.png](./era_correction/US-WestPhoenix_Qair_all_diurnal.png)](./era_correction/US-WestPhoenix_Qair_all_diurnal.png)
### PSurf diurnal bias correction

[![./era_correction/US-WestPhoenix_PSurf_all_diurnal.png](./era_correction/US-WestPhoenix_PSurf_all_diurnal.png)](./era_correction/US-WestPhoenix_PSurf_all_diurnal.png)
### LWdown diurnal bias correction

[![./era_correction/US-WestPhoenix_LWdown_all_diurnal.png](./era_correction/US-WestPhoenix_LWdown_all_diurnal.png)](./era_correction/US-WestPhoenix_LWdown_all_diurnal.png)
### SWdown diurnal bias correction

[![./era_correction/US-WestPhoenix_SWdown_all_diurnal.png](./era_correction/US-WestPhoenix_SWdown_all_diurnal.png)](./era_correction/US-WestPhoenix_SWdown_all_diurnal.png)
### Wind diurnal bias correction

[![./era_correction/US-WestPhoenix_Wind_all_diurnal.png](./era_correction/US-WestPhoenix_Wind_all_diurnal.png)](./era_correction/US-WestPhoenix_Wind_all_diurnal.png)
### Rainf diurnal bias correction

[![./era_correction/US-WestPhoenix_Rainf_all_diurnal.png](./era_correction/US-WestPhoenix_Rainf_all_diurnal.png)](./era_correction/US-WestPhoenix_Rainf_all_diurnal.png)


### Jump to section:

 - [Site forcing metadata](#site-forcing-metadata)
 - [Site images](#site-images)
 - [Site characteristics](#site-characteristics)
 - [Site forcing](#site-forcing)
 - [Quality control and gap filling procedure](#quality-control-qc-and-gap-filling-procedure)
 - [Bias correction diurnal comparison](#bias-correction-diurnal-comparison)

