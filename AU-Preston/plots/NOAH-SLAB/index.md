# AU-Preston: NOAH-SLAB

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |      MAE |      MBE |      NSD |        R |
|:-------|:-------------|---------:|---------:|---------:|---------:|
| SWnet  | baseline     |  2.58713 | 0.264984 | 0.87303  | 0.99991  |
| SWnet  | detailed     |  2.58713 | 0.264984 | 0.87303  | 0.99991  |
| LWnet  | baseline     |  4.75409 | 0.767305 | 0.865236 | 0.994218 |
| LWnet  | detailed     |  4.90324 | 1.06432  | 0.859713 | 0.994191 |
| Qle    | baseline     | 22.9608  | 2.90334  | 0.677905 | 0.655288 |
| Qle    | detailed     | 22.9067  | 2.93443  | 0.684946 | 0.655818 |
| Qh     | baseline     | 24.505   | 3.23059  | 1.23035  | 0.948437 |
| Qh     | detailed     | 24.5906  | 3.47155  | 1.23758  | 0.948311 |

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
 - [SWnet_subset_detailed](#swnet_subset_detailed)
 - [SWup](#swup)
 - [SWup_subset_baseline](#swup_subset_baseline)
 - [SWup_subset_detailed](#swup_subset_detailed)
 - [closure_baseline](#closure_baseline)
 - [closure_detailed](#closure_detailed)

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="albedo"></a>Albedo
[![NOAH-SLAB_AU-Preston_Albedo.png](NOAH-SLAB_AU-Preston_Albedo.png)](NOAH-SLAB_AU-Preston_Albedo.png)

### <a name="lwnet"></a>LWnet
[![NOAH-SLAB_AU-Preston_LWnet.png](NOAH-SLAB_AU-Preston_LWnet.png)](NOAH-SLAB_AU-Preston_LWnet.png)

### <a name="lwup"></a>LWup
[![NOAH-SLAB_AU-Preston_LWup.png](NOAH-SLAB_AU-Preston_LWup.png)](NOAH-SLAB_AU-Preston_LWup.png)

### <a name="qh"></a>Qh
[![NOAH-SLAB_AU-Preston_Qh.png](NOAH-SLAB_AU-Preston_Qh.png)](NOAH-SLAB_AU-Preston_Qh.png)

### <a name="qle"></a>Qle
[![NOAH-SLAB_AU-Preston_Qle.png](NOAH-SLAB_AU-Preston_Qle.png)](NOAH-SLAB_AU-Preston_Qle.png)

### <a name="swnet"></a>SWnet
[![NOAH-SLAB_AU-Preston_SWnet.png](NOAH-SLAB_AU-Preston_SWnet.png)](NOAH-SLAB_AU-Preston_SWnet.png)

### <a name="swnet_subset_baseline"></a>SWnet_subset_baseline
[![NOAH-SLAB_AU-Preston_SWnet_subset_baseline.png](NOAH-SLAB_AU-Preston_SWnet_subset_baseline.png)](NOAH-SLAB_AU-Preston_SWnet_subset_baseline.png)

### <a name="swnet_subset_detailed"></a>SWnet_subset_detailed
[![NOAH-SLAB_AU-Preston_SWnet_subset_detailed.png](NOAH-SLAB_AU-Preston_SWnet_subset_detailed.png)](NOAH-SLAB_AU-Preston_SWnet_subset_detailed.png)

### <a name="swup"></a>SWup
[![NOAH-SLAB_AU-Preston_SWup.png](NOAH-SLAB_AU-Preston_SWup.png)](NOAH-SLAB_AU-Preston_SWup.png)

### <a name="swup_subset_baseline"></a>SWup_subset_baseline
[![NOAH-SLAB_AU-Preston_SWup_subset_baseline.png](NOAH-SLAB_AU-Preston_SWup_subset_baseline.png)](NOAH-SLAB_AU-Preston_SWup_subset_baseline.png)

### <a name="swup_subset_detailed"></a>SWup_subset_detailed
[![NOAH-SLAB_AU-Preston_SWup_subset_detailed.png](NOAH-SLAB_AU-Preston_SWup_subset_detailed.png)](NOAH-SLAB_AU-Preston_SWup_subset_detailed.png)

### <a name="closure_baseline"></a>closure_baseline
[![NOAH-SLAB_AU-Preston_closure_baseline.png](NOAH-SLAB_AU-Preston_closure_baseline.png)](NOAH-SLAB_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![NOAH-SLAB_AU-Preston_closure_detailed.png](NOAH-SLAB_AU-Preston_closure_detailed.png)](NOAH-SLAB_AU-Preston_closure_detailed.png)

### out of range: baseline

 - NOAH-SLAB Qsm max value of 127.2791 is greater than expected 0.005 [kg/m2/s]
 - NOAH-SLAB Qsm min value of -10.5639 is less than expected 0.0 [kg/m2/s]

### out of range: detailed



[Link to variable definitions](../modelattrs/variable_definitions.md)

