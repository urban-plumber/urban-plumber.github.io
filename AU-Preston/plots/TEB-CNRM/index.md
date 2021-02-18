# AU-Preston: TEB-CNRM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |     MAE |       MBE |      NSD |        R |
|:-------|:-------------|--------:|----------:|---------:|---------:|
| SWnet  | baseline     | 10.2019 |   5.3249  | 0.887547 | 0.998684 |
| SWnet  | detailed     | 11.4215 |   7.29483 | 0.893415 | 0.998683 |
| LWnet  | baseline     | 17.3434 | -10.0063  | 1.2299   | 0.935575 |
| LWnet  | detailed     | 11.8745 |  -3.03027 | 1.0652   | 0.95462  |
| Qle    | baseline     | 27.9441 |  -5.33554 | 0.750799 | 0.467579 |
| Qle    | detailed     | 31.3471 |   7.18454 | 1.0221   | 0.515388 |
| Qh     | baseline     | 34.2178 |  26.6876  | 1.25471  | 0.934511 |
| Qh     | detailed     | 29.4299 |  14.3521  | 1.27547  | 0.918854 |

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
[![TEB-CNRM_AU-Preston_Albedo.png](TEB-CNRM_AU-Preston_Albedo.png)](TEB-CNRM_AU-Preston_Albedo.png)

### <a name="lwnet"></a>LWnet
[![TEB-CNRM_AU-Preston_LWnet.png](TEB-CNRM_AU-Preston_LWnet.png)](TEB-CNRM_AU-Preston_LWnet.png)

### <a name="lwup"></a>LWup
[![TEB-CNRM_AU-Preston_LWup.png](TEB-CNRM_AU-Preston_LWup.png)](TEB-CNRM_AU-Preston_LWup.png)

### <a name="qh"></a>Qh
[![TEB-CNRM_AU-Preston_Qh.png](TEB-CNRM_AU-Preston_Qh.png)](TEB-CNRM_AU-Preston_Qh.png)

### <a name="qle"></a>Qle
[![TEB-CNRM_AU-Preston_Qle.png](TEB-CNRM_AU-Preston_Qle.png)](TEB-CNRM_AU-Preston_Qle.png)

### <a name="swnet"></a>SWnet
[![TEB-CNRM_AU-Preston_SWnet.png](TEB-CNRM_AU-Preston_SWnet.png)](TEB-CNRM_AU-Preston_SWnet.png)

### <a name="swnet_subset_baseline"></a>SWnet_subset_baseline
[![TEB-CNRM_AU-Preston_SWnet_subset_baseline.png](TEB-CNRM_AU-Preston_SWnet_subset_baseline.png)](TEB-CNRM_AU-Preston_SWnet_subset_baseline.png)

### <a name="swnet_subset_detailed"></a>SWnet_subset_detailed
[![TEB-CNRM_AU-Preston_SWnet_subset_detailed.png](TEB-CNRM_AU-Preston_SWnet_subset_detailed.png)](TEB-CNRM_AU-Preston_SWnet_subset_detailed.png)

### <a name="swup"></a>SWup
[![TEB-CNRM_AU-Preston_SWup.png](TEB-CNRM_AU-Preston_SWup.png)](TEB-CNRM_AU-Preston_SWup.png)

### <a name="swup_subset_baseline"></a>SWup_subset_baseline
[![TEB-CNRM_AU-Preston_SWup_subset_baseline.png](TEB-CNRM_AU-Preston_SWup_subset_baseline.png)](TEB-CNRM_AU-Preston_SWup_subset_baseline.png)

### <a name="swup_subset_detailed"></a>SWup_subset_detailed
[![TEB-CNRM_AU-Preston_SWup_subset_detailed.png](TEB-CNRM_AU-Preston_SWup_subset_detailed.png)](TEB-CNRM_AU-Preston_SWup_subset_detailed.png)

### <a name="closure_baseline"></a>closure_baseline
[![TEB-CNRM_AU-Preston_closure_baseline.png](TEB-CNRM_AU-Preston_closure_baseline.png)](TEB-CNRM_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![TEB-CNRM_AU-Preston_closure_detailed.png](TEB-CNRM_AU-Preston_closure_detailed.png)](TEB-CNRM_AU-Preston_closure_detailed.png)

### out of range: baseline

 - TEB-CNRM TVeg max value of 0.0004 is greater than expected 0.0003 [kg/m2/s]

### out of range: detailed

 - TEB-CNRM Qh max value of 614.8715 is greater than expected 600.0 [W/m2]
 - TEB-CNRM TVeg max value of 0.0003 is greater than expected 0.0003 [kg/m2/s]


[Link to variable definitions](../modelattrs/variable_definitions.md)

