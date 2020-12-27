# Variable definitions

| short_name   | long_name (positive direction)                      | units   |    min.    |      max.  :|
|:-------------|:----------------------------------------------------|:--------|-----------:|------------:|
| SWnet        | Net shortwave radiation (downward)                  | W/m2    |     0      |   1200      |
| LWnet        | Net longwave radiation (downward)                   | W/m2    |  -500      |    510      |
| Qle          | Latent heat flux (upward)                           | W/m2    |  -700      |    700      |
| Qh           | Sensible heat flux (upward)                         | W/m2    |  -600      |    600      |
| Qanth        | Anthropogenic heat flux (upward)                    | W/m2    |     0      |   1000      |
| Qstor        | Net storage heat flux in all materials (increase)   | W/m2    |  -800      |    800      |
| SWup         | Upwelling shortwave radiation flux (downward)       | W/m2    |     0      |   1360      |
| LWup         | Upwelling longwave radiation flux (upward)          | W/m2    |     0      |   1000      |
| Qg           | Ground heat flux (downward)                         | W/m2    |  -500      |    500      |
| Qanth_Qh     | Anthropogenic sensible heat flux (upward)           | W/m2    |     0      |   1000      |
| Qanth_Qle    | Anthropogenic latent heat flux (upward)             | W/m2    |     0      |   1000      |
| Qtau         | Momentum flux (downward)                            | N/m2    |  -100      |    100      |
| Snowf        | Snowfall rate (downward)                            | kg/m2/s |     0      |      0.0085 |
| Rainf        | Rainfall rate (downward)                            | kg/m2/s |     0      |      0.02   |
| Evap         | Total evapotranspiration (upward)                   | kg/m2/s |    -0.0003 |      0.0003 |
| Qs           | Surface runoff (out of gridcell)                    | kg/m2/s |     0      |      5      |
| Qsb          | Subsurface runoff (out of gridcell)                 | kg/m2/s |     0      |      5      |
| Qsm          | Snowmelt (solid to liquid)                          | kg/m2/s |     0      |      0.005  |
| Qfz          | Re-freezing of water in the snow (liquid to solid)  | kg/m2/s |     0      |      0.005  |
| DelSoilMoist | Change in soil moisture (increase)                  | kg/m2   | -2000      |   2000      |
| DelSWE       | Change in snow water equivalent (increase)          | kg/m2   | -2000      |   2000      |
| DelIntercept | Change in interception storage (increase)           | kg/m2   |  -100      |    100      |
| Qirrig       | Anthropogenic water flux from irrigation (increase) | kg/m2/s |     0      |      0.02   |
| SnowT        | Snow surface temperature                            | K       |   213      |    280      |
| VegT         | Vegetation canopy temperature                       | K       |   213      |    333      |
| BaresoilT    | Temperature of bare soil                            | K       |   213      |    343      |
| AvgSurfT     | Average surface temperature (skin)                  | K       |   213      |    333      |
| RadT         | Surface radiative temperature                       | K       |   213      |    353      |
| Albedo       | Surface albedo                                      | 1       |     0      |      1      |
| SWE          | Snow water equivalent                               | kg/m2   |     0      |   2000      |
| SurfStor     | Surface water storage                               | kg/m2   |     0      |   2000      |
| SnowFrac     | Snow covered fraction                               | 1       |     0      |      1      |
| SAlbedo      | Snow albedo                                         | 1       |     0      |      1      |
| CAlbedo      | Vegetation canopy albedo                            | 1       |     0      |      1      |
| UAlbedo      | Urban canopy albedo                                 | 1       |     0      |      1      |
| LAI          | Leaf area index                                     | 1       |     0      |     15      |
| RoofSurfT    | Roof surface temperature (skin)                     | K       |   213      |    343      |
| WallSurfT    | Wall surface temperature (skin)                     | K       |   213      |    343      |
| RoadSurfT    | Road surface temperature (skin)                     | K       |   213      |    343      |
| TairSurf     | Near surface air temperature (2m)                   | K       |   213      |    333      |
| TairCanyon   | Air temperature in street canyon (bulk)             | K       |   213      |    333      |
| TairBuilding | Air temperature in buildings (bulk)                 | K       |   253      |    333      |
| SoilMoist    | Average layer soil moisture                         | kg/m2   |     0      |   2000      |
| SoilTemp     | Average layer soil temperature                      | K       |   213      |    333      |
| TVeg         | Vegetation transpiration                            | kg/m2/s |    -0.0003 |      0.0003 |
| ESoil        | Bare soil evaporation                               | kg/m2/s |    -0.0003 |      0.0003 |
| RootMoist    | Root zone soil moisture                             | kg/m2   |     0      |   2000      |
| SoilWet      | Total soil wetness                                  | 1       |    -0.2    |      1.2    |
| ACond        | Aerodynamic conductance                             | m/s     |     0      |      1      |
| SWdown       | Downward shortwave radiation at measurement height  | W/m2    |     0      |   1360      |
| LWdown       | Downward longwave radiation at measurement height   | W/m2    |     0      |    750      |
| Tair         | Air temperature at measurement height               | K       |   213      |    333      |
| Qair         | Specific humidity at measurement height             | 1       |     0      |      0.03   |
| PSurf        | Air pressure at measurement height                  | Pa      |  5000      | 110000      |
| Wind         | Wind speed at measurement height                    | m/s     |   -75      |     75      |
| alb          | implied albedo calculated from forcing              | 1       |     0      |      1      |
