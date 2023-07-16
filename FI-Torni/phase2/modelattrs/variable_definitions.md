# Variable definitions

for more details refer to the [ALMA protocol definitions](https://www.lmd.jussieu.fr/~polcher/ALMA/convention_output_3.html)

| short_name   | long_name (positive direction)                       | units   |  min.  |  max. | 
|:-------------|:-----------------------------------------------------|:--------|-----------:|------------:|
| SWnet        | Net shortwave radiation (positive downward)          | W/m2    |     0      |   1200      |
| LWnet        | Net longwave radiation (positive downward)           | W/m2    |  -500      |    510      |
| Qle          | Latent heat flux (positive upward)                   | W/m2    |  -700      |    700      |
| Qh           | Sensible heat flux (positive upward)                 | W/m2    |  -600      |    600      |
| Qanth        | Anthropogenic heat flux (positive upward)            | W/m2    |     0      |   1000      |
| Qstor        | Net storage heat flux in all materials (increase)    | W/m2    |  -800      |    800      |
| SWup         | Upwelling shortwave radiation flux (positive upward) | W/m2    |     0      |   1360      |
| LWup         | Upwelling longwave radiation flux (positive upward)  | W/m2    |     0      |   1000      |
| Qg           | Ground heat flux (positive downward)                 | W/m2    |  -500      |    500      |
| Qanth_Qh     | Anthropogenic sensible heat flux (positive upward)   | W/m2    |     0      |   1000      |
| Qanth_Qle    | Anthropogenic latent heat flux (positive upward)     | W/m2    |     0      |   1000      |
| Qtau         | Momentum flux (positive downward)                    | N/m2    |  -100      |    100      |
| Albedo       | Surface albedo                                       | 1       |     0      |      1      |
| CAlbedo      | Vegetation canopy albedo                             | 1       |     0      |      1      |
| UAlbedo      | Urban canopy albedo                                  | 1       |     0      |      1      |
| SAlbedo      | Snow albedo                                          | 1       |     0      |      1      |
| LAI          | Leaf area index                                      | 1       |     0      |     15      |
| SnowFrac     | Snow covered fraction                                | 1       |     0      |      1      |
| SWE          | Snow water equivalent                                | kg/m2   |     0      |   2000      |
| SurfStor     | Surface water storage                                | kg/m2   |     0      |   2000      |
| RoofSurfT    | Roof surface temperature (skin)                      | K       |   213      |    353      |
| WallSurfT    | Wall surface temperature (skin)                      | K       |   213      |    353      |
| RoadSurfT    | Road surface temperature (skin)                      | K       |   213      |    353      |
| TairSurf     | Near surface air temperature (2m)                    | K       |   213      |    333      |
| TairCanyon   | Air temperature in street canyon (bulk)              | K       |   213      |    333      |
| TairBuilding | Air temperature in buildings (bulk)                  | K       |   253      |    333      |
| SnowT        | Snow surface temperature                             | K       |   213      |    280      |
| VegT         | Vegetation canopy temperature                        | K       |   213      |    333      |
| BaresoilT    | Temperature of bare soil                             | K       |   213      |    343      |
| AvgSurfT     | Average surface temperature (skin)                   | K       |   213      |    333      |
| RadT         | Surface radiative temperature                        | K       |   213      |    353      |
| SoilTemp     | Average layer soil temperature                       | K       |   213      |    333      |
| SoilMoist    | Average layer soil moisture                          | kg/m2   |     0      |   2000      |
| SoilWet      | Total soil wetness                                   | 1       |    -0.2    |      1.2    |
| TVeg         | Vegetation transpiration                             | kg/m2/s |    -0.0003 |      0.0003 |
| ESoil        | Bare soil evaporation                                | kg/m2/s |    -0.0003 |      0.0003 |
| RootMoist    | Root zone soil moisture                              | kg/m2   |     0      |   2000      |
| ACond        | Aerodynamic conductance                              | m/s     |     0      |      1      |
| Qirrig       | Anthropogenic water flux from irrigation (increase)  | kg/m2/s |     0      |      0.02   |
| Evap         | Total evapotranspiration (positive upward)           | kg/m2/s |    -0.0003 |      0.0003 |
| Qs           | Surface runoff (positive out of gridcell)            | kg/m2/s |     0      |      5      |
| Qsb          | Subsurface runoff (positive out of gridcell)         | kg/m2/s |     0      |      5      |
| Qsm          | Snowmelt (solid to liquid)                           | kg/m2/s |     0      |      0.005  |
| Qfz          | Re-freezing of water in the snow (liquid to solid)   | kg/m2/s |     0      |      0.005  |
| DelSoilMoist | Change in soil moisture (increase)                   | kg/m2   | -2000      |   2000      |
| DelSWE       | Change in snow water equivalent (increase)           | kg/m2   | -2000      |   2000      |
| DelIntercept | Change in interception storage (increase)            | kg/m2   |  -100      |    100      |
| SWdown       | Downward shortwave radiation at measurement height   | W/m2    |     0      |   1360      |
| LWdown       | Downward longwave radiation at measurement height    | W/m2    |     0      |    750      |
| Tair         | Air temperature at measurement height                | K       |   213      |    333      |
| Qair         | Specific humidity at measurement height              | 1       |     0      |      0.03   |
| Rainf        | Rainfall rate (positive downward)                    | kg/m2/s |     0      |      0.02   |
| Snowf        | Snowfall rate (positive downward)                    | kg/m2/s |     0      |      0.0085 |
| PSurf        | Air pressure at measurement height                   | Pa      |  5000      | 110000      |
| Wind         | Wind speed at measurement height                     | m/s     |   -75      |     75      |
| alb          | Implied albedo calculated from SWdown and SWnet      | 1       |     0      |      1      |
| Qstar        | Net all wave radiation flux                          | W/m2    |  -500      |   1200      |
