# AU-Preston: ASLUMv3.1

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |      MAE |        MBE |      NSD |        R |      NMAE |
|:-------|:-------------|---------:|-----------:|---------:|---------:|----------:|
| SWnet  | baseline     |  3.02656 |   0.574647 | 0.876165 | 0.999878 | 0.0104247 |
| SWnet  | detailed     |  5.23381 |   3.60529  | 0.881326 | 0.999686 | 0.0180274 |
| LWnet  | baseline     |  9.41164 |   3.18835  | 1.02734  | 0.971659 | 0.133097  |
| LWnet  | detailed     |  7.18022 |   3.59711  | 0.936578 | 0.98053  | 0.101541  |
| Qle    | baseline     | 25.9497  |  -3.97237  | 0.821213 | 0.622819 | 0.785943  |
| Qle    | detailed     | 27.5589  |   8.56075  | 1.01074  | 0.652777 | 0.834681  |
| Qh     | baseline     | 23.5725  | -13.5445   | 0.754718 | 0.93544  | 0.631526  |
| Qh     | detailed     | 22.0004  | -12.0841   | 0.918674 | 0.933932 | 0.589409  |

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
[![ASLUMv3.1_AU-Preston_LWnet.png](ASLUMv3.1_AU-Preston_LWnet.png)](ASLUMv3.1_AU-Preston_LWnet.png)

### <a name="lwup"></a>LWup
[![ASLUMv3.1_AU-Preston_LWup.png](ASLUMv3.1_AU-Preston_LWup.png)](ASLUMv3.1_AU-Preston_LWup.png)

### <a name="qh"></a>Qh
[![ASLUMv3.1_AU-Preston_Qh.png](ASLUMv3.1_AU-Preston_Qh.png)](ASLUMv3.1_AU-Preston_Qh.png)

### <a name="qle"></a>Qle
[![ASLUMv3.1_AU-Preston_Qle.png](ASLUMv3.1_AU-Preston_Qle.png)](ASLUMv3.1_AU-Preston_Qle.png)

### <a name="swnet"></a>SWnet
[![ASLUMv3.1_AU-Preston_SWnet.png](ASLUMv3.1_AU-Preston_SWnet.png)](ASLUMv3.1_AU-Preston_SWnet.png)

### <a name="swnet_subset_baseline"></a>SWnet_subset_baseline
[![ASLUMv3.1_AU-Preston_SWnet_subset_baseline.png](ASLUMv3.1_AU-Preston_SWnet_subset_baseline.png)](ASLUMv3.1_AU-Preston_SWnet_subset_baseline.png)

### <a name="swnet_subset_detailed"></a>SWnet_subset_detailed
[![ASLUMv3.1_AU-Preston_SWnet_subset_detailed.png](ASLUMv3.1_AU-Preston_SWnet_subset_detailed.png)](ASLUMv3.1_AU-Preston_SWnet_subset_detailed.png)

### <a name="swup"></a>SWup
[![ASLUMv3.1_AU-Preston_SWup.png](ASLUMv3.1_AU-Preston_SWup.png)](ASLUMv3.1_AU-Preston_SWup.png)

### <a name="swup_subset_baseline"></a>SWup_subset_baseline
[![ASLUMv3.1_AU-Preston_SWup_subset_baseline.png](ASLUMv3.1_AU-Preston_SWup_subset_baseline.png)](ASLUMv3.1_AU-Preston_SWup_subset_baseline.png)

### <a name="swup_subset_detailed"></a>SWup_subset_detailed
[![ASLUMv3.1_AU-Preston_SWup_subset_detailed.png](ASLUMv3.1_AU-Preston_SWup_subset_detailed.png)](ASLUMv3.1_AU-Preston_SWup_subset_detailed.png)

### <a name="closure_baseline"></a>closure_baseline
[![ASLUMv3.1_AU-Preston_closure_baseline.png](ASLUMv3.1_AU-Preston_closure_baseline.png)](ASLUMv3.1_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![ASLUMv3.1_AU-Preston_closure_detailed.png](ASLUMv3.1_AU-Preston_closure_detailed.png)](ASLUMv3.1_AU-Preston_closure_detailed.png)

### out of range: baseline


### out of range: detailed

 - ASLUMv3.1 ESoil max value of 0.0003 is greater than expected 0.0003 [kg/m2/s]


[Link to variable definitions](../modelattrs/variable_definitions.md)

