# AU-Preston: CLMU5

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |   MAE |     MBE |    NSD |      R |
|:-------|:-------------|------:|--------:|-------:|-------:|
| SWnet  | baseline     |  2.84 |  -0.959 | 0.8718 | 0.9999 |
| SWnet  | detailed     |  2.61 |   0.036 | 0.873  | 0.9999 |
| LWnet  | baseline     | 12.22 | -10.037 | 1.0947 | 0.9679 |
| LWnet  | detailed     | 12.84 | -10.758 | 1.1167 | 0.9655 |
| Qle    | baseline     | 25.33 |  -5.396 | 0.8196 | 0.6365 |
| Qle    | detailed     | 25    |  -6.45  | 0.7905 | 0.6338 |
| Qh     | baseline     | 24.3  |   7.863 | 1.1166 | 0.9352 |
| Qh     | detailed     | 23.12 |   7.494 | 1.0894 | 0.9376 |

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
 - [SWnet_subset_baseline](#swnet_subset_baseline)
 - [SWnet_subset_detailed](#swnet_subset_detailed)
 - [SWup](#swup)
 - [SWup_subset_baseline](#swup_subset_baseline)
 - [SWup_subset_detailed](#swup_subset_detailed)
 - [closure_baseline](#closure_baseline)
 - [closure_detailed](#closure_detailed)

[Link to variable definitions](variable_definitions.md)

### <a name="albedo"></a>Albedo
[![CLMU5_AU-Preston_Albedo.png](CLMU5_AU-Preston_Albedo.png)](CLMU5_AU-Preston_Albedo.png)

### <a name="lwnet"></a>LWnet
[![CLMU5_AU-Preston_LWnet.png](CLMU5_AU-Preston_LWnet.png)](CLMU5_AU-Preston_LWnet.png)

### <a name="lwup"></a>LWup
[![CLMU5_AU-Preston_LWup.png](CLMU5_AU-Preston_LWup.png)](CLMU5_AU-Preston_LWup.png)

### <a name="qh"></a>Qh
[![CLMU5_AU-Preston_Qh.png](CLMU5_AU-Preston_Qh.png)](CLMU5_AU-Preston_Qh.png)

### <a name="qle"></a>Qle
[![CLMU5_AU-Preston_Qle.png](CLMU5_AU-Preston_Qle.png)](CLMU5_AU-Preston_Qle.png)

### <a name="swnet"></a>SWnet
[![CLMU5_AU-Preston_SWnet.png](CLMU5_AU-Preston_SWnet.png)](CLMU5_AU-Preston_SWnet.png)

### <a name="swnet_subset_baseline"></a>SWnet_subset_baseline
[![CLMU5_AU-Preston_SWnet_subset_baseline.png](CLMU5_AU-Preston_SWnet_subset_baseline.png)](CLMU5_AU-Preston_SWnet_subset_baseline.png)

### <a name="swnet_subset_detailed"></a>SWnet_subset_detailed
[![CLMU5_AU-Preston_SWnet_subset_detailed.png](CLMU5_AU-Preston_SWnet_subset_detailed.png)](CLMU5_AU-Preston_SWnet_subset_detailed.png)

### <a name="swup"></a>SWup
[![CLMU5_AU-Preston_SWup.png](CLMU5_AU-Preston_SWup.png)](CLMU5_AU-Preston_SWup.png)

### <a name="swup_subset_baseline"></a>SWup_subset_baseline
[![CLMU5_AU-Preston_SWup_subset_baseline.png](CLMU5_AU-Preston_SWup_subset_baseline.png)](CLMU5_AU-Preston_SWup_subset_baseline.png)

### <a name="swup_subset_detailed"></a>SWup_subset_detailed
[![CLMU5_AU-Preston_SWup_subset_detailed.png](CLMU5_AU-Preston_SWup_subset_detailed.png)](CLMU5_AU-Preston_SWup_subset_detailed.png)

### <a name="closure_baseline"></a>closure_baseline
[![CLMU5_AU-Preston_closure_baseline.png](CLMU5_AU-Preston_closure_baseline.png)](CLMU5_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![CLMU5_AU-Preston_closure_detailed.png](CLMU5_AU-Preston_closure_detailed.png)](CLMU5_AU-Preston_closure_detailed.png)

### out of range: baseline

 - CLMU5 SWup min value of -398.8712 is less than expected 0.0 [W/m2]
 - CLMU5 alb min value of -0.9996 is less than expected 0.0 [1]

### out of range: detailed

 - CLMU5 SWup min value of -400.3411 is less than expected 0.0 [W/m2]
 - CLMU5 alb min value of -0.9914 is less than expected 0.0 [1]


[Link to variable definitions](variable_definitions.md)

