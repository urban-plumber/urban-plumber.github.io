# AU-Preston: BEPCOL

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |   MAE |     MBE |    NSD |      R |
|:-------|:-------------|------:|--------:|-------:|-------:|
| SWnet  | baseline     |  5.79 |   5.653 | 0.891  | 1      |
| SWnet  | detailed     |  3.35 |   3.019 | 0.8825 | 0.9999 |
| LWnet  | baseline     | 15.48 | -14.935 | 0.988  | 0.9791 |
| LWnet  | detailed     | 17.61 | -15.927 | 1.0375 | 0.9619 |
| Qle    | baseline     | 30.2  | -13.088 | 0.6607 | 0.3952 |
| Qle    | detailed     | 29.05 | -14.809 | 0.6684 | 0.4792 |
| Qh     | baseline     | 38.54 |  28.518 | 1.3403 | 0.9272 |
| Qh     | detailed     | 38.39 |  32.11  | 1.1847 | 0.9214 |

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
[![BEPCOL_AU-Preston_Albedo.png](BEPCOL_AU-Preston_Albedo.png)](BEPCOL_AU-Preston_Albedo.png)

### <a name="lwnet"></a>LWnet
[![BEPCOL_AU-Preston_LWnet.png](BEPCOL_AU-Preston_LWnet.png)](BEPCOL_AU-Preston_LWnet.png)

### <a name="lwup"></a>LWup
[![BEPCOL_AU-Preston_LWup.png](BEPCOL_AU-Preston_LWup.png)](BEPCOL_AU-Preston_LWup.png)

### <a name="qh"></a>Qh
[![BEPCOL_AU-Preston_Qh.png](BEPCOL_AU-Preston_Qh.png)](BEPCOL_AU-Preston_Qh.png)

### <a name="qle"></a>Qle
[![BEPCOL_AU-Preston_Qle.png](BEPCOL_AU-Preston_Qle.png)](BEPCOL_AU-Preston_Qle.png)

### <a name="swnet"></a>SWnet
[![BEPCOL_AU-Preston_SWnet.png](BEPCOL_AU-Preston_SWnet.png)](BEPCOL_AU-Preston_SWnet.png)

### <a name="swnet_subset_baseline"></a>SWnet_subset_baseline
[![BEPCOL_AU-Preston_SWnet_subset_baseline.png](BEPCOL_AU-Preston_SWnet_subset_baseline.png)](BEPCOL_AU-Preston_SWnet_subset_baseline.png)

### <a name="swnet_subset_detailed"></a>SWnet_subset_detailed
[![BEPCOL_AU-Preston_SWnet_subset_detailed.png](BEPCOL_AU-Preston_SWnet_subset_detailed.png)](BEPCOL_AU-Preston_SWnet_subset_detailed.png)

### <a name="swup"></a>SWup
[![BEPCOL_AU-Preston_SWup.png](BEPCOL_AU-Preston_SWup.png)](BEPCOL_AU-Preston_SWup.png)

### <a name="swup_subset_baseline"></a>SWup_subset_baseline
[![BEPCOL_AU-Preston_SWup_subset_baseline.png](BEPCOL_AU-Preston_SWup_subset_baseline.png)](BEPCOL_AU-Preston_SWup_subset_baseline.png)

### <a name="swup_subset_detailed"></a>SWup_subset_detailed
[![BEPCOL_AU-Preston_SWup_subset_detailed.png](BEPCOL_AU-Preston_SWup_subset_detailed.png)](BEPCOL_AU-Preston_SWup_subset_detailed.png)

### <a name="closure_baseline"></a>closure_baseline
[![BEPCOL_AU-Preston_closure_baseline.png](BEPCOL_AU-Preston_closure_baseline.png)](BEPCOL_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![BEPCOL_AU-Preston_closure_detailed.png](BEPCOL_AU-Preston_closure_detailed.png)](BEPCOL_AU-Preston_closure_detailed.png)

### out of range: baseline

 - BEPCOL Qh max value of 777.1300 is greater than expected 600.0 [W/m2]

### out of range: detailed

 - BEPCOL Qh max value of 726.0000 is greater than expected 600.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

