Submitted variables
-------------------
![Variables](submitted_variables.png)

Metadata
--------

|               | baseline                                                    | detailed                                              |
|:--------------|:------------------------------------------------------------|:------------------------------------------------------|
| ASLUMv2.0     | [ASLUMv2.0](ASLUMv2.0_AU-Preston_baseline_attrs.md)         | [ASLUMv2.0](ASLUMv2.0_AU-Preston_detailed_attrs.md)   |
| ASLUMv3.1     | [ASLUMv3.1](ASLUMv3.1_AU-Preston_baseline_attrs.md)         | [ASLUMv3.1](ASLUMv3.1_AU-Preston_detailed_attrs.md)   |
| CABLE         | [CABLE](CABLE_AU-Preston_baseline_attrs.md)                 |                                                       |
| CHTESSEL-CTL  | [CHTESSEL-CTL](CHTESSEL-CTL_AU-Preston_baseline_attrs.md)   |                                                       |
| CHTESSEL-URB1 | [CHTESSEL-URB1](CHTESSEL-URB1_AU-Preston_baseline_attrs.md) |                                                       |
| CHTESSEL-URB2 | [CHTESSEL-URB2](CHTESSEL-URB2_AU-Preston_baseline_attrs.md) |                                                       |
| CLMU5         | [CLMU5](CLMU5_AU-Preston_baseline_attrs.md)                 | [CLMU5](CLMU5_AU-Preston_detailed_attrs.md)           |
| CM-BEM        | [CM-BEM](CM-BEM_AU-Preston_baseline_attrs.md)               | [CM-BEM](CM-BEM_AU-Preston_detailed_attrs.md)         |
| CM            | [CM](CM_AU-Preston_baseline_attrs.md)                       | [CM](CM_AU-Preston_detailed_attrs.md)                 |
| Lodz-SUEB     | [Lodz-SUEB](Lodz-SUEB_AU-Preston_baseline_attrs.md)         | [Lodz-SUEB](Lodz-SUEB_AU-Preston_detailed_attrs.md)   |
| NOAH-SLAB     | [NOAH-SLAB](NOAH-SLAB_AU-Preston_baseline_attrs.md)         |                                                       |
| NOAH-SLUCM    | [NOAH-SLUCM](NOAH-SLUCM_AU-Preston_baseline_attrs.md)       | [NOAH-SLUCM](NOAH-SLUCM_AU-Preston_detailed_attrs.md) |
| SUEWS         | [SUEWS](SUEWS_AU-Preston_baseline_attrs.md)                 |                                                       |
| TEB           | [TEB](TEB_AU-Preston_baseline_attrs.md)                     | [TEB](TEB_AU-Preston_detailed_attrs.md)               |
| TERRA         | [TERRA](TERRA_AU-Preston_baseline_attrs.md)                 |                                                       |
| UT&C          | [UT&C](UT&C_AU-Preston_baseline_attrs.md)                   | [UT&C](UT&C_AU-Preston_detailed_attrs.md)             |
| TARGET        |                                                             | [TARGET](TARGET_AU-Preston_detailed_attrs.md)         |
| VTUF-3D       |                                                             | [VTUF-3D](VTUF-3D_AU-Preston_detailed_attrs.md)       |

Variable definitions
--------------------

| short_name   | long_name (positive direction)                      | units   |
|--------------|-----------------------------------------------------|---------|
| SWnet        | Net shortwave radiation (downward)                  | W/m2    |
| LWnet        | Net longwave radiation (downward)                   | W/m2    |
| Qle          | Latent heat flux (upward)                           | W/m2    |
| Qh           | Sensible heat flux (upward)                         | W/m2    |
| Qanth        | Anthropogenic heat flux (upward)                    | W/m2    |
| Qstor        | Net storage heat flux in all materials (increase)   | W/m2    |
| Qg           | Ground heat flux (downward)                         | W/m2    |
| Qanth_Qh     | Anthropogenic sensible heat flux (upward)           | W/m2    |
| Qanth_Qle    | Anthropogenic latent heat flux (upward)             | W/m2    |
| Qtau         | Momentum flux (downward)                            | N/m2    |
| Snowf        | Snowfall rate (downward)                            | kg/m2/s |
| Rainf        | Rainfall rate (downward)                            | kg/m2/s |
| Evap         | Total evapotranspiration (upward)                   | kg/m2/s |
| Qs           | Surface runoff (out of gridcell)                    | kg/m2/s |
| Qsb          | Subsurface runoff (out of gridcell)                 | kg/m2/s |
| Qsm          | Snowmelt (solid to liquid)                          | kg/m2/s |
| Qfz          | Re-freezing of water in the snow (liquid to solid)  | kg/m2/s |
| DelSoilMoist | Change in soil moisture (increase)                  | kg/m2   |
| DelSWE       | Change in snow water equivalent (increase)          | kg/m2   |
| DelIntercept | Change in interception storage (increase)           | kg/m2   |
| Qirrig       | Anthropogenic water flux from irrigation (increase) | kg/m2/s |
| SnowT        | Snow surface temperature                            | K       |
| VegT         | Vegetation canopy temperature                       | K       |
| BaresoilT    | Temperature of bare soil (skin)                     | K       |
| AvgSurfT     | Average surface temperature (skin)                  | K       |
| RadT         | Surface radiative temperature                       | K       |
| Albedo       | Surface albedo                                      | 1       |
| SWE          | Snow water equivalent                               | kg/m2   |
| SurfStor     | Surface water storage                               | kg/m2   |
| SnowFrac     | Snow covered fraction                               | 1       |
| SAlbedo      | Snow albedo                                         | 1       |
| CAlbedo      | Vegetation canopy albedo                            | 1       |
| UAlbedo      | Urban canopy albedo                                 | 1       |
| LAI          | Leaf area index                                     | m2/m2   |
| RoofSurfT    | Roof surface temperature (skin)                     | K       |
| WallSurfT    | Wall surface temperature (skin)                     | K       |
| RoadSurfT    | Road surface temperature (skin)                     | K       |
| TairSurf     | Near surface air temperature (2m)                   | K       |
| TairCanyon   | Air temperature in street canyon (bulk)             | K       |
| TairBuilding | Air temperature in buildings (bulk)                 | K       |
| SoilMoist    | Average layer soil moisture                         | kg/m2   |
| SoilTemp     | Average layer soil temperature                      | K       |
| TVeg         | Vegetation transpiration                            | kg/m2/s |
| ESoil        | Bare soil evaporation                               | kg/m2/s |
| RootMoist    | Root zone soil moisture                             | kg/m2   |
| SoilWet      | Total soil wetness                                  | 1       |
| ACond        | Aerodynamic conductance                             | m/s     |
| SWdown       | Downward shortwave radiation                        | W/m2    |
| LWdown       | Downward longwave radiation                         | W/m2    |
| Tair         | Air temperature                                     | K       |
| Qair         | Specific humidity                                   | kg/kg   |
| PSurf        | Air pressure                                        | Pa      |
| Wind         | Wind speed                                          | m/s     |
