# AU-Preston: NOAH-SLAB

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |      MAE |       MBE |      NSD |        R |
|:-------|:-------------|---------:|----------:|---------:|---------:|
| SWnet  | baseline     |  2.58764 |  0.264956 | 0.873044 | 0.99991  |
| SWnet  | detailed     |  2.58764 |  0.264956 | 0.873044 | 0.99991  |
| SWup   | baseline     |  2.58777 | -0.272209 | 0.882332 | 0.996948 |
| SWup   | detailed     |  2.58777 | -0.272209 | 0.882332 | 0.996948 |
| LWnet  | baseline     |  4.75409 |  0.767305 | 0.865236 | 0.994218 |
| LWnet  | detailed     |  4.90324 |  1.06432  | 0.859713 | 0.994191 |
| LWup   | baseline     |  4.75409 | -0.767304 | 0.894167 | 0.991382 |
| LWup   | detailed     |  4.90324 | -1.06432  | 0.888263 | 0.991134 |
| Qle    | baseline     | 22.9608  |  2.90334  | 0.677905 | 0.655288 |
| Qle    | detailed     | 22.9067  |  2.93443  | 0.684946 | 0.655818 |
| Qh     | baseline     | 24.505   |  3.23059  | 1.23035  | 0.948437 |
| Qh     | detailed     | 24.5906  |  3.47155  | 1.23758  | 0.948311 |

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
 - [subset_Qg](#subset_qg)
 - [subset_Qh](#subset_qh)
 - [subset_Qle](#subset_qle)
 - [subset_SWnet](#subset_swnet)
 - [subset_SWup](#subset_swup)

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

### <a name="swup"></a>SWup
[![NOAH-SLAB_AU-Preston_SWup.png](NOAH-SLAB_AU-Preston_SWup.png)](NOAH-SLAB_AU-Preston_SWup.png)

### <a name="closure_baseline"></a>closure_baseline
[![NOAH-SLAB_AU-Preston_closure_baseline.png](NOAH-SLAB_AU-Preston_closure_baseline.png)](NOAH-SLAB_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![NOAH-SLAB_AU-Preston_closure_detailed.png](NOAH-SLAB_AU-Preston_closure_detailed.png)](NOAH-SLAB_AU-Preston_closure_detailed.png)

### <a name="subset_qg"></a>subset_Qg
[![NOAH-SLAB_AU-Preston_subset_Qg.png](NOAH-SLAB_AU-Preston_subset_Qg.png)](NOAH-SLAB_AU-Preston_subset_Qg.png)

### <a name="subset_qh"></a>subset_Qh
[![NOAH-SLAB_AU-Preston_subset_Qh.png](NOAH-SLAB_AU-Preston_subset_Qh.png)](NOAH-SLAB_AU-Preston_subset_Qh.png)

### <a name="subset_qle"></a>subset_Qle
[![NOAH-SLAB_AU-Preston_subset_Qle.png](NOAH-SLAB_AU-Preston_subset_Qle.png)](NOAH-SLAB_AU-Preston_subset_Qle.png)

### <a name="subset_swnet"></a>subset_SWnet
[![NOAH-SLAB_AU-Preston_subset_SWnet.png](NOAH-SLAB_AU-Preston_subset_SWnet.png)](NOAH-SLAB_AU-Preston_subset_SWnet.png)

### <a name="subset_swup"></a>subset_SWup
[![NOAH-SLAB_AU-Preston_subset_SWup.png](NOAH-SLAB_AU-Preston_subset_SWup.png)](NOAH-SLAB_AU-Preston_subset_SWup.png)

### out of range: baseline

 - NOAH-SLAB Qsm max value of 127.2791 is greater than expected 0.005 [kg/m2/s]
 - NOAH-SLAB Qsm min value of -10.5639 is less than expected 0.0 [kg/m2/s]

### out of range: detailed



[Link to variable definitions](../modelattrs/variable_definitions.md)

