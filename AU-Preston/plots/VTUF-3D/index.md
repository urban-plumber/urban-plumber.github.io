# AU-Preston: VTUF-3D

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |     MAE |       MBE |      NSD |        R |      NMAE |
|:-------|:-------------|--------:|----------:|---------:|---------:|----------:|
| SWnet  | baseline     | 20.5319 |  17.1963  | 0.929545 | 0.993021 | 0.0707204 |
| SWnet  | detailed     | 17.5564 |  14.2184  | 0.92067  | 0.993016 | 0.0604716 |
| LWnet  | baseline     | 11.1539 |   5.00609 | 0.766411 | 0.941009 | 0.157736  |
| LWnet  | detailed     | 11.2747 |   5.16051 | 0.764142 | 0.939679 | 0.159444  |
| Qle    | baseline     | 28.6302 | -16.1801  | 0.431989 | 0.502977 | 0.867126  |
| Qle    | detailed     | 28.6308 | -16.1797  | 0.431988 | 0.502977 | 0.867144  |
| Qh     | baseline     | 24.9385 |  -6.5701  | 0.8155   | 0.920659 | 0.668121  |
| Qh     | detailed     | 25.2898 |  -7.45652 | 0.80219  | 0.919343 | 0.677534  |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)

### jump to figure:
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

### <a name="lwnet"></a>LWnet
[![VTUF-3D_AU-Preston_LWnet.png](VTUF-3D_AU-Preston_LWnet.png)](VTUF-3D_AU-Preston_LWnet.png)

### <a name="lwup"></a>LWup
[![VTUF-3D_AU-Preston_LWup.png](VTUF-3D_AU-Preston_LWup.png)](VTUF-3D_AU-Preston_LWup.png)

### <a name="qh"></a>Qh
[![VTUF-3D_AU-Preston_Qh.png](VTUF-3D_AU-Preston_Qh.png)](VTUF-3D_AU-Preston_Qh.png)

### <a name="qle"></a>Qle
[![VTUF-3D_AU-Preston_Qle.png](VTUF-3D_AU-Preston_Qle.png)](VTUF-3D_AU-Preston_Qle.png)

### <a name="swnet"></a>SWnet
[![VTUF-3D_AU-Preston_SWnet.png](VTUF-3D_AU-Preston_SWnet.png)](VTUF-3D_AU-Preston_SWnet.png)

### <a name="swnet_subset_baseline"></a>SWnet_subset_baseline
[![VTUF-3D_AU-Preston_SWnet_subset_baseline.png](VTUF-3D_AU-Preston_SWnet_subset_baseline.png)](VTUF-3D_AU-Preston_SWnet_subset_baseline.png)

### <a name="swnet_subset_detailed"></a>SWnet_subset_detailed
[![VTUF-3D_AU-Preston_SWnet_subset_detailed.png](VTUF-3D_AU-Preston_SWnet_subset_detailed.png)](VTUF-3D_AU-Preston_SWnet_subset_detailed.png)

### <a name="swup"></a>SWup
[![VTUF-3D_AU-Preston_SWup.png](VTUF-3D_AU-Preston_SWup.png)](VTUF-3D_AU-Preston_SWup.png)

### <a name="swup_subset_baseline"></a>SWup_subset_baseline
[![VTUF-3D_AU-Preston_SWup_subset_baseline.png](VTUF-3D_AU-Preston_SWup_subset_baseline.png)](VTUF-3D_AU-Preston_SWup_subset_baseline.png)

### <a name="swup_subset_detailed"></a>SWup_subset_detailed
[![VTUF-3D_AU-Preston_SWup_subset_detailed.png](VTUF-3D_AU-Preston_SWup_subset_detailed.png)](VTUF-3D_AU-Preston_SWup_subset_detailed.png)

### <a name="closure_baseline"></a>closure_baseline
[![VTUF-3D_AU-Preston_closure_baseline.png](VTUF-3D_AU-Preston_closure_baseline.png)](VTUF-3D_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![VTUF-3D_AU-Preston_closure_detailed.png](VTUF-3D_AU-Preston_closure_detailed.png)](VTUF-3D_AU-Preston_closure_detailed.png)

### out of range: baseline

 - VTUF-3D SWnet min value of -0.0002 is less than expected 0.0 [W/m2]

### out of range: detailed

 - VTUF-3D SWnet min value of -0.0003 is less than expected 0.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

