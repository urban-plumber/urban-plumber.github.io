# AU-Preston: K-UCMv1

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |      MAE |        MBE |      NSD |        R |
|:-------|:-------------|---------:|-----------:|---------:|---------:|
| SWnet  | baseline     |  4.69359 |  -0.503954 | 0.871388 | 0.999703 |
| SWnet  | detailed     |  6.75655 |   5.77147  | 0.887976 | 0.999679 |
| SWup   | baseline     |  4.69288 |   0.491307 | 0.896897 | 0.990629 |
| SWup   | detailed     |  6.74852 |  -5.76547  | 0.802546 | 0.988188 |
| LWnet  | baseline     | 15.8296  |  13.2748   | 1.0899   | 0.981457 |
| LWnet  | detailed     |  7.85811 |   2.44106  | 1.04777  | 0.983915 |
| LWup   | baseline     | 15.8296  | -13.2748   | 1.07902  | 0.977038 |
| LWup   | detailed     |  7.85811 |  -2.44106  | 1.03637  | 0.980614 |
| Qle    | baseline     | 27.0937  |  11.1633   | 0.803028 | 0.6528   |
| Qle    | detailed     | 24.2898  |   1.88988  | 0.670255 | 0.648461 |
| Qh     | baseline     | 28.294   |   6.57122  | 0.887317 | 0.898715 |
| Qh     | detailed     | 28.9433  |   0.267453 | 0.754467 | 0.893409 |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)

### jump to figure:
 - [Albedo](#albedo)
 - [LWnet](#lwnet)
 - [LWup](#lwup)
 - [Qanth](#qanth)
 - [Qh](#qh)
 - [Qle](#qle)
 - [SWnet](#swnet)
 - [SWup](#swup)
 - [closure_baseline](#closure_baseline)
 - [closure_detailed](#closure_detailed)
 - [subset_LWnet](#subset_lwnet)
 - [subset_LWup](#subset_lwup)
 - [subset_Qanth](#subset_qanth)
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

### <a name="qanth"></a>Qanth
[![K-UCMv1_AU-Preston_Qanth.png](K-UCMv1_AU-Preston_Qanth.png)](K-UCMv1_AU-Preston_Qanth.png)

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

### <a name="subset_lwnet"></a>subset_LWnet
[![K-UCMv1_AU-Preston_subset_LWnet.png](K-UCMv1_AU-Preston_subset_LWnet.png)](K-UCMv1_AU-Preston_subset_LWnet.png)

### <a name="subset_lwup"></a>subset_LWup
[![K-UCMv1_AU-Preston_subset_LWup.png](K-UCMv1_AU-Preston_subset_LWup.png)](K-UCMv1_AU-Preston_subset_LWup.png)

### <a name="subset_qanth"></a>subset_Qanth
[![K-UCMv1_AU-Preston_subset_Qanth.png](K-UCMv1_AU-Preston_subset_Qanth.png)](K-UCMv1_AU-Preston_subset_Qanth.png)

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

