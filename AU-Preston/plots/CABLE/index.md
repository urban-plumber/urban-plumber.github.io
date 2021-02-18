# AU-Preston: CABLE

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |     MAE |      MBE |      NSD |        R |
|:-------|:-------------|--------:|---------:|---------:|---------:|
| SWnet  | baseline     | 10.6937 |  10.6871 | 0.904454 | 0.999857 |
| LWnet  | baseline     | 16.3623 | -13.8319 | 1.33093  | 0.937785 |
| Qle    | baseline     | 38.6025 |  16.6814 | 1.4167   | 0.531026 |
| Qh     | baseline     | 27.8693 | -12.2246 | 1.00756  | 0.893465 |

 - MAE: mean absolute error (close to 0 is better)
 - NME: absolute mean error normalised by difference from mean  (closer to 0 is better)
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
 - [SWnet_subset_baseline](#swnet_subset_baseline)
 - [SWup](#swup)
 - [SWup_subset_baseline](#swup_subset_baseline)
 - [closure_baseline](#closure_baseline)

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="albedo"></a>Albedo
[![CABLE_AU-Preston_Albedo.png](CABLE_AU-Preston_Albedo.png)](CABLE_AU-Preston_Albedo.png)

### <a name="lwnet"></a>LWnet
[![CABLE_AU-Preston_LWnet.png](CABLE_AU-Preston_LWnet.png)](CABLE_AU-Preston_LWnet.png)

### <a name="lwup"></a>LWup
[![CABLE_AU-Preston_LWup.png](CABLE_AU-Preston_LWup.png)](CABLE_AU-Preston_LWup.png)

### <a name="qh"></a>Qh
[![CABLE_AU-Preston_Qh.png](CABLE_AU-Preston_Qh.png)](CABLE_AU-Preston_Qh.png)

### <a name="qle"></a>Qle
[![CABLE_AU-Preston_Qle.png](CABLE_AU-Preston_Qle.png)](CABLE_AU-Preston_Qle.png)

### <a name="swnet"></a>SWnet
[![CABLE_AU-Preston_SWnet.png](CABLE_AU-Preston_SWnet.png)](CABLE_AU-Preston_SWnet.png)

### <a name="swnet_subset_baseline"></a>SWnet_subset_baseline
[![CABLE_AU-Preston_SWnet_subset_baseline.png](CABLE_AU-Preston_SWnet_subset_baseline.png)](CABLE_AU-Preston_SWnet_subset_baseline.png)

### <a name="swup"></a>SWup
[![CABLE_AU-Preston_SWup.png](CABLE_AU-Preston_SWup.png)](CABLE_AU-Preston_SWup.png)

### <a name="swup_subset_baseline"></a>SWup_subset_baseline
[![CABLE_AU-Preston_SWup_subset_baseline.png](CABLE_AU-Preston_SWup_subset_baseline.png)](CABLE_AU-Preston_SWup_subset_baseline.png)

### <a name="closure_baseline"></a>closure_baseline
[![CABLE_AU-Preston_closure_baseline.png](CABLE_AU-Preston_closure_baseline.png)](CABLE_AU-Preston_closure_baseline.png)

### out of range: baseline

 - CABLE Qle max value of 758.7974 is greater than expected 700.0 [W/m2]
 - CABLE Evap max value of 0.0003 is greater than expected 0.0003 [kg/m2/s]
 - CABLE Qair max value of 1.5326 is greater than expected 0.03 [1]
 - CABLE PSurf min value of 974.2000 is less than expected 5000.0 [Pa]

### out of range: detailed



[Link to variable definitions](../modelattrs/variable_definitions.md)

