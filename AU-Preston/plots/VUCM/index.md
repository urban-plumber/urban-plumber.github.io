# AU-Preston: VUCM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |   MAE |    MBE |    NSD |      R |
|:-------|:-------------|------:|-------:|-------:|-------:|
| SWnet  | baseline     |  5.56 |  5.276 | 0.8902 | 0.9999 |
| SWnet  | detailed     |  3.25 |  1.724 | 0.8799 | 0.9999 |
| LWnet  | baseline     |  7.95 |  0.255 | 0.8788 | 0.9773 |
| LWnet  | detailed     | 14.48 | 12.96  | 0.8753 | 0.9624 |
| Qle    | baseline     | 30.07 |  2.033 | 0.8245 | 0.483  |
| Qle    | detailed     | 30.26 |  1.654 | 0.8245 | 0.471  |
| Qh     | baseline     | 27.56 |  8.11  | 1.013  | 0.9068 |
| Qh     | detailed     | 26.12 |  8.954 | 0.9883 | 0.9144 |

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
[![VUCM_AU-Preston_LWnet.png](VUCM_AU-Preston_LWnet.png)](VUCM_AU-Preston_LWnet.png)

### <a name="lwup"></a>LWup
[![VUCM_AU-Preston_LWup.png](VUCM_AU-Preston_LWup.png)](VUCM_AU-Preston_LWup.png)

### <a name="qh"></a>Qh
[![VUCM_AU-Preston_Qh.png](VUCM_AU-Preston_Qh.png)](VUCM_AU-Preston_Qh.png)

### <a name="qle"></a>Qle
[![VUCM_AU-Preston_Qle.png](VUCM_AU-Preston_Qle.png)](VUCM_AU-Preston_Qle.png)

### <a name="swnet"></a>SWnet
[![VUCM_AU-Preston_SWnet.png](VUCM_AU-Preston_SWnet.png)](VUCM_AU-Preston_SWnet.png)

### <a name="swnet_subset_baseline"></a>SWnet_subset_baseline
[![VUCM_AU-Preston_SWnet_subset_baseline.png](VUCM_AU-Preston_SWnet_subset_baseline.png)](VUCM_AU-Preston_SWnet_subset_baseline.png)

### <a name="swnet_subset_detailed"></a>SWnet_subset_detailed
[![VUCM_AU-Preston_SWnet_subset_detailed.png](VUCM_AU-Preston_SWnet_subset_detailed.png)](VUCM_AU-Preston_SWnet_subset_detailed.png)

### <a name="swup"></a>SWup
[![VUCM_AU-Preston_SWup.png](VUCM_AU-Preston_SWup.png)](VUCM_AU-Preston_SWup.png)

### <a name="swup_subset_baseline"></a>SWup_subset_baseline
[![VUCM_AU-Preston_SWup_subset_baseline.png](VUCM_AU-Preston_SWup_subset_baseline.png)](VUCM_AU-Preston_SWup_subset_baseline.png)

### <a name="swup_subset_detailed"></a>SWup_subset_detailed
[![VUCM_AU-Preston_SWup_subset_detailed.png](VUCM_AU-Preston_SWup_subset_detailed.png)](VUCM_AU-Preston_SWup_subset_detailed.png)

### <a name="closure_baseline"></a>closure_baseline
[![VUCM_AU-Preston_closure_baseline.png](VUCM_AU-Preston_closure_baseline.png)](VUCM_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![VUCM_AU-Preston_closure_detailed.png](VUCM_AU-Preston_closure_detailed.png)](VUCM_AU-Preston_closure_detailed.png)

### out of range: baseline

 - VUCM Qh max value of 606.7470 is greater than expected 600.0 [W/m2]
 - VUCM SWup min value of -0.3180 is less than expected 0.0 [W/m2]
 - VUCM alb min value of -0.1534 is less than expected 0.0 [1]

### out of range: detailed

 - VUCM SWup min value of -0.3140 is less than expected 0.0 [W/m2]
 - VUCM alb min value of -0.1506 is less than expected 0.0 [1]


[Link to variable definitions](variable_definitions.md)

