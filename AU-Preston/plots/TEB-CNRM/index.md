# AU-Preston: TEB-CNRM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |      MAE |       MBE |      NSD |        R |
|:-------|:-------------|---------:|----------:|---------:|---------:|
| SWnet  | baseline     | 10.2042  |   5.32612 | 0.887562 | 0.998683 |
| SWnet  | detailed     | 11.424   |   7.29649 | 0.89343  | 0.998683 |
| SWup   | baseline     |  7.30539 |  -7.1863  | 0.761564 | 0.995622 |
| SWup   | detailed     |  9.20621 |  -9.15147 | 0.727958 | 0.995622 |
| LWnet  | baseline     | 17.3434  | -10.0063  | 1.2299   | 0.935575 |
| LWnet  | detailed     | 11.8745  |  -3.03027 | 1.0652   | 0.95462  |
| LWup   | baseline     | 17.1237  |  10.019   | 1.34924  | 0.966758 |
| LWup   | detailed     | 11.653   |   3.04291 | 1.18259  | 0.975177 |
| Qle    | baseline     | 27.9441  |  -5.33554 | 0.750799 | 0.467579 |
| Qle    | detailed     | 31.3471  |   7.18454 | 1.0221   | 0.515388 |
| Qh     | baseline     | 34.2178  |  26.6876  | 1.25471  | 0.934511 |
| Qh     | detailed     | 29.4299  |  14.3521  | 1.27547  | 0.918854 |

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
 - [SWup](#swup)
 - [closure_baseline](#closure_baseline)
 - [closure_detailed](#closure_detailed)
 - [subset_Qg](#subset_qg)
 - [subset_Qh](#subset_qh)
 - [subset_Qle](#subset_qle)
 - [subset_Qtau](#subset_qtau)
 - [subset_SWnet](#subset_swnet)
 - [subset_SWup](#subset_swup)

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

### <a name="swup"></a>SWup
[![TEB-CNRM_AU-Preston_SWup.png](TEB-CNRM_AU-Preston_SWup.png)](TEB-CNRM_AU-Preston_SWup.png)

### <a name="closure_baseline"></a>closure_baseline
[![TEB-CNRM_AU-Preston_closure_baseline.png](TEB-CNRM_AU-Preston_closure_baseline.png)](TEB-CNRM_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![TEB-CNRM_AU-Preston_closure_detailed.png](TEB-CNRM_AU-Preston_closure_detailed.png)](TEB-CNRM_AU-Preston_closure_detailed.png)

### <a name="subset_qg"></a>subset_Qg
[![TEB-CNRM_AU-Preston_subset_Qg.png](TEB-CNRM_AU-Preston_subset_Qg.png)](TEB-CNRM_AU-Preston_subset_Qg.png)

### <a name="subset_qh"></a>subset_Qh
[![TEB-CNRM_AU-Preston_subset_Qh.png](TEB-CNRM_AU-Preston_subset_Qh.png)](TEB-CNRM_AU-Preston_subset_Qh.png)

### <a name="subset_qle"></a>subset_Qle
[![TEB-CNRM_AU-Preston_subset_Qle.png](TEB-CNRM_AU-Preston_subset_Qle.png)](TEB-CNRM_AU-Preston_subset_Qle.png)

### <a name="subset_qtau"></a>subset_Qtau
[![TEB-CNRM_AU-Preston_subset_Qtau.png](TEB-CNRM_AU-Preston_subset_Qtau.png)](TEB-CNRM_AU-Preston_subset_Qtau.png)

### <a name="subset_swnet"></a>subset_SWnet
[![TEB-CNRM_AU-Preston_subset_SWnet.png](TEB-CNRM_AU-Preston_subset_SWnet.png)](TEB-CNRM_AU-Preston_subset_SWnet.png)

### <a name="subset_swup"></a>subset_SWup
[![TEB-CNRM_AU-Preston_subset_SWup.png](TEB-CNRM_AU-Preston_subset_SWup.png)](TEB-CNRM_AU-Preston_subset_SWup.png)

### out of range: baseline

 - TEB-CNRM TVeg max value of 0.0004 is greater than expected 0.0003 [kg/m2/s]

### out of range: detailed

 - TEB-CNRM Qh max value of 614.8715 is greater than expected 600.0 [W/m2]
 - TEB-CNRM TVeg max value of 0.0003 is greater than expected 0.0003 [kg/m2/s]


[Link to variable definitions](../modelattrs/variable_definitions.md)

