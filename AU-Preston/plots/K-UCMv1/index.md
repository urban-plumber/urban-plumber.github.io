# AU-Preston: K-UCMv1

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |   MAE |    MBE |    NSD |      R |
|:-------|:-------------|------:|-------:|-------:|-------:|
| SWnet  | baseline     |  4.69 | -0.502 | 0.8714 | 0.9997 |
| SWnet  | detailed     |  6.75 |  5.768 | 0.888  | 0.9997 |
| LWnet  | baseline     | 15.83 | 13.278 | 1.0899 | 0.9814 |
| LWnet  | detailed     |  7.86 |  2.444 | 1.0477 | 0.9839 |
| Qle    | baseline     | 27.41 | 11.001 | 0.7929 | 0.6443 |
| Qle    | detailed     | 24.62 |  1.737 | 0.6618 | 0.6399 |
| Qh     | baseline     | 28.34 |  6.62  | 0.8868 | 0.8985 |
| Qh     | detailed     | 29    |  0.327 | 0.7541 | 0.8931 |

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

[Link to variable definitions](variable_definitions.md)

### <a name="albedo"></a>Albedo
[![K-UCMv1_AU-Preston_Albedo.png](K-UCMv1_AU-Preston_Albedo.png)](K-UCMv1_AU-Preston_Albedo.png)

### <a name="lwnet"></a>LWnet
[![K-UCMv1_AU-Preston_LWnet.png](K-UCMv1_AU-Preston_LWnet.png)](K-UCMv1_AU-Preston_LWnet.png)

### <a name="lwup"></a>LWup
[![K-UCMv1_AU-Preston_LWup.png](K-UCMv1_AU-Preston_LWup.png)](K-UCMv1_AU-Preston_LWup.png)

### <a name="qh"></a>Qh
[![K-UCMv1_AU-Preston_Qh.png](K-UCMv1_AU-Preston_Qh.png)](K-UCMv1_AU-Preston_Qh.png)

### <a name="qle"></a>Qle
[![K-UCMv1_AU-Preston_Qle.png](K-UCMv1_AU-Preston_Qle.png)](K-UCMv1_AU-Preston_Qle.png)

### <a name="swnet"></a>SWnet
[![K-UCMv1_AU-Preston_SWnet.png](K-UCMv1_AU-Preston_SWnet.png)](K-UCMv1_AU-Preston_SWnet.png)

### <a name="swnet_subset_baseline"></a>SWnet_subset_baseline
[![K-UCMv1_AU-Preston_SWnet_subset_baseline.png](K-UCMv1_AU-Preston_SWnet_subset_baseline.png)](K-UCMv1_AU-Preston_SWnet_subset_baseline.png)

### <a name="swnet_subset_detailed"></a>SWnet_subset_detailed
[![K-UCMv1_AU-Preston_SWnet_subset_detailed.png](K-UCMv1_AU-Preston_SWnet_subset_detailed.png)](K-UCMv1_AU-Preston_SWnet_subset_detailed.png)

### <a name="swup"></a>SWup
[![K-UCMv1_AU-Preston_SWup.png](K-UCMv1_AU-Preston_SWup.png)](K-UCMv1_AU-Preston_SWup.png)

### <a name="swup_subset_baseline"></a>SWup_subset_baseline
[![K-UCMv1_AU-Preston_SWup_subset_baseline.png](K-UCMv1_AU-Preston_SWup_subset_baseline.png)](K-UCMv1_AU-Preston_SWup_subset_baseline.png)

### <a name="swup_subset_detailed"></a>SWup_subset_detailed
[![K-UCMv1_AU-Preston_SWup_subset_detailed.png](K-UCMv1_AU-Preston_SWup_subset_detailed.png)](K-UCMv1_AU-Preston_SWup_subset_detailed.png)

### <a name="closure_baseline"></a>closure_baseline
[![K-UCMv1_AU-Preston_closure_baseline.png](K-UCMv1_AU-Preston_closure_baseline.png)](K-UCMv1_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![K-UCMv1_AU-Preston_closure_detailed.png](K-UCMv1_AU-Preston_closure_detailed.png)](K-UCMv1_AU-Preston_closure_detailed.png)

### out of range: baseline

 - K-UCMv1 SWnet min value of -13.9929 is less than expected 0.0 [W/m2]

### out of range: detailed

 - K-UCMv1 SWnet min value of -8.7294 is less than expected 0.0 [W/m2]


[Link to variable definitions](variable_definitions.md)

