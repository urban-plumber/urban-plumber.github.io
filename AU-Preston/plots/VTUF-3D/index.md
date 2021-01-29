# AU-Preston: VTUF-3D

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |   MAE |     MBE |    NSD |      R |
|:-------|:-------------|------:|--------:|-------:|-------:|
| SWnet  | baseline     | 20.54 |  17.2   | 0.9296 | 0.993  |
| SWnet  | detailed     | 17.56 |  14.221 | 0.9207 | 0.993  |
| LWnet  | baseline     | 11.15 |   5.006 | 0.7664 | 0.941  |
| LWnet  | detailed     | 11.27 |   5.161 | 0.7641 | 0.9397 |
| Qle    | baseline     | 28.64 | -16.216 | 0.4319 | 0.5041 |
| Qle    | detailed     | 28.64 | -16.215 | 0.4319 | 0.5041 |
| Qh     | baseline     | 24.95 |  -6.555 | 0.8154 | 0.9206 |
| Qh     | detailed     | 25.3  |  -7.441 | 0.8021 | 0.9193 |

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

