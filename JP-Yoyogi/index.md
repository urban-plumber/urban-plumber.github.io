
# Yoyogi, Tokyo, Japan (JP-Yoyogi)

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

|                           | observation_attributes                                                                                                                                                                                                                                                                           |
|:--------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| title                     | URBAN-PLUMBER forcing data for JP-Yoyogi                                                                                                                                                                                                                                                         |
| summary                   | Observed and ERA5-derived surface meteorological data for Yoyogi, Tokyo, Japan. Data is for use by registered participants of Urban-PLUMBER in this project only. Do not distribute. All times in UTC.                                                                                           |
| sitename                  | JP-Yoyogi                                                                                                                                                                                                                                                                                        |
| long_sitename             | Yoyogi, Tokyo, Japan                                                                                                                                                                                                                                                                             |
| version                   | v0.9                                                                                                                                                                                                                                                                                             |
| conventions               | ALMA+CF.rev13                                                                                                                                                                                                                                                                                    |
| featureType               | timeSeries                                                                                                                                                                                                                                                                                       |
| time_coverage_start       | 2006-01-01 00:00:00                                                                                                                                                                                                                                                                              |
| time_coverage_end         | 2020-03-31 14:00:00                                                                                                                                                                                                                                                                              |
| time_analysis_start       | 2016-03-31 15:00:00                                                                                                                                                                                                                                                                              |
| time_shown_in             | UTC                                                                                                                                                                                                                                                                                              |
| local_utc_offset_hours    | 9.0                                                                                                                                                                                                                                                                                              |
| timestep_interval_seconds | 3600.0                                                                                                                                                                                                                                                                                           |
| timestep_number_spinup    | 89823                                                                                                                                                                                                                                                                                            |
| timestep_number_analysis  | 35064                                                                                                                                                                                                                                                                                            |
| observations_contact      | Hirofumi Sugawara (hiros@nda.ac.jp)                                                                                                                                                                                                                                                              |
| observations_reference    | Hirano, Sugawara, Murayama, Kondo (2015): https://doi.org/10.2151/sola.2015-024; Sugawara, Shimizu, Hirano, Murayama and Kondo (2014): https://doi.org/10.14887/kazekosymp.23.0_49; Ishidoya, Sugawara,Terao, Kaneyasu, Aoki, Tsuboi and Kondo. (2020): https://doi.org/10.5194/acp-20-5293-2020 |
| project_contact           | Mathew Lipson: m.lipson@unsw.edu.au, Sue Grimmond: c.s.grimmond@reading.ac.uk, Martin Best: martin.best@metoffice.gov.uk                                                                                                                                                                         |
| date_created              | 2021-09-15 00:41:01                                                                                                                                                                                                                                                                              |
| other_references          | ERA5: Copernicus Climate Change Service (C3S) (2017): https://cds.climate.copernicus.eu/cdsapp#!/home NCI Australia: http://doi.org/10.25914/5f48874388857                                                                                                                                       |
| acknowledgements          | Contains modified Copernicus Climate Change Service Information (ERA5 hourly data on single levels). Data from replica hosted by NCI Australia. With thanks to all involved in collecting, processing and hosting observational data                                                             |
| comment                   | Observations for turbulent fluxes removed from sectors 170°-260° because of land surface inhomogeneities. Gap-filling for the forcing data using data at nearby observatories (less than 8 km distance).                                                                                         |
| history                   | v0.9 (2021-09-08): beta issue                                                                                                                                                                                                                                                                    |

## Site images

|                                             |                                             |    
|:-------------------------------------------:|:-------------------------------------------:|
| [![Region](./images/JP-Yoyogi_region_map.jpg)](./images/JP-Yoyogi_region_map.jpg)  <sub>Regional map. © OpenStreetMap</sub>    | [![site_map](./images/JP-Yoyogi_site_map.jpg)](./images/JP-Yoyogi_site_map.jpg) <sub>Site map with 500 m radius. © OpenStreetMap</sub>    |
| [![site_photo](./images/JP-Yoyogi_site_photo.jpg)](./images/JP-Yoyogi_site_photo.jpg) <sub>Site photo. © H. Sugawara</sub>    | [![site_sat](./images/JP-Yoyogi_site_sat.jpg)](./images/JP-Yoyogi_site_sat.jpg) <sub>Site aerial photo with 500 m radius. © OpenStreetMap, Microsoft</sub>    |

