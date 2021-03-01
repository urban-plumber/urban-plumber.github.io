# AU-Preston: TEB-SPARTCS

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |      MAE |       MBE |      NSD |        R |
|:-------|:-------------|---------:|----------:|---------:|---------:|
| SWnet  | baseline     | 10.1706  |   5.29    | 0.887285 | 0.998684 |
| SWnet  | detailed     | 11.4761  |   7.23948 | 0.89415  | 0.998678 |
| SWup   | baseline     |  7.26782 |  -7.1504  | 0.76315  | 0.995641 |
| SWup   | detailed     |  9.16569 |  -9.09392 | 0.723937 | 0.995421 |
| LWnet  | baseline     | 17.5648  | -11.1934  | 1.24545  | 0.937353 |
| LWnet  | detailed     | 12.8924  |  -7.81062 | 1.12985  | 0.956815 |
| LWup   | baseline     | 17.374   |  11.2061  | 1.36073  | 0.967787 |
| LWup   | detailed     | 12.7519  |   7.82326 | 1.22519  | 0.975839 |
| Qle    | baseline     | 27.9477  |  -5.32807 | 0.751989 | 0.4673   |
| Qle    | detailed     | 31.1246  |   7.07667 | 1.0319   | 0.52387  |
| Qh     | baseline     | 33.5029  |  25.5641  | 1.25232  | 0.934539 |
| Qh     | detailed     | 27.4765  |   9.75629 | 1.2485   | 0.920165 |

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

### <a name="swup"></a>SWup
[![TEB-SPARTCS_AU-Preston_SWup.png](TEB-SPARTCS_AU-Preston_SWup.png)](TEB-SPARTCS_AU-Preston_SWup.png)

### <a name="closure_baseline"></a>closure_baseline
[![TEB-SPARTCS_AU-Preston_closure_baseline.png](TEB-SPARTCS_AU-Preston_closure_baseline.png)](TEB-SPARTCS_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![TEB-SPARTCS_AU-Preston_closure_detailed.png](TEB-SPARTCS_AU-Preston_closure_detailed.png)](TEB-SPARTCS_AU-Preston_closure_detailed.png)

### <a name="subset_qg"></a>subset_Qg
[![TEB-SPARTCS_AU-Preston_subset_Qg.png](TEB-SPARTCS_AU-Preston_subset_Qg.png)](TEB-SPARTCS_AU-Preston_subset_Qg.png)

### <a name="subset_qh"></a>subset_Qh
[![TEB-SPARTCS_AU-Preston_subset_Qh.png](TEB-SPARTCS_AU-Preston_subset_Qh.png)](TEB-SPARTCS_AU-Preston_subset_Qh.png)

### <a name="subset_qle"></a>subset_Qle
[![TEB-SPARTCS_AU-Preston_subset_Qle.png](TEB-SPARTCS_AU-Preston_subset_Qle.png)](TEB-SPARTCS_AU-Preston_subset_Qle.png)

### <a name="subset_qtau"></a>subset_Qtau
[![TEB-SPARTCS_AU-Preston_subset_Qtau.png](TEB-SPARTCS_AU-Preston_subset_Qtau.png)](TEB-SPARTCS_AU-Preston_subset_Qtau.png)

### <a name="subset_swnet"></a>subset_SWnet
[![TEB-SPARTCS_AU-Preston_subset_SWnet.png](TEB-SPARTCS_AU-Preston_subset_SWnet.png)](TEB-SPARTCS_AU-Preston_subset_SWnet.png)

### <a name="subset_swup"></a>subset_SWup
[![TEB-SPARTCS_AU-Preston_subset_SWup.png](TEB-SPARTCS_AU-Preston_subset_SWup.png)](TEB-SPARTCS_AU-Preston_subset_SWup.png)

### out of range: baseline

 - TEB-SPARTCS TVeg max value of 0.0004 is greater than expected 0.0003 [kg/m2/s]

### out of range: detailed

 - TEB-SPARTCS Qh max value of 602.5126 is greater than expected 600.0 [W/m2]
 - TEB-SPARTCS TVeg max value of 0.0004 is greater than expected 0.0003 [kg/m2/s]


[Link to variable definitions](../modelattrs/variable_definitions.md)

