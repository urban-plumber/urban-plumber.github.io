# AU-Preston: UT&C

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |   MAE |    MBE |    NSD |      R |
|:-------|:-------------|------:|-------:|-------:|-------:|
| SWnet  | baseline     | 12.49 | 12.158 | 0.9103 | 0.9999 |
| SWnet  | detailed     |  4.16 |  3.34  | 0.8838 | 0.9999 |
| LWnet  | baseline     | 11.03 | -9.175 | 1.0185 | 0.9772 |
| LWnet  | detailed     | 11.98 | -9.525 | 1.0332 | 0.9714 |
| Qle    | baseline     | 26.13 | 10.603 | 0.9376 | 0.6704 |
| Qle    | detailed     | 23.83 |  3.91  | 0.8121 | 0.654  |
| Qh     | baseline     | 27.15 | 16.054 | 1.1686 | 0.9355 |
| Qh     | detailed     | 26.31 | 16.534 | 1.1226 | 0.9363 |

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

[Link to variable definitions](variable_definitions.md)

### <a name="lwnet"></a>LWnet
[![UT&C_AU-Preston_LWnet.png](UT&C_AU-Preston_LWnet.png)](UT&C_AU-Preston_LWnet.png)

### <a name="lwup"></a>LWup
[![UT&C_AU-Preston_LWup.png](UT&C_AU-Preston_LWup.png)](UT&C_AU-Preston_LWup.png)

### <a name="qh"></a>Qh
[![UT&C_AU-Preston_Qh.png](UT&C_AU-Preston_Qh.png)](UT&C_AU-Preston_Qh.png)

### <a name="qle"></a>Qle
[![UT&C_AU-Preston_Qle.png](UT&C_AU-Preston_Qle.png)](UT&C_AU-Preston_Qle.png)

### <a name="swnet"></a>SWnet
[![UT&C_AU-Preston_SWnet.png](UT&C_AU-Preston_SWnet.png)](UT&C_AU-Preston_SWnet.png)

### <a name="swnet_subset_baseline"></a>SWnet_subset_baseline
[![UT&C_AU-Preston_SWnet_subset_baseline.png](UT&C_AU-Preston_SWnet_subset_baseline.png)](UT&C_AU-Preston_SWnet_subset_baseline.png)

### <a name="swnet_subset_detailed"></a>SWnet_subset_detailed
[![UT&C_AU-Preston_SWnet_subset_detailed.png](UT&C_AU-Preston_SWnet_subset_detailed.png)](UT&C_AU-Preston_SWnet_subset_detailed.png)

### <a name="swup"></a>SWup
[![UT&C_AU-Preston_SWup.png](UT&C_AU-Preston_SWup.png)](UT&C_AU-Preston_SWup.png)

### <a name="swup_subset_baseline"></a>SWup_subset_baseline
[![UT&C_AU-Preston_SWup_subset_baseline.png](UT&C_AU-Preston_SWup_subset_baseline.png)](UT&C_AU-Preston_SWup_subset_baseline.png)

### <a name="swup_subset_detailed"></a>SWup_subset_detailed
[![UT&C_AU-Preston_SWup_subset_detailed.png](UT&C_AU-Preston_SWup_subset_detailed.png)](UT&C_AU-Preston_SWup_subset_detailed.png)

### <a name="closure_baseline"></a>closure_baseline
[![UT&C_AU-Preston_closure_baseline.png](UT&C_AU-Preston_closure_baseline.png)](UT&C_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![UT&C_AU-Preston_closure_detailed.png](UT&C_AU-Preston_closure_detailed.png)](UT&C_AU-Preston_closure_detailed.png)

### out of range: baseline

 - UT&C SWup min value of -436.2685 is less than expected 0.0 [W/m2]
 - UT&C alb min value of -0.9974 is less than expected 0.0 [1]

### out of range: detailed

 - UT&C SWup min value of -409.7354 is less than expected 0.0 [W/m2]
 - UT&C alb min value of -0.9970 is less than expected 0.0 [1]


[Link to variable definitions](variable_definitions.md)

