# AU-Preston: ASLUMv2.0

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |      MAE |       MBE |      NSD |        R |
|:-------|:-------------|---------:|----------:|---------:|---------:|
| SWnet  | baseline     |  6.68486 | -6.05743  | 0.852905 | 0.999908 |
| SWnet  | detailed     |  2.76296 |  0.974014 | 0.873172 | 0.999901 |
| SWup   | baseline     |  6.66965 |  6.03319  | 0.997876 | 0.996944 |
| SWup   | detailed     |  2.76238 | -0.979763 | 0.882148 | 0.996708 |
| LWnet  | baseline     | 10.3624  | -0.265008 | 1.05969  | 0.965052 |
| LWnet  | detailed     |  7.69378 |  1.71794  | 0.97688  | 0.975403 |
| LWup   | baseline     | 10.3624  |  0.265008 | 1.1069   | 0.968975 |
| LWup   | detailed     |  7.69378 | -1.71794  | 1.01174  | 0.975787 |
| Qle    | baseline     | 24.855   |  1.03968  | 0.863984 | 0.650585 |
| Qle    | detailed     | 27.9454  | 11.5054   | 1.04417  | 0.663451 |
| Qh     | baseline     | 20.4404  | -6.6682   | 0.859524 | 0.937649 |
| Qh     | detailed     | 22.1163  |  1.25815  | 1.12145  | 0.92145  |

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
 - [subset_Qg](#subset_qg)
 - [subset_Qh](#subset_qh)
 - [subset_Qle](#subset_qle)
 - [subset_SWnet](#subset_swnet)
 - [subset_SWup](#subset_swup)

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="lwnet"></a>LWnet
[![ASLUMv2.0_AU-Preston_LWnet.png](ASLUMv2.0_AU-Preston_LWnet.png)](ASLUMv2.0_AU-Preston_LWnet.png)

### <a name="lwup"></a>LWup
[![ASLUMv2.0_AU-Preston_LWup.png](ASLUMv2.0_AU-Preston_LWup.png)](ASLUMv2.0_AU-Preston_LWup.png)

### <a name="qh"></a>Qh
[![ASLUMv2.0_AU-Preston_Qh.png](ASLUMv2.0_AU-Preston_Qh.png)](ASLUMv2.0_AU-Preston_Qh.png)

### <a name="qle"></a>Qle
[![ASLUMv2.0_AU-Preston_Qle.png](ASLUMv2.0_AU-Preston_Qle.png)](ASLUMv2.0_AU-Preston_Qle.png)

### <a name="swnet"></a>SWnet
[![ASLUMv2.0_AU-Preston_SWnet.png](ASLUMv2.0_AU-Preston_SWnet.png)](ASLUMv2.0_AU-Preston_SWnet.png)

### <a name="swup"></a>SWup
[![ASLUMv2.0_AU-Preston_SWup.png](ASLUMv2.0_AU-Preston_SWup.png)](ASLUMv2.0_AU-Preston_SWup.png)

### <a name="closure_baseline"></a>closure_baseline
[![ASLUMv2.0_AU-Preston_closure_baseline.png](ASLUMv2.0_AU-Preston_closure_baseline.png)](ASLUMv2.0_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![ASLUMv2.0_AU-Preston_closure_detailed.png](ASLUMv2.0_AU-Preston_closure_detailed.png)](ASLUMv2.0_AU-Preston_closure_detailed.png)

### <a name="subset_qg"></a>subset_Qg
[![ASLUMv2.0_AU-Preston_subset_Qg.png](ASLUMv2.0_AU-Preston_subset_Qg.png)](ASLUMv2.0_AU-Preston_subset_Qg.png)

### <a name="subset_qh"></a>subset_Qh
[![ASLUMv2.0_AU-Preston_subset_Qh.png](ASLUMv2.0_AU-Preston_subset_Qh.png)](ASLUMv2.0_AU-Preston_subset_Qh.png)

### <a name="subset_qle"></a>subset_Qle
[![ASLUMv2.0_AU-Preston_subset_Qle.png](ASLUMv2.0_AU-Preston_subset_Qle.png)](ASLUMv2.0_AU-Preston_subset_Qle.png)

### <a name="subset_swnet"></a>subset_SWnet
[![ASLUMv2.0_AU-Preston_subset_SWnet.png](ASLUMv2.0_AU-Preston_subset_SWnet.png)](ASLUMv2.0_AU-Preston_subset_SWnet.png)

### <a name="subset_swup"></a>subset_SWup
[![ASLUMv2.0_AU-Preston_subset_SWup.png](ASLUMv2.0_AU-Preston_subset_SWup.png)](ASLUMv2.0_AU-Preston_subset_SWup.png)

### out of range: baseline


### out of range: detailed

 - ASLUMv2.0 Qh max value of 744.3455 is greater than expected 600.0 [W/m2]
 - ASLUMv2.0 ESoil max value of 0.0003 is greater than expected 0.0003 [kg/m2/s]


[Link to variable definitions](../modelattrs/variable_definitions.md)

