# AU-Preston: TEB-SPARTCS

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |     MAE |       MBE |      NSD |        R |
|:-------|:-------------|--------:|----------:|---------:|---------:|
| SWnet  | baseline     | 10.1684 |   5.28879 | 0.88727  | 0.998684 |
| SWnet  | detailed     | 15.5121 |  12.9248  | 0.910272 | 0.998685 |
| LWnet  | baseline     | 17.5648 | -11.1934  | 1.24545  | 0.937353 |
| LWnet  | detailed     | 13.3807 |  -8.31368 | 1.14575  | 0.95491  |
| Qle    | baseline     | 27.9477 |  -5.32807 | 0.751989 | 0.4673   |
| Qle    | detailed     | 32.0947 |   7.0701  | 1.05947  | 0.508461 |
| Qh     | baseline     | 33.5029 |  25.5641  | 1.25232  | 0.934539 |
| Qh     | detailed     | 28.8241 |  12.3579  | 1.28877  | 0.919311 |

 - MAE: mean absolute error (close to 0 is better)
 - NME: absolute mean error normalised by difference from mean  (closer to 0 is better)
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
[![TEB-SPARTCS_AU-Preston_Albedo.png](TEB-SPARTCS_AU-Preston_Albedo.png)](TEB-SPARTCS_AU-Preston_Albedo.png)

### <a name="lwnet"></a>LWnet
[![TEB-SPARTCS_AU-Preston_LWnet.png](TEB-SPARTCS_AU-Preston_LWnet.png)](TEB-SPARTCS_AU-Preston_LWnet.png)

### <a name="lwup"></a>LWup
[![TEB-SPARTCS_AU-Preston_LWup.png](TEB-SPARTCS_AU-Preston_LWup.png)](TEB-SPARTCS_AU-Preston_LWup.png)

### <a name="qh"></a>Qh
[![TEB-SPARTCS_AU-Preston_Qh.png](TEB-SPARTCS_AU-Preston_Qh.png)](TEB-SPARTCS_AU-Preston_Qh.png)

### <a name="qle"></a>Qle
[![TEB-SPARTCS_AU-Preston_Qle.png](TEB-SPARTCS_AU-Preston_Qle.png)](TEB-SPARTCS_AU-Preston_Qle.png)

### <a name="swnet"></a>SWnet
[![TEB-SPARTCS_AU-Preston_SWnet.png](TEB-SPARTCS_AU-Preston_SWnet.png)](TEB-SPARTCS_AU-Preston_SWnet.png)

### <a name="swnet_subset_baseline"></a>SWnet_subset_baseline
[![TEB-SPARTCS_AU-Preston_SWnet_subset_baseline.png](TEB-SPARTCS_AU-Preston_SWnet_subset_baseline.png)](TEB-SPARTCS_AU-Preston_SWnet_subset_baseline.png)

### <a name="swnet_subset_detailed"></a>SWnet_subset_detailed
[![TEB-SPARTCS_AU-Preston_SWnet_subset_detailed.png](TEB-SPARTCS_AU-Preston_SWnet_subset_detailed.png)](TEB-SPARTCS_AU-Preston_SWnet_subset_detailed.png)

### <a name="swup"></a>SWup
[![TEB-SPARTCS_AU-Preston_SWup.png](TEB-SPARTCS_AU-Preston_SWup.png)](TEB-SPARTCS_AU-Preston_SWup.png)

### <a name="swup_subset_baseline"></a>SWup_subset_baseline
[![TEB-SPARTCS_AU-Preston_SWup_subset_baseline.png](TEB-SPARTCS_AU-Preston_SWup_subset_baseline.png)](TEB-SPARTCS_AU-Preston_SWup_subset_baseline.png)

### <a name="swup_subset_detailed"></a>SWup_subset_detailed
[![TEB-SPARTCS_AU-Preston_SWup_subset_detailed.png](TEB-SPARTCS_AU-Preston_SWup_subset_detailed.png)](TEB-SPARTCS_AU-Preston_SWup_subset_detailed.png)

### <a name="closure_baseline"></a>closure_baseline
[![TEB-SPARTCS_AU-Preston_closure_baseline.png](TEB-SPARTCS_AU-Preston_closure_baseline.png)](TEB-SPARTCS_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![TEB-SPARTCS_AU-Preston_closure_detailed.png](TEB-SPARTCS_AU-Preston_closure_detailed.png)](TEB-SPARTCS_AU-Preston_closure_detailed.png)

### out of range: baseline

 - TEB-SPARTCS TVeg max value of 0.0004 is greater than expected 0.0003 [kg/m2/s]

### out of range: detailed

 - TEB-SPARTCS Qh max value of 614.1366 is greater than expected 600.0 [W/m2]
 - TEB-SPARTCS TVeg max value of 0.0004 is greater than expected 0.0003 [kg/m2/s]


[Link to variable definitions](../modelattrs/variable_definitions.md)

