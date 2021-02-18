# AU-Preston: ASLUMv2.0

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |      MAE |       MBE |      NSD |        R |       NMAE |
|:-------|:-------------|---------:|----------:|---------:|---------:|-----------:|
| SWnet  | baseline     |  6.6834  | -6.05596  | 0.852891 | 0.999908 | 0.0230204  |
| SWnet  | detailed     |  2.76242 |  0.97389  | 0.873157 | 0.999901 | 0.00951492 |
| LWnet  | baseline     | 10.3624  | -0.265008 | 1.05969  | 0.965052 | 0.146542   |
| LWnet  | detailed     |  7.69378 |  1.71794  | 0.97688  | 0.975403 | 0.108803   |
| Qle    | baseline     | 24.855   |  1.03968  | 0.863984 | 0.650585 | 0.752786   |
| Qle    | detailed     | 27.9454  | 11.5054   | 1.04417  | 0.663451 | 0.846386   |
| Qh     | baseline     | 20.4404  | -6.6682   | 0.859524 | 0.937649 | 0.547615   |
| Qh     | detailed     | 22.1163  |  1.25815  | 1.12145  | 0.92145  | 0.592512   |

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
[![ASLUMv2.0_AU-Preston_LWnet.png](ASLUMv2.0_AU-Preston_LWnet.png)](ASLUMv2.0_AU-Preston_LWnet.png)

### <a name="lwup"></a>LWup
[![ASLUMv2.0_AU-Preston_LWup.png](ASLUMv2.0_AU-Preston_LWup.png)](ASLUMv2.0_AU-Preston_LWup.png)

### <a name="qh"></a>Qh
[![ASLUMv2.0_AU-Preston_Qh.png](ASLUMv2.0_AU-Preston_Qh.png)](ASLUMv2.0_AU-Preston_Qh.png)

### <a name="qle"></a>Qle
[![ASLUMv2.0_AU-Preston_Qle.png](ASLUMv2.0_AU-Preston_Qle.png)](ASLUMv2.0_AU-Preston_Qle.png)

### <a name="swnet"></a>SWnet
[![ASLUMv2.0_AU-Preston_SWnet.png](ASLUMv2.0_AU-Preston_SWnet.png)](ASLUMv2.0_AU-Preston_SWnet.png)

### <a name="swnet_subset_baseline"></a>SWnet_subset_baseline
[![ASLUMv2.0_AU-Preston_SWnet_subset_baseline.png](ASLUMv2.0_AU-Preston_SWnet_subset_baseline.png)](ASLUMv2.0_AU-Preston_SWnet_subset_baseline.png)

### <a name="swnet_subset_detailed"></a>SWnet_subset_detailed
[![ASLUMv2.0_AU-Preston_SWnet_subset_detailed.png](ASLUMv2.0_AU-Preston_SWnet_subset_detailed.png)](ASLUMv2.0_AU-Preston_SWnet_subset_detailed.png)

### <a name="swup"></a>SWup
[![ASLUMv2.0_AU-Preston_SWup.png](ASLUMv2.0_AU-Preston_SWup.png)](ASLUMv2.0_AU-Preston_SWup.png)

### <a name="swup_subset_baseline"></a>SWup_subset_baseline
[![ASLUMv2.0_AU-Preston_SWup_subset_baseline.png](ASLUMv2.0_AU-Preston_SWup_subset_baseline.png)](ASLUMv2.0_AU-Preston_SWup_subset_baseline.png)

### <a name="swup_subset_detailed"></a>SWup_subset_detailed
[![ASLUMv2.0_AU-Preston_SWup_subset_detailed.png](ASLUMv2.0_AU-Preston_SWup_subset_detailed.png)](ASLUMv2.0_AU-Preston_SWup_subset_detailed.png)

### <a name="closure_baseline"></a>closure_baseline
[![ASLUMv2.0_AU-Preston_closure_baseline.png](ASLUMv2.0_AU-Preston_closure_baseline.png)](ASLUMv2.0_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![ASLUMv2.0_AU-Preston_closure_detailed.png](ASLUMv2.0_AU-Preston_closure_detailed.png)](ASLUMv2.0_AU-Preston_closure_detailed.png)

### out of range: baseline


### out of range: detailed

 - ASLUMv2.0 Qh max value of 744.3455 is greater than expected 600.0 [W/m2]
 - ASLUMv2.0 ESoil max value of 0.0003 is greater than expected 0.0003 [kg/m2/s]


[Link to variable definitions](../modelattrs/variable_definitions.md)

