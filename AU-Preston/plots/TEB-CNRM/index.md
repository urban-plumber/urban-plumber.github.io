# AU-Preston: TEB-CNRM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |   MAE |     MBE |    NSD |      R |
|:-------|:-------------|------:|--------:|-------:|-------:|
| SWnet  | baseline     | 10.2  |   5.327 | 0.8876 | 0.9987 |
| SWnet  | detailed     | 11.42 |   7.297 | 0.8934 | 0.9987 |
| LWnet  | baseline     | 17.34 | -10.006 | 1.2299 | 0.9356 |
| LWnet  | detailed     | 11.99 |  -3.319 | 1.07   | 0.9543 |
| Qle    | baseline     | 27.96 |  -5.363 | 0.7506 | 0.4682 |
| Qle    | detailed     | 31.52 |   2.729 | 0.9909 | 0.48   |
| Qh     | baseline     | 34.23 |  26.7   | 1.2546 | 0.9344 |
| Qh     | detailed     | 31.39 |  18.483 | 1.3142 | 0.9195 |

MAE = mean absolute error, MBE = mean bias error, NSD = ratio of model:obs standard deviation, R = Pearson's correlation

### jump to figure:
 - [Albedo](#albedo)
 - [LWnet](#lwnet)
 - [LWup](#lwup)
 - [Qh](#qh)
 - [Qle](#qle)
 - [SWnet](#swnet)
 - [SWnet_subset_baseline](#swnet_subset_baseline)
 - [SWnet_subset_detailed](#swnet_subset_detailed)
 - [SWup](#swup)
 - [SWup_subset_baseline](#swup_subset_baseline)
 - [SWup_subset_detailed](#swup_subset_detailed)
 - [closure_baseline](#closure_baseline)
 - [closure_detailed](#closure_detailed)

[Link to variable definitions](variable_definitions.md)

### <a name="albedo"></a>Albedo
[![TEB-CNRM_AU-Preston_Albedo.png](TEB-CNRM_AU-Preston_Albedo.png)](TEB-CNRM_AU-Preston_Albedo.png)

### <a name="lwnet"></a>LWnet
[![TEB-CNRM_AU-Preston_LWnet.png](TEB-CNRM_AU-Preston_LWnet.png)](TEB-CNRM_AU-Preston_LWnet.png)

### <a name="lwup"></a>LWup
[![TEB-CNRM_AU-Preston_LWup.png](TEB-CNRM_AU-Preston_LWup.png)](TEB-CNRM_AU-Preston_LWup.png)

### <a name="qh"></a>Qh
[![TEB-CNRM_AU-Preston_Qh.png](TEB-CNRM_AU-Preston_Qh.png)](TEB-CNRM_AU-Preston_Qh.png)

### <a name="qle"></a>Qle
[![TEB-CNRM_AU-Preston_Qle.png](TEB-CNRM_AU-Preston_Qle.png)](TEB-CNRM_AU-Preston_Qle.png)

### <a name="swnet"></a>SWnet
[![TEB-CNRM_AU-Preston_SWnet.png](TEB-CNRM_AU-Preston_SWnet.png)](TEB-CNRM_AU-Preston_SWnet.png)

### <a name="swnet_subset_baseline"></a>SWnet_subset_baseline
[![TEB-CNRM_AU-Preston_SWnet_subset_baseline.png](TEB-CNRM_AU-Preston_SWnet_subset_baseline.png)](TEB-CNRM_AU-Preston_SWnet_subset_baseline.png)

### <a name="swnet_subset_detailed"></a>SWnet_subset_detailed
[![TEB-CNRM_AU-Preston_SWnet_subset_detailed.png](TEB-CNRM_AU-Preston_SWnet_subset_detailed.png)](TEB-CNRM_AU-Preston_SWnet_subset_detailed.png)

### <a name="swup"></a>SWup
[![TEB-CNRM_AU-Preston_SWup.png](TEB-CNRM_AU-Preston_SWup.png)](TEB-CNRM_AU-Preston_SWup.png)

### <a name="swup_subset_baseline"></a>SWup_subset_baseline
[![TEB-CNRM_AU-Preston_SWup_subset_baseline.png](TEB-CNRM_AU-Preston_SWup_subset_baseline.png)](TEB-CNRM_AU-Preston_SWup_subset_baseline.png)

### <a name="swup_subset_detailed"></a>SWup_subset_detailed
[![TEB-CNRM_AU-Preston_SWup_subset_detailed.png](TEB-CNRM_AU-Preston_SWup_subset_detailed.png)](TEB-CNRM_AU-Preston_SWup_subset_detailed.png)

### <a name="closure_baseline"></a>closure_baseline
[![TEB-CNRM_AU-Preston_closure_baseline.png](TEB-CNRM_AU-Preston_closure_baseline.png)](TEB-CNRM_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![TEB-CNRM_AU-Preston_closure_detailed.png](TEB-CNRM_AU-Preston_closure_detailed.png)](TEB-CNRM_AU-Preston_closure_detailed.png)

### out of range: baseline

 - TEB-CNRM RoofSurfT max value of 344.1260 is greater than expected 343.0 [K]
 - TEB-CNRM TVeg max value of 984.8733 is greater than expected 0.0003 [kg/m2/s]
 - TEB-CNRM TVeg min value of -0.7139 is less than expected -0.0003 [kg/m2/s]
 - TEB-CNRM ESoil max value of 286.3034 is greater than expected 0.0003 [kg/m2/s]
 - TEB-CNRM ESoil min value of -8.6155 is less than expected -0.0003 [kg/m2/s]
 - TEB-CNRM SoilWet max value of 1.6047 is greater than expected 1.2 [1]
 - TEB-CNRM SoilWet min value of -0.9861 is less than expected -0.2 [1]

### out of range: detailed

 - TEB-CNRM Qh max value of 622.6617 is greater than expected 600.0 [W/m2]
 - TEB-CNRM Qanth min value of -2.7514 is less than expected 0.0 [W/m2]
 - TEB-CNRM RoofSurfT max value of 343.9942 is greater than expected 343.0 [K]
 - TEB-CNRM TVeg max value of 851.9094 is greater than expected 0.0003 [kg/m2/s]
 - TEB-CNRM TVeg min value of -4.7255 is less than expected -0.0003 [kg/m2/s]
 - TEB-CNRM ESoil max value of 195.7182 is greater than expected 0.0003 [kg/m2/s]
 - TEB-CNRM ESoil min value of -8.7137 is less than expected -0.0003 [kg/m2/s]
 - TEB-CNRM SoilWet max value of 1.6163 is greater than expected 1.2 [1]
 - TEB-CNRM SoilWet min value of -1.0039 is less than expected -0.2 [1]


[Link to variable definitions](variable_definitions.md)

