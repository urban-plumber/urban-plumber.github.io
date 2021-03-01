# AU-Preston: VTUF-3D

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |     MAE |       MBE |      NSD |        R |
|:-------|:-------------|--------:|----------:|---------:|---------:|
| SWnet  | baseline     | 20.5365 |  17.2002  | 0.92956  | 0.993019 |
| SWnet  | detailed     | 17.5603 |  14.2214  | 0.920685 | 0.993014 |
| SWup   | baseline     | 18.8836 | -18.8834  | 0.549533 | 0.996363 |
| SWup   | detailed     | 15.9026 | -15.899   | 0.600387 | 0.996551 |
| LWnet  | baseline     | 11.1539 |   5.00609 | 0.766411 | 0.941009 |
| LWnet  | detailed     | 11.2747 |   5.16051 | 0.764142 | 0.939679 |
| LWup   | baseline     | 10.8391 |  -4.66726 | 0.698409 | 0.962328 |
| LWup   | detailed     | 10.9599 |  -4.82259 | 0.695423 | 0.961216 |
| Qle    | baseline     | 28.6302 | -16.1801  | 0.431989 | 0.502977 |
| Qle    | detailed     | 28.6308 | -16.1797  | 0.431988 | 0.502977 |
| Qh     | baseline     | 24.9385 |  -6.5701  | 0.8155   | 0.920659 |
| Qh     | detailed     | 25.2898 |  -7.45652 | 0.80219  | 0.919343 |

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
 - [SWup](#swup)
 - [closure_baseline](#closure_baseline)
 - [closure_detailed](#closure_detailed)
 - [subset_Qh](#subset_qh)
 - [subset_Qle](#subset_qle)
 - [subset_SWnet](#subset_swnet)
 - [subset_SWup](#subset_swup)

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

### <a name="swup"></a>SWup
[![VTUF-3D_AU-Preston_SWup.png](VTUF-3D_AU-Preston_SWup.png)](VTUF-3D_AU-Preston_SWup.png)

### <a name="closure_baseline"></a>closure_baseline
[![VTUF-3D_AU-Preston_closure_baseline.png](VTUF-3D_AU-Preston_closure_baseline.png)](VTUF-3D_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![VTUF-3D_AU-Preston_closure_detailed.png](VTUF-3D_AU-Preston_closure_detailed.png)](VTUF-3D_AU-Preston_closure_detailed.png)

### <a name="subset_qh"></a>subset_Qh
[![VTUF-3D_AU-Preston_subset_Qh.png](VTUF-3D_AU-Preston_subset_Qh.png)](VTUF-3D_AU-Preston_subset_Qh.png)

### <a name="subset_qle"></a>subset_Qle
[![VTUF-3D_AU-Preston_subset_Qle.png](VTUF-3D_AU-Preston_subset_Qle.png)](VTUF-3D_AU-Preston_subset_Qle.png)

### <a name="subset_swnet"></a>subset_SWnet
[![VTUF-3D_AU-Preston_subset_SWnet.png](VTUF-3D_AU-Preston_subset_SWnet.png)](VTUF-3D_AU-Preston_subset_SWnet.png)

### <a name="subset_swup"></a>subset_SWup
[![VTUF-3D_AU-Preston_subset_SWup.png](VTUF-3D_AU-Preston_subset_SWup.png)](VTUF-3D_AU-Preston_subset_SWup.png)

### out of range: baseline

 - VTUF-3D SWnet min value of -0.0002 is less than expected 0.0 [W/m2]

### out of range: detailed

 - VTUF-3D SWnet min value of -0.0003 is less than expected 0.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

