# AU-Preston: K-UCMv1

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |      MAE |       MBE |      NSD |        R |      NMAE |
|:-------|:-------------|---------:|----------:|---------:|---------:|----------:|
| SWnet  | baseline     |  4.69032 | -0.501649 | 0.871381 | 0.999703 | 0.0161554 |
| SWnet  | detailed     |  6.7508  |  5.76649  | 0.887969 | 0.99968  | 0.0232525 |
| LWnet  | baseline     | 15.8325  | 13.2782   | 1.08987  | 0.981444 | 0.223899  |
| LWnet  | detailed     |  7.86001 |  2.44403  | 1.04774  | 0.983903 | 0.111154  |
| Qle    | baseline     | 27.3878  | 11.0634   | 0.793141 | 0.64504  | 0.829498  |
| Qle    | detailed     | 24.5988  |  1.79996  | 0.662003 | 0.64062  | 0.745027  |
| Qh     | baseline     | 28.33    |  6.60223  | 0.886933 | 0.898541 | 0.758982  |
| Qh     | detailed     | 28.984   |  0.307816 | 0.75414  | 0.893213 | 0.776504  |

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


[Link to variable definitions](../modelattrs/variable_definitions.md)

