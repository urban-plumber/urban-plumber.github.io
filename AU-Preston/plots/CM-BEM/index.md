# AU-Preston: CM-BEM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |      MAE |       MBE |      NSD |        R |
|:-------|:-------------|---------:|----------:|---------:|---------:|
| SWnet  | baseline     |  8.99357 |  -5.50367 | 0.86693  | 0.998931 |
| SWnet  | detailed     |  7.30024 |  -2.50052 | 0.873806 | 0.999199 |
| SWup   | baseline     |  8.97902 |   5.48518 | 0.935472 | 0.96543  |
| SWup   | detailed     |  7.29053 |   2.48717 | 0.891416 | 0.972046 |
| LWnet  | baseline     | 13.3388  |  -2.18656 | 1.1925   | 0.952848 |
| LWnet  | detailed     | 10.7418  |   3.81546 | 1.08481  | 0.970728 |
| LWup   | baseline     | 13.3388  |   2.18656 | 1.24477  | 0.961501 |
| LWup   | detailed     | 10.7418  |  -3.81546 | 1.10327  | 0.97075  |
| Qle    | baseline     | 27.8082  | -14.5935  | 0.625117 | 0.594866 |
| Qle    | detailed     | 24.1384  |  -8.64399 | 0.640403 | 0.644817 |
| Qh     | baseline     | 34.9618  |  18.3685  | 0.831494 | 0.892799 |
| Qh     | detailed     | 30.5154  |  18.0798  | 1.02748  | 0.909328 |

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
[![CM-BEM_AU-Preston_Albedo.png](CM-BEM_AU-Preston_Albedo.png)](CM-BEM_AU-Preston_Albedo.png)

### <a name="lwnet"></a>LWnet
[![CM-BEM_AU-Preston_LWnet.png](CM-BEM_AU-Preston_LWnet.png)](CM-BEM_AU-Preston_LWnet.png)

### <a name="lwup"></a>LWup
[![CM-BEM_AU-Preston_LWup.png](CM-BEM_AU-Preston_LWup.png)](CM-BEM_AU-Preston_LWup.png)

### <a name="qh"></a>Qh
[![CM-BEM_AU-Preston_Qh.png](CM-BEM_AU-Preston_Qh.png)](CM-BEM_AU-Preston_Qh.png)

### <a name="qle"></a>Qle
[![CM-BEM_AU-Preston_Qle.png](CM-BEM_AU-Preston_Qle.png)](CM-BEM_AU-Preston_Qle.png)

### <a name="swnet"></a>SWnet
[![CM-BEM_AU-Preston_SWnet.png](CM-BEM_AU-Preston_SWnet.png)](CM-BEM_AU-Preston_SWnet.png)

### <a name="swup"></a>SWup
[![CM-BEM_AU-Preston_SWup.png](CM-BEM_AU-Preston_SWup.png)](CM-BEM_AU-Preston_SWup.png)

### <a name="closure_baseline"></a>closure_baseline
[![CM-BEM_AU-Preston_closure_baseline.png](CM-BEM_AU-Preston_closure_baseline.png)](CM-BEM_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![CM-BEM_AU-Preston_closure_detailed.png](CM-BEM_AU-Preston_closure_detailed.png)](CM-BEM_AU-Preston_closure_detailed.png)

### <a name="subset_qh"></a>subset_Qh
[![CM-BEM_AU-Preston_subset_Qh.png](CM-BEM_AU-Preston_subset_Qh.png)](CM-BEM_AU-Preston_subset_Qh.png)

### <a name="subset_qle"></a>subset_Qle
[![CM-BEM_AU-Preston_subset_Qle.png](CM-BEM_AU-Preston_subset_Qle.png)](CM-BEM_AU-Preston_subset_Qle.png)

### <a name="subset_swnet"></a>subset_SWnet
[![CM-BEM_AU-Preston_subset_SWnet.png](CM-BEM_AU-Preston_subset_SWnet.png)](CM-BEM_AU-Preston_subset_SWnet.png)

### <a name="subset_swup"></a>subset_SWup
[![CM-BEM_AU-Preston_subset_SWup.png](CM-BEM_AU-Preston_subset_SWup.png)](CM-BEM_AU-Preston_subset_SWup.png)

### out of range: baseline

 - CM-BEM SWnet min value of -0.3225 is less than expected 0.0 [W/m2]
 - CM-BEM Qanth_Qle min value of -1.9800 is less than expected 0.0 [W/m2]

### out of range: detailed

 - CM-BEM SWnet min value of -0.2986 is less than expected 0.0 [W/m2]
 - CM-BEM Qanth_Qle min value of -1.8900 is less than expected 0.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

