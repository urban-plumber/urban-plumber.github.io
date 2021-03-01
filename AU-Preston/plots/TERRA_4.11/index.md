# AU-Preston: TERRA_4.11

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |      MAE |        MBE |      NSD |        R |
|:-------|:-------------|---------:|-----------:|---------:|---------:|
| SWnet  | baseline     | 14.811   |  14.811    | 0.916729 | 0.99991  |
| SWnet  | detailed     |  2.59186 |   0.183974 | 0.872794 | 0.99991  |
| SWup   | baseline     | 14.7794  | -14.7794   | 0.632148 | 0.996952 |
| SWup   | detailed     |  2.59195 |  -0.191491 | 0.883762 | 0.996951 |
| LWnet  | baseline     | 34.1173  |  33.5783   | 0.470153 | 0.985319 |
| LWnet  | detailed     |  9.92471 |  -8.38939  | 1.02621  | 0.97899  |
| LWup   | baseline     | 34.1173  | -33.5783   | 0.790938 | 0.845166 |
| LWup   | detailed     |  9.92471 |   8.38939  | 1.09289  | 0.985437 |
| Qle    | baseline     | 27.3496  | -18.4438   | 0.405597 | 0.572728 |
| Qle    | detailed     | 27.3457  | -18.2086   | 0.395459 | 0.563585 |
| Qh     | baseline     | 87.5967  |  86.9461   | 1.40657  | 0.926781 |
| Qh     | detailed     | 34.8788  |  30.8343   | 1.31841  | 0.946234 |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)

### jump to figure:
 - [Albedo](#albedo)
 - [LWnet](#lwnet)
 - [LWup](#lwup)
 - [Qh](#qh)
 - [Qle](#qle)
 - [SWnet](#swnet)
 - [SWup](#swup)
 - [closure_baseline](#closure_baseline)
 - [closure_detailed](#closure_detailed)
 - [subset_Qh](#subset_qh)
 - [subset_Qle](#subset_qle)
 - [subset_SWnet](#subset_swnet)
 - [subset_SWup](#subset_swup)

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="albedo"></a>Albedo
[![TERRA_4.11_AU-Preston_Albedo.png](TERRA_4.11_AU-Preston_Albedo.png)](TERRA_4.11_AU-Preston_Albedo.png)

### <a name="lwnet"></a>LWnet
[![TERRA_4.11_AU-Preston_LWnet.png](TERRA_4.11_AU-Preston_LWnet.png)](TERRA_4.11_AU-Preston_LWnet.png)

### <a name="lwup"></a>LWup
[![TERRA_4.11_AU-Preston_LWup.png](TERRA_4.11_AU-Preston_LWup.png)](TERRA_4.11_AU-Preston_LWup.png)

### <a name="qh"></a>Qh
[![TERRA_4.11_AU-Preston_Qh.png](TERRA_4.11_AU-Preston_Qh.png)](TERRA_4.11_AU-Preston_Qh.png)

### <a name="qle"></a>Qle
[![TERRA_4.11_AU-Preston_Qle.png](TERRA_4.11_AU-Preston_Qle.png)](TERRA_4.11_AU-Preston_Qle.png)

### <a name="swnet"></a>SWnet
[![TERRA_4.11_AU-Preston_SWnet.png](TERRA_4.11_AU-Preston_SWnet.png)](TERRA_4.11_AU-Preston_SWnet.png)

### <a name="swup"></a>SWup
[![TERRA_4.11_AU-Preston_SWup.png](TERRA_4.11_AU-Preston_SWup.png)](TERRA_4.11_AU-Preston_SWup.png)

### <a name="closure_baseline"></a>closure_baseline
[![TERRA_4.11_AU-Preston_closure_baseline.png](TERRA_4.11_AU-Preston_closure_baseline.png)](TERRA_4.11_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![TERRA_4.11_AU-Preston_closure_detailed.png](TERRA_4.11_AU-Preston_closure_detailed.png)](TERRA_4.11_AU-Preston_closure_detailed.png)

### <a name="subset_qh"></a>subset_Qh
[![TERRA_4.11_AU-Preston_subset_Qh.png](TERRA_4.11_AU-Preston_subset_Qh.png)](TERRA_4.11_AU-Preston_subset_Qh.png)

### <a name="subset_qle"></a>subset_Qle
[![TERRA_4.11_AU-Preston_subset_Qle.png](TERRA_4.11_AU-Preston_subset_Qle.png)](TERRA_4.11_AU-Preston_subset_Qle.png)

### <a name="subset_swnet"></a>subset_SWnet
[![TERRA_4.11_AU-Preston_subset_SWnet.png](TERRA_4.11_AU-Preston_subset_SWnet.png)](TERRA_4.11_AU-Preston_subset_SWnet.png)

### <a name="subset_swup"></a>subset_SWup
[![TERRA_4.11_AU-Preston_subset_SWup.png](TERRA_4.11_AU-Preston_subset_SWup.png)](TERRA_4.11_AU-Preston_subset_SWup.png)

### out of range: baseline

 - TERRA_4.11 Qh max value of 731.2208 is greater than expected 600.0 [W/m2]
 - TERRA_4.11 Qs min value of -0.0000 is less than expected 0.0 [kg/m2/s]

### out of range: detailed

 - TERRA_4.11 Qs min value of -0.0000 is less than expected 0.0 [kg/m2/s]


[Link to variable definitions](../modelattrs/variable_definitions.md)

