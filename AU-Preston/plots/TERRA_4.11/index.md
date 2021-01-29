# AU-Preston: TERRA_4.11

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |   MAE |     MBE |    NSD |      R |
|:-------|:-------------|------:|--------:|-------:|-------:|
| SWnet  | baseline     | 14.83 |  14.831 | 0.9168 | 0.9999 |
| SWnet  | detailed     | 33.57 |  -1.014 | 0.8635 | 0.9842 |
| LWnet  | baseline     | 33.19 |  32.651 | 0.4878 | 0.9842 |
| LWnet  | detailed     | 35.45 |  34.878 | 0.4294 | 0.9808 |
| Qle    | baseline     | 32.03 | -24.899 | 0.1611 | 0.5335 |
| Qle    | detailed     | 31.78 | -24.589 | 0.1536 | 0.5338 |
| Qh     | baseline     | 93.01 |  92.309 | 1.4132 | 0.9217 |
| Qh     | detailed     | 66.74 |  65.842 | 1.4127 | 0.9363 |

MAE = mean absolute error
MBE = mean bias error
NSD = ratio of model to obs standard deviation
R = Pearson's correlation

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
[![TERRA_4.11_AU-Preston_LWnet.png](TERRA_4.11_AU-Preston_LWnet.png)](TERRA_4.11_AU-Preston_LWnet.png)

### <a name="lwup"></a>LWup
[![TERRA_4.11_AU-Preston_LWup.png](TERRA_4.11_AU-Preston_LWup.png)](TERRA_4.11_AU-Preston_LWup.png)

### <a name="qh"></a>Qh
[![TERRA_4.11_AU-Preston_Qh.png](TERRA_4.11_AU-Preston_Qh.png)](TERRA_4.11_AU-Preston_Qh.png)

### <a name="qle"></a>Qle
[![TERRA_4.11_AU-Preston_Qle.png](TERRA_4.11_AU-Preston_Qle.png)](TERRA_4.11_AU-Preston_Qle.png)

### <a name="swnet"></a>SWnet
[![TERRA_4.11_AU-Preston_SWnet.png](TERRA_4.11_AU-Preston_SWnet.png)](TERRA_4.11_AU-Preston_SWnet.png)

### <a name="swnet_subset_baseline"></a>SWnet_subset_baseline
[![TERRA_4.11_AU-Preston_SWnet_subset_baseline.png](TERRA_4.11_AU-Preston_SWnet_subset_baseline.png)](TERRA_4.11_AU-Preston_SWnet_subset_baseline.png)

### <a name="swnet_subset_detailed"></a>SWnet_subset_detailed
[![TERRA_4.11_AU-Preston_SWnet_subset_detailed.png](TERRA_4.11_AU-Preston_SWnet_subset_detailed.png)](TERRA_4.11_AU-Preston_SWnet_subset_detailed.png)

### <a name="swup"></a>SWup
[![TERRA_4.11_AU-Preston_SWup.png](TERRA_4.11_AU-Preston_SWup.png)](TERRA_4.11_AU-Preston_SWup.png)

### <a name="swup_subset_baseline"></a>SWup_subset_baseline
[![TERRA_4.11_AU-Preston_SWup_subset_baseline.png](TERRA_4.11_AU-Preston_SWup_subset_baseline.png)](TERRA_4.11_AU-Preston_SWup_subset_baseline.png)

### <a name="swup_subset_detailed"></a>SWup_subset_detailed
[![TERRA_4.11_AU-Preston_SWup_subset_detailed.png](TERRA_4.11_AU-Preston_SWup_subset_detailed.png)](TERRA_4.11_AU-Preston_SWup_subset_detailed.png)

### <a name="closure_baseline"></a>closure_baseline
[![TERRA_4.11_AU-Preston_closure_baseline.png](TERRA_4.11_AU-Preston_closure_baseline.png)](TERRA_4.11_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![TERRA_4.11_AU-Preston_closure_detailed.png](TERRA_4.11_AU-Preston_closure_detailed.png)](TERRA_4.11_AU-Preston_closure_detailed.png)

### out of range: baseline

 - TERRA_4.11 Qh max value of 733.2882 is greater than expected 600.0 [W/m2]
 - TERRA_4.11 SWup min value of -443.5046 is less than expected 0.0 [W/m2]
 - TERRA_4.11 alb min value of -0.9981 is less than expected 0.0 [1]

### out of range: detailed

 - TERRA_4.11 Qh max value of 655.5526 is greater than expected 600.0 [W/m2]
 - TERRA_4.11 SWup min value of -392.7304 is less than expected 0.0 [W/m2]
 - TERRA_4.11 alb min value of -0.9995 is less than expected 0.0 [1]


[Link to variable definitions](variable_definitions.md)