<sub>Maps developed from:
    Hrisko, J. (2020). [Geographic Visualizations in Python with Cartopy](https://makersportal.com/blog/2020/4/24/geographic-visualizations-in-python-with-cartopy). Maker Portal.</sub> 

## Site characteristics

|   id | parameter                          |      value | units         | source                              | doi                                                                                                                                                          |
|-----:|:-----------------------------------|-----------:|:--------------|:------------------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------|
|    1 | latitude                           |    35.6645 | degrees_north | Hirano et al. (2015)                | [https://doi.org/10.2151/sola.2015-024](https://doi.org/10.2151/sola.2015-024)                                                                               |
|    2 | longitude                          |   139.685  | degrees_east  | Hirano et al. (2015)                | [https://doi.org/10.2151/sola.2015-024](https://doi.org/10.2151/sola.2015-024)                                                                               |
|    3 | ground_height                      |    39      | m             | Hirano et al. (2015)                | [https://doi.org/10.2151/sola.2015-024](https://doi.org/10.2151/sola.2015-024)                                                                               |
|    4 | measurement_height_above_ground    |    52      | m             | Hirano et al. (2015)                | [https://doi.org/10.2151/sola.2015-024](https://doi.org/10.2151/sola.2015-024)                                                                               |
|    5 | impervious_area_fraction           |     0.92   | 1             | estimated, see notes                | area fractions within 500 m radius, from satellite imagery with sector 170-260 deg excluded                                                                  |
|    6 | tree_area_fraction                 |     0.06   | 1             | estimated, see notes                | area fractions within 500 m radius, from satellite imagery with sector 170-260 deg excluded                                                                  |
|    7 | grass_area_fraction                |     0.01   | 1             | estimated, see notes                | area fractions within 500 m radius, from satellite imagery with sector 170-260 deg excluded                                                                  |
|    8 | bare_soil_area_fraction            |     0.01   | 1             | estimated, see notes                | area fractions within 500 m radius, from satellite imagery with sector 170-260 deg excluded                                                                  |
|    9 | water_area_fraction                |     0      | 1             | estimated, see notes                | area fractions within 500 m radius, from satellite imagery with sector 170-260 deg excluded                                                                  |
|   10 | roof_area_fraction                 |     0.41   | 1             | estimated, see notes                | area fractions within 500 m radius, from satellite imagery with sector 170-260 deg excluded                                                                  |
|   11 | road_area_fraction                 |     0.32   | 1             | estimated, see notes                | area fractions within 500 m radius, from satellite imagery with sector 170-260 deg excluded                                                                  |
|   12 | other_paved_area_fraction          |     0.19   | 1             | estimated, see notes                | area fractions within 500 m radius, from satellite imagery with sector 170-260 deg excluded                                                                  |
|   13 | building_mean_height               |     9      | m             | Hirano et al. (2015)                | [https://doi.org/10.2151/sola.2015-024](https://doi.org/10.2151/sola.2015-024)                                                                               |
|   14 | tree_mean_height                   |    15      | m             | estimate                            | -                                                                                                                                                            |
|   15 | roughness_length_momentum          |     1.1    | m             | Hirano et al (2016) (anemometric)   | [https://www.jstage.jst.go.jp/article/kazekosymp/24/0/24_85/_article/-char/en](https://www.jstage.jst.go.jp/article/kazekosymp/24/0/24_85/_article/-char/en) |
|   16 | displacement_height                |    28      | m             | Sugawara et al (2014) (anemometric) | [https://doi.org/10.14887/kazekosymp.23.0_49](https://doi.org/10.14887/kazekosymp.23.0_49)                                                                   |
|   17 | canyon_height_width_ratio          |     1.2    | 1             | Sugawara, pers. comms               | derived from GIS/3D model                                                                                                                                    |
|   18 | wall_to_plan_area_ratio            |     1.14   | 1             | Sugawara, pers. comms               | derived from GIS/3D model                                                                                                                                    |
|   19 | average_albedo_at_midday           |     0.133  | 1             | median of observations              | -                                                                                                                                                            |
|   20 | resident_population_density        | 16600      | person/km2    | Hirano et al. (2015)                | [https://doi.org/10.2151/sola.2015-024](https://doi.org/10.2151/sola.2015-024)                                                                               |
|   21 | anthropogenic_heat_flux_mean       |    20      | W/m2          | Moriwaki et al (2008)               | https://doi.org/10.1029/2007WR006624                                                                                                                         |
|   22 | topsoil_clay_fraction              |     0.23   | 1             | OpenLandMap                         | [https://doi.org/10.5281/zenodo.2525663](https://doi.org/10.5281/zenodo.2525663)                                                                             |
|   23 | topsoil_sand_fraction              |     0.39   | 1             | OpenLandMap                         | [https://doi.org/10.5281/zenodo.2525662](https://doi.org/10.5281/zenodo.2525662)                                                                             |
|   24 | topsoil_bulk_density               |  1350      | kg/m3         | OpenLandMap                         | [https://doi.org/10.5281/zenodo.2525665](https://doi.org/10.5281/zenodo.2525665)                                                                             |
|   25 | building_height_standard_deviation |     9.75   | m             | Sugawara et al (2014)               | [https://doi.org/10.14887/kazekosymp.23.0_49](https://doi.org/10.14887/kazekosymp.23.0_49)                                                                   |
|   26 | roughness_length_momentum_mac      |     0.63   | m             | Macdonald method                    | derived from morphology using eq. 26 of [Macdonald et al. (1998)](https://doi.org/10.1016/S1352-2310(97)00403-2)                                             |
|   27 | displacement_height_mac            |     6.12   | m             | Macdonald method                    | derived from morphology using eq. 23 of [Macdonald et al. (1998)](https://doi.org/10.1016/S1352-2310(97)00403-2)                                             |
|   28 | roughness_length_momentum_kanda    |     2.76   | m             | Kanda method                        | derived from morphology using eq. 12a of [Kanda et al. (2013)](https://doi.org/10.1007/s10546-013-9818-x)                                                    |
|   29 | displacement_height_kanda          |    20.46   | m             | Kanda method                        | derived from morphology using eq. 10a of [Kanda et al. (2013)](https://doi.org/10.1007/s10546-013-9818-x)                                                    |

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

[![./era_correction/JP-Yoyogi_Tair_all_diurnal.png](./era_correction/JP-Yoyogi_Tair_all_diurnal.png)](./era_correction/JP-Yoyogi_Tair_all_diurnal.png)
### Qair diurnal bias correction

[![./era_correction/JP-Yoyogi_Qair_all_diurnal.png](./era_correction/JP-Yoyogi_Qair_all_diurnal.png)](./era_correction/JP-Yoyogi_Qair_all_diurnal.png)
### PSurf diurnal bias correction

[![./era_correction/JP-Yoyogi_PSurf_all_diurnal.png](./era_correction/JP-Yoyogi_PSurf_all_diurnal.png)](./era_correction/JP-Yoyogi_PSurf_all_diurnal.png)
### LWdown diurnal bias correction

[![./era_correction/JP-Yoyogi_LWdown_all_diurnal.png](./era_correction/JP-Yoyogi_LWdown_all_diurnal.png)](./era_correction/JP-Yoyogi_LWdown_all_diurnal.png)
### SWdown diurnal bias correction

[![./era_correction/JP-Yoyogi_SWdown_all_diurnal.png](./era_correction/JP-Yoyogi_SWdown_all_diurnal.png)](./era_correction/JP-Yoyogi_SWdown_all_diurnal.png)
### Wind diurnal bias correction

[![./era_correction/JP-Yoyogi_Wind_all_diurnal.png](./era_correction/JP-Yoyogi_Wind_all_diurnal.png)](./era_correction/JP-Yoyogi_Wind_all_diurnal.png)
### Rainf diurnal bias correction

[![./era_correction/JP-Yoyogi_Rainf_all_diurnal.png](./era_correction/JP-Yoyogi_Rainf_all_diurnal.png)](./era_correction/JP-Yoyogi_Rainf_all_diurnal.png)


### Jump to section:

 - [Site forcing metadata](#site-forcing-metadata)
 - [Site images](#site-images)
 - [Site characteristics](#site-characteristics)
 - [Site forcing](#site-forcing)
 - [Quality control and gap filling procedure](#quality-control-qc-and-gap-filling-procedure)
 - [Bias correction diurnal comparison](#bias-correction-diurnal-comparison)

