# AU-Preston: NOAH-SLUCM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |   MAE |     MBE |     NSD |      R |
|:-------|:-------------|------:|--------:|--------:|-------:|
| SWnet  | baseline     | 69.85 | -69.768 |  0.6594 | 0.9998 |
| SWnet  | detailed     | 55.29 | -55.201 |  0.7029 | 0.9998 |
| LWnet  | baseline     | 41.99 | -41.782 | 35.8017 | 0.0041 |
| LWnet  | detailed     | 21.46 | -21.114 |  3.572  | 0.1912 |
| Qle    | baseline     | 25.93 | -15.628 |  0.4326 | 0.5986 |
| Qle    | detailed     | 25.92 | -15.049 |  0.4571 | 0.5784 |
| Qh     | baseline     | 21.07 |   9.069 |  1.1248 | 0.9485 |
| Qh     | detailed     | 22.08 |   8.632 |  1.1714 | 0.9489 |

MAE = mean absolute error
MBE = mean bias error
NSD = ratio of model to obs standard deviation
R = Pearson's correlation

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
[![NOAH-SLUCM_AU-Preston_Albedo.png](NOAH-SLUCM_AU-Preston_Albedo.png)](NOAH-SLUCM_AU-Preston_Albedo.png)

### <a name="lwnet"></a>LWnet
[![NOAH-SLUCM_AU-Preston_LWnet.png](NOAH-SLUCM_AU-Preston_LWnet.png)](NOAH-SLUCM_AU-Preston_LWnet.png)

### <a name="lwup"></a>LWup
[![NOAH-SLUCM_AU-Preston_LWup.png](NOAH-SLUCM_AU-Preston_LWup.png)](NOAH-SLUCM_AU-Preston_LWup.png)

### <a name="qh"></a>Qh
[![NOAH-SLUCM_AU-Preston_Qh.png](NOAH-SLUCM_AU-Preston_Qh.png)](NOAH-SLUCM_AU-Preston_Qh.png)

### <a name="qle"></a>Qle
[![NOAH-SLUCM_AU-Preston_Qle.png](NOAH-SLUCM_AU-Preston_Qle.png)](NOAH-SLUCM_AU-Preston_Qle.png)

### <a name="swnet"></a>SWnet
[![NOAH-SLUCM_AU-Preston_SWnet.png](NOAH-SLUCM_AU-Preston_SWnet.png)](NOAH-SLUCM_AU-Preston_SWnet.png)

### <a name="swnet_subset_baseline"></a>SWnet_subset_baseline
[![NOAH-SLUCM_AU-Preston_SWnet_subset_baseline.png](NOAH-SLUCM_AU-Preston_SWnet_subset_baseline.png)](NOAH-SLUCM_AU-Preston_SWnet_subset_baseline.png)

### <a name="swnet_subset_detailed"></a>SWnet_subset_detailed
[![NOAH-SLUCM_AU-Preston_SWnet_subset_detailed.png](NOAH-SLUCM_AU-Preston_SWnet_subset_detailed.png)](NOAH-SLUCM_AU-Preston_SWnet_subset_detailed.png)

### <a name="swup"></a>SWup
[![NOAH-SLUCM_AU-Preston_SWup.png](NOAH-SLUCM_AU-Preston_SWup.png)](NOAH-SLUCM_AU-Preston_SWup.png)

### <a name="swup_subset_baseline"></a>SWup_subset_baseline
[![NOAH-SLUCM_AU-Preston_SWup_subset_baseline.png](NOAH-SLUCM_AU-Preston_SWup_subset_baseline.png)](NOAH-SLUCM_AU-Preston_SWup_subset_baseline.png)

### <a name="swup_subset_detailed"></a>SWup_subset_detailed
[![NOAH-SLUCM_AU-Preston_SWup_subset_detailed.png](NOAH-SLUCM_AU-Preston_SWup_subset_detailed.png)](NOAH-SLUCM_AU-Preston_SWup_subset_detailed.png)

### <a name="closure_baseline"></a>closure_baseline
[![NOAH-SLUCM_AU-Preston_closure_baseline.png](NOAH-SLUCM_AU-Preston_closure_baseline.png)](NOAH-SLUCM_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![NOAH-SLUCM_AU-Preston_closure_detailed.png](NOAH-SLUCM_AU-Preston_closure_detailed.png)](NOAH-SLUCM_AU-Preston_closure_detailed.png)

### out of range: baseline

 - NOAH-SLUCM LWnet min value of -179448.4531 is less than expected -500.0 [W/m2]
 - NOAH-SLUCM SWup min value of -254.5751 is less than expected 0.0 [W/m2]
 - NOAH-SLUCM LWup max value of 179806.8531 is greater than expected 1000.0 [W/m2]
 - NOAH-SLUCM Evap max value of 397.3634 is greater than expected 0.0003 [kg/m2/s]
 - NOAH-SLUCM Evap min value of -21.5631 is less than expected -0.0003 [kg/m2/s]
 - NOAH-SLUCM Qsm max value of 109.4080 is greater than expected 0.005 [kg/m2/s]
 - NOAH-SLUCM Qsm min value of -16.3000 is less than expected 0.0 [kg/m2/s]
 - NOAH-SLUCM Qfz min value of -0.0000 is less than expected 0.0 [kg/m2/s]
 - NOAH-SLUCM AvgSurfT max value of 1355.9984 is greater than expected 333.0 [K]
 - NOAH-SLUCM AvgSurfT min value of -62.7736 is less than expected 213.0 [K]
 - NOAH-SLUCM RadT max value of 1355.9984 is greater than expected 353.0 [K]
 - NOAH-SLUCM RadT min value of 62.7736 is less than expected 213.0 [K]
 - NOAH-SLUCM TVeg max value of 363.9469 is greater than expected 0.0003 [kg/m2/s]
 - NOAH-SLUCM alb min value of -0.9739 is less than expected 0.0 [1]

### out of range: detailed

 - NOAH-SLUCM LWnet min value of -18590.7520 is less than expected -500.0 [W/m2]
 - NOAH-SLUCM SWup min value of -281.8973 is less than expected 0.0 [W/m2]
 - NOAH-SLUCM LWup max value of 18935.9720 is greater than expected 1000.0 [W/m2]
 - NOAH-SLUCM Evap max value of 412.8776 is greater than expected 0.0003 [kg/m2/s]
 - NOAH-SLUCM Evap min value of -21.6109 is less than expected -0.0003 [kg/m2/s]
 - NOAH-SLUCM Qsm max value of 109.9217 is greater than expected 0.005 [kg/m2/s]
 - NOAH-SLUCM Qsm min value of -16.5773 is less than expected 0.0 [kg/m2/s]
 - NOAH-SLUCM Qfz min value of -0.0000 is less than expected 0.0 [kg/m2/s]
 - NOAH-SLUCM AvgSurfT max value of 772.0754 is greater than expected 333.0 [K]
 - NOAH-SLUCM AvgSurfT min value of -119.9518 is less than expected 213.0 [K]
 - NOAH-SLUCM RadT max value of 772.0754 is greater than expected 353.0 [K]
 - NOAH-SLUCM RadT min value of 75.5868 is less than expected 213.0 [K]
 - NOAH-SLUCM TVeg max value of 372.4022 is greater than expected 0.0003 [kg/m2/s]
 - NOAH-SLUCM alb min value of -0.9838 is less than expected 0.0 [1]


[Link to variable definitions](variable_definitions.md)

