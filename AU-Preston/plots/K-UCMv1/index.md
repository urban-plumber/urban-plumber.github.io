# AU-Preston: K-UCMv1

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |      MAE |        MBE |      NSD |        R |
|:-------|:-------------|---------:|-----------:|---------:|---------:|
| SWnet  | baseline     |  4.69104 |  -0.501488 | 0.871396 | 0.999703 |
| SWnet  | detailed     |  6.7521  |   5.76797  | 0.887983 | 0.99968  |
| SWup   | baseline     |  4.69224 |   0.489575 | 0.896944 | 0.990632 |
| SWup   | detailed     |  6.74729 |  -5.76468  | 0.802588 | 0.988192 |
| LWnet  | baseline     | 15.8325  |  13.2782   | 1.08987  | 0.981444 |
| LWnet  | detailed     |  7.86001 |   2.44403  | 1.04774  | 0.983903 |
| LWup   | baseline     | 15.8325  | -13.2782   | 1.07875  | 0.977016 |
| LWup   | detailed     |  7.86001 |  -2.44403  | 1.03611  | 0.9806   |
| Qle    | baseline     | 27.3878  |  11.0634   | 0.793141 | 0.64504  |
| Qle    | detailed     | 24.5988  |   1.79996  | 0.662003 | 0.64062  |
| Qh     | baseline     | 28.33    |   6.60223  | 0.886933 | 0.898541 |
| Qh     | detailed     | 28.984   |   0.307816 | 0.75414  | 0.893213 |

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
 - [subset_Qh](#subset_qh)
 - [subset_Qle](#subset_qle)
 - [subset_SWnet](#subset_swnet)
 - [subset_SWup](#subset_swup)

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

### <a name="swup"></a>SWup
[![K-UCMv1_AU-Preston_SWup.png](K-UCMv1_AU-Preston_SWup.png)](K-UCMv1_AU-Preston_SWup.png)

### <a name="closure_baseline"></a>closure_baseline
[![K-UCMv1_AU-Preston_closure_baseline.png](K-UCMv1_AU-Preston_closure_baseline.png)](K-UCMv1_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![K-UCMv1_AU-Preston_closure_detailed.png](K-UCMv1_AU-Preston_closure_detailed.png)](K-UCMv1_AU-Preston_closure_detailed.png)

### <a name="subset_qh"></a>subset_Qh
[![K-UCMv1_AU-Preston_subset_Qh.png](K-UCMv1_AU-Preston_subset_Qh.png)](K-UCMv1_AU-Preston_subset_Qh.png)

### <a name="subset_qle"></a>subset_Qle
[![K-UCMv1_AU-Preston_subset_Qle.png](K-UCMv1_AU-Preston_subset_Qle.png)](K-UCMv1_AU-Preston_subset_Qle.png)

### <a name="subset_swnet"></a>subset_SWnet
[![K-UCMv1_AU-Preston_subset_SWnet.png](K-UCMv1_AU-Preston_subset_SWnet.png)](K-UCMv1_AU-Preston_subset_SWnet.png)

### <a name="subset_swup"></a>subset_SWup
[![K-UCMv1_AU-Preston_subset_SWup.png](K-UCMv1_AU-Preston_subset_SWup.png)](K-UCMv1_AU-Preston_subset_SWup.png)

### out of range: baseline

 - K-UCMv1 SWnet min value of -13.9929 is less than expected 0.0 [W/m2]

### out of range: detailed

 - K-UCMv1 SWnet min value of -8.7294 is less than expected 0.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

