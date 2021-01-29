# AU-Preston: NOAH-SLUCM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |   MAE |     MBE |    NSD |      R |
|:-------|:-------------|------:|--------:|-------:|-------:|
| SWnet  | baseline     |  9.5  |  -9.105 | 0.845  | 0.9999 |
| SWnet  | detailed     |  3.35 |  -1.822 | 0.8669 | 0.9999 |
| LWnet  | baseline     | 20.7  | -20.32  | 1.1835 | 0.9586 |
| LWnet  | detailed     | 22.89 | -22.43  | 1.2528 | 0.9493 |
| Qle    | baseline     | 25.87 | -15.164 | 0.452  | 0.5833 |
| Qle    | detailed     | 25.88 | -15.142 | 0.4536 | 0.5826 |
| Qh     | baseline     | 20.63 |   7.603 | 1.1127 | 0.9476 |
| Qh     | detailed     | 21.08 |   6.386 | 1.1426 | 0.9489 |

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

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="albedo"></a>Albedo
[![NOAH-SLUCM_AU-Preston_Albedo.png](NOAH-SLUCM_AU-Preston_Albedo.png)](NOAH-SLUCM_AU-Preston_Albedo.png)

### <a name="lwnet"></a>LWnet
[![NOAH-SLUCM_AU-Preston_LWnet.png](NOAH-SLUCM_AU-Preston_LWnet.png)](NOAH-SLUCM_AU-Preston_LWnet.png)

### <a name="lwup"></a>LWup
[![NOAH-SLUCM_AU-Preston_LWup.png](NOAH-SLUCM_AU-Preston_LWup.png)](NOAH-SLUCM_AU-Preston_LWup.png)

### <a name="qh"></a>Qh
[![NOAH-SLUCM_AU-Preston_Qh.png](NOAH-SLUCM_AU-Preston_Qh.png)](NOAH-SLUCM_AU-Preston_Qh.png)

### <a name="qle"></a>Qle
[![NOAH-SLUCM_AU-Preston_Qle.png](NOAH-SLUCM_AU-Preston_Qle.png)](NOAH-SLUCM_AU-Preston_Qle.png)

### <a name="swnet"></a>SWnet
[![NOAH-SLUCM_AU-Preston_SWnet.png](NOAH-SLUCM_AU-Preston_SWnet.png)](NOAH-SLUCM_AU-Preston_SWnet.png)

### <a name="swnet_subset_baseline"></a>SWnet_subset_baseline
[![NOAH-SLUCM_AU-Preston_SWnet_subset_baseline.png](NOAH-SLUCM_AU-Preston_SWnet_subset_baseline.png)](NOAH-SLUCM_AU-Preston_SWnet_subset_baseline.png)

### <a name="swnet_subset_detailed"></a>SWnet_subset_detailed
[![NOAH-SLUCM_AU-Preston_SWnet_subset_detailed.png](NOAH-SLUCM_AU-Preston_SWnet_subset_detailed.png)](NOAH-SLUCM_AU-Preston_SWnet_subset_detailed.png)

### <a name="swup"></a>SWup
[![NOAH-SLUCM_AU-Preston_SWup.png](NOAH-SLUCM_AU-Preston_SWup.png)](NOAH-SLUCM_AU-Preston_SWup.png)

### <a name="swup_subset_baseline"></a>SWup_subset_baseline
[![NOAH-SLUCM_AU-Preston_SWup_subset_baseline.png](NOAH-SLUCM_AU-Preston_SWup_subset_baseline.png)](NOAH-SLUCM_AU-Preston_SWup_subset_baseline.png)

### <a name="swup_subset_detailed"></a>SWup_subset_detailed
[![NOAH-SLUCM_AU-Preston_SWup_subset_detailed.png](NOAH-SLUCM_AU-Preston_SWup_subset_detailed.png)](NOAH-SLUCM_AU-Preston_SWup_subset_detailed.png)

### <a name="closure_baseline"></a>closure_baseline
[![NOAH-SLUCM_AU-Preston_closure_baseline.png](NOAH-SLUCM_AU-Preston_closure_baseline.png)](NOAH-SLUCM_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![NOAH-SLUCM_AU-Preston_closure_detailed.png](NOAH-SLUCM_AU-Preston_closure_detailed.png)](NOAH-SLUCM_AU-Preston_closure_detailed.png)

### out of range: baseline

 - NOAH-SLUCM Qsm max value of 103.0613 is greater than expected 0.005 [kg/m2/s]
 - NOAH-SLUCM Qsm min value of -15.2233 is less than expected 0.0 [kg/m2/s]
 - NOAH-SLUCM Qfz min value of -0.0000 is less than expected 0.0 [kg/m2/s]
 - NOAH-SLUCM AvgSurfT max value of 370.4353 is greater than expected 333.0 [K]

### out of range: detailed

 - NOAH-SLUCM Qsm max value of 103.0613 is greater than expected 0.005 [kg/m2/s]
 - NOAH-SLUCM Qsm min value of -15.2233 is less than expected 0.0 [kg/m2/s]
 - NOAH-SLUCM Qfz min value of -0.0000 is less than expected 0.0 [kg/m2/s]


[Link to variable definitions](../modelattrs/variable_definitions.md)

